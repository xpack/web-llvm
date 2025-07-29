---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/spsoptional
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SPSOptional` Class Template

<p>SPS tag type for optionals. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename SPSTagT&gt;
class llvm::orc::shared::SPSOptional&lt;SPSTagT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">llvm/ExecutionEngine/Orc/Shared/SimplePackedSerialization.h</a>"
</div>

## Description {#details}

<p>SPS tag type for optionals.</p>


<p>SPSOptionals should be serialized as a bool with true indicating that an SPSTagT value is present, and false indicating that there is no value. If the boolean is true then the serialized SPSTagT will follow immediately after it.</p>


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
