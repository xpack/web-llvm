---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/analysiskey
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AnalysisKey` Struct Reference

<p>A special type used by analysis passes to provide an address that identifies that particular analysis pass type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AnalysisKey { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">llvm/IR/Analysis.h</a>"
</div>

## Description {#details}

<p>A special type used by analysis passes to provide an address that identifies that particular analysis pass type.</p>


<p>Analysis passes should have a static data member of this type and derive from the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/analysisinfomixin">AnalysisInfoMixin</a></span> to get a static <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> method used to identify the analysis in the pass management infrastructure.</p>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
