# web-llvm

This project is a repro to help diagnose the large (20k+ docs) Docusaurus failed build.

The issues was reported as:

- https://github.com/facebook/docusaurus/discussions/11259

The builds were attempted on a macOS with 32 GB of RAM.

The problem is a huge memory consumption, with the machine starting to swap
and eventually the build hanging or crashing.

The test is a bit extreme, trying to build a large site (the LLVM reference
pages).

## tl;dr

To run the build, the only required steps are the usual

- `npm install`
- `npm run build`

in the `website` folder.

The steps below are for completeness, and document how to generate the
Doxygen documentation and convert it to Docusaurus MD.

## Preliminary results

The issue seems related to the very large number of files, some of them very large.

After changing the converter to generate MD files instead of MDX, and adding
a configuration option to disable the program listing, it was possible
to build the site locally, but the memory usage is not reasonable, it
peeked more than 74 GB, going deep into swap, which slowed things considerably.

---

## LLVM

The original LLVM reference web is:

- https://llvm.org/doxygen/

The LLVM documentation is in the main LLVM repo. It can be downloaded either
by cloning the Git, or by running the provided script:

```sh
mkdir web-llvm.git
cd web-llvm.git

curl -L https://raw.githubusercontent.com/llvm/llvm-project/refs/heads/main/llvm/utils/release/build-docs.sh -o build-docs.sh

bash build-docs.sh -release 20.1.6 -no-sphinx -no-doxygen
```

This script downloads the archive with the requested LLVM source code
(2GB+, 160K+ files).

## Doxygen

For this test, the Doxygen configuration needs some small adjustments,
especially `CASE_SENSE_NAMES=SYSTEM` if the build runs on macOS,
and `EXTRACT_ANON_NSPACES=YES`, to avoid some issues with anonymous namespaces.

```sh
cd web-llvm.git
find llvm-project -name doxygen.cfg.in \
-print \
-exec sed -i.bak \
-e 's|GENERATE_XML           = NO|GENERATE_XML           = YES|' \
-e 's|CLASS_DIAGRAMS         = YES|CLASS_DIAGRAMS         = NO|' \
-e 's|CASE_SENSE_NAMES       = YES|CASE_SENSE_NAMES       = SYSTEM|' \
-e 's|HAVE_DOT               = YES|HAVE_DOT               = NO|' \
-e 's|EXTRACT_ANON_NSPACES   = NO|EXTRACT_ANON_NSPACES   = YES|' \
-e 's|LOOKUP_CACHE_SIZE      = 4|LOOKUP_CACHE_SIZE      = 5|' \
'{}' ';'
```

The actual Doxygen build is performed by the same script.
The prerequisites are: cmake, ninja, doxygen.

```sh
cd web-llvm.git
bash -x build-docs.sh -srcdir llvm-project/llvm -no-sphinx
```

The build runs multiple steps in several folders and generates a
large `docs-build` folder (7G+, 135K+ files).

Note: the script has a small bug, it tries to run the Sphinx step,
although instructed not to do so.

The `html` and `xml` output folders are in `docs-build/docs/doxygen`.

The original documentation can be viewed directly with a browser, by
opening the `docs-build/docs/doxygen/html/index.html` file.

The xml files are used to generate the Docusaurus MDX files.

## Docusaurus

The Docusaurus configuration is created with 3.8.1.

```sh
npx create-docusaurus@3.8.1-canary-6366 website classic --typescript
```

## doxygen2docusaurus

The MD files were created with
[`doxygen2docusaurus`](https://github.com/xpack/doxygen2docusaurus),
a CLI tool to generate MD docs from Doxygen XML files.

To install it, run:

```sh
(cd website; npm install @xpack/doxygen2docusaurus --save-dev)
```

Add the new command to `website/package.json` npm scripts:

```json
  "scripts": {
    "convert-doxygen": "node --max-old-space-size=8192 --stack-size=2048 ./node_modules/.bin/doxygen2docusaurus",
  }
```

Please note the conversion requires most of the objects in memory,
and for this large site the heap and stack must be increased, otherwise
node will run out of memory,

To run the conversion:

```sh
(cd website; npm run convert-doxygen)
```

On my Mac this step takes about 7 minutes; it reports some warnings and errors,
but they are not relevant for this test.

The generated MD files are in `website/docs/api`
and the JSON files with the custom sidebar and menu are in `website`.

More details in the project [README](https://github.com/xpack/doxygen2docusaurus).

## docusaurus-faster

The initial attempts to build the Docusaurus site failed; a new attempt
with the new _faster_ plugin was made.

```sh
(cd website; npm install @docusaurus/faster)
```

and an addition to `website/docusaurus-config.ts`

```js
  future: {
    v4: {
      removeLegacyPostBuildHeadAttribute: true
    },
    experimental_faster: true,
  },
```

## concatenateModules: false

Another build attempt was done with the `concatenateModules` property disabled:

```js
  plugins: [
    // ...
    function disableExpensiveBundlerOptimizationPlugin() {
      return {
        name: "disable-expensive-bundler-optimizations",
        configureWebpack(_config, isServer) {
          return {
            optimization: {
              concatenateModules: false,
            },
          };
        },
      };
    },
  ],
```

The build apparently went farther, but it also failed.

## Final notes

- To conserve considerable space, the original LLVM files and the generated
documentation are not included in this project.
- The generated MD files are not final and may require further
refinement (suggestions are welcome!).
