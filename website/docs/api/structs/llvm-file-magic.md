---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/file-magic
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `file_magic` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/file-magic">file_magic</a> - An "enum class" enumeration of file types based on magic (the first N bytes of the file). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::file_magic { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/magic-h">llvm/BinaryFormat/Magic.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Impl { <a href="#a39d74d9fa08229878443101289698b3a">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6502602c47a83f3d73b3ed976f2747d">file_magic</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa09d49d3e3826a95427d68ea587e307f">file_magic</a> (Impl V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cba8bf14f43d382dd7860617b4ba549">operator Impl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2074531f036688b5b438162e811e891a">is_object</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a39d74d9fa08229878443101289698b3a">Impl</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb2b7cc333947707a4d5238dbc5ea520">V</a> = <a href="#a39d74d9fa08229878443101289698b3aae5a2f339dd671d3caf9b616ef7bf1efd">unknown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/file-magic">file_magic</a> - An "enum class" enumeration of file types based on magic (the first N bytes of the file).</p>

<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/magic-h">Magic.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Impl {#a39d74d9fa08229878443101289698b3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::file_magic::Impl </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">unknown<a id="a39d74d9fa08229878443101289698b3aae5a2f339dd671d3caf9b616ef7bf1efd"></a></td>
<td class="doxyEnumItemDescription">Unrecognized file (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">bitcode<a id="a39d74d9fa08229878443101289698b3aa9b217cf59bac16d57cf52c3e76f3ce50"></a></td>
<td class="doxyEnumItemDescription">Bitcode file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">clang_ast<a id="a39d74d9fa08229878443101289698b3aabb25bd86fcacafa4654636a3985d0f5e"></a></td>
<td class="doxyEnumItemDescription">Clang PCH or PCM</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">archive<a id="a39d74d9fa08229878443101289698b3aa35fa482a9a36a65cbd44ed6a98563cd9"></a></td>
<td class="doxyEnumItemDescription">ar style archive file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">elf<a id="a39d74d9fa08229878443101289698b3aad31db91c55e2f1f5090ddbe652c20b1f"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> Unknown type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">elf_relocatable<a id="a39d74d9fa08229878443101289698b3aa1b167178973059ff5b3a4b2bf2377450"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> Relocatable object file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">elf_executable<a id="a39d74d9fa08229878443101289698b3aa46a884b4756415ac19d0ac5d2bf56079"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> Executable image</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">elf_shared_object<a id="a39d74d9fa08229878443101289698b3aa380638a0d06dd9003d4dd307f7b0851c"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> dynamically linked shared lib</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">elf_core<a id="a39d74d9fa08229878443101289698b3aabf5672e0a28c6ed1db85035f1b85fc5b"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> core image</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">goff_object<a id="a39d74d9fa08229878443101289698b3aa40ebaa45e99e5d81f24d506e33afdb42"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/goff">GOFF</a> object file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">macho_object<a id="a39d74d9fa08229878443101289698b3aac557d5088dac1a5cca0c2c7e78174632"></a></td>
<td class="doxyEnumItemDescription">Mach-O Object file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">macho_executable<a id="a39d74d9fa08229878443101289698b3aae3fbcf9e4d077fe08e7e73eb785f0a2c"></a></td>
<td class="doxyEnumItemDescription">Mach-O Executable</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">macho_fixed_virtual_memory_shared_lib<a id="a39d74d9fa08229878443101289698b3aae796c2e08310bfe518ffc166cb788601"></a></td>
<td class="doxyEnumItemDescription">Mach-O Shared Lib, FVM</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">macho_core<a id="a39d74d9fa08229878443101289698b3aaa01c66176cb9de4bb75c2b551133e38e"></a></td>
<td class="doxyEnumItemDescription">Mach-O Core File</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">macho_preload_executable<a id="a39d74d9fa08229878443101289698b3aa590d298012f657bc6b970e50d9f774c1"></a></td>
<td class="doxyEnumItemDescription">Mach-O Preloaded Executable</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">macho_dynamically_linked_shared_lib<a id="a39d74d9fa08229878443101289698b3aa45f3946b8331a826457113aa5d81bc96"></a></td>
<td class="doxyEnumItemDescription">Mach-O dynlinked shared lib</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">macho_dynamic_linker<a id="a39d74d9fa08229878443101289698b3aaea9f98c476ea8892d4bf66157d526cde"></a></td>
<td class="doxyEnumItemDescription">The Mach-O dynamic linker</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">macho_bundle<a id="a39d74d9fa08229878443101289698b3aad50da1fb17899eb0b0f714edf96c83c7"></a></td>
<td class="doxyEnumItemDescription">Mach-O Bundle file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">macho_dynamically_linked_shared_lib_stub<a id="a39d74d9fa08229878443101289698b3aa56440a39ccbe80c75e2e674aaafd00d4"></a></td>
<td class="doxyEnumItemDescription">Mach-O Shared lib stub</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">macho_dsym_companion<a id="a39d74d9fa08229878443101289698b3aae40fb5199f3d0b10d917738a06b4b6b0"></a></td>
<td class="doxyEnumItemDescription">Mach-O dSYM companion file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">macho_kext_bundle<a id="a39d74d9fa08229878443101289698b3aa86da0e718a3fbe29422c095c55af3bfa"></a></td>
<td class="doxyEnumItemDescription">Mach-O kext bundle file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">macho_universal_binary<a id="a39d74d9fa08229878443101289698b3aa9afb9b390f3041249d9a2dee384e4c1d"></a></td>
<td class="doxyEnumItemDescription">Mach-O universal binary</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">macho_file_set<a id="a39d74d9fa08229878443101289698b3aa75fee6d4cd7dfafcb268524c93b56101"></a></td>
<td class="doxyEnumItemDescription">Mach-O file set binary</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">minidump<a id="a39d74d9fa08229878443101289698b3aa41c57613a130abf5992d1e1a16497b04"></a></td>
<td class="doxyEnumItemDescription">Windows minidump file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">coff_cl_gl_object<a id="a39d74d9fa08229878443101289698b3aadcfa112d629e18c0a4eed4980ca4a7ae"></a></td>
<td class="doxyEnumItemDescription">Microsoft cl.exe's intermediate code file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">coff_object<a id="a39d74d9fa08229878443101289698b3aac575f4e16f05741d7656211f860dfcc3"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> object file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">coff_import_library<a id="a39d74d9fa08229878443101289698b3aa007729224f13c224129cef854ce5fc0c"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> import library</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">pecoff_executable<a id="a39d74d9fa08229878443101289698b3aa906a95690dc1df5a24e4253c83edd77c"></a></td>
<td class="doxyEnumItemDescription">PECOFF executable file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">windows_resource<a id="a39d74d9fa08229878443101289698b3aab93daf35debe3630ad69460b3c1d072a"></a></td>
<td class="doxyEnumItemDescription">Windows compiled resource file (.res)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">xcoff_object_32<a id="a39d74d9fa08229878443101289698b3aaa39e4e5aa8493605e279d127dc484379"></a></td>
<td class="doxyEnumItemDescription">32-bit <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> object file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">xcoff_object_64<a id="a39d74d9fa08229878443101289698b3aa45ff397494885b031c2b6a75797e7d7e"></a></td>
<td class="doxyEnumItemDescription">64-bit <a href="/web-llvm/docs/api/namespaces/llvm/xcoff">XCOFF</a> object file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">wasm_object<a id="a39d74d9fa08229878443101289698b3aaa0dedd1117ef34a81cb4b8751c3c1e4f"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> Object file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">pdb<a id="a39d74d9fa08229878443101289698b3aa0d7b7082a37cb024864ce149d0b04f5f"></a></td>
<td class="doxyEnumItemDescription">Windows PDB debug info file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">tapi_file<a id="a39d74d9fa08229878443101289698b3aafa3f3f16300b9876aa0147b61ca8edaa"></a></td>
<td class="doxyEnumItemDescription">Text-based Dynamic Library Stub file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">cuda_fatbinary<a id="a39d74d9fa08229878443101289698b3aadeb5166eb440a9fc83a3c586223b25e8"></a></td>
<td class="doxyEnumItemDescription">CUDA Fatbinary object file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">offload_binary<a id="a39d74d9fa08229878443101289698b3aa91e1aaaa67b1f5232dbea39497ef9250"></a></td>
<td class="doxyEnumItemDescription">LLVM offload object file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">dxcontainer_object<a id="a39d74d9fa08229878443101289698b3aa8570da074cd02b24514d79e2b84dd600"></a></td>
<td class="doxyEnumItemDescription">DirectX container file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">offload_bundle<a id="a39d74d9fa08229878443101289698b3aa5b3ee11ca5b4c14dd6c13ac147d76b77"></a></td>
<td class="doxyEnumItemDescription">Clang offload bundle file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">offload_bundle_compressed<a id="a39d74d9fa08229878443101289698b3aa73165d81a387644aea1856f9a567a23a"></a></td>
<td class="doxyEnumItemDescription">Compressed clang offload bundle file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">spirv_object<a id="a39d74d9fa08229878443101289698b3aa11ec46239073e8ad58f263bedf619cbc"></a></td>
<td class="doxyEnumItemDescription">A binary SPIR-V file</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/magic-h">Magic.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### file\_magic() {#ac6502602c47a83f3d73b3ed976f2747d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::file_magic::file_magic ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/magic-h">Magic.h</a>.</p>

</div>
</div>

### file\_magic() {#aa09d49d3e3826a95427d68ea587e307f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::file_magic::file_magic (<a href="#a39d74d9fa08229878443101289698b3a">Impl</a> V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/magic-h">Magic.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator Impl() {#a2cba8bf14f43d382dd7860617b4ba549}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::file_magic::operator Impl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/magic-h">Magic.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### is\_object() {#a2074531f036688b5b438162e811e891a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::file_magic::is_object ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/magic-h">Magic.h</a>.</p>


<p>Reference <a href="#a39d74d9fa08229878443101289698b3aae5a2f339dd671d3caf9b616ef7bf1efd">unknown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### V {#abb2b7cc333947707a4d5238dbc5ea520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Impl llvm::file_magic::V = <a href="#a39d74d9fa08229878443101289698b3aae5a2f339dd671d3caf9b616ef7bf1efd">unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/magic-h">Magic.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/magic-h">Magic.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
