---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/patternmatch/m-intrinsic-ty
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `m_Intrinsic_Ty` Struct Template Reference

<p><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic">Intrinsic</a> matches are combinations of <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> matchers, and argument matchers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T0 = void, typename T1 = void, typename T2 = void, typename T3 = void, typename T4 = void, typename T5 = void, typename T6 = void, typename T7 = void, typename T8 = void, typename T9 = void, typename T10 = void&gt;
struct llvm::PatternMatch::m_Intrinsic_Ty&lt;T0, T1, T2, T3, T4, T5, T6, T7, T8, T9, T10&gt; { ... }
</div>

## Description {#details}

<p><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic">Intrinsic</a> matches are combinations of <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> matchers, and argument matchers.</p>


<p>Higher arity matcher are defined recursively in terms of and-ing them with lower arity matchers. Here's some convenient typedefs for up to several arguments, and more can be added as needed</p>


<p>Definition at line 2594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
