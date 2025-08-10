---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `VPlanHCFGBuilder.h` File

<p>This file defines the VPlanHCFGBuilder class which contains the public interface (buildHierarchicalCFG) to build a VPlan-based Hierarchical CFG (H-CFG) for an incoming IR. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplandominatortree-h">VPlanDominatorTree.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vplanhcfgbuilder">VPlanHCFGBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main class to build the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> H-CFG for an incoming IR. <a href="/web-llvm/docs/api/classes/llvm/vplanhcfgbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This file defines the VPlanHCFGBuilder class which contains the public interface (buildHierarchicalCFG) to build a VPlan-based Hierarchical CFG (H-CFG) for an incoming IR.</p>


<p>A H-CFG in VPlan is a control-flow graph whose nodes are VPBasicBlocks and/or VPRegionBlocks (i.e., other H-CFGs). The outermost H-CFG of a VPlan consists of a VPRegionBlock, denoted Top Region, which encloses any other VPBlockBase in the H-CFG. This guarantees that any VPBlockBase in the H-CFG other than the Top Region will have a parent VPRegionBlock and allows us to easily add more nodes before/after the main vector loop (such as the reduction epilogue).</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
