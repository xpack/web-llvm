---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/analysisresultmodel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AnalysisResultModel` Struct Template

<p>Wrapper to model the analysis result concept. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename IRUnitT, typename PassT, typename ResultT, typename InvalidatorT, bool HasInvalidateHandler = ResultHasInvalidateMethod&lt;IRUnitT, ResultT&gt;::Value&gt;
struct llvm::detail::AnalysisResultModel&lt;IRUnitT, PassT, ResultT, InvalidatorT, HasInvalidateHandler&gt; { ... }
</div>

## Description {#details}

<p>Wrapper to model the analysis result concept.</p>


<p>By default, this will implement the invalidate method with a trivial implementation so that the actual analysis result doesn't need to provide an invalidation handler. It is only selected when the invalidation handler is not part of the ResultT's interface.</p>


<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
