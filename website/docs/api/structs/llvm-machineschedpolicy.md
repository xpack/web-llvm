---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/machineschedpolicy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MachineSchedPolicy` Struct Reference

<p>Define a generic scheduling policy for targets that don't provide their own <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MachineSchedPolicy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">llvm/CodeGen/MachineScheduler.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5276330718d6152d1adc226d68d10216">MachineSchedPolicy</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee4e3964174cee8cf362508ccef135ca">ShouldTrackPressure</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3e6dd2ea28909a7bdc5fefae67766b9">ShouldTrackLaneMasks</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track LaneMasks to allow reordering of independent subregister writes of the same vreg. <a href="#af3e6dd2ea28909a7bdc5fefae67766b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f609dd4ed94ea69ab680a7228f8786b">OnlyTopDown</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47ee8ec29daa3551f798ff4449fbf4d5">OnlyBottomUp</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2600398bcf6d98dea6035e652870b41a">DisableLatencyHeuristic</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76f64154875d2640526bff12b11f41bb">ComputeDFSResult</a> = false</td>
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

<p>Define a generic scheduling policy for targets that don't provide their own <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a>.</p>


<p>This can be overriden for each scheduling region before building the DAG.</p>


<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachineSchedPolicy() {#a5276330718d6152d1adc226d68d10216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineSchedPolicy::MachineSchedPolicy ()</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ComputeDFSResult {#a76f64154875d2640526bff12b11f41bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineSchedPolicy::ComputeDFSResult = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### DisableLatencyHeuristic {#a2600398bcf6d98dea6035e652870b41a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineSchedPolicy::DisableLatencyHeuristic = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a4ba514719cbb75b668499574cd6f238e">llvm::AArch64Subtarget::overrideSchedPolicy</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#a8b5b05466a0b20a9ccb6ff4cf3476523">llvm::RISCVSubtarget::overrideSchedPolicy</a>.</p>

</div>
</div>

### OnlyBottomUp {#a47ee8ec29daa3551f798ff4449fbf4d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineSchedPolicy::OnlyBottomUp = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#a86947dbacbd971019d8257dbfe60ce05">llvm::RISCVSubtarget::overridePostRASchedPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a4ba514719cbb75b668499574cd6f238e">llvm::AArch64Subtarget::overrideSchedPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#aec6845ed5bb22b096581b6887d6db618">llvm::GCNSubtarget::overrideSchedPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a62b85cc5821fb2328cf0040aa9f8230b">llvm::PPCSubtarget::overrideSchedPolicy</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#a8b5b05466a0b20a9ccb6ff4cf3476523">llvm::RISCVSubtarget::overrideSchedPolicy</a>.</p>

</div>
</div>

### OnlyTopDown {#a0f609dd4ed94ea69ab680a7228f8786b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineSchedPolicy::OnlyTopDown = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#a86947dbacbd971019d8257dbfe60ce05">llvm::RISCVSubtarget::overridePostRASchedPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a4ba514719cbb75b668499574cd6f238e">llvm::AArch64Subtarget::overrideSchedPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#aec6845ed5bb22b096581b6887d6db618">llvm::GCNSubtarget::overrideSchedPolicy</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#a8b5b05466a0b20a9ccb6ff4cf3476523">llvm::RISCVSubtarget::overrideSchedPolicy</a>.</p>

</div>
</div>

### ShouldTrackLaneMasks {#af3e6dd2ea28909a7bdc5fefae67766b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineSchedPolicy::ShouldTrackLaneMasks = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Track LaneMasks to allow reordering of independent subregister writes of the same vreg.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy/#af1f5d487c749cd8b3fe868e48b80a84d">MachineSchedStrategy::shouldTrackLaneMasks()</a></p></dd>
</dl>


<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#aec6845ed5bb22b096581b6887d6db618">llvm::GCNSubtarget::overrideSchedPolicy</a>.</p>

</div>
</div>

### ShouldTrackPressure {#aee4e3964174cee8cf362508ccef135ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineSchedPolicy::ShouldTrackPressure = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#aec6845ed5bb22b096581b6887d6db618">llvm::GCNSubtarget::overrideSchedPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a62b85cc5821fb2328cf0040aa9f8230b">llvm::PPCSubtarget::overrideSchedPolicy</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#a8b5b05466a0b20a9ccb6ff4cf3476523">llvm::RISCVSubtarget::overrideSchedPolicy</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
