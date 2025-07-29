---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/scalartraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ScalarTraits` Struct Template

<p>This class should be specialized by type that requires custom conversion to/from a yaml scalar. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, typename Enable = void&gt;
struct llvm::yaml::ScalarTraits&lt;T, Enable&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
</div>

## Description {#details}

<p>This class should be specialized by type that requires custom conversion to/from a yaml scalar.</p>


<p>For example:</p>


<p>template&lt;&gt; struct <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits">ScalarTraits&lt;MyType&gt;</a> { static void output(const MyType &amp;val, void*, llvm::raw_ostream &amp;out) { // stream out custom formatting out &lt;&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>("%x", val); } static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> input(StringRef scalar, void*, MyType &amp;value) { // parse scalar and set <span class="doxyComputerOutput">value</span> // return empty string on success, or error string return StringRef(); } static <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2e9b09c50b4fff3bad8cba23daef8757">QuotingType</a> mustQuote(StringRef) { return <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2e9b09c50b4fff3bad8cba23daef8757a66ba162102bbf6ae31b522aec561735e">QuotingType::Single</a>; } };</p>


<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
