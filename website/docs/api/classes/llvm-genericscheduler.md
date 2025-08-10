---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/genericscheduler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GenericScheduler` Class

<p><a href="/web-llvm/docs/api/classes/llvm/genericscheduler">GenericScheduler</a> shrinks the unscheduled zone using heuristics to balance the schedule. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GenericScheduler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">llvm/CodeGen/MachineScheduler.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase">GenericSchedulerBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for <a href="/web-llvm/docs/api/classes/llvm/genericscheduler">GenericScheduler</a>. <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy">GCNSchedStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a minimal scheduler strategy. <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy">PPCPreRASchedStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> implementation for PowerPC pre RA scheduling. <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8dd2d1a734d828faa812af4a9a135e3">GenericScheduler</a> (const MachineSchedContext *C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8e2225e71c3b7d40575a2ab9bfffc78">initPolicy</a> (MachineBasicBlock::iterator Begin, MachineBasicBlock::iterator End, unsigned NumRegionInstrs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the per-region scheduling policy. <a href="#ac8e2225e71c3b7d40575a2ab9bfffc78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8329c2fe0a6267d1e0f94dc4aecc5892">dumpPolicy</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1ad1eb71432f2b381687717ced8b052">shouldTrackPressure</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if pressure tracking is needed before building the DAG and initializing this strategy. <a href="#ab1ad1eb71432f2b381687717ced8b052">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada10b0f311c10e4c89f7449fdd38b965">shouldTrackLaneMasks</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if lanemasks should be tracked. <a href="#ada10b0f311c10e4c89f7449fdd38b965">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8cddd2ea015f8177a8395035f87e332">initialize</a> (ScheduleDAGMI *dag) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the strategy after building the DAG for a new region. <a href="#aa8cddd2ea015f8177a8395035f87e332">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4cc558b6cbcc4e9cea5df915c197e14">pickNode</a> (bool &amp;IsTopNode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick the best node to balance the schedule. Implements <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a>. <a href="#ad4cc558b6cbcc4e9cea5df915c197e14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf574ab3455d7292bed998d8ba50bfeb">schedNode</a> (SUnit *SU, bool IsTopNode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the scheduler's state after scheduling a node. <a href="#adf574ab3455d7292bed998d8ba50bfeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc4369e500d02fac8e313e69947b2611">releaseTopNode</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When all predecessor dependencies have been resolved, free this node for top-down scheduling. <a href="#acc4369e500d02fac8e313e69947b2611">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a779430fb54fa19f8bf9d94d1618bf7f5">releaseBottomNode</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When all successor dependencies have been resolved, free this node for bottom-up scheduling. <a href="#a779430fb54fa19f8bf9d94d1618bf7f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac047246e76df6b86564a6b62c2403aef">registerRoots</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notify this strategy that all roots have been released (including those that depend on EntrySU or ExitSU). <a href="#ac047246e76df6b86564a6b62c2403aef">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa33f27fbf7be1e7e53512ceb6de885">checkAcyclicLatency</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set IsAcyclicLatencyLimited if the acyclic path is longer than the cyclic critical path by more cycles than it takes to drain the instruction buffer. <a href="#a0aa33f27fbf7be1e7e53512ceb6de885">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d12eb20352f092840f7f8df60abe26">initCandidate</a> (SchedCandidate &amp;Cand, SUnit *SU, bool AtTop, const RegPressureTracker &amp;RPTracker, RegPressureTracker &amp;TempTracker)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ef23d22af6c895d9c255de3e940b8bf">tryCandidate</a> (SchedCandidate &amp;Cand, SchedCandidate &amp;TryCand, SchedBoundary *Zone) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply a set of heuristics to a new candidate. <a href="#a6ef23d22af6c895d9c255de3e940b8bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef82bce77971408815c3b90979188d1e">pickNodeBidirectional</a> (bool &amp;IsTopNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick the best candidate node from either the top or bottom queue. <a href="#aef82bce77971408815c3b90979188d1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9779ec3011b4547f9a509af82d87a6e">pickNodeFromQueue</a> (SchedBoundary &amp;Zone, const CandPolicy &amp;ZonePolicy, const RegPressureTracker &amp;RPTracker, SchedCandidate &amp;Candidate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick the best candidate from the queue. <a href="#ad9779ec3011b4547f9a509af82d87a6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad04f609cdff2331741525e5328836598">reschedulePhysReg</a> (SUnit *SU, bool isTop)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive">ScheduleDAGMILive</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75edfd9bb13c765b11b0b400cbe2aaed">DAG</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedboundary">SchedBoundary</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a253bc2bd1ae8e7f36e0c3c1c9bb67367">Top</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedboundary">SchedBoundary</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3763f96e92009d4dc101837627fff3bd">Bot</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33cc1a55125b89319e048d24625a2925">TopCand</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Candidate last picked from Top boundary. <a href="#a33cc1a55125b89319e048d24625a2925">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a190c2995c11bd6de755bbd8311a8f176">BotCand</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Candidate last picked from Bot boundary. <a href="#a190c2995c11bd6de755bbd8311a8f176">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/genericscheduler">GenericScheduler</a> shrinks the unscheduled zone using heuristics to balance the schedule.</p>

<p>Definition at line 1223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GenericScheduler() {#ae8dd2d1a734d828faa812af4a9a135e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericScheduler::GenericScheduler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
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



<p>Definition at line 1225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="#a3763f96e92009d4dc101837627fff3bd">Bot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#abf7a31296b8d3ede091a25b7777c3a15">llvm::GenericSchedulerBase::GenericSchedulerBase</a> and <a href="#a253bc2bd1ae8e7f36e0c3c1c9bb67367">Top</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a14f3300bee7a18474eb2f103afa3ea22">llvm::GCNSchedStrategy::GCNSchedStrategy</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#abba4e9ebd3e9e473606faccedbc063b5">llvm::PPCPreRASchedStrategy::PPCPreRASchedStrategy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dumpPolicy() {#a8329c2fe0a6267d1e0f94dc4aecc5892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GenericScheduler::dumpPolicy ()</td>
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



<p>Declaration at line 1233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3321 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8e13153e8ed7676ddbba73dd9318d35e">llvm::GenericSchedulerBase::RegionPolicy</a>.</p>

</div>
</div>

### initialize() {#aa8cddd2ea015f8177a8395035f87e332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GenericScheduler::initialize (<a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> * DAG)</td>
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

<p>Initialize the strategy after building the DAG for a new region.</p>

<p>Declaration at line 1243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3245 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3763f96e92009d4dc101837627fff3bd">Bot</a>, <a href="#a190c2995c11bd6de755bbd8311a8f176">BotCand</a>, <a href="#a75edfd9bb13c765b11b0b400cbe2aaed">DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a78c0f3feb8a81ca338f843494cff564e">llvm::ScheduleDAGMI::hasVRegLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8e13153e8ed7676ddbba73dd9318d35e">llvm::GenericSchedulerBase::RegionPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a3cab76d375dbb626e5179b96f84fd3dc">llvm::GenericSchedulerBase::Rem</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a9730ea0068843718868a8667f52e3680">llvm::GenericSchedulerBase::SchedModel</a>, <a href="#a253bc2bd1ae8e7f36e0c3c1c9bb67367">Top</a>, <a href="#a33cc1a55125b89319e048d24625a2925">TopCand</a> and <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae9476ffbc2f3f195a2116b13f3186194">llvm::GenericSchedulerBase::TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ab57c0b13438062a884d3e620300fbc03">llvm::GCNSchedStrategy::initialize</a>.</p>

</div>
</div>

### initPolicy() {#ac8e2225e71c3b7d40575a2ab9bfffc78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GenericScheduler::initPolicy (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> End, unsigned NumRegionInstrs)</td>
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

<p>Initialize the per-region scheduling policy.</p>

<p>Declaration at line 1229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3275 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/misched/#a76ffbaf191b81010c8e5da3c4ce028b3aab012f17d1537ed7a7c6d45b1d2fc0e9">llvm::MISched::Bidirectional</a>, <a href="/web-llvm/docs/api/namespaces/llvm/misched/#a76ffbaf191b81010c8e5da3c4ce028b3abd98ce24773c9ca1e3f7ce3c541e43ea">llvm::MISched::BottomUp</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ad0f9f52bf2f7c54d9546cedd1c47ef45">llvm::GenericSchedulerBase::Context</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a589614403a45de30e887d6401dc1be2a">EnableRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1a78b9f867cb5be3a052d6ad972484ca">llvm::TargetLoweringBase::getRegClassFor</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ade3f0d8b35d67c43df9425bb730a9a7c">llvm::TargetSubtargetInfo::getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a9cd7c54e0bb13cc01c4e2a4133a40ee4">llvm::TargetSubtargetInfo::overrideSchedPolicy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa9ff814049edfef549accbca1a8e9eff">llvm::PreRADirection</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8e13153e8ed7676ddbba73dd9318d35e">llvm::GenericSchedulerBase::RegionPolicy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/misched/#a76ffbaf191b81010c8e5da3c4ce028b3ae89742249a15ad5696e3dcec82f0e76a">llvm::MISched::TopDown</a>.</p>

</div>
</div>

### pickNode() {#ad4cc558b6cbcc4e9cea5df915c197e14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * GenericScheduler::pickNode (bool &amp; IsTopNode)</td>
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

<p>Pick the best node to balance the schedule. Implements <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a>.</p>

<p>Declaration at line 1245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3738 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3763f96e92009d4dc101837627fff3bd">Bot</a>, <a href="#a190c2995c11bd6de755bbd8311a8f176">BotCand</a>, <a href="#a75edfd9bb13c765b11b0b400cbe2aaed">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ac198a5fb130b4c09836ba20e01b4290d">llvm::SUnit::isBottomReady</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae0b8da4dfde85d4ddc32359ca52dc493">llvm::SUnit::isTopReady</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a810d389a7def234e94c2631683ab0ece">llvm::GenericSchedulerBase::NoCand</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="#aef82bce77971408815c3b90979188d1e">pickNodeBidirectional</a>, <a href="#ad9779ec3011b4547f9a509af82d87a6e">pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8e13153e8ed7676ddbba73dd9318d35e">llvm::GenericSchedulerBase::RegionPolicy</a>, <a href="#a253bc2bd1ae8e7f36e0c3c1c9bb67367">Top</a>, <a href="#a33cc1a55125b89319e048d24625a2925">TopCand</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a14c35b53586841aad69751a52b7d358a">tracePick</a>.</p>

</div>
</div>

### registerRoots() {#ac047246e76df6b86564a6b62c2403aef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GenericScheduler::registerRoots ()</td>
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

<p>Notify this strategy that all roots have been released (including those that depend on EntrySU or ExitSU).</p>

<p>Declaration at line 1265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3369 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a3763f96e92009d4dc101837627fff3bd">Bot</a>, <a href="#a0aa33f27fbf7be1e7e53512ceb6de885">checkAcyclicLatency</a>, <a href="#a75edfd9bb13c765b11b0b400cbe2aaed">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82ab0315644106de03b36f143328179f">llvm::DumpCriticalPathLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a2f23c1bd760a7a5a5acc6e4eb40bd9d9">EnableCyclicPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8926b25df7254ba2730fa5d7ec139862">llvm::SUnit::getDepth</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a3cab76d375dbb626e5179b96f84fd3dc">llvm::GenericSchedulerBase::Rem</a> and <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a9730ea0068843718868a8667f52e3680">llvm::GenericSchedulerBase::SchedModel</a>.</p>

</div>
</div>

### releaseBottomNode() {#a779430fb54fa19f8bf9d94d1618bf7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericScheduler::releaseBottomNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>When all successor dependencies have been resolved, free this node for bottom-up scheduling.</p>

<p>Definition at line 1257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="#a3763f96e92009d4dc101837627fff3bd">Bot</a>, <a href="#a190c2995c11bd6de755bbd8311a8f176">BotCand</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aa1dfdcdc657e12c47e72d9dbe251ac85">llvm::SUnit::BotReadyCycle</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>.</p>

</div>
</div>

### releaseTopNode() {#acc4369e500d02fac8e313e69947b2611}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericScheduler::releaseTopNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>When all predecessor dependencies have been resolved, free this node for top-down scheduling.</p>

<p>Definition at line 1249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>, <a href="#a253bc2bd1ae8e7f36e0c3c1c9bb67367">Top</a>, <a href="#a33cc1a55125b89319e048d24625a2925">TopCand</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2a6f92b9c5aba34d3b07f3ebe229ccff">llvm::SUnit::TopReadyCycle</a>.</p>

</div>
</div>

### schedNode() {#adf574ab3455d7292bed998d8ba50bfeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GenericScheduler::schedNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, bool IsTopNode)</td>
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

<p>Update the scheduler's state after scheduling a node.</p>


<p>This is the same node that was just returned by <a href="#ad4cc558b6cbcc4e9cea5df915c197e14">pickNode()</a>. However, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive">ScheduleDAGMILive</a> needs to update it's state based on the current cycle before <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> does.</p>


<p>FIXME: Eventually, we may bundle physreg copies rather than rescheduling them here. See comments in biasPhysReg.</p>


<p>Declaration at line 1247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3829 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a3763f96e92009d4dc101837627fff3bd">Bot</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aa1dfdcdc657e12c47e72d9dbe251ac85">llvm::SUnit::BotReadyCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a9d9a8b8d5225f85cecbbada4ce4406b0">llvm::SUnit::hasPhysRegDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#adc4d8df3725fd70ffbaffeead756025c">llvm::SUnit::hasPhysRegUses</a>, <a href="#ad04f609cdff2331741525e5328836598">reschedulePhysReg</a>, <a href="#a253bc2bd1ae8e7f36e0c3c1c9bb67367">Top</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2a6f92b9c5aba34d3b07f3ebe229ccff">llvm::SUnit::TopReadyCycle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a886677d13d24c974e4cb3086df524e7b">llvm::GCNSchedStrategy::schedNode</a>.</p>

</div>
</div>

### shouldTrackLaneMasks() {#ada10b0f311c10e4c89f7449fdd38b965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericScheduler::shouldTrackLaneMasks ()</td>
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

<p>Returns true if lanemasks should be tracked.</p>


<p>LaneMask tracking is necessary to reorder independent subregister defs for the same vreg. This has to be enabled in combination with <a href="#ab1ad1eb71432f2b381687717ced8b052">shouldTrackPressure()</a>.</p>


<p>Definition at line 1239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8e13153e8ed7676ddbba73dd9318d35e">llvm::GenericSchedulerBase::RegionPolicy</a>.</p>

</div>
</div>

### shouldTrackPressure() {#ab1ad1eb71432f2b381687717ced8b052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericScheduler::shouldTrackPressure ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if pressure tracking is needed before building the DAG and initializing this strategy.</p>


<p>Called after initPolicy.</p>


<p>Definition at line 1235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8e13153e8ed7676ddbba73dd9318d35e">llvm::GenericSchedulerBase::RegionPolicy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### checkAcyclicLatency() {#a0aa33f27fbf7be1e7e53512ceb6de885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GenericScheduler::checkAcyclicLatency ()</td>
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

<p>Set IsAcyclicLatencyLimited if the acyclic path is longer than the cyclic critical path by more cycles than it takes to drain the instruction buffer.</p>


<p>We estimate an upper bounds on in-flight instructions as:</p>


<p>CyclesPerIteration = max( CyclicPath, Loop-Resource-Height ) InFlightIterations = AcyclicPath / CyclesPerIteration InFlightResources = InFlightIterations * LoopResources</p>


<p>TODO: <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> execution resources in addition to IssueCount.</p>


<p>Declaration at line 1279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3341 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a3cab76d375dbb626e5179b96f84fd3dc">llvm::GenericSchedulerBase::Rem</a> and <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a9730ea0068843718868a8667f52e3680">llvm::GenericSchedulerBase::SchedModel</a>.</p>


<p>Referenced by <a href="#ac047246e76df6b86564a6b62c2403aef">registerRoots</a>.</p>

</div>
</div>

### initCandidate() {#ab0d12eb20352f092840f7f8df60abe26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GenericScheduler::initCandidate (<a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; Cand, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, bool AtTop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> &amp; RPTracker, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> &amp; TempTracker)</td>
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



<p>Declaration at line 1281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3476 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a87328c4ecbb87961dd2c970d343b9ca0">llvm::GenericSchedulerBase::SchedCandidate::AtTop</a>, <a href="#a75edfd9bb13c765b11b0b400cbe2aaed">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#aff9c3b403c6d4af795dd8be1c9612240">llvm::RegPressureDelta::Excess</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a972fa38378a3d49a9bb48ca584621438">llvm::RegPressureTracker::getMaxDownwardPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a41a3118fb6bd46e397256b3c9794b61c">llvm::RegPressureTracker::getMaxUpwardPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurechange/#ad47247ae6eaa7104e4d4ef6e002840f9">llvm::PressureChange::getPSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurechange/#a1eef24878593ee0080b20b96ce3eb4c4">llvm::PressureChange::getUnitInc</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#af7a0688faef62284ad684e70f342b3da">llvm::RegPressureTracker::getUpwardPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurechange/#a488d33ac015981b0f8e2086fcbd49db2">llvm::PressureChange::isValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a81fbfdac1b8c1e736493b56b50853322">llvm::GenericSchedulerBase::SchedCandidate::RPDelta</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a310a170b7d2442d12634d53db262fb92">llvm::GenericSchedulerBase::SchedCandidate::SU</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae9476ffbc2f3f195a2116b13f3186194">llvm::GenericSchedulerBase::TRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4d101d816188a045c0b595a6a2c5d3a3">llvm::VerifyScheduling</a>.</p>


<p>Referenced by <a href="#ad9779ec3011b4547f9a509af82d87a6e">pickNodeFromQueue</a>.</p>

</div>
</div>

### pickNodeBidirectional() {#aef82bce77971408815c3b90979188d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * GenericScheduler::pickNodeBidirectional (bool &amp; IsTopNode)</td>
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

<p>Pick the best candidate node from either the top or bottom queue.</p>

<p>Declaration at line 1288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3660 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a87328c4ecbb87961dd2c970d343b9ca0">llvm::GenericSchedulerBase::SchedCandidate::AtTop</a>, <a href="#a3763f96e92009d4dc101837627fff3bd">Bot</a>, <a href="#a190c2995c11bd6de755bbd8311a8f176">BotCand</a>, <a href="#a75edfd9bb13c765b11b0b400cbe2aaed">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a810d389a7def234e94c2631683ab0ece">llvm::GenericSchedulerBase::NoCand</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a3e5ec7d7634a70f61fd64c3ef22d02f1">llvm::GenericSchedulerBase::Only1</a>, <a href="#ad9779ec3011b4547f9a509af82d87a6e">pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a361fa10c095c303e093021c6a1d04e75">llvm::GenericSchedulerBase::SchedCandidate::reset</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a294e77c4f7245940981e5e259045c7c0">llvm::GenericSchedulerBase::SchedCandidate::setBest</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8668556014566994c07b21391762551b">llvm::GenericSchedulerBase::setPolicy</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a310a170b7d2442d12634d53db262fb92">llvm::GenericSchedulerBase::SchedCandidate::SU</a>, <a href="#a253bc2bd1ae8e7f36e0c3c1c9bb67367">Top</a>, <a href="#a33cc1a55125b89319e048d24625a2925">TopCand</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a14c35b53586841aad69751a52b7d358a">tracePick</a>, <a href="#a6ef23d22af6c895d9c255de3e940b8bf">tryCandidate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4d101d816188a045c0b595a6a2c5d3a3">llvm::VerifyScheduling</a>.</p>


<p>Referenced by <a href="#ad4cc558b6cbcc4e9cea5df915c197e14">pickNode</a>.</p>

</div>
</div>

### pickNodeFromQueue() {#ad9779ec3011b4547f9a509af82d87a6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GenericScheduler::pickNodeFromQueue (<a href="/web-llvm/docs/api/classes/llvm/schedboundary">SchedBoundary</a> &amp; Zone, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy">CandPolicy</a> &amp; ZonePolicy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> &amp; RPTracker, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; Cand)</td>
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

<p>Pick the best candidate from the queue.</p>


<p>TODO: getMaxPressureDelta results can be mostly cached for each <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> during DAG building. To adjust for the current scheduling location we need to maintain the number of vreg uses remaining to be top-scheduled.</p>


<p>Declaration at line 1290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3635 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a87328c4ecbb87961dd2c970d343b9ca0">llvm::GenericSchedulerBase::SchedCandidate::AtTop</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#aa49fbb78ca6f0a19a967f2f8fb70097d">llvm::SchedBoundary::Available</a>, <a href="#a75edfd9bb13c765b11b0b400cbe2aaed">DAG</a>, <a href="#ab0d12eb20352f092840f7f8df60abe26">initCandidate</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a47cc8c89db10ac27483585cd61cf4f91">llvm::GenericSchedulerBase::SchedCandidate::initResourceDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a589e51a1ef960a2b6aaa3854ce04d77a">llvm::SchedBoundary::isTop</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ab86856838bf1e1577210f03d35273ccb">llvm::GenericSchedulerBase::SchedCandidate::ResDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a9730ea0068843718868a8667f52e3680">llvm::GenericSchedulerBase::SchedModel</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a294e77c4f7245940981e5e259045c7c0">llvm::GenericSchedulerBase::SchedCandidate::setBest</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a> and <a href="#a6ef23d22af6c895d9c255de3e940b8bf">tryCandidate</a>.</p>


<p>Referenced by <a href="#ad4cc558b6cbcc4e9cea5df915c197e14">pickNode</a> and <a href="#aef82bce77971408815c3b90979188d1e">pickNodeBidirectional</a>.</p>

</div>
</div>

### reschedulePhysReg() {#ad04f609cdff2331741525e5328836598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GenericScheduler::reschedulePhysReg (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, bool isTop)</td>
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



<p>Declaration at line 1295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3798 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a75edfd9bb13c765b11b0b400cbe2aaed">DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#afacc26f29d80e10be4785a96ed6444dc">llvm::Register::isPhysicalRegister</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a>.</p>


<p>Referenced by <a href="#adf574ab3455d7292bed998d8ba50bfeb">schedNode</a>.</p>

</div>
</div>

### tryCandidate() {#a6ef23d22af6c895d9c255de3e940b8bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GenericScheduler::tryCandidate (<a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; Cand, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; TryCand, <a href="/web-llvm/docs/api/classes/llvm/schedboundary">SchedBoundary</a> * Zone)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply a set of heuristics to a new candidate.</p>


<p>Heuristics are currently hierarchical. This may be more efficient than a graduated cost model because we don't need to evaluate all aspects of the model for each node in the queue. But it's really done to make the heuristics easier to debug and statistically analyze.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Cand</td>
<td class="doxyParamItemDescription"><p>provides the policy and current best candidate.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TryCand</td>
<td class="doxyParamItemDescription"><p>refers to the next <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> candidate, otherwise uninitialized.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Zone</td>
<td class="doxyParamItemDescription"><p>describes the scheduled zone that we are extending, or nullptr if Cand is from a different zone than TryCand.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">true</span> if TryCand is better than Cand (Reason is NOT NoCand)</p></dd>
</dl>


<p>Declaration at line 1285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3524 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a87328c4ecbb87961dd2c970d343b9ca0">llvm::GenericSchedulerBase::SchedCandidate::AtTop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb4b9423201406d79ba16481c90cb6cb">llvm::biasPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a5a905614458af47ec4a5054a53d23e1b">llvm::GenericSchedulerBase::Cluster</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a277da5755f2b30ebcebdba51d0de1acf">llvm::RegPressureDelta::CriticalMax</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedresourcedelta/#a3ffd08e01bba20c9af1ae13630ed7acd">llvm::GenericSchedulerBase::SchedResourceDelta::CritResources</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a589e1a7e9a8a095d8d01ff8ba32b3d14">llvm::RegPressureDelta::CurrentMax</a>, <a href="#a75edfd9bb13c765b11b0b400cbe2aaed">DAG</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedresourcedelta/#ab660550157a92f83f7b4f2db2d2d9304">llvm::GenericSchedulerBase::SchedResourceDelta::DemandedResources</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#aff9c3b403c6d4af795dd8be1c9612240">llvm::RegPressureDelta::Excess</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#ac984b92ac3a64875c7f2908ef617584d">llvm::SchedBoundary::getCurrMOps</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a4a674627365b72b17a9b2e0a99d40ce1">llvm::SchedBoundary::getLatencyStallCycles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a13933f8ac2f5e1a34cf53b2c1e1bdc5b">llvm::getWeakLeft</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a47cc8c89db10ac27483585cd61cf4f91">llvm::GenericSchedulerBase::SchedCandidate::initResourceDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a589e51a1ef960a2b6aaa3854ce04d77a">llvm::SchedBoundary::isTop</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#acdc733638a93dca6bb0eb290ec896271">llvm::GenericSchedulerBase::SchedCandidate::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a810d389a7def234e94c2631683ab0ece">llvm::GenericSchedulerBase::NoCand</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3aa00a8e5741a604eb07320e981473b4e7">llvm::GenericSchedulerBase::NodeOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3ab58c08e8fa9324ebf332e11601ec6c0d">llvm::GenericSchedulerBase::PhysReg</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ae861d440b366cf033d7f2764b2b34be0">llvm::GenericSchedulerBase::SchedCandidate::Policy</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ad9372964d55580636efe92281b42ad6c">llvm::GenericSchedulerBase::SchedCandidate::Reason</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy/#acd9f1ecfaa9db2800e6fe15a385b4a6f">llvm::GenericSchedulerBase::CandPolicy::ReduceLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a974161ce84e375b6d40bd8855c29dd7f">llvm::GenericSchedulerBase::RegCritical</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a01d264553167fb005aba23a6d2a6e9bb">llvm::GenericSchedulerBase::RegExcess</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8e13153e8ed7676ddbba73dd9318d35e">llvm::GenericSchedulerBase::RegionPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a01ef8d8423fe645e50ad5a179b4f4483">llvm::GenericSchedulerBase::RegMax</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a3cab76d375dbb626e5179b96f84fd3dc">llvm::GenericSchedulerBase::Rem</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ab86856838bf1e1577210f03d35273ccb">llvm::GenericSchedulerBase::SchedCandidate::ResDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a07409a8a5b9657af23f0a1c962f5c0c1">llvm::GenericSchedulerBase::ResourceDemand</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a56637d3435d7e1953a615371cfe4d5ec">llvm::GenericSchedulerBase::ResourceReduce</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a81fbfdac1b8c1e736493b56b50853322">llvm::GenericSchedulerBase::SchedCandidate::RPDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a9730ea0068843718868a8667f52e3680">llvm::GenericSchedulerBase::SchedModel</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3ab6aae8902e724a36ed16d537784777a2">llvm::GenericSchedulerBase::Stall</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a310a170b7d2442d12634d53db262fb92">llvm::GenericSchedulerBase::SchedCandidate::SU</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae9476ffbc2f3f195a2116b13f3186194">llvm::GenericSchedulerBase::TRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab618de2b7dea1e1859018a1a7e8b3ee5">llvm::tryGreater</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9a83bf7b5f6e85f215ff07a31e0fbe">llvm::tryLatency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae0fdc8ed1e4e4ae29b810aeffc13fb47">llvm::tryLess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62cf34ac18c5612524978166788b5c80">llvm::tryPressure</a> and <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3aed8b719fe1a669c2fed4bacc6f46e8df">llvm::GenericSchedulerBase::Weak</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a26b8231b39c104871f78b2da6dc1eff5">llvm::GCNSchedStrategy::pickNodeBidirectional</a>, <a href="#aef82bce77971408815c3b90979188d1e">pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a> and <a href="#ad9779ec3011b4547f9a509af82d87a6e">pickNodeFromQueue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Bot {#a3763f96e92009d4dc101837627fff3bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedBoundary llvm::GenericScheduler::Bot</td>
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



<p>Definition at line 1272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#ae8dd2d1a734d828faa812af4a9a135e3">GenericScheduler</a>, <a href="#aa8cddd2ea015f8177a8395035f87e332">initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#af3f3a45f145bc8538e160bc3177ffc8f">llvm::GCNSchedStrategy::pickNode</a>, <a href="#ad4cc558b6cbcc4e9cea5df915c197e14">pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a26b8231b39c104871f78b2da6dc1eff5">llvm::GCNSchedStrategy::pickNodeBidirectional</a>, <a href="#aef82bce77971408815c3b90979188d1e">pickNodeBidirectional</a>, <a href="#ac047246e76df6b86564a6b62c2403aef">registerRoots</a>, <a href="#a779430fb54fa19f8bf9d94d1618bf7f5">releaseBottomNode</a> and <a href="#adf574ab3455d7292bed998d8ba50bfeb">schedNode</a>.</p>

</div>
</div>

### BotCand {#a190c2995c11bd6de755bbd8311a8f176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedCandidate llvm::GenericScheduler::BotCand</td>
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

<p>Candidate last picked from Bot boundary.</p>

<p>Definition at line 1277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#aa8cddd2ea015f8177a8395035f87e332">initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#af3f3a45f145bc8538e160bc3177ffc8f">llvm::GCNSchedStrategy::pickNode</a>, <a href="#ad4cc558b6cbcc4e9cea5df915c197e14">pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a26b8231b39c104871f78b2da6dc1eff5">llvm::GCNSchedStrategy::pickNodeBidirectional</a>, <a href="#aef82bce77971408815c3b90979188d1e">pickNodeBidirectional</a> and <a href="#a779430fb54fa19f8bf9d94d1618bf7f5">releaseBottomNode</a>.</p>

</div>
</div>

### DAG {#a75edfd9bb13c765b11b0b400cbe2aaed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGMILive* llvm::GenericScheduler::DAG = nullptr</td>
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



<p>Definition at line 1268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ad173097d2f6789c7d00843386252855e">llvm::GCNSchedStrategy::initCandidate</a>, <a href="#ab0d12eb20352f092840f7f8df60abe26">initCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ab57c0b13438062a884d3e620300fbc03">llvm::GCNSchedStrategy::initialize</a>, <a href="#aa8cddd2ea015f8177a8395035f87e332">initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#af3f3a45f145bc8538e160bc3177ffc8f">llvm::GCNSchedStrategy::pickNode</a>, <a href="#ad4cc558b6cbcc4e9cea5df915c197e14">pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a26b8231b39c104871f78b2da6dc1eff5">llvm::GCNSchedStrategy::pickNodeBidirectional</a>, <a href="#aef82bce77971408815c3b90979188d1e">pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a>, <a href="#ad9779ec3011b4547f9a509af82d87a6e">pickNodeFromQueue</a>, <a href="#ac047246e76df6b86564a6b62c2403aef">registerRoots</a>, <a href="#ad04f609cdff2331741525e5328836598">reschedulePhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="#a6ef23d22af6c895d9c255de3e940b8bf">tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### Top {#a253bc2bd1ae8e7f36e0c3c1c9bb67367}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedBoundary llvm::GenericScheduler::Top</td>
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



<p>Definition at line 1271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#ae8dd2d1a734d828faa812af4a9a135e3">GenericScheduler</a>, <a href="#aa8cddd2ea015f8177a8395035f87e332">initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#af3f3a45f145bc8538e160bc3177ffc8f">llvm::GCNSchedStrategy::pickNode</a>, <a href="#ad4cc558b6cbcc4e9cea5df915c197e14">pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a26b8231b39c104871f78b2da6dc1eff5">llvm::GCNSchedStrategy::pickNodeBidirectional</a>, <a href="#aef82bce77971408815c3b90979188d1e">pickNodeBidirectional</a>, <a href="#acc4369e500d02fac8e313e69947b2611">releaseTopNode</a> and <a href="#adf574ab3455d7292bed998d8ba50bfeb">schedNode</a>.</p>

</div>
</div>

### TopCand {#a33cc1a55125b89319e048d24625a2925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedCandidate llvm::GenericScheduler::TopCand</td>
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

<p>Candidate last picked from Top boundary.</p>

<p>Definition at line 1275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#aa8cddd2ea015f8177a8395035f87e332">initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#af3f3a45f145bc8538e160bc3177ffc8f">llvm::GCNSchedStrategy::pickNode</a>, <a href="#ad4cc558b6cbcc4e9cea5df915c197e14">pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a26b8231b39c104871f78b2da6dc1eff5">llvm::GCNSchedStrategy::pickNodeBidirectional</a>, <a href="#aef82bce77971408815c3b90979188d1e">pickNodeBidirectional</a> and <a href="#acc4369e500d02fac8e313e69947b2611">releaseTopNode</a>.</p>

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
