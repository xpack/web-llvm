---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/function-ref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `function_ref` Class Template Reference

<p>An efficient, type-erasing, non-owning reference to a callable. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename Fn&gt;
class llvm::function_ref&lt;Fn&gt; { ... }
</div>

## Description {#details}

<p>An efficient, type-erasing, non-owning reference to a callable.</p>


<p>This is intended for use as the type of a function parameter that is not used after the function in question returns.</p>


<p>This class does not own the callable, so it is not in general safe to store a <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>.</p>


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlfunctionalextras-h">STLFunctionalExtras.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
