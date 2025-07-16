---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/memorydependenceresults/nonlocalpointerinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `NonLocalPointerInfo` Struct Reference

<p>This record is the information kept for each (value, is load) pair. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MemoryDependenceResults::NonLocalPointerInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbcf559f73088fbf400cb279ec36abd7">NonLocalPointerInfo</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">BBSkipFirstBlockPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e74c0913a89098382c67a442128599">Pair</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The pair of the block and the skip-first-block flag. <a href="#a87e74c0913a89098382c67a442128599">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a1fb5d4e618ecf28ecd42ab6fab5a4245">NonLocalDepInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a715267f23d6775341197137f64e47ee7">NonLocalDeps</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The results of the query for each relevant block. <a href="#a715267f23d6775341197137f64e47ee7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4e77e2935b9f1c3e4c980ecc439b103">Size</a> = <a href="/web-llvm/docs/api/classes/llvm/locationsize/#ac01c1aa625e97bf21d27474544c463e5">LocationSize::afterPointer</a>()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum size of the dereferences of the pointer. <a href="#af4e77e2935b9f1c3e4c980ecc439b103">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4b47e292013d475c8103f80698be5c9">AATags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> tags associated with dereferences of the pointer. <a href="#ac4b47e292013d475c8103f80698be5c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This record is the information kept for each (value, is load) pair.</p>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NonLocalPointerInfo() {#adbcf559f73088fbf400cb279ec36abd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryDependenceResults::NonLocalPointerInfo::NonLocalPointerInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AATags {#ac4b47e292013d475c8103f80698be5c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMDNodes llvm::MemoryDependenceResults::NonLocalPointerInfo::AATags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> tags associated with dereferences of the pointer.</p>


<p>The members may be null if there are no tags or conflicting tags.</p>


<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### NonLocalDeps {#a715267f23d6775341197137f64e47ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NonLocalDepInfo llvm::MemoryDependenceResults::NonLocalPointerInfo::NonLocalDeps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The results of the query for each relevant block.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### Pair {#a87e74c0913a89098382c67a442128599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BBSkipFirstBlockPair llvm::MemoryDependenceResults::NonLocalPointerInfo::Pair</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The pair of the block and the skip-first-block flag.</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### Size {#af4e77e2935b9f1c3e4c980ecc439b103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationSize llvm::MemoryDependenceResults::NonLocalPointerInfo::Size = <a href="/web-llvm/docs/api/classes/llvm/locationsize/#ac01c1aa625e97bf21d27474544c463e5">LocationSize::afterPointer</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum size of the dereferences of the pointer.</p>


<p>May be UnknownSize if the sizes are unknown.</p>


<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
