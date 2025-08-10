---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/unique-function
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `unique_function` Class Template

<p><a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a> is a type-erasing functor similar to std::function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename FunctionT&gt;
class llvm::unique_function&lt;FunctionT&gt; { ... }
</div>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a> is a type-erasing functor similar to std::function.</p>


<p>It can hold move-only function objects, like lambdas capturing unique_ptrs. Accordingly, it is movable but not copyable.</p>


<p>It supports const-qualification:</p>


<ul class="doxyList ">
<li><a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function&lt;int() const&gt;</a> has a const operator(). It can only hold functions which themselves have a const operator().</li>
<li><a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function&lt;int()&gt;</a> has a non-const operator(). It can hold functions with a non-const operator(), like mutable lambdas.</li>
</ul>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
