---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/convergingvliwscheduler/schedcandidate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SchedCandidate` Struct Reference

<p>Store the state used by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler">ConvergingVLIWScheduler</a> heuristics, required for the lifetime of one invocation of <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a3bee087d8d270d2eb8823dc5b9dd4e0e">pickNode()</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ConvergingVLIWScheduler::SchedCandidate { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">llvm/CodeGen/VLIWMachineScheduler.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac70f9c9f862f1f706aca473a47b8bef4">SchedCandidate</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff1fbd60b344a6c92df3676c7e4abc78">SU</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/regpressuredelta">RegPressureDelta</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56e7a6b15ad7a5e7d0989ea13d3db5d3">RPDelta</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ad8d58d4dc381ab6a5f54c4f809217">SCost</a> = 0</td>
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

<p>Store the state used by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler">ConvergingVLIWScheduler</a> heuristics, required for the lifetime of one invocation of <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a3bee087d8d270d2eb8823dc5b9dd4e0e">pickNode()</a>.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SchedCandidate() {#ac70f9c9f862f1f706aca473a47b8bef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConvergingVLIWScheduler::SchedCandidate::SchedCandidate ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### RPDelta {#a56e7a6b15ad7a5e7d0989ea13d3db5d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegPressureDelta llvm::ConvergingVLIWScheduler::SchedCandidate::RPDelta</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aa641d58b022e9702656e1a58369931e5">llvm::ConvergingVLIWScheduler::pickNodeFromQueue</a>.</p>

</div>
</div>

### SCost {#ad8ad8d58d4dc381ab6a5f54c4f809217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ConvergingVLIWScheduler::SchedCandidate::SCost = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#adb98e755dacbd7d91a9910fe4dcea63c">llvm::ConvergingVLIWScheduler::pickNodeBidrectional</a> and <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aa641d58b022e9702656e1a58369931e5">llvm::ConvergingVLIWScheduler::pickNodeFromQueue</a>.</p>

</div>
</div>

### SU {#aff1fbd60b344a6c92df3676c7e4abc78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit* llvm::ConvergingVLIWScheduler::SchedCandidate::SU = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a3bee087d8d270d2eb8823dc5b9dd4e0e">llvm::ConvergingVLIWScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#adb98e755dacbd7d91a9910fe4dcea63c">llvm::ConvergingVLIWScheduler::pickNodeBidrectional</a> and <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aa641d58b022e9702656e1a58369931e5">llvm::ConvergingVLIWScheduler::pickNodeFromQueue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
