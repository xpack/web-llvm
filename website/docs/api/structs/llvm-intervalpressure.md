---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/intervalpressure
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IntervalPressure` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/registerpressure">RegisterPressure</a> computed within a region of instructions delimited by TopIdx and BottomIdx. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::IntervalPressure { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">llvm/CodeGen/RegisterPressure.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/registerpressure">RegisterPressure</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for register pressure results. <a href="/web-llvm/docs/api/structs/llvm/registerpressure/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08225fe2adf56bf962e71483729fd99c">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the result so it can be used for another round of pressure tracking. <a href="#a08225fe2adf56bf962e71483729fd99c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad388da0eac059da0c6cf642204a6308a">openTop</a> (SlotIndex NextTop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the current top is not less than or equal to the next index, open it. <a href="#ad388da0eac059da0c6cf642204a6308a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fb4cf12022684a5149e2fba6b65a522">openBottom</a> (SlotIndex PrevBottom)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the current bottom is not greater than the previous index, open it. <a href="#a0fb4cf12022684a5149e2fba6b65a522">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf1e1810feaee0a0a5b54040ad46d0d8">TopIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the boundary of the region being tracked. <a href="#abf1e1810feaee0a0a5b54040ad46d0d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60f833a5cb8a08708e1a2d0aadc373c5">BottomIdx</a></td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registerpressure">RegisterPressure</a> computed within a region of instructions delimited by TopIdx and BottomIdx.</p>


<p>During pressure computation, the maximum pressure per register pressure set is increased. Once pressure within a region is fully computed, the live-in and live-out sets are recorded.</p>


<p>This is preferable to <a href="/web-llvm/docs/api/structs/llvm/regionpressure">RegionPressure</a> when <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> are available, because delimiting regions by <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> is more robust and convenient than holding block iterators. The block contents can change without invalidating the pressure result.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### openBottom() {#a0fb4cf12022684a5149e2fba6b65a522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IntervalPressure::openBottom (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> PrevBottom)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the current bottom is not greater than the previous index, open it.</p>

<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="#a60f833a5cb8a08708e1a2d0aadc373c5">BottomIdx</a> and <a href="/web-llvm/docs/api/structs/llvm/registerpressure/#aaf4867227a975bcae4b285003d7a8554">llvm::RegisterPressure::LiveInRegs</a>.</p>

</div>
</div>

### openTop() {#ad388da0eac059da0c6cf642204a6308a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IntervalPressure::openTop (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> NextTop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the current top is not less than or equal to the next index, open it.</p>


<p>We happen to need the <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> for the next top for pressure update.</p>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/registerpressure/#aaf4867227a975bcae4b285003d7a8554">llvm::RegisterPressure::LiveInRegs</a> and <a href="#abf1e1810feaee0a0a5b54040ad46d0d8">TopIdx</a>.</p>

</div>
</div>

### reset() {#a08225fe2adf56bf962e71483729fd99c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IntervalPressure::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear the result so it can be used for another round of pressure tracking.</p>

<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="#a60f833a5cb8a08708e1a2d0aadc373c5">BottomIdx</a>, <a href="/web-llvm/docs/api/structs/llvm/registerpressure/#aaf4867227a975bcae4b285003d7a8554">llvm::RegisterPressure::LiveInRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/registerpressure/#a8e0d374fff11a3139a343cb42338b989">llvm::RegisterPressure::LiveOutRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/registerpressure/#af444f3c79d12bb654d6477d629cbe7c0">llvm::RegisterPressure::MaxSetPressure</a> and <a href="#abf1e1810feaee0a0a5b54040ad46d0d8">TopIdx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BottomIdx {#a60f833a5cb8a08708e1a2d0aadc373c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::IntervalPressure::BottomIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="#a0fb4cf12022684a5149e2fba6b65a522">openBottom</a> and <a href="#a08225fe2adf56bf962e71483729fd99c">reset</a>.</p>

</div>
</div>

### TopIdx {#abf1e1810feaee0a0a5b54040ad46d0d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::IntervalPressure::TopIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the boundary of the region being tracked.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="#ad388da0eac059da0c6cf642204a6308a">openTop</a> and <a href="#a08225fe2adf56bf962e71483729fd99c">reset</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
