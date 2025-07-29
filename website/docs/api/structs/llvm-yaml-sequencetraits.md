---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/sequencetraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SequenceTraits` Struct Template

<p>This class should be specialized by any type that needs to be converted to/from a YAML sequence. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, typename EnableIf = void&gt;
struct llvm::yaml::SequenceTraits&lt;T, EnableIf&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
</div>

## Description {#details}

<p>This class should be specialized by any type that needs to be converted to/from a YAML sequence.</p>


<p>For example:</p>


<p>template&lt;&gt; struct <a href="/web-llvm/docs/api/structs/llvm/yaml/sequencetraits">SequenceTraits&lt;MyContainer&gt;</a> { static size_t size(IO &amp;io, MyContainer &amp;seq) { return seq.size(); } static MyType&amp; element(IO &amp;, MyContainer &amp;seq, size_t index) { if ( index &gt;= seq.size() ) seq.resize(index+1); return seq[index]; } };</p>


<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
