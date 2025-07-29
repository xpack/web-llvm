---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vplanhcfgbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VPlanHCFGBuilder` Class

<p>Main class to build the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> H-CFG for an incoming IR. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPlanHCFGBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-h">Transforms/Vectorize/VPlanHCFGBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bce0f5c7b119755cf368c61363dc230">VPlanHCFGBuilder</a> (Loop *Lp, LoopInfo *LI, VPlan &amp;P)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef4332eb7802ff0c53ca8ba7e999298">buildHierarchicalCFG</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build H-CFG for TheLoop and update Plan accordingly. <a href="#a8ef4332eb7802ff0c53ca8ba7e999298">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb2ec7c60a31d3341ad78c2bb83629ed">buildPlainCFG</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build plain CFG for TheLoop and connects it to Plan's entry. <a href="#acb2ec7c60a31d3341ad78c2bb83629ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5324c5d437209c2951d7662458c7e78">VPlanTestIRBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d2016b5c581909382d4a9b834051f88">TheLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6685153ab83fed9377f66572d0eb4fe">LI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b3a1bed65fb42eaa58c5645eb8ce76">Plan</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpdominatortree">VPDominatorTree</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ad3b91849c9b261bd99616640aceda1">VPDomTree</a></td>
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

## Description {#details}

<p>Main class to build the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> H-CFG for an incoming IR.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-h">VPlanHCFGBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VPlanHCFGBuilder() {#a8bce0f5c7b119755cf368c61363dc230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPlanHCFGBuilder::VPlanHCFGBuilder (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * Lp, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-h">VPlanHCFGBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### buildHierarchicalCFG() {#a8ef4332eb7802ff0c53ca8ba7e999298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanHCFGBuilder::buildHierarchicalCFG ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build H-CFG for TheLoop and update Plan accordingly.</p>

<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-h">VPlanHCFGBuilder.h</a>, definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildPlainCFG() {#acb2ec7c60a31d3341ad78c2bb83629ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPlanHCFGBuilder::buildPlainCFG ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build plain CFG for TheLoop and connects it to Plan's entry.</p>

<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-h">VPlanHCFGBuilder.h</a>, definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LI {#ae6685153ab83fed9377f66572d0eb4fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::VPlanHCFGBuilder::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-h">VPlanHCFGBuilder.h</a>.</p>

</div>
</div>

### Plan {#a74b3a1bed65fb42eaa58c5645eb8ce76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlan&amp; llvm::VPlanHCFGBuilder::Plan</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-h">VPlanHCFGBuilder.h</a>.</p>

</div>
</div>

### TheLoop {#a5d2016b5c581909382d4a9b834051f88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* llvm::VPlanHCFGBuilder::TheLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-h">VPlanHCFGBuilder.h</a>.</p>

</div>
</div>

### VPDomTree {#a9ad3b91849c9b261bd99616640aceda1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPDominatorTree llvm::VPlanHCFGBuilder::VPDomTree</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-h">VPlanHCFGBuilder.h</a>.</p>

</div>
</div>

### VPlanTestIRBase {#ac5324c5d437209c2951d7662458c7e78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::VPlanHCFGBuilder::VPlanTestIRBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-h">VPlanHCFGBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-cpp">VPlanHCFGBuilder.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanhcfgbuilder-h">VPlanHCFGBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
