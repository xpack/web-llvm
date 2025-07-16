---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-inlinecost-cpp-/instructioncostdetail
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `InstructionCostDetail` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{InlineCost.cpp}::InstructionCostDetail { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c370a5355842f34cbad8c9363cc3874">getThresholdDelta</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a852b7d92db856caa5a7cb3d0a65ca416">getCostDelta</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a201c03ac33bdb906eef0d0ae46df5eb2">hasThresholdChanged</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe1737745f08bf77641bffc17488e3a2">CostBefore</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3b93538dde19d1b1ef679d6b731e3f">CostAfter</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45ac15e50730dfdd4f785bc1ab7728f4">ThresholdBefore</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78fadaaaa7734f2e37f7511c37e6b972">ThresholdAfter</a> = 0</td>
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


<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getCostDelta() {#a852b7d92db856caa5a7cb3d0a65ca416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InstructionCostDetail::getCostDelta ()</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#a9e3b93538dde19d1b1ef679d6b731e3f">CostAfter</a> and <a href="#afe1737745f08bf77641bffc17488e3a2">CostBefore</a>.</p>

</div>
</div>

### getThresholdDelta() {#a4c370a5355842f34cbad8c9363cc3874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InstructionCostDetail::getThresholdDelta ()</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#a78fadaaaa7734f2e37f7511c37e6b972">ThresholdAfter</a> and <a href="#a45ac15e50730dfdd4f785bc1ab7728f4">ThresholdBefore</a>.</p>

</div>
</div>

### hasThresholdChanged() {#a201c03ac33bdb906eef0d0ae46df5eb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineCost.cpp}::InstructionCostDetail::hasThresholdChanged ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>References <a href="#a78fadaaaa7734f2e37f7511c37e6b972">ThresholdAfter</a> and <a href="#a45ac15e50730dfdd4f785bc1ab7728f4">ThresholdBefore</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CostAfter {#a9e3b93538dde19d1b1ef679d6b731e3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InstructionCostDetail::CostAfter = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a852b7d92db856caa5a7cb3d0a65ca416">getCostDelta</a>.</p>

</div>
</div>

### CostBefore {#afe1737745f08bf77641bffc17488e3a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InstructionCostDetail::CostBefore = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a852b7d92db856caa5a7cb3d0a65ca416">getCostDelta</a>.</p>

</div>
</div>

### ThresholdAfter {#a78fadaaaa7734f2e37f7511c37e6b972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InstructionCostDetail::ThresholdAfter = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a4c370a5355842f34cbad8c9363cc3874">getThresholdDelta</a> and <a href="#a201c03ac33bdb906eef0d0ae46df5eb2">hasThresholdChanged</a>.</p>

</div>
</div>

### ThresholdBefore {#a45ac15e50730dfdd4f785bc1ab7728f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineCost.cpp}::InstructionCostDetail::ThresholdBefore = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a>.</p>


<p>Referenced by <a href="#a4c370a5355842f34cbad8c9363cc3874">getThresholdDelta</a> and <a href="#a201c03ac33bdb906eef0d0ae46df5eb2">hasThresholdChanged</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/inlinecost-cpp">InlineCost.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
