---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/firstindexoftype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `FirstIndexOfType` Struct Template

<p>Find the first index where a type appears in a list of types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, typename... Us&gt;
struct llvm::FirstIndexOfType&lt;T, Us&gt; { ... }
</div>

## Description {#details}

<p>Find the first index where a type appears in a list of types.</p>


<p>FirstIndexOfType&lt;T, Us...&gt;::value is the first index of T in Us.</p>


<p>Typically only meaningful when it is otherwise statically known that the type pack has no duplicate types. This should be guaranteed explicitly with static_assert(TypesAreDistinct&lt;Us...&gt;::value).</p>


<p>It is a compile-time error to instantiate when T is not present in Us, i.e. if is_one_of&lt;T, Us...&gt;::value is false.</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
