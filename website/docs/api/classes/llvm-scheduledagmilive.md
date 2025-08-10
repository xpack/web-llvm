---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scheduledagmilive
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ScheduleDAGMILive` Class

<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive">ScheduleDAGMILive</a> is an implementation of <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> that schedules machine instructions while updating <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> and tracking regpressure. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ScheduleDAGMILive { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">llvm/CodeGen/MachineScheduler.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> is an implementation of <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> that simply schedules machine instructions according to the given <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> without much extra book-keeping. <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler">GCNIterativeScheduler</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnscheduledagmilive">GCNScheduleDAGMILive</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi">SIScheduleDAGMI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler">VLIWMachineScheduler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extend the standard <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive">ScheduleDAGMILive</a> to provide more context and override the top-level <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">schedule()</a> driver. <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67da2c9a62e43ae7b66bc5ca91f55a05">ScheduleDAGMILive</a> (MachineSchedContext *C, std::unique_ptr&lt; MachineSchedStrategy &gt; S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada767569b82d6e57bf0b25f5d35d22df">~ScheduleDAGMILive</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91c62f0ae0c40d54d8dd13c703618af4">hasVRegLiveness</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this DAG supports VReg liveness and RegPressure. <a href="#a91c62f0ae0c40d54d8dd13c703618af4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87daf83eb223263e4c8766d10aa911be">isTrackingPressure</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if register pressure tracking is enabled. <a href="#a87daf83eb223263e4c8766d10aa911be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/intervalpressure">IntervalPressure</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb5c9c3ec4fdd43313202df94e3c3c1">getTopPressure</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get current register pressure for the top scheduled instructions. <a href="#aefb5c9c3ec4fdd43313202df94e3c3c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac50964e02990b51922da2dc47576b64">getTopRPTracker</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/intervalpressure">IntervalPressure</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a95fae69c6ef3a956f2450e417edcc">getBotPressure</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get current register pressure for the bottom scheduled instructions. <a href="#ad1a95fae69c6ef3a956f2450e417edcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a642560b62069c00ff76aa0a3f27a54b0">getBotRPTracker</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/intervalpressure">IntervalPressure</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9bc3efdc06ed731273758563df1b9eb">getRegPressure</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get register pressure for the entire scheduling region before scheduling. <a href="#ac9bc3efdc06ed731273758563df1b9eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/pressurechange">PressureChange</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af06cc7cea58d96c7e069499a976ca8a0">getRegionCriticalPSets</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pressurediff">PressureDiff</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24c23a8dc39475b1e913e41f1249c9f7">getPressureDiff</a> (const SUnit *SU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pressurediff">PressureDiff</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa80e188af21b1d7b6ada57dc03a2581e">getPressureDiff</a> (const SUnit *SU) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21c7721fcb12ebb55872b86d33e61e27">computeDFSResult</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute a DFSResult after DAG building is complete, and before any queue comparisons. <a href="#a21c7721fcb12ebb55872b86d33e61e27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheddfsresult">SchedDFSResult</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e08a30279df354627265dbf5fb9d473">getDFSResult</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a non-null DFS result if the scheduling strategy initialized it. <a href="#a9e08a30279df354627265dbf5fb9d473">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7868cdbf0bc5f751ca5de77b9d85831">getScheduledTrees</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34481791fdd8f5d9131431cb0a1a0c01">enterRegion</a> (MachineBasicBlock *bb, MachineBasicBlock::iterator begin, MachineBasicBlock::iterator end, unsigned regioninstrs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement the <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> interface for handling the next scheduling region. <a href="#a34481791fdd8f5d9131431cb0a1a0c01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1583ce23a69e8a1b4af8065e2019c75f">schedule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> interface for scheduling a sequence of reorderable instructions. <a href="#a1583ce23a69e8a1b4af8065e2019c75f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bb19d3e5b68421bc97c3c4b524e7888">computeCyclicCriticalPath</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the cyclic critical path through the DAG. <a href="#a7bb19d3e5b68421bc97c3c4b524e7888">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add5e3e74f2db8e669b830ae35edc8c02">dump</a> () const override</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4be5ffcd4f76d433cc753be146a872b7">buildDAGWithRegPressure</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">ScheduleDAGInstrs::buildSchedGraph</a> with register pressure tracking enabled. <a href="#a4be5ffcd4f76d433cc753be146a872b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3668b7c35103540be55d96cd68948f43">initQueues</a> (ArrayRef&lt; SUnit * &gt; TopRoots, ArrayRef&lt; SUnit * &gt; BotRoots)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release ExitSU predecessors and setup scheduler queues. <a href="#a3668b7c35103540be55d96cd68948f43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04a2c04f918397dbac27a79e58807136">scheduleMI</a> (SUnit *SU, bool IsTopNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move an instruction and update register pressure. <a href="#a04a2c04f918397dbac27a79e58807136">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86daf2b1fb72fdd9a8785a4042ac1457">initRegPressure</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91251ec06d557b21578095955b7b7fa7">updatePressureDiffs</a> (ArrayRef&lt; VRegMaskOrUnit &gt; LiveUses)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the <a href="/web-llvm/docs/api/classes/llvm/pressurediff">PressureDiff</a> array for liveness after scheduling this instruction. <a href="#a91251ec06d557b21578095955b7b7fa7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a556d08e5789e4c99bb9c24aa4e226f9b">updateScheduledPressure</a> (const SUnit *SU, const std::vector&lt; unsigned &gt; &amp;NewMaxPressure)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a920652e64042f72e913f81f9660b4f2f">collectVRegUses</a> (SUnit &amp;SU)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registerclassinfo">RegisterClassInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9539744d7a0c1681540a64e935b671dd">RegClassInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheddfsresult">SchedDFSResult</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3000d2b281b2c4c46c1afb89e060ce04">DFSResult</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Information about DAG subtrees. <a href="#a3000d2b281b2c4c46c1afb89e060ce04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaa92f00c361a14dd3da3992078894f1">ScheduledTrees</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8d156802e79e1d8f76dadc3e5d265b5">LiveRegionEnd</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a1d9cbced9f5f0b7402f69721fd99597c">VReg2SUnitMultiMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a173db28fde5f079ed3dce74bb078551e">VRegUses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps vregs to the SUnits of their uses in the current scheduling region. <a href="#a173db28fde5f079ed3dce74bb078551e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pressurediffs">PressureDiffs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6326ec771a59a9d13a860922f9e21b6c">SUPressureDiffs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac46dc81cc2feaf48751834a3dd13e33a">ShouldTrackPressure</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> pressure in this region computed by initRegPressure. <a href="#ac46dc81cc2feaf48751834a3dd13e33a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dfceb23c208cc886dcd2a82dab9d5c2">ShouldTrackLaneMasks</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/intervalpressure">IntervalPressure</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2d03740fbd63d159d9f7432bfb3de72">RegPressure</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd3a9c68e31ad35d6468f200facdd0e3">RPTracker</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/pressurechange">PressureChange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d37514645e531a608da1d7292057886">RegionCriticalPSets</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of pressure sets that exceed the target's pressure limit before scheduling, listed in increasing set <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> order. <a href="#a4d37514645e531a608da1d7292057886">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/intervalpressure">IntervalPressure</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5910374e4846726fd055b303893720c0">TopPressure</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The top of the unscheduled zone. <a href="#a5910374e4846726fd055b303893720c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7781c87ae9e210811389a826d7d4835">TopRPTracker</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/intervalpressure">IntervalPressure</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a842d507c07056303d6aef3eb5acfe2b2">BotPressure</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The bottom of the unscheduled zone. <a href="#a842d507c07056303d6aef3eb5acfe2b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a461ba62db23baf1682449292b89e4fe1">BotRPTracker</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive">ScheduleDAGMILive</a> is an implementation of <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> that schedules machine instructions while updating <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> and tracking regpressure.</p>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ScheduleDAGMILive() {#a67da2c9a62e43ae7b66bc5ca91f55a05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ScheduleDAGMILive::ScheduleDAGMILive (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> &gt; S)</td>
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



<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="#a842d507c07056303d6aef3eb5acfe2b2">BotPressure</a>, <a href="#a461ba62db23baf1682449292b89e4fe1">BotRPTracker</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a9539744d7a0c1681540a64e935b671dd">RegClassInfo</a>, <a href="#af2d03740fbd63d159d9f7432bfb3de72">RegPressure</a>, <a href="#abd3a9c68e31ad35d6468f200facdd0e3">RPTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a629982ca3ef5632e63f32b5682fde927">llvm::ScheduleDAGMI::ScheduleDAGMI</a>, <a href="#a5910374e4846726fd055b303893720c0">TopPressure</a> and <a href="#af7781c87ae9e210811389a826d7d4835">TopRPTracker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnscheduledagmilive/#a586d595322e6cb11cc1663b937d9aca7">llvm::GCNScheduleDAGMILive::GCNScheduleDAGMILive</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a771c24fd27edfc5b9fdf7ae8422cc236">llvm::SIScheduleDAGMI::SIScheduleDAGMI</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#a93b6189b77c7f1e42ace4d1c9940cd90">llvm::VLIWMachineScheduler::VLIWMachineScheduler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ScheduleDAGMILive() {#ada767569b82d6e57bf0b25f5d35d22df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGMILive::~ScheduleDAGMILive ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1184 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>Reference <a href="#a3000d2b281b2c4c46c1afb89e060ce04">DFSResult</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeCyclicCriticalPath() {#a7bb19d3e5b68421bc97c3c4b524e7888}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ScheduleDAGMILive::computeCyclicCriticalPath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the cyclic critical path through the DAG.</p>


<p>Compute the max cyclic critical path through the DAG.</p>


<p>The scheduling DAG only provides the critical path for single block loops. To handle loops that span blocks, we could use the vreg path latencies provided by <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics">MachineTraceMetrics</a> instead. However, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics">MachineTraceMetrics</a> is not currently available for use in the scheduler.</p>


<p>The cyclic path estimation identifies a def-use pair that crosses the back edge and considers the depth and height of the nodes. For example, consider the following instruction sequence where each instruction has unit latency and defines an eponymous virtual register:</p>


<p>a-&gt;b(a,c)-&gt;c(b)-&gt;d(c)-&gt;exit</p>


<p>The cyclic critical path is a two cycles: b-&gt;c-&gt;b The acyclic critical path is four cycles: a-&gt;b-&gt;c-&gt;d-&gt;exit LiveOutHeight = height(c) = len(c-&gt;d-&gt;exit) = 2 LiveOutDepth = depth(c) + 1 = len(a-&gt;b-&gt;c) + 1 = 3 LiveInHeight = height(b) + 1 = len(b-&gt;c-&gt;d-&gt;exit) + 1 = 4 LiveInDepth = depth(b) = len(a-&gt;b) = 1</p>


<p>LiveOutDepth - LiveInDepth = 3 - 1 = 2 LiveInHeight - LiveOutHeight = 4 - 2 = 2 CyclicCriticalPath = min(2, 2) = 2</p>


<p>This could be relevant to PostRA scheduling, but is currently implemented assuming <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a>.</p>


<p>Declaration at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1574 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8926b25df7254ba2730fa5d7ec139862">llvm::SUnit::getDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a582da862b28b876ef2235781392cffa6">llvm::SUnit::getHeight</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab75cd37a7a0319d5a4c77189cca106ec">llvm::ScheduleDAGInstrs::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a7e1ec6260b229b2f5913405b758bc146">llvm::LiveRange::getVNInfoBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae72fbcf51be7574c84817cde814df07e">llvm::VNInfo::isPHIDef</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a72e0568b7bf0e9a97260c34264a549a0">llvm::SUnit::Latency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>, <a href="#abd3a9c68e31ad35d6468f200facdd0e3">RPTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a527e4a21e13a8455c75eb0d811701066">llvm::LiveQueryResult::valueIn</a> and <a href="#a173db28fde5f079ed3dce74bb078551e">VRegUses</a>.</p>

</div>
</div>

### computeDFSResult() {#a21c7721fcb12ebb55872b86d33e61e27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMILive::computeDFSResult ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute a DFSResult after DAG building is complete, and before any queue comparisons.</p>

<p>Declaration at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1538 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a3000d2b281b2c4c46c1afb89e060ce04">DFSResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a20646b5e577c00ae6fc2912a4081f9d5">MinSubtreeSize</a>, <a href="#aeaa92f00c361a14dd3da3992078894f1">ScheduledTrees</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/ilpscheduler/#a6fc742f69804969334c5298829787a0d">anonymous{MachineScheduler.cpp}::ILPScheduler::initialize</a>.</p>

</div>
</div>

### dump() {#add5e3e74f2db8e669b830ae35edc8c02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMILive::dump ()</td>
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



<p>Declaration at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1422 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurediff/#a86962b61c920a437e06eda5dafd929d5">llvm::PressureDiff::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a917f4d40ed0bbdaf4ab50e5df4de067b">llvm::ScheduleDAG::dumpNodeAll</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a521bf68518a92483130a58680716d153">llvm::ScheduleDAG::EntrySU</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a>, <a href="#a24c23a8dc39475b1e913e41f1249c9f7">getPressureDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#abb11b650b88a61630eba2a1b2eaa6fd0">llvm::ScheduleDAGInstrs::SchedModel</a>, <a href="#ac46dc81cc2feaf48751834a3dd13e33a">ShouldTrackPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>.</p>


<p>Referenced by <a href="#a1583ce23a69e8a1b4af8065e2019c75f">schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>.</p>

</div>
</div>

### enterRegion() {#a34481791fdd8f5d9131431cb0a1a0c01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMILive::enterRegion (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * bb, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> end, unsigned regioninstrs)</td>
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

<p>Implement the <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> interface for handling the next scheduling region.</p>


<p>enterRegion - Called back from <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a8539983d1d0a8b07d92b91c16b9f7a5a">MachineScheduler::runOnMachineFunction</a> after crossing a scheduling boundary.</p>


<p>This covers all instructions in a block, while <a href="#a1583ce23a69e8a1b4af8065e2019c75f">schedule()</a> may only cover a subset.</p>


<p>[begin, end) includes all instructions in the region, including the boundary itself and single-instruction regions that don't get scheduled.</p>


<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab50b64c518a7455daf3e0bc87aee5514">llvm::ScheduleDAGInstrs::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a21805259f54dab47c2b3da009216996a">llvm::ScheduleDAGInstrs::end</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a78e3672daf3301153eac2266dbc32885">llvm::ScheduleDAGMI::enterRegion</a>, <a href="#ae8d156802e79e1d8f76dadc3e5d265b5">LiveRegionEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a3f74b283acf0dfb537bc387e49344f04">llvm::ScheduleDAGInstrs::RegionEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a0318c90d99b85c47bc82d9e0844462f6">llvm::ScheduleDAGMI::SchedImpl</a>, <a href="#a3dfceb23c208cc886dcd2a82dab9d5c2">ShouldTrackLaneMasks</a>, <a href="#ac46dc81cc2feaf48751834a3dd13e33a">ShouldTrackPressure</a> and <a href="#a6326ec771a59a9d13a860922f9e21b6c">SUPressureDiffs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a0fdf731113f2b02fd779a07e4d433717">llvm::GCNIterativeScheduler::enterRegion</a>.</p>

</div>
</div>

### getBotPressure() {#ad1a95fae69c6ef3a956f2450e417edcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IntervalPressure &amp; llvm::ScheduleDAGMILive::getBotPressure ()</td>
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

<p>Get current register pressure for the bottom scheduled instructions.</p>

<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a842d507c07056303d6aef3eb5acfe2b2">BotPressure</a>.</p>

</div>
</div>

### getBotRPTracker() {#a642560b62069c00ff76aa0a3f27a54b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegPressureTracker &amp; llvm::ScheduleDAGMILive::getBotRPTracker ()</td>
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



<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a461ba62db23baf1682449292b89e4fe1">BotRPTracker</a>.</p>

</div>
</div>

### getDFSResult() {#a9e08a30279df354627265dbf5fb9d473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SchedDFSResult * llvm::ScheduleDAGMILive::getDFSResult ()</td>
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

<p>Return a non-null DFS result if the scheduling strategy initialized it.</p>

<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a3000d2b281b2c4c46c1afb89e060ce04">DFSResult</a>.</p>

</div>
</div>

### getPressureDiff() {#a24c23a8dc39475b1e913e41f1249c9f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PressureDiff &amp; llvm::ScheduleDAGMILive::getPressureDiff (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a> and <a href="#a6326ec771a59a9d13a860922f9e21b6c">SUPressureDiffs</a>.</p>


<p>Referenced by <a href="#add5e3e74f2db8e669b830ae35edc8c02">dump</a>, <a href="#a91251ec06d557b21578095955b7b7fa7">updatePressureDiffs</a> and <a href="#a556d08e5789e4c99bb9c24aa4e226f9b">updateScheduledPressure</a>.</p>

</div>
</div>

### getPressureDiff() {#aa80e188af21b1d7b6ada57dc03a2581e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PressureDiff &amp; llvm::ScheduleDAGMILive::getPressureDiff (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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



<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a> and <a href="#a6326ec771a59a9d13a860922f9e21b6c">SUPressureDiffs</a>.</p>

</div>
</div>

### getRegionCriticalPSets() {#af06cc7cea58d96c7e069499a976ca8a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; PressureChange &gt; &amp; llvm::ScheduleDAGMILive::getRegionCriticalPSets ()</td>
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



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a4d37514645e531a608da1d7292057886">RegionCriticalPSets</a>.</p>

</div>
</div>

### getRegPressure() {#ac9bc3efdc06ed731273758563df1b9eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IntervalPressure &amp; llvm::ScheduleDAGMILive::getRegPressure ()</td>
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

<p>Get register pressure for the entire scheduling region before scheduling.</p>

<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#af2d03740fbd63d159d9f7432bfb3de72">RegPressure</a>.</p>

</div>
</div>

### getScheduledTrees() {#ae7868cdbf0bc5f751ca5de77b9d85831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::ScheduleDAGMILive::getScheduledTrees ()</td>
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



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#aeaa92f00c361a14dd3da3992078894f1">ScheduledTrees</a>.</p>

</div>
</div>

### getTopPressure() {#aefb5c9c3ec4fdd43313202df94e3c3c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IntervalPressure &amp; llvm::ScheduleDAGMILive::getTopPressure ()</td>
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

<p>Get current register pressure for the top scheduled instructions.</p>

<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a5910374e4846726fd055b303893720c0">TopPressure</a>.</p>

</div>
</div>

### getTopRPTracker() {#aac50964e02990b51922da2dc47576b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegPressureTracker &amp; llvm::ScheduleDAGMILive::getTopRPTracker ()</td>
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



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#af7781c87ae9e210811389a826d7d4835">TopRPTracker</a>.</p>

</div>
</div>

### hasVRegLiveness() {#a91c62f0ae0c40d54d8dd13c703618af4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScheduleDAGMILive::hasVRegLiveness ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this DAG supports VReg liveness and RegPressure.</p>

<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### isTrackingPressure() {#a87daf83eb223263e4c8766d10aa911be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScheduleDAGMILive::isTrackingPressure ()</td>
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

<p>Return true if register pressure tracking is enabled.</p>

<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#ac46dc81cc2feaf48751834a3dd13e33a">ShouldTrackPressure</a>.</p>

</div>
</div>

### schedule() {#a1583ce23a69e8a1b4af8065e2019c75f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMILive::schedule ()</td>
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

<p>Implement <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> interface for scheduling a sequence of reorderable instructions.</p>


<p>schedule - Called back from <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a8539983d1d0a8b07d92b91c16b9f7a5a">MachineScheduler::runOnMachineFunction</a> after setting up the current scheduling region.</p>


<p>[RegionBegin, RegionEnd) only includes instructions that have DAG nodes, not scheduling boundaries.</p>


<p>This is a skeletal driver, with all the functionality pushed into helpers, so that it can be easily extended by experimental schedulers. Generally, implementing <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> should be sufficient to implement a new scheduling algorithm. However, if a scheduler further subclasses <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive">ScheduleDAGMILive</a> then it will want to override this virtual method in order to update any specialized state.</p>


<p>Declaration at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1455 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab50b64c518a7455daf3e0bc87aee5514">llvm::ScheduleDAGInstrs::begin</a>, <a href="#a4be5ffcd4f76d433cc753be146a872b7">buildDAGWithRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a569fc4139bec0217794e9f830d6ba852">llvm::ScheduleDAGMI::checkSchedLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a7435e842606f5db4bca092e5829befc6">llvm::ScheduleDAGMI::CurrentBottom</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac8abe1b0d869087bd0c14a6637356dc0">llvm::ScheduleDAGMI::CurrentTop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a3000d2b281b2c4c46c1afb89e060ce04">DFSResult</a>, <a href="#add5e3e74f2db8e669b830ae35edc8c02">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a01b02e76c87211e7084ec17f18a2d16f">llvm::ScheduleDAGMI::dumpSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a6d0a0b4903e8d4d12c98b0f43fe83878">llvm::ScheduleDAGMI::findRootsAndBiasEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="#a3668b7c35103540be55d96cd68948f43">initQueues</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac2dafe98c88d43b256622413886e2152">llvm::ScheduleDAGMI::placeDebugValues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a2aa2eb6fd6a44ff6b9cbad960d446c7a">llvm::ScheduleDAGMI::postProcessDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e9fde7ed08fd233750d0a947147dfa1">llvm::PrintDAGs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a0318c90d99b85c47bc82d9e0844462f6">llvm::ScheduleDAGMI::SchedImpl</a>, <a href="#aeaa92f00c361a14dd3da3992078894f1">ScheduledTrees</a>, <a href="#a04a2c04f918397dbac27a79e58807136">scheduleMI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#abfdd9a95217810c69b2557060a130318">llvm::ScheduleDAGMI::updateQueues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a8b7babb023cad0842f5a177e7abe3651">llvm::ScheduleDAGMI::viewGraph</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5ec9cfe35d76125af923975fa0c1730a">llvm::ViewMISchedDAGs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### buildDAGWithRegPressure() {#a4be5ffcd4f76d433cc753be146a872b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMILive::buildDAGWithRegPressure ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Call <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">ScheduleDAGInstrs::buildSchedGraph</a> with register pressure tracking enabled.</p>


<p>Build the DAG and setup three register pressure trackers.</p>


<p>This sets up three trackers. RPTracker will cover the entire DAG region, TopTracker and BottomTracker will be initialized to the top and bottom of the DAG region without covereing any unscheduled instruction.</p>


<p>Declaration at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1515 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a79b8428bb41e16b71ae2bb0139bce5eb">llvm::ScheduleDAGMI::AA</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="#a86daf2b1fb72fdd9a8785a4042ac1457">initRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>, <a href="#ae8d156802e79e1d8f76dadc3e5d265b5">LiveRegionEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="#a9539744d7a0c1681540a64e935b671dd">RegClassInfo</a>, <a href="#a4d37514645e531a608da1d7292057886">RegionCriticalPSets</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a3f74b283acf0dfb537bc387e49344f04">llvm::ScheduleDAGInstrs::RegionEnd</a>, <a href="#abd3a9c68e31ad35d6468f200facdd0e3">RPTracker</a>, <a href="#a3dfceb23c208cc886dcd2a82dab9d5c2">ShouldTrackLaneMasks</a>, <a href="#ac46dc81cc2feaf48751834a3dd13e33a">ShouldTrackPressure</a> and <a href="#a6326ec771a59a9d13a860922f9e21b6c">SUPressureDiffs</a>.</p>


<p>Referenced by <a href="#a1583ce23a69e8a1b4af8065e2019c75f">schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>.</p>

</div>
</div>

### collectVRegUses() {#a920652e64042f72e913f81f9660b4f2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMILive::collectVRegUses (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; SU)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">llvm::LaneBitmask::getNone</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/vreg2sunit/#a62cea84ba15a90f1f6c497f16d8eeda3">llvm::VReg2SUnit::SU</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a96bb77f51ee973b0613bf5083144fa69">llvm::ScheduleDAGInstrs::TrackLaneMasks</a> and <a href="#a173db28fde5f079ed3dce74bb078551e">VRegUses</a>.</p>


<p>Referenced by <a href="#a86daf2b1fb72fdd9a8785a4042ac1457">initRegPressure</a>.</p>

</div>
</div>

### initQueues() {#a3668b7c35103540be55d96cd68948f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMILive::initQueues (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; TopRoots, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; BotRoots)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Release ExitSU predecessors and setup scheduler queues.</p>


<p>Re-position the Top RP tracker in case the region beginning has changed.</p>


<p>Declaration at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1635 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac8abe1b0d869087bd0c14a6637356dc0">llvm::ScheduleDAGMI::CurrentTop</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1f98694f104d052d71ed74ade38d69f0">llvm::ScheduleDAGMI::initQueues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae81ad8ece7681af658742f6d4e2fcfb1">llvm::ScheduleDAGInstrs::RegionBegin</a>, <a href="#ac46dc81cc2feaf48751834a3dd13e33a">ShouldTrackPressure</a> and <a href="#af7781c87ae9e210811389a826d7d4835">TopRPTracker</a>.</p>


<p>Referenced by <a href="#a1583ce23a69e8a1b4af8065e2019c75f">schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>.</p>

</div>
</div>

### initRegPressure() {#a86daf2b1fb72fdd9a8785a4042ac1457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMILive::initRegPressure ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>, <a href="#a461ba62db23baf1682449292b89e4fe1">BotRPTracker</a>, <a href="#a920652e64042f72e913f81f9660b4f2f">collectVRegUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb6fca77863850136760be488d6ea345">llvm::dumpRegSetPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>, <a href="#ae8d156802e79e1d8f76dadc3e5d265b5">LiveRegionEnd</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a1b09f4d9c91e25f7bc2ac60b3b929d11">llvm::ScheduleDAG::MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a459acab05344caa836aa036f1829c928">priorNonDebug</a>, <a href="#a9539744d7a0c1681540a64e935b671dd">RegClassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae81ad8ece7681af658742f6d4e2fcfb1">llvm::ScheduleDAGInstrs::RegionBegin</a>, <a href="#a4d37514645e531a608da1d7292057886">RegionCriticalPSets</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a3f74b283acf0dfb537bc387e49344f04">llvm::ScheduleDAGInstrs::RegionEnd</a>, <a href="#abd3a9c68e31ad35d6468f200facdd0e3">RPTracker</a>, <a href="#a3dfceb23c208cc886dcd2a82dab9d5c2">ShouldTrackLaneMasks</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>, <a href="#af7781c87ae9e210811389a826d7d4835">TopRPTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>, <a href="#a91251ec06d557b21578095955b7b7fa7">updatePressureDiffs</a> and <a href="#a173db28fde5f079ed3dce74bb078551e">VRegUses</a>.</p>


<p>Referenced by <a href="#a4be5ffcd4f76d433cc753be146a872b7">buildDAGWithRegPressure</a>.</p>

</div>
</div>

### scheduleMI() {#a04a2c04f918397dbac27a79e58807136}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMILive::scheduleMI (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, bool IsTopNode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move an instruction and update register pressure.</p>

<p>Declaration at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1645 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a8affa4b2a934ff08aa04e63253a00126">llvm::RegisterOperands::adjustLaneLiveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a461ba62db23baf1682449292b89e4fe1">BotRPTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a74e0a918c9705f23a1e5b66f68cc97e9">llvm::RegisterOperands::collect</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a7435e842606f5db4bca092e5829befc6">llvm::ScheduleDAGMI::CurrentBottom</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac8abe1b0d869087bd0c14a6637356dc0">llvm::ScheduleDAGMI::CurrentTop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#acee6dacd4d30da478f3ad67f7fc27142">llvm::RegisterOperands::detectDeadDefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb6fca77863850136760be488d6ea345">llvm::dumpRegSetPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ac198a5fb130b4c09836ba20e01b4290d">llvm::SUnit::isBottomReady</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae0b8da4dfde85d4ddc32359ca52dc493">llvm::SUnit::isTopReady</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a2209b15a069023499cc665b373e67703">llvm::ScheduleDAGMI::moveInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a1b09f4d9c91e25f7bc2ac60b3b929d11">llvm::ScheduleDAG::MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a1c8a9363a3eb113ca42064a03636b135">nextIfDebug</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a459acab05344caa836aa036f1829c928">priorNonDebug</a>, <a href="#a3dfceb23c208cc886dcd2a82dab9d5c2">ShouldTrackLaneMasks</a>, <a href="#ac46dc81cc2feaf48751834a3dd13e33a">ShouldTrackPressure</a>, <a href="#af7781c87ae9e210811389a826d7d4835">TopRPTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>, <a href="#a91251ec06d557b21578095955b7b7fa7">updatePressureDiffs</a> and <a href="#a556d08e5789e4c99bb9c24aa4e226f9b">updateScheduledPressure</a>.</p>


<p>Referenced by <a href="#a1583ce23a69e8a1b4af8065e2019c75f">schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>.</p>

</div>
</div>

### updatePressureDiffs() {#a91251ec06d557b21578095955b7b7fa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMILive::updatePressureDiffs (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a> &gt; LiveUses)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the <a href="/web-llvm/docs/api/classes/llvm/pressurediff">PressureDiff</a> array for liveness after scheduling this instruction.</p>

<p>Declaration at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1355 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pressurediff/#aae6716327eea2325dc426c98cbcc74b4">llvm::PressureDiff::addPressureChange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>, <a href="#a461ba62db23baf1682449292b89e4fe1">BotRPTracker</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurediff/#a86962b61c920a437e06eda5dafd929d5">llvm::PressureDiff::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="#a24c23a8dc39475b1e913e41f1249c9f7">getPressureDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a7e1ec6260b229b2f5913405b758bc146">llvm::LiveRange::getVNInfoBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a1b09f4d9c91e25f7bc2ac60b3b929d11">llvm::ScheduleDAG::MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a1c8a9363a3eb113ca42064a03636b135">nextIfDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e30e18d6f7ebd943eaf8ebc3a2b2930">llvm::PrintLaneMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a788c5905de970028eb0efa2266bd10bf">llvm::printVRegOrUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>, <a href="#a3dfceb23c208cc886dcd2a82dab9d5c2">ShouldTrackLaneMasks</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a527e4a21e13a8455c75eb0d811701066">llvm::LiveQueryResult::valueIn</a> and <a href="#a173db28fde5f079ed3dce74bb078551e">VRegUses</a>.</p>


<p>Referenced by <a href="#a86daf2b1fb72fdd9a8785a4042ac1457">initRegPressure</a> and <a href="#a04a2c04f918397dbac27a79e58807136">scheduleMI</a>.</p>

</div>
</div>

### updateScheduledPressure() {#a556d08e5789e4c99bb9c24aa4e226f9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMILive::updateScheduledPressure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; unsigned &gt; &amp; NewMaxPressure)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1327 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a461ba62db23baf1682449292b89e4fe1">BotRPTracker</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a24c23a8dc39475b1e913e41f1249c9f7">getPressureDiff</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a9539744d7a0c1681540a64e935b671dd">RegClassInfo</a>, <a href="#a4d37514645e531a608da1d7292057886">RegionCriticalPSets</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>.</p>


<p>Referenced by <a href="#a04a2c04f918397dbac27a79e58807136">scheduleMI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BotPressure {#a842d507c07056303d6aef3eb5acfe2b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntervalPressure llvm::ScheduleDAGMILive::BotPressure</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The bottom of the unscheduled zone.</p>

<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#ad1a95fae69c6ef3a956f2450e417edcc">getBotPressure</a> and <a href="#a67da2c9a62e43ae7b66bc5ca91f55a05">ScheduleDAGMILive</a>.</p>

</div>
</div>

### BotRPTracker {#a461ba62db23baf1682449292b89e4fe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegPressureTracker llvm::ScheduleDAGMILive::BotRPTracker</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a642560b62069c00ff76aa0a3f27a54b0">getBotRPTracker</a>, <a href="#a86daf2b1fb72fdd9a8785a4042ac1457">initRegPressure</a>, <a href="#a67da2c9a62e43ae7b66bc5ca91f55a05">ScheduleDAGMILive</a>, <a href="#a04a2c04f918397dbac27a79e58807136">scheduleMI</a>, <a href="#a91251ec06d557b21578095955b7b7fa7">updatePressureDiffs</a> and <a href="#a556d08e5789e4c99bb9c24aa4e226f9b">updateScheduledPressure</a>.</p>

</div>
</div>

### DFSResult {#a3000d2b281b2c4c46c1afb89e060ce04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedDFSResult* llvm::ScheduleDAGMILive::DFSResult = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Information about DAG subtrees.</p>


<p>If DFSResult is NULL, then SchedulerTrees will be empty.</p>


<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a21c7721fcb12ebb55872b86d33e61e27">computeDFSResult</a>, <a href="#a9e08a30279df354627265dbf5fb9d473">getDFSResult</a>, <a href="#a1583ce23a69e8a1b4af8065e2019c75f">schedule</a> and <a href="#ada767569b82d6e57bf0b25f5d35d22df">~ScheduleDAGMILive</a>.</p>

</div>
</div>

### LiveRegionEnd {#ae8d156802e79e1d8f76dadc3e5d265b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::ScheduleDAGMILive::LiveRegionEnd</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a4be5ffcd4f76d433cc753be146a872b7">buildDAGWithRegPressure</a>, <a href="#a34481791fdd8f5d9131431cb0a1a0c01">enterRegion</a> and <a href="#a86daf2b1fb72fdd9a8785a4042ac1457">initRegPressure</a>.</p>

</div>
</div>

### RegClassInfo {#a9539744d7a0c1681540a64e935b671dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterClassInfo* llvm::ScheduleDAGMILive::RegClassInfo</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a4be5ffcd4f76d433cc753be146a872b7">buildDAGWithRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#acece183f6f4f1551b1a1fa9dd93925a5">llvm::VLIWMachineScheduler::getRegClassInfo</a>, <a href="#a86daf2b1fb72fdd9a8785a4042ac1457">initRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#ab6c5bda21b39ff9494fc2661de4aa974">llvm::SIScheduleDAGMI::initRPTracker</a>, <a href="#a67da2c9a62e43ae7b66bc5ca91f55a05">ScheduleDAGMILive</a> and <a href="#a556d08e5789e4c99bb9c24aa4e226f9b">updateScheduledPressure</a>.</p>

</div>
</div>

### RegionCriticalPSets {#a4d37514645e531a608da1d7292057886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;PressureChange&gt; llvm::ScheduleDAGMILive::RegionCriticalPSets</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of pressure sets that exceed the target's pressure limit before scheduling, listed in increasing set <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> order.</p>


<p>Each pressure set is paired with its max pressure in the currently scheduled regions.</p>


<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a4be5ffcd4f76d433cc753be146a872b7">buildDAGWithRegPressure</a>, <a href="#af06cc7cea58d96c7e069499a976ca8a0">getRegionCriticalPSets</a>, <a href="#a86daf2b1fb72fdd9a8785a4042ac1457">initRegPressure</a> and <a href="#a556d08e5789e4c99bb9c24aa4e226f9b">updateScheduledPressure</a>.</p>

</div>
</div>

### RegPressure {#af2d03740fbd63d159d9f7432bfb3de72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntervalPressure llvm::ScheduleDAGMILive::RegPressure</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#ac9bc3efdc06ed731273758563df1b9eb">getRegPressure</a> and <a href="#a67da2c9a62e43ae7b66bc5ca91f55a05">ScheduleDAGMILive</a>.</p>

</div>
</div>

### RPTracker {#abd3a9c68e31ad35d6468f200facdd0e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegPressureTracker llvm::ScheduleDAGMILive::RPTracker</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a4be5ffcd4f76d433cc753be146a872b7">buildDAGWithRegPressure</a>, <a href="#a7bb19d3e5b68421bc97c3c4b524e7888">computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a1ad25ec135803e03e30ccb77c4b734cb">llvm::SIScheduleDAGMI::getInRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#aba5a6d4d063ef267e00c9e98494449f7">llvm::SIScheduleDAGMI::getOutRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ab7703967e4547dc33bde51d360068021">llvm::GCNIterativeScheduler::getSchedulePressure</a>, <a href="#a86daf2b1fb72fdd9a8785a4042ac1457">initRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#ab6c5bda21b39ff9494fc2661de4aa974">llvm::SIScheduleDAGMI::initRPTracker</a> and <a href="#a67da2c9a62e43ae7b66bc5ca91f55a05">ScheduleDAGMILive</a>.</p>

</div>
</div>

### ScheduledTrees {#aeaa92f00c361a14dd3da3992078894f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::ScheduleDAGMILive::ScheduledTrees</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a21c7721fcb12ebb55872b86d33e61e27">computeDFSResult</a>, <a href="#ae7868cdbf0bc5f751ca5de77b9d85831">getScheduledTrees</a> and <a href="#a1583ce23a69e8a1b4af8065e2019c75f">schedule</a>.</p>

</div>
</div>

### ShouldTrackLaneMasks {#a3dfceb23c208cc886dcd2a82dab9d5c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScheduleDAGMILive::ShouldTrackLaneMasks = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a4be5ffcd4f76d433cc753be146a872b7">buildDAGWithRegPressure</a>, <a href="#a34481791fdd8f5d9131431cb0a1a0c01">enterRegion</a>, <a href="#a86daf2b1fb72fdd9a8785a4042ac1457">initRegPressure</a>, <a href="#a04a2c04f918397dbac27a79e58807136">scheduleMI</a> and <a href="#a91251ec06d557b21578095955b7b7fa7">updatePressureDiffs</a>.</p>

</div>
</div>

### ShouldTrackPressure {#ac46dc81cc2feaf48751834a3dd13e33a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScheduleDAGMILive::ShouldTrackPressure = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> pressure in this region computed by initRegPressure.</p>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a4be5ffcd4f76d433cc753be146a872b7">buildDAGWithRegPressure</a>, <a href="#add5e3e74f2db8e669b830ae35edc8c02">dump</a>, <a href="#a34481791fdd8f5d9131431cb0a1a0c01">enterRegion</a>, <a href="#a3668b7c35103540be55d96cd68948f43">initQueues</a>, <a href="#a87daf83eb223263e4c8766d10aa911be">isTrackingPressure</a> and <a href="#a04a2c04f918397dbac27a79e58807136">scheduleMI</a>.</p>

</div>
</div>

### SUPressureDiffs {#a6326ec771a59a9d13a860922f9e21b6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PressureDiffs llvm::ScheduleDAGMILive::SUPressureDiffs</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a4be5ffcd4f76d433cc753be146a872b7">buildDAGWithRegPressure</a>, <a href="#a34481791fdd8f5d9131431cb0a1a0c01">enterRegion</a>, <a href="#a24c23a8dc39475b1e913e41f1249c9f7">getPressureDiff</a> and <a href="#aa80e188af21b1d7b6ada57dc03a2581e">getPressureDiff</a>.</p>

</div>
</div>

### TopPressure {#a5910374e4846726fd055b303893720c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntervalPressure llvm::ScheduleDAGMILive::TopPressure</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The top of the unscheduled zone.</p>

<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#aefb5c9c3ec4fdd43313202df94e3c3c1">getTopPressure</a> and <a href="#a67da2c9a62e43ae7b66bc5ca91f55a05">ScheduleDAGMILive</a>.</p>

</div>
</div>

### TopRPTracker {#af7781c87ae9e210811389a826d7d4835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegPressureTracker llvm::ScheduleDAGMILive::TopRPTracker</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#aac50964e02990b51922da2dc47576b64">getTopRPTracker</a>, <a href="#a3668b7c35103540be55d96cd68948f43">initQueues</a>, <a href="#a86daf2b1fb72fdd9a8785a4042ac1457">initRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a>, <a href="#a67da2c9a62e43ae7b66bc5ca91f55a05">ScheduleDAGMILive</a> and <a href="#a04a2c04f918397dbac27a79e58807136">scheduleMI</a>.</p>

</div>
</div>

### VRegUses {#a173db28fde5f079ed3dce74bb078551e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VReg2SUnitMultiMap llvm::ScheduleDAGMILive::VRegUses</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps vregs to the SUnits of their uses in the current scheduling region.</p>

<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a920652e64042f72e913f81f9660b4f2f">collectVRegUses</a>, <a href="#a7bb19d3e5b68421bc97c3c4b524e7888">computeCyclicCriticalPath</a>, <a href="#a86daf2b1fb72fdd9a8785a4042ac1457">initRegPressure</a> and <a href="#a91251ec06d557b21578095955b7b7fa7">updatePressureDiffs</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
