---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vregmaskorunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `VRegMaskOrUnit` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::VRegMaskOrUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">llvm/CodeGen/RegisterPressure.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4083bf50def8cdfabca0243ec86c2520">VRegMaskOrUnit</a> (Register RegUnit, LaneBitmask LaneMask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a850b5c0b8b36bb79d7bb84f4bb96f91e">RegUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virtual register or register unit. <a href="#a850b5c0b8b36bb79d7bb84f4bb96f91e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77670492e7be5b863b106969e8963a47">LaneMask</a></td>
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


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VRegMaskOrUnit() {#a4083bf50def8cdfabca0243ec86c2520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VRegMaskOrUnit::VRegMaskOrUnit (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegUnit, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>References <a href="#a77670492e7be5b863b106969e8963a47">LaneMask</a> and <a href="#a850b5c0b8b36bb79d7bb84f4bb96f91e">RegUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LaneMask {#a77670492e7be5b863b106969e8963a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask llvm::VRegMaskOrUnit::LaneMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#adfcb78856461567d0d6f7012aee7a89a">addRegLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a60e96ac40c51e2ad7e24f9776fda71d1">llvm::RegPressureTracker::discoverLiveInOrOut</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a474e65b5df97bf9cf404aa9b85eb6262">llvm::RegPressureTracker::initLiveThru</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregset/#a56de2152c7bead150b8341a48e083230">llvm::LiveRegSet::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a7241534b422b4edd167aedf565fb8d5c">removeRegLanes</a> and <a href="#a4083bf50def8cdfabca0243ec86c2520">VRegMaskOrUnit</a>.</p>

</div>
</div>

### RegUnit {#a850b5c0b8b36bb79d7bb84f4bb96f91e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::VRegMaskOrUnit::RegUnit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Virtual register or register unit.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#adfcb78856461567d0d6f7012aee7a89a">addRegLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a60e96ac40c51e2ad7e24f9776fda71d1">llvm::RegPressureTracker::discoverLiveInOrOut</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregset/#a123f73e0b47037e76ad341d46dcc46d1">llvm::LiveRegSet::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a474e65b5df97bf9cf404aa9b85eb6262">llvm::RegPressureTracker::initLiveThru</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregset/#a56de2152c7bead150b8341a48e083230">llvm::LiveRegSet::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a7241534b422b4edd167aedf565fb8d5c">removeRegLanes</a> and <a href="#a4083bf50def8cdfabca0243ec86c2520">VRegMaskOrUnit</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
