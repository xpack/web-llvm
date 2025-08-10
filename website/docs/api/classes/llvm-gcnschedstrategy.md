---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcnschedstrategy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GCNSchedStrategy` Class

<p>This is a minimal scheduler strategy. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GCNSchedStrategy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">Target/AMDGPU/GCNSchedStrategy.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/genericscheduler">GenericScheduler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/genericscheduler">GenericScheduler</a> shrinks the unscheduled zone using heuristics to balance the schedule. <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy">GCNMaxILPSchedStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The goal of this scheduling strategy is to maximize ILP for a single wave (i.e. <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy">GCNMaxMemoryClauseSchedStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The goal of this scheduling strategy is to maximize memory clause for a single wave. <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnmaxoccupancyschedstrategy">GCNMaxOccupancySchedStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The goal of this scheduling strategy is to maximize kernel occupancy (i.e. <a href="/web-llvm/docs/api/classes/llvm/gcnmaxoccupancyschedstrategy/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f3300bee7a18474eb2f103afa3ea22">GCNSchedStrategy</a> (const MachineSchedContext *C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3f3a45f145bc8538e160bc3177ffc8f">pickNode</a> (bool &amp;IsTopNode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick the next node to schedule, or return NULL. <a href="#af3f3a45f145bc8538e160bc3177ffc8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a886677d13d24c974e4cb3086df524e7b">schedNode</a> (SUnit *SU, bool IsTopNode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notify <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> that <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> has scheduled an instruction and updated scheduled/remaining flags in the DAG nodes. <a href="#a886677d13d24c974e4cb3086df524e7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab57c0b13438062a884d3e620300fbc03">initialize</a> (ScheduleDAGMI *DAG) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the strategy after building the DAG for a new region. <a href="#ab57c0b13438062a884d3e620300fbc03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad37490b68720625392a017b47f21b349">getTargetOccupancy</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad79aeb604df3043f82a984f37d9511be">setTargetOccupancy</a> (unsigned Occ)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0">GCNSchedStageID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5303450aec4d4b8fe49b3af743da555a">getCurrentStage</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a797dfd2abf170515d119ff35a4b5ffe7">advanceStage</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a405838f7f99c2b64659702103f8bf43f">hasNextStage</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0">GCNSchedStageID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff69df5b1b61c9a71b8b75855e303e35">getNextStage</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker">GCNDownwardRPTracker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fb4d350598854a68264637b888d3676">getDownwardTracker</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker">GCNUpwardRPTracker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa4a2ed99ec1f703c8571b3e00b3e540">getUpwardTracker</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b8231b39c104871f78b2da6dc1eff5">pickNodeBidirectional</a> (bool &amp;IsTopNode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2777a131d60f64dbebce2d7116f198c7">pickNodeFromQueue</a> (SchedBoundary &amp;Zone, const CandPolicy &amp;ZonePolicy, const RegPressureTracker &amp;RPTracker, SchedCandidate &amp;Cand, bool IsBottomUp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad173097d2f6789c7d00843386252855e">initCandidate</a> (SchedCandidate &amp;Cand, SUnit *SU, bool AtTop, const RegPressureTracker &amp;RPTracker, const SIRegisterInfo *SRI, unsigned SGPRPressure, unsigned VGPRPressure, bool IsBottomUp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1902cf3722582eecec1d87862513ba3b">HasHighPressure</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a508f8eece85480c2520ebf5d1f3ef945">KnownExcessRP</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca0e645faeaad83ce440e96cc39b6763">ErrorMargin</a> = 3</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07d3ce50a12f46f5923bc2496b05bfb6">HighRPSGPRBias</a> = 7</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc922b5ccbfe87a7c54c8d07e122eea7">HighRPVGPRBias</a> = 7</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed3b8acc5fc8c2f5c155620b5c32555">SGPRCriticalLimit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87648a3c33abb5fb8ff110b760424ecc">VGPRCriticalLimit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5bfab3502e3953ac33f90ae4c86fecc">SGPRLimitBias</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af100c4ee35e4de0856b35b151479ec3d">VGPRLimitBias</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab169c359dc2328b0a4e93f5f95b82fc0">Pressure</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d63ae4c61c0f0cce4bcff4a33587d31">MaxPressure</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8793c7d097d298c1590b67980054d8b">SGPRExcessLimit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54479ded7088e7b425de5d6c1f77fb7a">VGPRExcessLimit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45c6b23ba1bf5916572a93ef35d962c5">TargetOccupancy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5655f7a9e04872d7a5834a44a1d5359c">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0">GCNSchedStageID</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1736ffcc1fcc46c9c47748d5a9a04c4b">SchedStages</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0">GCNSchedStageID</a> &gt;::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb7baa0abad1c0fb63869eae07507a7">CurrentStage</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker">GCNDownwardRPTracker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c520a204af32794c1f39b7df769c209">DownwardTracker</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker">GCNUpwardRPTracker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab92590ff43ffbc2173b1429750362fb3">UpwardTracker</a></td>
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

<p>This is a minimal scheduler strategy.</p>


<p>The main difference between this and the <a href="/web-llvm/docs/api/classes/llvm/genericscheduler">GenericScheduler</a> is that <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy">GCNSchedStrategy</a> uses different heuristics to determine excess/critical pressure sets.</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GCNSchedStrategy() {#a14f3300bee7a18474eb2f103afa3ea22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNSchedStrategy::GCNSchedStrategy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a0c520a204af32794c1f39b7df769c209">DownwardTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ae8dd2d1a734d828faa812af4a9a135e3">llvm::GenericScheduler::GenericScheduler</a>, <a href="#a1902cf3722582eecec1d87862513ba3b">HasHighPressure</a>, <a href="#a5655f7a9e04872d7a5834a44a1d5359c">MF</a>, <a href="#a45c6b23ba1bf5916572a93ef35d962c5">TargetOccupancy</a> and <a href="#ab92590ff43ffbc2173b1429750362fb3">UpwardTracker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#ab9b774c18357fd89d3da62c07828868d">llvm::GCNMaxILPSchedStrategy::GCNMaxILPSchedStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#ae5dff5cf85f1ae74f4b05b1c7638d694">llvm::GCNMaxMemoryClauseSchedStrategy::GCNMaxMemoryClauseSchedStrategy</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnmaxoccupancyschedstrategy/#a1aaa47dd65d2e5e66930f7c3bdb2a6bd">llvm::GCNMaxOccupancySchedStrategy::GCNMaxOccupancySchedStrategy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### advanceStage() {#a797dfd2abf170515d119ff35a4b5ffe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNSchedStrategy::advanceStage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7eb7baa0abad1c0fb63869eae07507a7">CurrentStage</a> and <a href="#a1736ffcc1fcc46c9c47748d5a9a04c4b">SchedStages</a>.</p>

</div>
</div>

### getCurrentStage() {#a5303450aec4d4b8fe49b3af743da555a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNSchedStageID GCNSchedStrategy::getCurrentStage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7eb7baa0abad1c0fb63869eae07507a7">CurrentStage</a> and <a href="#a1736ffcc1fcc46c9c47748d5a9a04c4b">SchedStages</a>.</p>

</div>
</div>

### getDownwardTracker() {#a9fb4d350598854a68264637b888d3676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNDownwardRPTracker * llvm::GCNSchedStrategy::getDownwardTracker ()</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Reference <a href="#a0c520a204af32794c1f39b7df769c209">DownwardTracker</a>.</p>

</div>
</div>

### getNextStage() {#aff69df5b1b61c9a71b8b75855e303e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNSchedStageID GCNSchedStrategy::getNextStage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7eb7baa0abad1c0fb63869eae07507a7">CurrentStage</a> and <a href="#a1736ffcc1fcc46c9c47748d5a9a04c4b">SchedStages</a>.</p>

</div>
</div>

### getTargetOccupancy() {#ad37490b68720625392a017b47f21b349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSchedStrategy::getTargetOccupancy ()</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Reference <a href="#a45c6b23ba1bf5916572a93ef35d962c5">TargetOccupancy</a>.</p>

</div>
</div>

### getUpwardTracker() {#afa4a2ed99ec1f703c8571b3e00b3e540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNUpwardRPTracker * llvm::GCNSchedStrategy::getUpwardTracker ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Reference <a href="#ab92590ff43ffbc2173b1429750362fb3">UpwardTracker</a>.</p>

</div>
</div>

### hasNextStage() {#a405838f7f99c2b64659702103f8bf43f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNSchedStrategy::hasNextStage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7eb7baa0abad1c0fb63869eae07507a7">CurrentStage</a> and <a href="#a1736ffcc1fcc46c9c47748d5a9a04c4b">SchedStages</a>.</p>

</div>
</div>

### initialize() {#ab57c0b13438062a884d3e620300fbc03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNSchedStrategy::initialize (<a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> * DAG)</td>
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

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a41896492f62ee8d25cf8aaad70bd88aa">llvm::alignDown</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ad0f9f52bf2f7c54d9546cedd1c47ef45">llvm::GenericSchedulerBase::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a75edfd9bb13c765b11b0b400cbe2aaed">llvm::GenericScheduler::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aca0e645faeaad83ce440e96cc39b6763">ErrorMargin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a842a99d2928e264423f0ac73b0910ec9">llvm::AMDGPU::IsaInfo::getAddressableNumVGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ab51348abdbbc76d0e8db5c01a5ee5280">llvm::SIMachineFunctionInfo::getMinAllowedOccupancy</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a09166d86fd4b0141f17b248f6fcdf0b6">llvm::SIMachineFunctionInfo::getOccupancy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ae47a2723f63ec4e85b4228b56e5d759c">llvm::AMDGPU::IsaInfo::getVGPRAllocGranule</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#aa8cddd2ea015f8177a8395035f87e332">llvm::GenericScheduler::initialize</a>, <a href="#a508f8eece85480c2520ebf5d1f3ef945">KnownExcessRP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a5655f7a9e04872d7a5834a44a1d5359c">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#a598d5d447ded5b784ea021c159a58615">RelaxedOcc</a>, <a href="#a2ed3b8acc5fc8c2f5c155620b5c32555">SGPRCriticalLimit</a>, <a href="#aa8793c7d097d298c1590b67980054d8b">SGPRExcessLimit</a>, <a href="#aa5bfab3502e3953ac33f90ae4c86fecc">SGPRLimitBias</a>, <a href="#a45c6b23ba1bf5916572a93ef35d962c5">TargetOccupancy</a>, <a href="#a87648a3c33abb5fb8ff110b760424ecc">VGPRCriticalLimit</a>, <a href="#a54479ded7088e7b425de5d6c1f77fb7a">VGPRExcessLimit</a> and <a href="#af100c4ee35e4de0856b35b151479ec3d">VGPRLimitBias</a>.</p>

</div>
</div>

### pickNode() {#af3f3a45f145bc8538e160bc3177ffc8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * GCNSchedStrategy::pickNode (bool &amp; IsTopNode)</td>
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

<p>Pick the next node to schedule, or return NULL.</p>


<p>Set IsTopNode to true to schedule the node at the top of the unscheduled region. Otherwise it will be scheduled at the bottom.</p>


<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a3763f96e92009d4dc101837627fff3bd">llvm::GenericScheduler::Bot</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a190c2995c11bd6de755bbd8311a8f176">llvm::GenericScheduler::BotCand</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a75edfd9bb13c765b11b0b400cbe2aaed">llvm::GenericScheduler::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ac198a5fb130b4c09836ba20e01b4290d">llvm::SUnit::isBottomReady</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae0b8da4dfde85d4ddc32359ca52dc493">llvm::SUnit::isTopReady</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a810d389a7def234e94c2631683ab0ece">llvm::GenericSchedulerBase::NoCand</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="#a26b8231b39c104871f78b2da6dc1eff5">pickNodeBidirectional</a>, <a href="#a2777a131d60f64dbebce2d7116f198c7">pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8e13153e8ed7676ddbba73dd9318d35e">llvm::GenericSchedulerBase::RegionPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a253bc2bd1ae8e7f36e0c3c1c9bb67367">llvm::GenericScheduler::Top</a> and <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a33cc1a55125b89319e048d24625a2925">llvm::GenericScheduler::TopCand</a>.</p>

</div>
</div>

### schedNode() {#a886677d13d24c974e4cb3086df524e7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNSchedStrategy::schedNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, bool IsTopNode)</td>
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

<p>Notify <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> that <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> has scheduled an instruction and updated scheduled/remaining flags in the DAG nodes.</p>

<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="#a0c520a204af32794c1f39b7df769c209">DownwardTracker</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#a00473ec6bae66ae8a3e6a0fe74ee1aaa">GCNTrackers</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#adf574ab3455d7292bed998d8ba50bfeb">llvm::GenericScheduler::schedNode</a> and <a href="#ab92590ff43ffbc2173b1429750362fb3">UpwardTracker</a>.</p>

</div>
</div>

### setTargetOccupancy() {#ad79aeb604df3043f82a984f37d9511be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GCNSchedStrategy::setTargetOccupancy (unsigned Occ)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Reference <a href="#a45c6b23ba1bf5916572a93ef35d962c5">TargetOccupancy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a9d479174d357214e5ea495943b55fdd2">llvm::GCNIterativeScheduler::scheduleLegacyMaxOccupancy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### initCandidate() {#ad173097d2f6789c7d00843386252855e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNSchedStrategy::initCandidate (<a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; Cand, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, bool AtTop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> &amp; RPTracker, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> * SRI, unsigned SGPRPressure, unsigned VGPRPressure, bool IsBottomUp)</td>
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



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a87328c4ecbb87961dd2c970d343b9ca0">llvm::GenericSchedulerBase::SchedCandidate::AtTop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#aba393b0035b052e3477fc32a72643750">canUsePressureDiffs</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a277da5755f2b30ebcebdba51d0de1acf">llvm::RegPressureDelta::CriticalMax</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a75edfd9bb13c765b11b0b400cbe2aaed">llvm::GenericScheduler::DAG</a>, <a href="#a0c520a204af32794c1f39b7df769c209">DownwardTracker</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#aff9c3b403c6d4af795dd8be1c9612240">llvm::RegPressureDelta::Excess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#a00473ec6bae66ae8a3e6a0fe74ee1aaa">GCNTrackers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#ad8dc903ae7dd7695e082f3d3fb80be92">getRegisterPressures</a>, <a href="#a1902cf3722582eecec1d87862513ba3b">HasHighPressure</a>, <a href="#a3d63ae4c61c0f0cce4bcff4a33587d31">MaxPressure</a>, <a href="#ab169c359dc2328b0a4e93f5f95b82fc0">Pressure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a81fbfdac1b8c1e736493b56b50853322">llvm::GenericSchedulerBase::SchedCandidate::RPDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurechange/#a4b74a0d0d1bc2e22fa7376eda3fdd85f">llvm::PressureChange::setUnitInc</a>, <a href="#a2ed3b8acc5fc8c2f5c155620b5c32555">SGPRCriticalLimit</a>, <a href="#aa8793c7d097d298c1590b67980054d8b">SGPRExcessLimit</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a310a170b7d2442d12634d53db262fb92">llvm::GenericSchedulerBase::SchedCandidate::SU</a>, <a href="#ab92590ff43ffbc2173b1429750362fb3">UpwardTracker</a>, <a href="#a87648a3c33abb5fb8ff110b760424ecc">VGPRCriticalLimit</a> and <a href="#a54479ded7088e7b425de5d6c1f77fb7a">VGPRExcessLimit</a>.</p>


<p>Referenced by <a href="#a2777a131d60f64dbebce2d7116f198c7">pickNodeFromQueue</a>.</p>

</div>
</div>

### pickNodeBidirectional() {#a26b8231b39c104871f78b2da6dc1eff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * GCNSchedStrategy::pickNodeBidirectional (bool &amp; IsTopNode)</td>
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



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a3763f96e92009d4dc101837627fff3bd">llvm::GenericScheduler::Bot</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a190c2995c11bd6de755bbd8311a8f176">llvm::GenericScheduler::BotCand</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a75edfd9bb13c765b11b0b400cbe2aaed">llvm::GenericScheduler::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a810d389a7def234e94c2631683ab0ece">llvm::GenericSchedulerBase::NoCand</a>, <a href="#a2777a131d60f64dbebce2d7116f198c7">pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a361fa10c095c303e093021c6a1d04e75">llvm::GenericSchedulerBase::SchedCandidate::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8668556014566994c07b21391762551b">llvm::GenericSchedulerBase::setPolicy</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a310a170b7d2442d12634d53db262fb92">llvm::GenericSchedulerBase::SchedCandidate::SU</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a253bc2bd1ae8e7f36e0c3c1c9bb67367">llvm::GenericScheduler::Top</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a33cc1a55125b89319e048d24625a2925">llvm::GenericScheduler::TopCand</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4d101d816188a045c0b595a6a2c5d3a3">llvm::VerifyScheduling</a>.</p>


<p>Referenced by <a href="#af3f3a45f145bc8538e160bc3177ffc8f">pickNode</a>.</p>

</div>
</div>

### pickNodeFromQueue() {#a2777a131d60f64dbebce2d7116f198c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNSchedStrategy::pickNodeFromQueue (<a href="/web-llvm/docs/api/classes/llvm/schedboundary">SchedBoundary</a> &amp; Zone, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy">CandPolicy</a> &amp; ZonePolicy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> &amp; RPTracker, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; Cand, bool IsBottomUp)</td>
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



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a87328c4ecbb87961dd2c970d343b9ca0">llvm::GenericSchedulerBase::SchedCandidate::AtTop</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#aa49fbb78ca6f0a19a967f2f8fb70097d">llvm::SchedBoundary::Available</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a75edfd9bb13c765b11b0b400cbe2aaed">llvm::GenericScheduler::DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a4f3e434b23939cec7a3c61b45071a017">llvm::SchedBoundary::DAG</a>, <a href="#a0c520a204af32794c1f39b7df769c209">DownwardTracker</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#a00473ec6bae66ae8a3e6a0fe74ee1aaa">GCNTrackers</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#acd579b6c2156091eb3134238f13053e0">llvm::RegPressureTracker::getRegSetPressureAtPos</a>, <a href="#ad173097d2f6789c7d00843386252855e">initCandidate</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a47cc8c89db10ac27483585cd61cf4f91">llvm::GenericSchedulerBase::SchedCandidate::initResourceDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a589e51a1ef960a2b6aaa3854ce04d77a">llvm::SchedBoundary::isTop</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a810d389a7def234e94c2631683ab0ece">llvm::GenericSchedulerBase::NoCand</a>, <a href="#ab169c359dc2328b0a4e93f5f95b82fc0">Pressure</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ad9372964d55580636efe92281b42ad6c">llvm::GenericSchedulerBase::SchedCandidate::Reason</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ab86856838bf1e1577210f03d35273ccb">llvm::GenericSchedulerBase::SchedCandidate::ResDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a9730ea0068843718868a8667f52e3680">llvm::GenericSchedulerBase::SchedModel</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a294e77c4f7245940981e5e259045c7c0">llvm::GenericSchedulerBase::SchedCandidate::setBest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae9476ffbc2f3f195a2116b13f3186194">llvm::GenericSchedulerBase::TRI</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a> and <a href="#ab92590ff43ffbc2173b1429750362fb3">UpwardTracker</a>.</p>


<p>Referenced by <a href="#af3f3a45f145bc8538e160bc3177ffc8f">pickNode</a> and <a href="#a26b8231b39c104871f78b2da6dc1eff5">pickNodeBidirectional</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ErrorMargin {#aca0e645faeaad83ce440e96cc39b6763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSchedStrategy::ErrorMargin = 3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#ab57c0b13438062a884d3e620300fbc03">initialize</a>.</p>

</div>
</div>

### HasHighPressure {#a1902cf3722582eecec1d87862513ba3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSchedStrategy::HasHighPressure</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#a14f3300bee7a18474eb2f103afa3ea22">GCNSchedStrategy</a> and <a href="#ad173097d2f6789c7d00843386252855e">initCandidate</a>.</p>

</div>
</div>

### HighRPSGPRBias {#a07d3ce50a12f46f5923bc2496b05bfb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::GCNSchedStrategy::HighRPSGPRBias = 7</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>

</div>
</div>

### HighRPVGPRBias {#abc922b5ccbfe87a7c54c8d07e122eea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::GCNSchedStrategy::HighRPVGPRBias = 7</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>

</div>
</div>

### KnownExcessRP {#a508f8eece85480c2520ebf5d1f3ef945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSchedStrategy::KnownExcessRP = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#ab57c0b13438062a884d3e620300fbc03">initialize</a>.</p>

</div>
</div>

### SGPRCriticalLimit {#a2ed3b8acc5fc8c2f5c155620b5c32555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSchedStrategy::SGPRCriticalLimit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#ad173097d2f6789c7d00843386252855e">initCandidate</a> and <a href="#ab57c0b13438062a884d3e620300fbc03">initialize</a>.</p>

</div>
</div>

### SGPRLimitBias {#aa5bfab3502e3953ac33f90ae4c86fecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSchedStrategy::SGPRLimitBias = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#ab57c0b13438062a884d3e620300fbc03">initialize</a>.</p>

</div>
</div>

### VGPRCriticalLimit {#a87648a3c33abb5fb8ff110b760424ecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSchedStrategy::VGPRCriticalLimit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#ad173097d2f6789c7d00843386252855e">initCandidate</a> and <a href="#ab57c0b13438062a884d3e620300fbc03">initialize</a>.</p>

</div>
</div>

### VGPRLimitBias {#af100c4ee35e4de0856b35b151479ec3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSchedStrategy::VGPRLimitBias = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#ab57c0b13438062a884d3e620300fbc03">initialize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CurrentStage {#a7eb7baa0abad1c0fb63869eae07507a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt;GCNSchedStageID&gt;::iterator llvm::GCNSchedStrategy::CurrentStage = nullptr</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#a797dfd2abf170515d119ff35a4b5ffe7">advanceStage</a>, <a href="#a5303450aec4d4b8fe49b3af743da555a">getCurrentStage</a>, <a href="#aff69df5b1b61c9a71b8b75855e303e35">getNextStage</a> and <a href="#a405838f7f99c2b64659702103f8bf43f">hasNextStage</a>.</p>

</div>
</div>

### DownwardTracker {#a0c520a204af32794c1f39b7df769c209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNDownwardRPTracker llvm::GCNSchedStrategy::DownwardTracker</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#a14f3300bee7a18474eb2f103afa3ea22">GCNSchedStrategy</a>, <a href="#a9fb4d350598854a68264637b888d3676">getDownwardTracker</a>, <a href="#ad173097d2f6789c7d00843386252855e">initCandidate</a>, <a href="#a2777a131d60f64dbebce2d7116f198c7">pickNodeFromQueue</a> and <a href="#a886677d13d24c974e4cb3086df524e7b">schedNode</a>.</p>

</div>
</div>

### MaxPressure {#a3d63ae4c61c0f0cce4bcff4a33587d31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::GCNSchedStrategy::MaxPressure</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#ad173097d2f6789c7d00843386252855e">initCandidate</a>.</p>

</div>
</div>

### MF {#a5655f7a9e04872d7a5834a44a1d5359c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::GCNSchedStrategy::MF</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#a14f3300bee7a18474eb2f103afa3ea22">GCNSchedStrategy</a> and <a href="#ab57c0b13438062a884d3e620300fbc03">initialize</a>.</p>

</div>
</div>

### Pressure {#ab169c359dc2328b0a4e93f5f95b82fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::GCNSchedStrategy::Pressure</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#ad173097d2f6789c7d00843386252855e">initCandidate</a> and <a href="#a2777a131d60f64dbebce2d7116f198c7">pickNodeFromQueue</a>.</p>

</div>
</div>

### SchedStages {#a1736ffcc1fcc46c9c47748d5a9a04c4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;GCNSchedStageID, 4&gt; llvm::GCNSchedStrategy::SchedStages</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#a797dfd2abf170515d119ff35a4b5ffe7">advanceStage</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#ab9b774c18357fd89d3da62c07828868d">llvm::GCNMaxILPSchedStrategy::GCNMaxILPSchedStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#ae5dff5cf85f1ae74f4b05b1c7638d694">llvm::GCNMaxMemoryClauseSchedStrategy::GCNMaxMemoryClauseSchedStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxoccupancyschedstrategy/#a1aaa47dd65d2e5e66930f7c3bdb2a6bd">llvm::GCNMaxOccupancySchedStrategy::GCNMaxOccupancySchedStrategy</a>, <a href="#a5303450aec4d4b8fe49b3af743da555a">getCurrentStage</a>, <a href="#aff69df5b1b61c9a71b8b75855e303e35">getNextStage</a> and <a href="#a405838f7f99c2b64659702103f8bf43f">hasNextStage</a>.</p>

</div>
</div>

### SGPRExcessLimit {#aa8793c7d097d298c1590b67980054d8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSchedStrategy::SGPRExcessLimit</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#ad173097d2f6789c7d00843386252855e">initCandidate</a> and <a href="#ab57c0b13438062a884d3e620300fbc03">initialize</a>.</p>

</div>
</div>

### TargetOccupancy {#a45c6b23ba1bf5916572a93ef35d962c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSchedStrategy::TargetOccupancy</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#a14f3300bee7a18474eb2f103afa3ea22">GCNSchedStrategy</a>, <a href="#ad37490b68720625392a017b47f21b349">getTargetOccupancy</a>, <a href="#ab57c0b13438062a884d3e620300fbc03">initialize</a> and <a href="#ad79aeb604df3043f82a984f37d9511be">setTargetOccupancy</a>.</p>

</div>
</div>

### UpwardTracker {#ab92590ff43ffbc2173b1429750362fb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNUpwardRPTracker llvm::GCNSchedStrategy::UpwardTracker</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#a14f3300bee7a18474eb2f103afa3ea22">GCNSchedStrategy</a>, <a href="#afa4a2ed99ec1f703c8571b3e00b3e540">getUpwardTracker</a>, <a href="#ad173097d2f6789c7d00843386252855e">initCandidate</a>, <a href="#a2777a131d60f64dbebce2d7116f198c7">pickNodeFromQueue</a> and <a href="#a886677d13d24c974e4cb3086df524e7b">schedNode</a>.</p>

</div>
</div>

### VGPRExcessLimit {#a54479ded7088e7b425de5d6c1f77fb7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSchedStrategy::VGPRExcessLimit</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#ad173097d2f6789c7d00843386252855e">initCandidate</a> and <a href="#ab57c0b13438062a884d3e620300fbc03">initialize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
