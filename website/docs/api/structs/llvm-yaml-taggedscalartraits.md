---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/taggedscalartraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TaggedScalarTraits` Struct Template

<p>This class should be specialized by type that requires custom conversion to/from a YAML scalar with optional tags. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
struct llvm::yaml::TaggedScalarTraits&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
</div>

## Description {#details}

<p>This class should be specialized by type that requires custom conversion to/from a YAML scalar with optional tags.</p>


<p>For example:</p>


<p>template &lt;&gt; struct <a href="/web-llvm/docs/api/structs/llvm/yaml/taggedscalartraits">TaggedScalarTraits&lt;MyType&gt;</a> { static void output(const MyType &amp;Value, void*, llvm::raw_ostream
     &amp;ScalarOut, llvm::raw_ostream &amp;TagOut) { // stream out custom formatting including optional Tag Out &lt;&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>; } static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> input(StringRef Scalar, StringRef Tag, void*, MyType
     &amp;Value) { // parse scalar and set <span class="doxyComputerOutput">value</span> // return empty string on success, or error string return StringRef(); } static <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2e9b09c50b4fff3bad8cba23daef8757">QuotingType</a> mustQuote(const MyType &amp;Value, StringRef) { return <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2e9b09c50b4fff3bad8cba23daef8757a66ba162102bbf6ae31b522aec561735e">QuotingType::Single</a>; } };</p>


<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
