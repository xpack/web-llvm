---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/validate-format-parameters
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `validate_format_parameters` Struct Template Reference

<p>These are templated helper classes used by the format function that capture the object to be formatted and the format string. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename... Args&gt;
struct llvm::validate_format_parameters&lt;Args&gt; { ... }
</div>

## Description {#details}

<p>These are templated helper classes used by the format function that capture the object to be formatted and the format string.</p>


<p>When actually printed, this synthesizes the string into a temporary buffer provided and returns whether or not it is big enough.</p>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">Format.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
