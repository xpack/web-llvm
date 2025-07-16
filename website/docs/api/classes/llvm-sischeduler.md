---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sischeduler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SIScheduler` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SIScheduler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">Target/AMDGPU/SIMachineScheduler.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcda4261a7ef310abb8ae1e4d1bcebe2">SIScheduler</a> (SIScheduleDAGMI *DAG)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac183efcb4bced401aa24a2341f1607f4">~SIScheduler</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct <a href="/web-llvm/docs/api/structs/llvm/sischeduleblockresult">SIScheduleBlockResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91522b1e12e9b5d9e9a05928732f15f9">scheduleVariant</a> (SISchedulerBlockCreatorVariant BlockVariant, SISchedulerBlockSchedulerVariant ScheduleVariant)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi">SIScheduleDAGMI</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34cd2aa82ba44c213092b83c4b209610">DAG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sischeduleblockcreator">SIScheduleBlockCreator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80bbaa2fa63a7477ba4cedbe1b01dae1">BlockCreator</a></td>
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


<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIScheduler() {#afcda4261a7ef310abb8ae1e4d1bcebe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SIScheduler::SIScheduler (<a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi">SIScheduleDAGMI</a> * DAG)</td>
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



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a91522b1e12e9b5d9e9a05928732f15f9">scheduleVariant</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SIScheduler() {#ac183efcb4bced401aa24a2341f1607f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SIScheduler::~SIScheduler ()</td>
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



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Reference <a href="#a91522b1e12e9b5d9e9a05928732f15f9">scheduleVariant</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### scheduleVariant() {#a91522b1e12e9b5d9e9a05928732f15f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct SIScheduleBlockResult SIScheduler::scheduleVariant (<a href="/web-llvm/docs/api/namespaces/llvm/#a87e37096a7413b5df71c0af49d15d6b9">SISchedulerBlockCreatorVariant</a> BlockVariant, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d977510474f80bfa4550c11b1b5b1c9">SISchedulerBlockSchedulerVariant</a> ScheduleVariant)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>, definition at line 1720 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp">SIMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/structs/llvm/sischeduleblockresult/#a8cfeb7a8501b147cf6ec6617706bf227">llvm::SIScheduleBlockResult::MaxSGPRUsage</a>, <a href="/web-llvm/docs/api/structs/llvm/sischeduleblockresult/#a7e76c8d566e3f09c1b3ffe2add8562e1">llvm::SIScheduleBlockResult::MaxVGPRUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a1c735bd46fe1e1b5f6f85a710d99e149">Scheduler</a>, <a href="#a91522b1e12e9b5d9e9a05928732f15f9">scheduleVariant</a>, <a href="#afcda4261a7ef310abb8ae1e4d1bcebe2">SIScheduler</a> and <a href="/web-llvm/docs/api/structs/llvm/sischeduleblockresult/#afa48c69324d21c0d80e406f4731ed2ec">llvm::SIScheduleBlockResult::SUs</a>.</p>


<p>Referenced by <a href="#a91522b1e12e9b5d9e9a05928732f15f9">scheduleVariant</a> and <a href="#ac183efcb4bced401aa24a2341f1607f4">~SIScheduler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockCreator {#a80bbaa2fa63a7477ba4cedbe1b01dae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIScheduleBlockCreator llvm::SIScheduler::BlockCreator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>

</div>
</div>

### DAG {#a34cd2aa82ba44c213092b83c4b209610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIScheduleDAGMI* llvm::SIScheduler::DAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp">SIMachineScheduler.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
