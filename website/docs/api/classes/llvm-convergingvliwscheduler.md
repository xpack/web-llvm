---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/convergingvliwscheduler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ConvergingVLIWScheduler` Class



## Declaration

<div class="doxyDeclaration">
class llvm::ConvergingVLIWScheduler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">llvm/CodeGen/VLIWMachineScheduler.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> - Interface to the scheduling algorithm used by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a>. <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonconvergingvliwscheduler">HexagonConvergingVLIWScheduler</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CandResult { <a href="#af9a303a67b1bbedf1f0638d172404be3">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represent the type of <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/schedcandidate">SchedCandidate</a> found within a single queue. <a href="#af9a303a67b1bbedf1f0638d172404be3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a8838d66fd452f7cdd09e825269ecbf1f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sunit/#a26a3c0b6567d1e8cf9ac8492e6e5f62f">SUnit::NodeQueueId</a>: 0 (none), 1 (top), 2 (bot), 3 (both) <a href="#a8838d66fd452f7cdd09e825269ecbf1f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb7ccdb955d8d00eb2e06f255a5da223">ConvergingVLIWScheduler</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a989ea7a5acda7a8054e9bc0d827db888">~ConvergingVLIWScheduler</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef655ef720977fd68fbd4bf24b5ab3d8">initialize</a> (ScheduleDAGMI *dag) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the strategy after building the DAG for a new region. <a href="#aef655ef720977fd68fbd4bf24b5ab3d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bee087d8d270d2eb8823dc5b9dd4e0e">pickNode</a> (bool &amp;IsTopNode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick the best node to balance the schedule. Implements <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a>. <a href="#a3bee087d8d270d2eb8823dc5b9dd4e0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab76f5e165cdf261f940b854e739a789b">schedNode</a> (SUnit *SU, bool IsTopNode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the scheduler's state after scheduling a node. <a href="#ab76f5e165cdf261f940b854e739a789b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8c1e5b05c8d75032ef68b1282aef2b2">releaseTopNode</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When all predecessor dependencies have been resolved, free this node for top-down scheduling. <a href="#ad8c1e5b05c8d75032ef68b1282aef2b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a241c866b4c0500ad383acfd1d87d3983">releaseBottomNode</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When all successor dependencies have been resolved, free this node for bottom-up scheduling. <a href="#a241c866b4c0500ad383acfd1d87d3983">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b23d7e688d2aeeae0f12d2a32314857">reportPackets</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vliwresourcemodel">VLIWResourceModel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44151db7d080309a772d77b69aaa1984">createVLIWResourceModel</a> (const TargetSubtargetInfo &amp;STI, const TargetSchedModel *SchedModel) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb98e755dacbd7d91a9910fe4dcea63c">pickNodeBidrectional</a> (bool &amp;IsTopNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick the best candidate node from either the top or bottom queue. <a href="#adb98e755dacbd7d91a9910fe4dcea63c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72c1f9735ae80acb1e429fa095ce3739">pressureChange</a> (const SUnit *SU, bool isBotUp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the instruction changes the register pressure of a register in the high pressure set. <a href="#a72c1f9735ae80acb1e429fa095ce3739">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af64a330eb150020132eb5c092cb3f454">SchedulingCost</a> (ReadyQueue &amp;Q, SUnit *SU, SchedCandidate &amp;Candidate, RegPressureDelta &amp;Delta, bool verbose)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Single point to compute overall scheduling cost. <a href="#af64a330eb150020132eb5c092cb3f454">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af9a303a67b1bbedf1f0638d172404be3">CandResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa641d58b022e9702656e1a58369931e5">pickNodeFromQueue</a> (VLIWSchedBoundary &amp;Zone, const RegPressureTracker &amp;RPTracker, SchedCandidate &amp;Candidate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick the best candidate from the top queue. <a href="#aa641d58b022e9702656e1a58369931e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8c97fda1a0fecd51065dc8a3ce566a3">traceCandidate</a> (const char *Label, const ReadyQueue &amp;Q, SUnit *SU, int Cost, PressureChange P=PressureChange())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba911ea9e1feddf77d47ae9112f534e0">readyQueueVerboseDump</a> (const RegPressureTracker &amp;RPTracker, SchedCandidate &amp;Candidate, ReadyQueue &amp;Q)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler">VLIWMachineScheduler</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a187af70a733b698fbe59b50ff1fa0073">DAG</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeea464a2bbf5ddf0aadd356246ca08d">SchedModel</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary">VLIWSchedBoundary</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70cc4724751ac8752aacd038a455a1c9">Top</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary">VLIWSchedBoundary</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b1bc7ac4c6a5eb2974a5fe039a629d3">Bot</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a759b27358170a48eb481884a74250716">HighPressureSets</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of pressure sets that have a high pressure level in the region. <a href="#a759b27358170a48eb481884a74250716">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34187a370b7c8eb6b6d180ac6faccf29">PriorityOne</a> = 200</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae92e52d0090af0f8abe764f84b20fd98">PriorityTwo</a> = 50</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedc6b321add26cbefb719411e399115a">PriorityThree</a> = 75</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e0d2e07f9810de66c15e10d0d489a8f">ScaleTwo</a> = 10</td>
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


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a8838d66fd452f7cdd09e825269ecbf1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sunit/#a26a3c0b6567d1e8cf9ac8492e6e5f62f">SUnit::NodeQueueId</a>: 0 (none), 1 (top), 2 (bot), 3 (both)</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TopQID<a id="a8838d66fd452f7cdd09e825269ecbf1fa40f7f0675083aaa0ae6f43946859c03b"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BotQID<a id="a8838d66fd452f7cdd09e825269ecbf1fa0644396ca457428e0f89e799f32a1906"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LogMaxQID<a id="a8838d66fd452f7cdd09e825269ecbf1fa2ec88327b6f9d8705576e81f14e6a2fc"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>

</div>
</div>

### CandResult {#af9a303a67b1bbedf1f0638d172404be3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ConvergingVLIWScheduler::CandResult </td>
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

<p>Represent the type of <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/schedcandidate">SchedCandidate</a> found within a single queue.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoCand<a id="af9a303a67b1bbedf1f0638d172404be3ac3d851ccf9fb5b2af20e0a7b7cf50293"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NodeOrder<a id="af9a303a67b1bbedf1f0638d172404be3a150549a0e64f5931b47fb787a1f5a918"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SingleExcess<a id="af9a303a67b1bbedf1f0638d172404be3ac2bece2a2d95f83deb7849561dbdea72"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SingleCritical<a id="af9a303a67b1bbedf1f0638d172404be3a887ecae32c054a2da68904d6b66ae9c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SingleMax<a id="af9a303a67b1bbedf1f0638d172404be3ab5998e48e4aa19e1d0158142251e23a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MultiPressure<a id="af9a303a67b1bbedf1f0638d172404be3a3236f202562ff72d635a070985b2548e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BestCost<a id="af9a303a67b1bbedf1f0638d172404be3a078181451903d616be973699a842269c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Weak<a id="af9a303a67b1bbedf1f0638d172404be3a30e036317994335b912b3602e732a529"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ConvergingVLIWScheduler() {#aeb7ccdb955d8d00eb2e06f255a5da223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConvergingVLIWScheduler::ConvergingVLIWScheduler ()</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>References <a href="#a9b1bc7ac4c6a5eb2974a5fe039a629d3">Bot</a>, <a href="#a8838d66fd452f7cdd09e825269ecbf1fa0644396ca457428e0f89e799f32a1906">BotQID</a>, <a href="#a70cc4724751ac8752aacd038a455a1c9">Top</a> and <a href="#a8838d66fd452f7cdd09e825269ecbf1fa40f7f0675083aaa0ae6f43946859c03b">TopQID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary/#a2b9addafd0dbd0f989ed47c4cb88e704">llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::VLIWSchedBoundary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ConvergingVLIWScheduler() {#a989ea7a5acda7a8054e9bc0d827db888}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::ConvergingVLIWScheduler::~ConvergingVLIWScheduler ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### initialize() {#aef655ef720977fd68fbd4bf24b5ab3d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConvergingVLIWScheduler::initialize (<a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> * DAG)</td>
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

<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="#a9b1bc7ac4c6a5eb2974a5fe039a629d3">Bot</a>, <a href="#a44151db7d080309a772d77b69aaa1984">createVLIWResourceModel</a>, <a href="#a187af70a733b698fbe59b50ff1fa0073">DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="#a759b27358170a48eb481884a74250716">HighPressureSets</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp/#a896b704353a0944b794b7793550ccf96">RPThreshold</a>, <a href="#aeeea464a2bbf5ddf0aadd356246ca08d">SchedModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="#a70cc4724751ac8752aacd038a455a1c9">Top</a>.</p>

</div>
</div>

### pickNode() {#a3bee087d8d270d2eb8823dc5b9dd4e0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * ConvergingVLIWScheduler::pickNode (bool &amp; IsTopNode)</td>
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

<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 947 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9b1bc7ac4c6a5eb2974a5fe039a629d3">Bot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/misched/#a76ffbaf191b81010c8e5da3c4ce028b3abd98ce24773c9ca1e3f7ce3c541e43ea">llvm::MISched::BottomUp</a>, <a href="#a187af70a733b698fbe59b50ff1fa0073">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ac198a5fb130b4c09836ba20e01b4290d">llvm::SUnit::isBottomReady</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae0b8da4dfde85d4ddc32359ca52dc493">llvm::SUnit::isTopReady</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#af9a303a67b1bbedf1f0638d172404be3ac3d851ccf9fb5b2af20e0a7b7cf50293">NoCand</a>, <a href="#adb98e755dacbd7d91a9910fe4dcea63c">pickNodeBidrectional</a>, <a href="#aa641d58b022e9702656e1a58369931e5">pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa9ff814049edfef549accbca1a8e9eff">llvm::PreRADirection</a>, <a href="#a5b23d7e688d2aeeae0f12d2a32314857">reportPackets</a>, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/schedcandidate/#aff1fbd60b344a6c92df3676c7e4abc78">llvm::ConvergingVLIWScheduler::SchedCandidate::SU</a>, <a href="#a70cc4724751ac8752aacd038a455a1c9">Top</a> and <a href="/web-llvm/docs/api/namespaces/llvm/misched/#a76ffbaf191b81010c8e5da3c4ce028b3ae89742249a15ad5696e3dcec82f0e76a">llvm::MISched::TopDown</a>.</p>

</div>
</div>

### releaseBottomNode() {#a241c866b4c0500ad383acfd1d87d3983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConvergingVLIWScheduler::releaseBottomNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>When all successor dependencies have been resolved, free this node for bottom-up scheduling.</p>

<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9b1bc7ac4c6a5eb2974a5fe039a629d3">Bot</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aa1dfdcdc657e12c47e72d9dbe251ac85">llvm::SUnit::BotReadyCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a>.</p>

</div>
</div>

### releaseTopNode() {#ad8c1e5b05c8d75032ef68b1282aef2b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConvergingVLIWScheduler::releaseTopNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>When all predecessor dependencies have been resolved, free this node for top-down scheduling.</p>

<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a5eca2019521fd47b79fe5ef66d02fd43">llvm::SDep::getLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>, <a href="#a70cc4724751ac8752aacd038a455a1c9">Top</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2a6f92b9c5aba34d3b07f3ebe229ccff">llvm::SUnit::TopReadyCycle</a>.</p>

</div>
</div>

### reportPackets() {#a5b23d7e688d2aeeae0f12d2a32314857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ConvergingVLIWScheduler::reportPackets ()</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>References <a href="#a9b1bc7ac4c6a5eb2974a5fe039a629d3">Bot</a> and <a href="#a70cc4724751ac8752aacd038a455a1c9">Top</a>.</p>


<p>Referenced by <a href="#a3bee087d8d270d2eb8823dc5b9dd4e0e">pickNode</a>.</p>

</div>
</div>

### schedNode() {#ab76f5e165cdf261f940b854e739a789b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConvergingVLIWScheduler::schedNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, bool IsTopNode)</td>
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


<p>This is the same node that was just returned by <a href="#a3bee087d8d270d2eb8823dc5b9dd4e0e">pickNode()</a>. However, <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler">VLIWMachineScheduler</a> needs to update it's state based on the current cycle before <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> does.</p>


<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 996 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="#a9b1bc7ac4c6a5eb2974a5fe039a629d3">Bot</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aa1dfdcdc657e12c47e72d9dbe251ac85">llvm::SUnit::BotReadyCycle</a>, <a href="#a70cc4724751ac8752aacd038a455a1c9">Top</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2a6f92b9c5aba34d3b07f3ebe229ccff">llvm::SUnit::TopReadyCycle</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### createVLIWResourceModel() {#a44151db7d080309a772d77b69aaa1984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLIWResourceModel * ConvergingVLIWScheduler::createVLIWResourceModel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> * SchedModel)</td>
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



<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>Reference <a href="#aeeea464a2bbf5ddf0aadd356246ca08d">SchedModel</a>.</p>


<p>Referenced by <a href="#aef655ef720977fd68fbd4bf24b5ab3d8">initialize</a>.</p>

</div>
</div>

### pickNodeBidrectional() {#adb98e755dacbd7d91a9910fe4dcea63c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * ConvergingVLIWScheduler::pickNodeBidrectional (bool &amp; IsTopNode)</td>
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

<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 881 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9b1bc7ac4c6a5eb2974a5fe039a629d3">Bot</a>, <a href="#a187af70a733b698fbe59b50ff1fa0073">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#af9a303a67b1bbedf1f0638d172404be3ac3d851ccf9fb5b2af20e0a7b7cf50293">NoCand</a>, <a href="#aa641d58b022e9702656e1a58369931e5">pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/schedcandidate/#ad8ad8d58d4dc381ab6a5f54c4f809217">llvm::ConvergingVLIWScheduler::SchedCandidate::SCost</a>, <a href="#af9a303a67b1bbedf1f0638d172404be3a887ecae32c054a2da68904d6b66ae9c9">SingleCritical</a>, <a href="#af9a303a67b1bbedf1f0638d172404be3ac2bece2a2d95f83deb7849561dbdea72">SingleExcess</a>, <a href="#af9a303a67b1bbedf1f0638d172404be3ab5998e48e4aa19e1d0158142251e23a6">SingleMax</a>, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/schedcandidate/#aff1fbd60b344a6c92df3676c7e4abc78">llvm::ConvergingVLIWScheduler::SchedCandidate::SU</a> and <a href="#a70cc4724751ac8752aacd038a455a1c9">Top</a>.</p>


<p>Referenced by <a href="#a3bee087d8d270d2eb8823dc5b9dd4e0e">pickNode</a>.</p>

</div>
</div>

### pickNodeFromQueue() {#aa641d58b022e9702656e1a58369931e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConvergingVLIWScheduler::CandResult ConvergingVLIWScheduler::pickNodeFromQueue (<a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary">VLIWSchedBoundary</a> &amp; Zone, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> &amp; RPTracker, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/schedcandidate">SchedCandidate</a> &amp; Candidate)</td>
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

<p>Pick the best candidate from the top queue.</p>


<p>TODO: getMaxPressureDelta results can be mostly cached for each <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> during DAG building. To adjust for the current scheduling location we need to maintain the number of vreg uses remaining to be top-scheduled.</p>


<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 766 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary/#a82762ba9a6d9a67d70e532100f9512cb">llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::Available</a>, <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#a4afc92f2d387ce9eb2c2647dec8bf92a">llvm::ReadyQueue::begin</a>, <a href="#af9a303a67b1bbedf1f0638d172404be3a078181451903d616be973699a842269c">BestCost</a>, <a href="#a8838d66fd452f7cdd09e825269ecbf1fa0644396ca457428e0f89e799f32a1906">BotQID</a>, <a href="#a187af70a733b698fbe59b50ff1fa0073">DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#a61a4a769784e3da32d297c2752646aee">llvm::ReadyQueue::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#a1f6ee31ad507dd548edfd2fa1fa91b23">llvm::ReadyQueue::end</a>, <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#afe1bde7001d7b6a70198dc827f4a28e2">llvm::ReadyQueue::getID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a13933f8ac2f5e1a34cf53b2c1e1bdc5b">llvm::getWeakLeft</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary/#a22fcbadc45fff4fab6990448ae152ee9">llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::isLatencyBound</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#af9a303a67b1bbedf1f0638d172404be3ac3d851ccf9fb5b2af20e0a7b7cf50293">NoCand</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="#af9a303a67b1bbedf1f0638d172404be3a150549a0e64f5931b47fb787a1f5a918">NodeOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>, <a href="#aba911ea9e1feddf77d47ae9112f534e0">readyQueueVerboseDump</a>, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/schedcandidate/#a56e7a6b15ad7a5e7d0989ea13d3db5d3">llvm::ConvergingVLIWScheduler::SchedCandidate::RPDelta</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp/#ae505c7154e8681f73259461496fbc7fa">SchedDebugVerboseLevel</a>, <a href="#af64a330eb150020132eb5c092cb3f454">SchedulingCost</a>, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/schedcandidate/#ad8ad8d58d4dc381ab6a5f54c4f809217">llvm::ConvergingVLIWScheduler::SchedCandidate::SCost</a>, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/schedcandidate/#aff1fbd60b344a6c92df3676c7e4abc78">llvm::ConvergingVLIWScheduler::SchedCandidate::SU</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a>, <a href="#a8838d66fd452f7cdd09e825269ecbf1fa40f7f0675083aaa0ae6f43946859c03b">TopQID</a>, <a href="#af8c97fda1a0fecd51065dc8a3ce566a3">traceCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp/#a8d2400ea611460a68f3cff3456cbb4ae">UseNewerCandidate</a> and <a href="#af9a303a67b1bbedf1f0638d172404be3a30e036317994335b912b3602e732a529">Weak</a>.</p>


<p>Referenced by <a href="#a3bee087d8d270d2eb8823dc5b9dd4e0e">pickNode</a> and <a href="#adb98e755dacbd7d91a9910fe4dcea63c">pickNodeBidrectional</a>.</p>

</div>
</div>

### pressureChange() {#a72c1f9735ae80acb1e429fa095ce3739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ConvergingVLIWScheduler::pressureChange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, bool isBotUp)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the instruction changes the register pressure of a register in the high pressure set.</p>


<p>The function returns a negative value if the pressure decreases and a positive value is the pressure increases. If the instruction doesn't use a high pressure register or doesn't change the register pressure, then return 0.</p>


<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="#a187af70a733b698fbe59b50ff1fa0073">DAG</a>, <a href="#a759b27358170a48eb481884a74250716">HighPressureSets</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#af64a330eb150020132eb5c092cb3f454">SchedulingCost</a>.</p>

</div>
</div>

### readyQueueVerboseDump() {#aba911ea9e1feddf77d47ae9112f534e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConvergingVLIWScheduler::readyQueueVerboseDump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> &amp; RPTracker, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/schedcandidate">SchedCandidate</a> &amp; Candidate, <a href="/web-llvm/docs/api/classes/llvm/readyqueue">ReadyQueue</a> &amp; Q)</td>
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



<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#a4afc92f2d387ce9eb2c2647dec8bf92a">llvm::ReadyQueue::begin</a>, <a href="#a187af70a733b698fbe59b50ff1fa0073">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#a1f6ee31ad507dd548edfd2fa1fa91b23">llvm::ReadyQueue::end</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a25c90e70c6038993c4ef93aff49fb987">llvm::RegPressureTracker::getMaxPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#ac90e8349a5117f988bbb4cf8bf8c5f9f">llvm::ReadyQueue::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#af64a330eb150020132eb5c092cb3f454">SchedulingCost</a>.</p>


<p>Referenced by <a href="#aa641d58b022e9702656e1a58369931e5">pickNodeFromQueue</a>.</p>

</div>
</div>

### SchedulingCost() {#af64a330eb150020132eb5c092cb3f454}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ConvergingVLIWScheduler::SchedulingCost (<a href="/web-llvm/docs/api/classes/llvm/readyqueue">ReadyQueue</a> &amp; Q, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/schedcandidate">SchedCandidate</a> &amp; Candidate, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta">RegPressureDelta</a> &amp; Delta, bool verbose)</td>
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

<p>Single point to compute overall scheduling cost.</p>


<p>TODO: More heuristics will be used soon.</p>


<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="#a9b1bc7ac4c6a5eb2974a5fe039a629d3">Bot</a>, <a href="#a8838d66fd452f7cdd09e825269ecbf1fa0644396ca457428e0f89e799f32a1906">BotQID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp/#a6fda5b03c9cb06d554d7368694ee9a56">CheckEarlyAvail</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a277da5755f2b30ebcebdba51d0de1acf">llvm::RegPressureDelta::CriticalMax</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a589e1a7e9a8a095d8d01ff8ba32b3d14">llvm::RegPressureDelta::CurrentMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#aff9c3b403c6d4af795dd8be1c9612240">llvm::RegPressureDelta::Excess</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8926b25df7254ba2730fa5d7ec139862">llvm::SUnit::getDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a582da862b28b876ef2235781392cffa6">llvm::SUnit::getHeight</a>, <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#afe1bde7001d7b6a70198dc827f4a28e2">llvm::ReadyQueue::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a5eca2019521fd47b79fe5ef66d02fd43">llvm::SDep::getLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurechange/#a1eef24878593ee0080b20b96ce3eb4c4">llvm::PressureChange::getUnitInc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a13933f8ac2f5e1a34cf53b2c1e1bdc5b">llvm::getWeakLeft</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp/#a7b4721361efd8675d16257e7e8542bbe">IgnoreBBRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a6c89ab9b69b3bcaa536702845fd9542d">llvm::SDep::isAssignedRegDep</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abf37b74e017f80f204221fe3143ab89f">llvm::MachineInstr::isPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a7faf5b0345dd1c2fd4b60d7f5108f3b5">llvm::SUnit::isScheduleHigh</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp/#a07cd4ba9b3cd1a7ff745d0238726dab6">isSingleUnscheduledPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp/#ad85e209f5c4b8b0b4f804222439bc5ee">isSingleUnscheduledSucc</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>, <a href="#a72c1f9735ae80acb1e429fa095ce3739">pressureChange</a>, <a href="#a34187a370b7c8eb6b6d180ac6faccf29">PriorityOne</a>, <a href="#aedc6b321add26cbefb719411e399115a">PriorityThree</a>, <a href="#ae92e52d0090af0f8abe764f84b20fd98">PriorityTwo</a>, <a href="#a8e0d2e07f9810de66c15e10d0d489a8f">ScaleTwo</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a>, <a href="#a70cc4724751ac8752aacd038a455a1c9">Top</a> and <a href="#a8838d66fd452f7cdd09e825269ecbf1fa40f7f0675083aaa0ae6f43946859c03b">TopQID</a>.</p>


<p>Referenced by <a href="#aa641d58b022e9702656e1a58369931e5">pickNodeFromQueue</a>, <a href="#aba911ea9e1feddf77d47ae9112f534e0">readyQueueVerboseDump</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonconvergingvliwscheduler/#a5b1da83188ad8ac357edfd719ce2680f">llvm::HexagonConvergingVLIWScheduler::SchedulingCost</a>.</p>

</div>
</div>

### traceCandidate() {#af8c97fda1a0fecd51065dc8a3ce566a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConvergingVLIWScheduler::traceCandidate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Label, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/readyqueue">ReadyQueue</a> &amp; Q, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, int Cost, <a href="/web-llvm/docs/api/classes/llvm/pressurechange">PressureChange</a> P=<a href="/web-llvm/docs/api/classes/llvm/pressurechange">PressureChange</a>())</td>
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



<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="#a187af70a733b698fbe59b50ff1fa0073">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#ac90e8349a5117f988bbb4cf8bf8c5f9f">llvm::ReadyQueue::getName</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#aa641d58b022e9702656e1a58369931e5">pickNodeFromQueue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Bot {#a9b1bc7ac4c6a5eb2974a5fe039a629d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLIWSchedBoundary llvm::ConvergingVLIWScheduler::Bot</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#aeb7ccdb955d8d00eb2e06f255a5da223">ConvergingVLIWScheduler</a>, <a href="#aef655ef720977fd68fbd4bf24b5ab3d8">initialize</a>, <a href="#a3bee087d8d270d2eb8823dc5b9dd4e0e">pickNode</a>, <a href="#adb98e755dacbd7d91a9910fe4dcea63c">pickNodeBidrectional</a>, <a href="#a241c866b4c0500ad383acfd1d87d3983">releaseBottomNode</a>, <a href="#a5b23d7e688d2aeeae0f12d2a32314857">reportPackets</a>, <a href="#ab76f5e165cdf261f940b854e739a789b">schedNode</a>, <a href="#af64a330eb150020132eb5c092cb3f454">SchedulingCost</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonconvergingvliwscheduler/#a5b1da83188ad8ac357edfd719ce2680f">llvm::HexagonConvergingVLIWScheduler::SchedulingCost</a>.</p>

</div>
</div>

### DAG {#a187af70a733b698fbe59b50ff1fa0073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLIWMachineScheduler* llvm::ConvergingVLIWScheduler::DAG = nullptr</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#aef655ef720977fd68fbd4bf24b5ab3d8">initialize</a>, <a href="#a3bee087d8d270d2eb8823dc5b9dd4e0e">pickNode</a>, <a href="#adb98e755dacbd7d91a9910fe4dcea63c">pickNodeBidrectional</a>, <a href="#aa641d58b022e9702656e1a58369931e5">pickNodeFromQueue</a>, <a href="#a72c1f9735ae80acb1e429fa095ce3739">pressureChange</a>, <a href="#aba911ea9e1feddf77d47ae9112f534e0">readyQueueVerboseDump</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonconvergingvliwscheduler/#a5b1da83188ad8ac357edfd719ce2680f">llvm::HexagonConvergingVLIWScheduler::SchedulingCost</a> and <a href="#af8c97fda1a0fecd51065dc8a3ce566a3">traceCandidate</a>.</p>

</div>
</div>

### HighPressureSets {#a759b27358170a48eb481884a74250716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;bool&gt; llvm::ConvergingVLIWScheduler::HighPressureSets</td>
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

<p>List of pressure sets that have a high pressure level in the region.</p>

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#aef655ef720977fd68fbd4bf24b5ab3d8">initialize</a> and <a href="#a72c1f9735ae80acb1e429fa095ce3739">pressureChange</a>.</p>

</div>
</div>

### SchedModel {#aeeea464a2bbf5ddf0aadd356246ca08d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSchedModel* llvm::ConvergingVLIWScheduler::SchedModel = nullptr</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a44151db7d080309a772d77b69aaa1984">createVLIWResourceModel</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonconvergingvliwscheduler/#a311da7498b4505daad3a41b25a4315cf">llvm::HexagonConvergingVLIWScheduler::createVLIWResourceModel</a> and <a href="#aef655ef720977fd68fbd4bf24b5ab3d8">initialize</a>.</p>

</div>
</div>

### Top {#a70cc4724751ac8752aacd038a455a1c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLIWSchedBoundary llvm::ConvergingVLIWScheduler::Top</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#aeb7ccdb955d8d00eb2e06f255a5da223">ConvergingVLIWScheduler</a>, <a href="#aef655ef720977fd68fbd4bf24b5ab3d8">initialize</a>, <a href="#a3bee087d8d270d2eb8823dc5b9dd4e0e">pickNode</a>, <a href="#adb98e755dacbd7d91a9910fe4dcea63c">pickNodeBidrectional</a>, <a href="#ad8c1e5b05c8d75032ef68b1282aef2b2">releaseTopNode</a>, <a href="#a5b23d7e688d2aeeae0f12d2a32314857">reportPackets</a>, <a href="#ab76f5e165cdf261f940b854e739a789b">schedNode</a>, <a href="#af64a330eb150020132eb5c092cb3f454">SchedulingCost</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonconvergingvliwscheduler/#a5b1da83188ad8ac357edfd719ce2680f">llvm::HexagonConvergingVLIWScheduler::SchedulingCost</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### PriorityOne {#a34187a370b7c8eb6b6d180ac6faccf29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ConvergingVLIWScheduler::PriorityOne = 200</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#af64a330eb150020132eb5c092cb3f454">SchedulingCost</a>.</p>

</div>
</div>

### PriorityThree {#aedc6b321add26cbefb719411e399115a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ConvergingVLIWScheduler::PriorityThree = 75</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#af64a330eb150020132eb5c092cb3f454">SchedulingCost</a>.</p>

</div>
</div>

### PriorityTwo {#ae92e52d0090af0f8abe764f84b20fd98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ConvergingVLIWScheduler::PriorityTwo = 50</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#af64a330eb150020132eb5c092cb3f454">SchedulingCost</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonconvergingvliwscheduler/#a5b1da83188ad8ac357edfd719ce2680f">llvm::HexagonConvergingVLIWScheduler::SchedulingCost</a>.</p>

</div>
</div>

### ScaleTwo {#a8e0d2e07f9810de66c15e10d0d489a8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ConvergingVLIWScheduler::ScaleTwo = 10</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#af64a330eb150020132eb5c092cb3f454">SchedulingCost</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
