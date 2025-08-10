---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/postgenericscheduler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PostGenericScheduler` Class

<p><a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler">PostGenericScheduler</a> - Interface to the scheduling algorithm used by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PostGenericScheduler { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64postraschedstrategy">AArch64PostRASchedStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> implementation for <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> post RA scheduling. <a href="/web-llvm/docs/api/classes/llvm/aarch64postraschedstrategy/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ppcpostraschedstrategy">PPCPostRASchedStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> implementation for PowerPC post RA scheduling. <a href="/web-llvm/docs/api/classes/llvm/ppcpostraschedstrategy/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8d3e1ce009ee1e50dfd8897346404bb">PostGenericScheduler</a> (const MachineSchedContext *C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6a685edcf3974ea7f1eaac95c655715">~PostGenericScheduler</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04711828471ee40bed1b0e0ae8584cf4">initPolicy</a> (MachineBasicBlock::iterator Begin, MachineBasicBlock::iterator End, unsigned NumRegionInstrs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optionally override the per-region scheduling policy. <a href="#a04711828471ee40bed1b0e0ae8584cf4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a166bd59cd27ad6b2986ca7d7482e3013">shouldTrackPressure</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PostRA scheduling does not track pressure. <a href="#a166bd59cd27ad6b2986ca7d7482e3013">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a744ad04adf5ae507a33542ec18b0d97f">initialize</a> (ScheduleDAGMI *Dag) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the strategy after building the DAG for a new region. <a href="#a744ad04adf5ae507a33542ec18b0d97f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee5ca47cbb46d1237ce496179411b03e">registerRoots</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notify this strategy that all roots have been released (including those that depend on EntrySU or ExitSU). <a href="#aee5ca47cbb46d1237ce496179411b03e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8a37b0efa51cfd3f6b4729e3298de7f">pickNode</a> (bool &amp;IsTopNode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick the next node to schedule. <a href="#af8a37b0efa51cfd3f6b4729e3298de7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8950b6343e504e2112df60ee464603d">pickNodeBidirectional</a> (bool &amp;IsTopNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick the best candidate node from either the top or bottom queue. <a href="#ae8950b6343e504e2112df60ee464603d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e662247e5a490eb442f3c3fdc03fc55">scheduleTree</a> (unsigned SubtreeID) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scheduler callback to notify that a new subtree is scheduled. <a href="#a1e662247e5a490eb442f3c3fdc03fc55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19c13266ab002ad2ce608573c4d2c98e">schedNode</a> (SUnit *SU, bool IsTopNode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called after <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> has scheduled an instruction and updated scheduled/remaining flags in the DAG nodes. <a href="#a19c13266ab002ad2ce608573c4d2c98e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b2207fcd69085e114fe45fb49276ff2">releaseTopNode</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When all predecessor dependencies have been resolved, free this node for top-down scheduling. <a href="#a7b2207fcd69085e114fe45fb49276ff2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac32bc6bea26f0dc3cc421145f6c41af6">releaseBottomNode</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When all successor dependencies have been resolved, free this node for bottom-up scheduling. <a href="#ac32bc6bea26f0dc3cc421145f6c41af6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09835bd12a7088d224f84e7899946040">tryCandidate</a> (SchedCandidate &amp;Cand, SchedCandidate &amp;TryCand)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply a set of heuristics to a new candidate for PostRA scheduling. <a href="#a09835bd12a7088d224f84e7899946040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db5287f3514fcc23bb3f93d769b3e96">pickNodeFromQueue</a> (SchedBoundary &amp;Zone, SchedCandidate &amp;Cand)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a228f5e150e68f65407ed303218827a0a">DAG</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a406dc33395b3fd7b56da9a33fbccdc82">Top</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c76c3d1f5eb7366210f06001f8b9892">Bot</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79ea7cd8443aa229acb4b411fe0d7ba9">TopCand</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Candidate last picked from Top boundary. <a href="#a79ea7cd8443aa229acb4b411fe0d7ba9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a489c1082c995fab731252fd92020343c">BotCand</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Candidate last picked from Bot boundary. <a href="#a489c1082c995fab731252fd92020343c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler">PostGenericScheduler</a> - Interface to the scheduling algorithm used by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a>.</p>


<p>Callbacks from <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a>: initPolicy -&gt; initialize(DAG) -&gt; registerRoots -&gt; pickNode ...</p>


<p>Definition at line 1303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PostGenericScheduler() {#ac8d3e1ce009ee1e50dfd8897346404bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PostGenericScheduler::PostGenericScheduler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
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



<p>Definition at line 1315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="#a4c76c3d1f5eb7366210f06001f8b9892">Bot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#abf7a31296b8d3ede091a25b7777c3a15">llvm::GenericSchedulerBase::GenericSchedulerBase</a> and <a href="#a406dc33395b3fd7b56da9a33fbccdc82">Top</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64postraschedstrategy/#aade342dd21c4c6f42da585230b85ca18">llvm::AArch64PostRASchedStrategy::AArch64PostRASchedStrategy</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpostraschedstrategy/#a5e58d5d92c66c85df7c89ead1f68b58f">llvm::PPCPostRASchedStrategy::PPCPostRASchedStrategy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~PostGenericScheduler() {#ab6a685edcf3974ea7f1eaac95c655715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PostGenericScheduler::~PostGenericScheduler ()</td>
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



<p>Definition at line 1319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### initialize() {#a744ad04adf5ae507a33542ec18b0d97f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PostGenericScheduler::initialize (<a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> * DAG)</td>
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

<p>Declaration at line 1328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3875 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a4c76c3d1f5eb7366210f06001f8b9892">Bot</a>, <a href="#a228f5e150e68f65407ed303218827a0a">DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a3cab76d375dbb626e5179b96f84fd3dc">llvm::GenericSchedulerBase::Rem</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a9730ea0068843718868a8667f52e3680">llvm::GenericSchedulerBase::SchedModel</a>, <a href="#a406dc33395b3fd7b56da9a33fbccdc82">Top</a> and <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae9476ffbc2f3f195a2116b13f3186194">llvm::GenericSchedulerBase::TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcpostraschedstrategy/#af00cbef0e1f01812d6b3ba8a3a05cddd">llvm::PPCPostRASchedStrategy::initialize</a>.</p>

</div>
</div>

### initPolicy() {#a04711828471ee40bed1b0e0ae8584cf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PostGenericScheduler::initPolicy (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> End, unsigned NumRegionInstrs)</td>
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

<p>Optionally override the per-region scheduling policy.</p>

<p>Declaration at line 1321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3895 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/misched/#a76ffbaf191b81010c8e5da3c4ce028b3aab012f17d1537ed7a7c6d45b1d2fc0e9">llvm::MISched::Bidirectional</a>, <a href="/web-llvm/docs/api/namespaces/llvm/misched/#a76ffbaf191b81010c8e5da3c4ce028b3abd98ce24773c9ca1e3f7ce3c541e43ea">llvm::MISched::BottomUp</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a960319789166bad30f214270de5cbadc">llvm::TargetSubtargetInfo::overridePostRASchedPolicy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1e5fc889b7ee01722dbdfb92df8cb7df">llvm::PostRADirection</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8e13153e8ed7676ddbba73dd9318d35e">llvm::GenericSchedulerBase::RegionPolicy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/misched/#a76ffbaf191b81010c8e5da3c4ce028b3ae89742249a15ad5696e3dcec82f0e76a">llvm::MISched::TopDown</a>.</p>

</div>
</div>

### pickNode() {#af8a37b0efa51cfd3f6b4729e3298de7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * PostGenericScheduler::pickNode (bool &amp; IsTopNode)</td>
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

<p>Pick the next node to schedule.</p>

<p>Declaration at line 1332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 4086 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4c76c3d1f5eb7366210f06001f8b9892">Bot</a>, <a href="#a489c1082c995fab731252fd92020343c">BotCand</a>, <a href="#a228f5e150e68f65407ed303218827a0a">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ac198a5fb130b4c09836ba20e01b4290d">llvm::SUnit::isBottomReady</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae0b8da4dfde85d4ddc32359ca52dc493">llvm::SUnit::isTopReady</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a810d389a7def234e94c2631683ab0ece">llvm::GenericSchedulerBase::NoCand</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a3e5ec7d7634a70f61fd64c3ef22d02f1">llvm::GenericSchedulerBase::Only1</a>, <a href="#ae8950b6343e504e2112df60ee464603d">pickNodeBidirectional</a>, <a href="#a5db5287f3514fcc23bb3f93d769b3e96">pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8e13153e8ed7676ddbba73dd9318d35e">llvm::GenericSchedulerBase::RegionPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8668556014566994c07b21391762551b">llvm::GenericSchedulerBase::setPolicy</a>, <a href="#a406dc33395b3fd7b56da9a33fbccdc82">Top</a>, <a href="#a79ea7cd8443aa229acb4b411fe0d7ba9">TopCand</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a14c35b53586841aad69751a52b7d358a">tracePick</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcpostraschedstrategy/#a380e7f12bac02fcc58704de354b838dd">llvm::PPCPostRASchedStrategy::pickNode</a>.</p>

</div>
</div>

### pickNodeBidirectional() {#ae8950b6343e504e2112df60ee464603d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * PostGenericScheduler::pickNodeBidirectional (bool &amp; IsTopNode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pick the best candidate node from either the top or bottom queue.</p>

<p>Declaration at line 1334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 4005 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a87328c4ecbb87961dd2c970d343b9ca0">llvm::GenericSchedulerBase::SchedCandidate::AtTop</a>, <a href="#a4c76c3d1f5eb7366210f06001f8b9892">Bot</a>, <a href="#a489c1082c995fab731252fd92020343c">BotCand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a810d389a7def234e94c2631683ab0ece">llvm::GenericSchedulerBase::NoCand</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a3e5ec7d7634a70f61fd64c3ef22d02f1">llvm::GenericSchedulerBase::Only1</a>, <a href="#a5db5287f3514fcc23bb3f93d769b3e96">pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a361fa10c095c303e093021c6a1d04e75">llvm::GenericSchedulerBase::SchedCandidate::reset</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a294e77c4f7245940981e5e259045c7c0">llvm::GenericSchedulerBase::SchedCandidate::setBest</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8668556014566994c07b21391762551b">llvm::GenericSchedulerBase::setPolicy</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a310a170b7d2442d12634d53db262fb92">llvm::GenericSchedulerBase::SchedCandidate::SU</a>, <a href="#a406dc33395b3fd7b56da9a33fbccdc82">Top</a>, <a href="#a79ea7cd8443aa229acb4b411fe0d7ba9">TopCand</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a14c35b53586841aad69751a52b7d358a">tracePick</a>, <a href="#a09835bd12a7088d224f84e7899946040">tryCandidate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4d101d816188a045c0b595a6a2c5d3a3">llvm::VerifyScheduling</a>.</p>


<p>Referenced by <a href="#af8a37b0efa51cfd3f6b4729e3298de7f">pickNode</a>.</p>

</div>
</div>

### registerRoots() {#aee5ca47cbb46d1237ce496179411b03e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PostGenericScheduler::registerRoots ()</td>
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

<p>Declaration at line 1330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3921 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a4c76c3d1f5eb7366210f06001f8b9892">Bot</a>, <a href="#a228f5e150e68f65407ed303218827a0a">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82ab0315644106de03b36f143328179f">llvm::DumpCriticalPathLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8926b25df7254ba2730fa5d7ec139862">llvm::SUnit::getDepth</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a3cab76d375dbb626e5179b96f84fd3dc">llvm::GenericSchedulerBase::Rem</a>.</p>

</div>
</div>

### releaseBottomNode() {#ac32bc6bea26f0dc3cc421145f6c41af6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PostGenericScheduler::releaseBottomNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>Definition at line 1349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="#a4c76c3d1f5eb7366210f06001f8b9892">Bot</a>, <a href="#a489c1082c995fab731252fd92020343c">BotCand</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aa1dfdcdc657e12c47e72d9dbe251ac85">llvm::SUnit::BotReadyCycle</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>.</p>

</div>
</div>

### releaseTopNode() {#a7b2207fcd69085e114fe45fb49276ff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PostGenericScheduler::releaseTopNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>Definition at line 1342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>, <a href="#a406dc33395b3fd7b56da9a33fbccdc82">Top</a>, <a href="#a79ea7cd8443aa229acb4b411fe0d7ba9">TopCand</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2a6f92b9c5aba34d3b07f3ebe229ccff">llvm::SUnit::TopReadyCycle</a>.</p>

</div>
</div>

### schedNode() {#a19c13266ab002ad2ce608573c4d2c98e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PostGenericScheduler::schedNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, bool IsTopNode)</td>
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

<p>Called after <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> has scheduled an instruction and updated scheduled/remaining flags in the DAG nodes.</p>

<p>Declaration at line 1340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 4143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a4c76c3d1f5eb7366210f06001f8b9892">Bot</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aa1dfdcdc657e12c47e72d9dbe251ac85">llvm::SUnit::BotReadyCycle</a>, <a href="#a406dc33395b3fd7b56da9a33fbccdc82">Top</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2a6f92b9c5aba34d3b07f3ebe229ccff">llvm::SUnit::TopReadyCycle</a>.</p>

</div>
</div>

### scheduleTree() {#a1e662247e5a490eb442f3c3fdc03fc55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PostGenericScheduler::scheduleTree (unsigned SubtreeID)</td>
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

<p>Scheduler callback to notify that a new subtree is scheduled.</p>

<p>Definition at line 1336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### shouldTrackPressure() {#a166bd59cd27ad6b2986ca7d7482e3013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PostGenericScheduler::shouldTrackPressure ()</td>
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

<p>PostRA scheduling does not track pressure.</p>

<p>Definition at line 1326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### pickNodeFromQueue() {#a5db5287f3514fcc23bb3f93d769b3e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PostGenericScheduler::pickNodeFromQueue (<a href="/web-llvm/docs/api/classes/llvm/schedboundary">SchedBoundary</a> &amp; Zone, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; Cand)</td>
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



<p>Declaration at line 1359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3989 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a87328c4ecbb87961dd2c970d343b9ca0">llvm::GenericSchedulerBase::SchedCandidate::AtTop</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#aa49fbb78ca6f0a19a967f2f8fb70097d">llvm::SchedBoundary::Available</a>, <a href="#a228f5e150e68f65407ed303218827a0a">DAG</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a47cc8c89db10ac27483585cd61cf4f91">llvm::GenericSchedulerBase::SchedCandidate::initResourceDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a589e51a1ef960a2b6aaa3854ce04d77a">llvm::SchedBoundary::isTop</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ae861d440b366cf033d7f2764b2b34be0">llvm::GenericSchedulerBase::SchedCandidate::Policy</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a9730ea0068843718868a8667f52e3680">llvm::GenericSchedulerBase::SchedModel</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a294e77c4f7245940981e5e259045c7c0">llvm::GenericSchedulerBase::SchedCandidate::setBest</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a310a170b7d2442d12634d53db262fb92">llvm::GenericSchedulerBase::SchedCandidate::SU</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a> and <a href="#a09835bd12a7088d224f84e7899946040">tryCandidate</a>.</p>


<p>Referenced by <a href="#af8a37b0efa51cfd3f6b4729e3298de7f">pickNode</a> and <a href="#ae8950b6343e504e2112df60ee464603d">pickNodeBidirectional</a>.</p>

</div>
</div>

### tryCandidate() {#a09835bd12a7088d224f84e7899946040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PostGenericScheduler::tryCandidate (<a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; Cand, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; TryCand)</td>
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

<p>Apply a set of heuristics to a new candidate for PostRA scheduling.</p>


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
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">true</span> if TryCand is better than Cand (Reason is NOT NoCand)</p></dd>
</dl>


<p>Declaration at line 1357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3940 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a87328c4ecbb87961dd2c970d343b9ca0">llvm::GenericSchedulerBase::SchedCandidate::AtTop</a>, <a href="#a4c76c3d1f5eb7366210f06001f8b9892">Bot</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a5a905614458af47ec4a5054a53d23e1b">llvm::GenericSchedulerBase::Cluster</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedresourcedelta/#a3ffd08e01bba20c9af1ae13630ed7acd">llvm::GenericSchedulerBase::SchedResourceDelta::CritResources</a>, <a href="#a228f5e150e68f65407ed303218827a0a">DAG</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedresourcedelta/#ab660550157a92f83f7b4f2db2d2d9304">llvm::GenericSchedulerBase::SchedResourceDelta::DemandedResources</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#acdc733638a93dca6bb0eb290ec896271">llvm::GenericSchedulerBase::SchedCandidate::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a810d389a7def234e94c2631683ab0ece">llvm::GenericSchedulerBase::NoCand</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3aa00a8e5741a604eb07320e981473b4e7">llvm::GenericSchedulerBase::NodeOrder</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ae861d440b366cf033d7f2764b2b34be0">llvm::GenericSchedulerBase::SchedCandidate::Policy</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ad9372964d55580636efe92281b42ad6c">llvm::GenericSchedulerBase::SchedCandidate::Reason</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy/#acd9f1ecfaa9db2800e6fe15a385b4a6f">llvm::GenericSchedulerBase::CandPolicy::ReduceLatency</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ab86856838bf1e1577210f03d35273ccb">llvm::GenericSchedulerBase::SchedCandidate::ResDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a07409a8a5b9657af23f0a1c962f5c0c1">llvm::GenericSchedulerBase::ResourceDemand</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a56637d3435d7e1953a615371cfe4d5ec">llvm::GenericSchedulerBase::ResourceReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3ab6aae8902e724a36ed16d537784777a2">llvm::GenericSchedulerBase::Stall</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a310a170b7d2442d12634d53db262fb92">llvm::GenericSchedulerBase::SchedCandidate::SU</a>, <a href="#a406dc33395b3fd7b56da9a33fbccdc82">Top</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab618de2b7dea1e1859018a1a7e8b3ee5">llvm::tryGreater</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9a83bf7b5f6e85f215ff07a31e0fbe">llvm::tryLatency</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae0fdc8ed1e4e4ae29b810aeffc13fb47">llvm::tryLess</a>.</p>


<p>Referenced by <a href="#ae8950b6343e504e2112df60ee464603d">pickNodeBidirectional</a>, <a href="#a5db5287f3514fcc23bb3f93d769b3e96">pickNodeFromQueue</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64postraschedstrategy/#a13b69f0a0d56eb5e0802e40b938136a6">llvm::AArch64PostRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Bot {#a4c76c3d1f5eb7366210f06001f8b9892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedBoundary llvm::PostGenericScheduler::Bot</td>
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



<p>Definition at line 1307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a744ad04adf5ae507a33542ec18b0d97f">initialize</a>, <a href="#af8a37b0efa51cfd3f6b4729e3298de7f">pickNode</a>, <a href="#ae8950b6343e504e2112df60ee464603d">pickNodeBidirectional</a>, <a href="#ac8d3e1ce009ee1e50dfd8897346404bb">PostGenericScheduler</a>, <a href="#aee5ca47cbb46d1237ce496179411b03e">registerRoots</a>, <a href="#ac32bc6bea26f0dc3cc421145f6c41af6">releaseBottomNode</a>, <a href="#a19c13266ab002ad2ce608573c4d2c98e">schedNode</a> and <a href="#a09835bd12a7088d224f84e7899946040">tryCandidate</a>.</p>

</div>
</div>

### BotCand {#a489c1082c995fab731252fd92020343c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedCandidate llvm::PostGenericScheduler::BotCand</td>
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

<p>Definition at line 1312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#af8a37b0efa51cfd3f6b4729e3298de7f">pickNode</a>, <a href="#ae8950b6343e504e2112df60ee464603d">pickNodeBidirectional</a> and <a href="#ac32bc6bea26f0dc3cc421145f6c41af6">releaseBottomNode</a>.</p>

</div>
</div>

### DAG {#a228f5e150e68f65407ed303218827a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGMI* llvm::PostGenericScheduler::DAG = nullptr</td>
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



<p>Definition at line 1305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a744ad04adf5ae507a33542ec18b0d97f">initialize</a>, <a href="#af8a37b0efa51cfd3f6b4729e3298de7f">pickNode</a>, <a href="#a5db5287f3514fcc23bb3f93d769b3e96">pickNodeFromQueue</a>, <a href="#aee5ca47cbb46d1237ce496179411b03e">registerRoots</a>, <a href="#a09835bd12a7088d224f84e7899946040">tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpostraschedstrategy/#aa6664186ee0da2c7355def751d53a653">llvm::PPCPostRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### Top {#a406dc33395b3fd7b56da9a33fbccdc82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedBoundary llvm::PostGenericScheduler::Top</td>
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



<p>Definition at line 1306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a744ad04adf5ae507a33542ec18b0d97f">initialize</a>, <a href="#af8a37b0efa51cfd3f6b4729e3298de7f">pickNode</a>, <a href="#ae8950b6343e504e2112df60ee464603d">pickNodeBidirectional</a>, <a href="#ac8d3e1ce009ee1e50dfd8897346404bb">PostGenericScheduler</a>, <a href="#a7b2207fcd69085e114fe45fb49276ff2">releaseTopNode</a>, <a href="#a19c13266ab002ad2ce608573c4d2c98e">schedNode</a>, <a href="#a09835bd12a7088d224f84e7899946040">tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpostraschedstrategy/#aa6664186ee0da2c7355def751d53a653">llvm::PPCPostRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### TopCand {#a79ea7cd8443aa229acb4b411fe0d7ba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedCandidate llvm::PostGenericScheduler::TopCand</td>
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

<p>Definition at line 1310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#af8a37b0efa51cfd3f6b4729e3298de7f">pickNode</a>, <a href="#ae8950b6343e504e2112df60ee464603d">pickNodeBidirectional</a> and <a href="#a7b2207fcd69085e114fe45fb49276ff2">releaseTopNode</a>.</p>

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
