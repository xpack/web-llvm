---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/blockscalartraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BlockScalarTraits` Struct Template Reference

<p>This class should be specialized by type that requires custom conversion to/from a YAML literal block scalar. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
struct llvm::yaml::BlockScalarTraits&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
</div>

## Description {#details}

<p>This class should be specialized by type that requires custom conversion to/from a YAML literal block scalar.</p>


<p>For example:</p>


<p>template &lt;&gt; struct <a href="/web-llvm/docs/api/structs/llvm/yaml/blockscalartraits">BlockScalarTraits&lt;MyType&gt;</a> { static void output(const MyType &amp;Value, void*, llvm::raw_ostream &amp;Out) { // stream out custom formatting Out &lt;&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>; } static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> input(StringRef Scalar, void*, MyType &amp;Value) { // parse scalar and set <span class="doxyComputerOutput">value</span> // return empty string on success, or error string return StringRef(); } };</p>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
