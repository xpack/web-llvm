---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vliwmachinescheduler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VLIWMachineScheduler` Class

<p>Extend the standard <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive">ScheduleDAGMILive</a> to provide more context and override the top-level <a href="#ad25e72e64bc7ed157b69c60e85b4061e">schedule()</a> driver. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VLIWMachineScheduler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">llvm/CodeGen/VLIWMachineScheduler.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive">ScheduleDAGMILive</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive">ScheduleDAGMILive</a> is an implementation of <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> that schedules machine instructions while updating <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> and tracking regpressure. <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b6189b77c7f1e42ace4d1c9940cd90">VLIWMachineScheduler</a> (MachineSchedContext *C, std::unique_ptr&lt; MachineSchedStrategy &gt; S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad25e72e64bc7ed157b69c60e85b4061e">schedule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Schedule - This is called back from ScheduleDAGInstrs::Run() when it's time to do some work. <a href="#ad25e72e64bc7ed157b69c60e85b4061e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registerclassinfo">RegisterClassInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acece183f6f4f1551b1a1fa9dd93925a5">getRegClassInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c141a62b7a2ca52832410d948ada2c0">getBBSize</a> ()</td>
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

<p>Extend the standard <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive">ScheduleDAGMILive</a> to provide more context and override the top-level <a href="#ad25e72e64bc7ed157b69c60e85b4061e">schedule()</a> driver.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VLIWMachineScheduler() {#a93b6189b77c7f1e42ace4d1c9940cd90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VLIWMachineScheduler::VLIWMachineScheduler (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> &gt; S)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a67da2c9a62e43ae7b66bc5ca91f55a05">llvm::ScheduleDAGMILive::ScheduleDAGMILive</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBBSize() {#a7c141a62b7a2ca52832410d948ada2c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::VLIWMachineScheduler::getBBSize ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>.</p>

</div>
</div>

### getRegClassInfo() {#acece183f6f4f1551b1a1fa9dd93925a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterClassInfo * llvm::VLIWMachineScheduler::getRegClassInfo ()</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a9539744d7a0c1681540a64e935b671dd">llvm::ScheduleDAGMILive::RegClassInfo</a>.</p>

</div>
</div>

### schedule() {#ad25e72e64bc7ed157b69c60e85b4061e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VLIWMachineScheduler::schedule ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Schedule - This is called back from ScheduleDAGInstrs::Run() when it's time to do some work.</p>


<p>schedule - Called back from <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a8539983d1d0a8b07d92b91c16b9f7a5a">MachineScheduler::runOnMachineFunction</a> after setting up the current scheduling region.</p>


<p>[RegionBegin, RegionEnd) only includes instructions that have DAG nodes, not scheduling boundaries.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab50b64c518a7455daf3e0bc87aee5514">llvm::ScheduleDAGInstrs::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a4be5ffcd4f76d433cc753be146a872b7">llvm::ScheduleDAGMILive::buildDAGWithRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a569fc4139bec0217794e9f830d6ba852">llvm::ScheduleDAGMI::checkSchedLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a7435e842606f5db4bca092e5829befc6">llvm::ScheduleDAGMI::CurrentBottom</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac8abe1b0d869087bd0c14a6637356dc0">llvm::ScheduleDAGMI::CurrentTop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#add5e3e74f2db8e669b830ae35edc8c02">llvm::ScheduleDAGMILive::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a01b02e76c87211e7084ec17f18a2d16f">llvm::ScheduleDAGMI::dumpSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a6d0a0b4903e8d4d12c98b0f43fe83878">llvm::ScheduleDAGMI::findRootsAndBiasEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a3668b7c35103540be55d96cd68948f43">llvm::ScheduleDAGMILive::initQueues</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ad2b3e1939f6f39819ad55c714deefad6">llvm::ScheduleDAGInstrs::MLI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac2dafe98c88d43b256622413886e2152">llvm::ScheduleDAGMI::placeDebugValues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a2aa2eb6fd6a44ff6b9cbad960d446c7a">llvm::ScheduleDAGMI::postProcessDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a0318c90d99b85c47bc82d9e0844462f6">llvm::ScheduleDAGMI::SchedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a04a2c04f918397dbac27a79e58807136">llvm::ScheduleDAGMILive::scheduleMI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a8cd3eede9e2a32c7139cc5c7c481e08b">llvm::ScheduleDAGInstrs::Topo</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#abfdd9a95217810c69b2557060a130318">llvm::ScheduleDAGMI::updateQueues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a8b7babb023cad0842f5a177e7abe3651">llvm::ScheduleDAGMI::viewGraph</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5ec9cfe35d76125af923975fa0c1730a">llvm::ViewMISchedDAGs</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
