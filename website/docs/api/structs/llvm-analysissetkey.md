---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/analysissetkey
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AnalysisSetKey` Struct

<p>A special type used to provide an address that identifies a set of related analyses. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AnalysisSetKey { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">llvm/IR/Analysis.h</a>"
</div>

## Description {#details}

<p>A special type used to provide an address that identifies a set of related analyses.</p>


<p>These sets are primarily used below to mark sets of analyses as preserved.</p>


<p>For example, a transformation can indicate that it preserves the CFG of a function by preserving the appropriate <a href="/web-llvm/docs/api/structs/llvm/analysissetkey">AnalysisSetKey</a>. An analysis that depends only on the CFG can then check if that <a href="/web-llvm/docs/api/structs/llvm/analysissetkey">AnalysisSetKey</a> is preserved; if it is, the analysis knows that it itself is preserved.</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
