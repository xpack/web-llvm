---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/trailing-objects-internal/trailingobjectsbase/overloadtoken
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `OverloadToken` Struct Template Reference

<p><a href="/web-llvm/docs/api/structs/llvm/trailing-objects-internal/trailingobjectsbase/overloadtoken">OverloadToken</a>'s purpose is to allow specifying function overloads for different types, without actually taking the types as parameters. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
struct llvm::trailing_objects_internal::TrailingObjectsBase::OverloadToken&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">llvm/Support/TrailingObjects.h</a>"
</div>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/trailing-objects-internal/trailingobjectsbase/overloadtoken">OverloadToken</a>'s purpose is to allow specifying function overloads for different types, without actually taking the types as parameters.</p>


<p>(Necessary because member function templates cannot be specialized, so overloads must be used instead of specialization.)</p>


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
