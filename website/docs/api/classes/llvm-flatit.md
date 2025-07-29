---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/flatit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FlatIt` Class Template

<p>Marker class to iterate over the elements of a <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> in flat mode. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class GraphType&gt;
class llvm::FlatIt&lt;GraphType&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">llvm/Analysis/RegionInfo.h</a>"
</div>

## Description {#details}

<p>Marker class to iterate over the elements of a <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> in flat mode.</p>


<p>The class is used to either iterate in Flat mode or by not using it to not iterate in Flat mode. During a Flat mode iteration all Regions are entered and the iteration returns every <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>. If the Flat mode is not selected for SubRegions just one <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> containing the subregion is returned.</p>


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
