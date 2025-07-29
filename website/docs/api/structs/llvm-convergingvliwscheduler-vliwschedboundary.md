---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/convergingvliwscheduler/vliwschedboundary
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `VLIWSchedBoundary` Struct

<p>Each Scheduling boundary is associated with ready queues. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ConvergingVLIWScheduler::VLIWSchedBoundary { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">llvm/CodeGen/VLIWMachineScheduler.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b9addafd0dbd0f989ed47c4cb88e704">VLIWSchedBoundary</a> (unsigned ID, const Twine &amp;Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pending queues extend the ready queues with the same <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and the PendingFlag set. <a href="#a2b9addafd0dbd0f989ed47c4cb88e704">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af855b75902853f01361087338474e82d">VLIWSchedBoundary</a> (const VLIWSchedBoundary &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b1cf07509151d119465a18a1c381ea3">~VLIWSchedBoundary</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary">VLIWSchedBoundary</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c4d7600c9650983c896303892213221">operator=</a> (const VLIWSchedBoundary &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa50af97a81760e0b9bca79b4812d3e5">init</a> (VLIWMachineScheduler *dag, const TargetSchedModel *smodel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a6efc0e0ddae589abd29500051b42c9">isTop</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af46e7864fe409ea4ae6b1b56e8baa9a1">checkHazard</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this SU have a hazard within the current instruction group. <a href="#af46e7864fe409ea4ae6b1b56e8baa9a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d09c302c679e8cc5d2118123aed98ca">releaseNode</a> (SUnit *SU, unsigned ReadyCycle)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae180e4a4ffc42220d0fd4b80db901fac">bumpCycle</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move the boundary of scheduled code by one cycle. <a href="#ae180e4a4ffc42220d0fd4b80db901fac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5049c1efdcf61c9406251e4c41db15e0">bumpNode</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move the boundary of scheduled code by one <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="#a5049c1efdcf61c9406251e4c41db15e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f64e612634009b7ced96fbf06f6b445">releasePending</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release pending ready nodes in to the available queue. <a href="#a7f64e612634009b7ced96fbf06f6b445">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dbbbc058a8845ce06066006b544f7c5">removeReady</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove SU from the ready set for this boundary. <a href="#a2dbbbc058a8845ce06066006b544f7c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa18aa1832f12c6ca7ee45d51101385c8">pickOnlyChoice</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this queue only has one ready candidate, return it. <a href="#aa18aa1832f12c6ca7ee45d51101385c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22fcbadc45fff4fab6990448ae152ee9">isLatencyBound</a> (SUnit *SU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler">VLIWMachineScheduler</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef275178044762d05bab6fa2a2e8857">DAG</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a151c9cb90050c235a96edc7bece4d6b7">SchedModel</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/readyqueue">ReadyQueue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82762ba9a6d9a67d70e532100f9512cb">Available</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/readyqueue">ReadyQueue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d16717178e1d9f2818eb8482ea3df91">Pending</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a383ad990879424dc98e8c98d1739fa1c">CheckPending</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d9b7da4f22279749e353a8cfd4ad687">HazardRec</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vliwresourcemodel">VLIWResourceModel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a547811c189bc99f76bf3e59c8ac547d1">ResourceModel</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f6e6e08cf13bdeb2c3c2fb098245584">CurrCycle</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0154bd7be9607deec1be88b0c707c0f3">IssueCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a229ab3226e55a829d946a051d016254d">CriticalPathLength</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52cf937a31f5a9dff56918b97ed9a94b">MinReadyCycle</a> = std::numeric_limits&lt;unsigned&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MinReadyCycle - <a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> of the soonest available instruction. <a href="#a52cf937a31f5a9dff56918b97ed9a94b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8c871e37271deb3a0ea0f41f0c64347">MaxMinLatency</a> = 0</td>
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

<p>Each Scheduling boundary is associated with ready queues.</p>


<p>It tracks the current cycle in whichever direction at has moved, and maintains the state of "hazards" and other interlocks at the current cycle.</p>


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VLIWSchedBoundary() {#a2b9addafd0dbd0f989ed47c4cb88e704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::VLIWSchedBoundary (unsigned ID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
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

<p>Pending queues extend the ready queues with the same <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and the PendingFlag set.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>References <a href="#a82762ba9a6d9a67d70e532100f9512cb">Available</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aeb7ccdb955d8d00eb2e06f255a5da223">llvm::ConvergingVLIWScheduler::ConvergingVLIWScheduler</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a8838d66fd452f7cdd09e825269ecbf1fa2ec88327b6f9d8705576e81f14e6a2fc">llvm::ConvergingVLIWScheduler::LogMaxQID</a> and <a href="#a3d16717178e1d9f2818eb8482ea3df91">Pending</a>.</p>


<p>Referenced by <a href="#a3c4d7600c9650983c896303892213221">operator=</a> and <a href="#af855b75902853f01361087338474e82d">VLIWSchedBoundary</a>.</p>

</div>
</div>

### VLIWSchedBoundary() {#af855b75902853f01361087338474e82d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::VLIWSchedBoundary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary">VLIWSchedBoundary</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Reference <a href="#a2b9addafd0dbd0f989ed47c4cb88e704">VLIWSchedBoundary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VLIWSchedBoundary() {#a1b1cf07509151d119465a18a1c381ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConvergingVLIWScheduler::VLIWSchedBoundary::~VLIWSchedBoundary ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="#a4d9b7da4f22279749e353a8cfd4ad687">HazardRec</a> and <a href="#a547811c189bc99f76bf3e59c8ac547d1">ResourceModel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a3c4d7600c9650983c896303892213221}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLIWSchedBoundary &amp; llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary">VLIWSchedBoundary</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Reference <a href="#a2b9addafd0dbd0f989ed47c4cb88e704">VLIWSchedBoundary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### bumpCycle() {#ae180e4a4ffc42220d0fd4b80db901fac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConvergingVLIWScheduler::VLIWSchedBoundary::bumpCycle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move the boundary of scheduled code by one cycle.</p>

<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a82762ba9a6d9a67d70e532100f9512cb">Available</a>, <a href="#a383ad990879424dc98e8c98d1739fa1c">CheckPending</a>, <a href="#a7f6e6e08cf13bdeb2c3c2fb098245584">CurrCycle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a4d9b7da4f22279749e353a8cfd4ad687">HazardRec</a>, <a href="#a0154bd7be9607deec1be88b0c707c0f3">IssueCount</a>, <a href="#a4a6efc0e0ddae589abd29500051b42c9">isTop</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a52cf937a31f5a9dff56918b97ed9a94b">MinReadyCycle</a> and <a href="#a151c9cb90050c235a96edc7bece4d6b7">SchedModel</a>.</p>


<p>Referenced by <a href="#a5049c1efdcf61c9406251e4c41db15e0">bumpNode</a> and <a href="#aa18aa1832f12c6ca7ee45d51101385c8">pickOnlyChoice</a>.</p>

</div>
</div>

### bumpNode() {#a5049c1efdcf61c9406251e4c41db15e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConvergingVLIWScheduler::VLIWSchedBoundary::bumpNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move the boundary of scheduled code by one <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>

<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="#ae180e4a4ffc42220d0fd4b80db901fac">bumpCycle</a>, <a href="#a7f6e6e08cf13bdeb2c3c2fb098245584">CurrCycle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="#a4d9b7da4f22279749e353a8cfd4ad687">HazardRec</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a0be1f84d53e90c247d75f2ed63636761">llvm::SUnit::isCall</a>, <a href="#a0154bd7be9607deec1be88b0c707c0f3">IssueCount</a>, <a href="#a4a6efc0e0ddae589abd29500051b42c9">isTop</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a547811c189bc99f76bf3e59c8ac547d1">ResourceModel</a> and <a href="#a151c9cb90050c235a96edc7bece4d6b7">SchedModel</a>.</p>

</div>
</div>

### checkHazard() {#af46e7864fe409ea4ae6b1b56e8baa9a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConvergingVLIWScheduler::VLIWSchedBoundary::checkHazard (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Does this SU have a hazard within the current instruction group.</p>


<p>The scheduler supports two modes of hazard recognition. The first is the <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> API. It is a fully general hazard recognizer that supports highly complicated in-order reservation tables (<a href="/web-llvm/docs/api/classes/llvm/scoreboardhazardrecognizer">ScoreboardHazardRecognizer</a>) and arbitrary target-specific logic.</p>


<p>The second is a streamlined mechanism that checks for hazards based on simple counters that the scheduler itself maintains. It explicitly checks for instruction dispatch limitations, including the number of micro-ops that can dispatch per cycle.</p>


<p>TODO: Also check whether the SU must start a new group.</p>


<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="#a4d9b7da4f22279749e353a8cfd4ad687">HazardRec</a>, <a href="#a0154bd7be9607deec1be88b0c707c0f3">IssueCount</a>, <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267a4e42ac50bfd060349e49904842121cf1">llvm::ScheduleHazardRecognizer::NoHazard</a> and <a href="#a151c9cb90050c235a96edc7bece4d6b7">SchedModel</a>.</p>


<p>Referenced by <a href="#a2d09c302c679e8cc5d2118123aed98ca">releaseNode</a> and <a href="#a7f64e612634009b7ced96fbf06f6b445">releasePending</a>.</p>

</div>
</div>

### init() {#aaa50af97a81760e0b9bca79b4812d3e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::init (<a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler">VLIWMachineScheduler</a> * dag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> * smodel)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>References <a href="#a229ab3226e55a829d946a051d016254d">CriticalPathLength</a>, <a href="#a7f6e6e08cf13bdeb2c3c2fb098245584">CurrCycle</a>, <a href="#a8ef275178044762d05bab6fa2a2e8857">DAG</a>, <a href="#a0154bd7be9607deec1be88b0c707c0f3">IssueCount</a>, <a href="#a4a6efc0e0ddae589abd29500051b42c9">isTop</a> and <a href="#a151c9cb90050c235a96edc7bece4d6b7">SchedModel</a>.</p>

</div>
</div>

### isLatencyBound() {#a22fcbadc45fff4fab6990448ae152ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::isLatencyBound (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>References <a href="#a229ab3226e55a829d946a051d016254d">CriticalPathLength</a>, <a href="#a7f6e6e08cf13bdeb2c3c2fb098245584">CurrCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8926b25df7254ba2730fa5d7ec139862">llvm::SUnit::getDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a582da862b28b876ef2235781392cffa6">llvm::SUnit::getHeight</a> and <a href="#a4a6efc0e0ddae589abd29500051b42c9">isTop</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aa641d58b022e9702656e1a58369931e5">llvm::ConvergingVLIWScheduler::pickNodeFromQueue</a>.</p>

</div>
</div>

### isTop() {#a4a6efc0e0ddae589abd29500051b42c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::isTop ()</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>References <a href="#a82762ba9a6d9a67d70e532100f9512cb">Available</a> and <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a8838d66fd452f7cdd09e825269ecbf1fa40f7f0675083aaa0ae6f43946859c03b">llvm::ConvergingVLIWScheduler::TopQID</a>.</p>


<p>Referenced by <a href="#ae180e4a4ffc42220d0fd4b80db901fac">bumpCycle</a>, <a href="#a5049c1efdcf61c9406251e4c41db15e0">bumpNode</a>, <a href="#aaa50af97a81760e0b9bca79b4812d3e5">init</a>, <a href="#a22fcbadc45fff4fab6990448ae152ee9">isLatencyBound</a>, <a href="#aa18aa1832f12c6ca7ee45d51101385c8">pickOnlyChoice</a> and <a href="#a7f64e612634009b7ced96fbf06f6b445">releasePending</a>.</p>

</div>
</div>

### pickOnlyChoice() {#aa18aa1832f12c6ca7ee45d51101385c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * ConvergingVLIWScheduler::VLIWSchedBoundary::pickOnlyChoice ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this queue only has one ready candidate, return it.</p>


<p>As a side effect, advance the cycle until at least one node is ready. If multiple instructions are ready, return NULL.</p>


<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a82762ba9a6d9a67d70e532100f9512cb">Available</a>, <a href="#ae180e4a4ffc42220d0fd4b80db901fac">bumpCycle</a>, <a href="#a383ad990879424dc98e8c98d1739fa1c">CheckPending</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a13933f8ac2f5e1a34cf53b2c1e1bdc5b">llvm::getWeakLeft</a>, <a href="#a4d9b7da4f22279749e353a8cfd4ad687">HazardRec</a>, <a href="#a4a6efc0e0ddae589abd29500051b42c9">isTop</a>, <a href="#af8c871e37271deb3a0ea0f41f0c64347">MaxMinLatency</a>, <a href="#a3d16717178e1d9f2818eb8482ea3df91">Pending</a>, <a href="#a7f64e612634009b7ced96fbf06f6b445">releasePending</a> and <a href="#a547811c189bc99f76bf3e59c8ac547d1">ResourceModel</a>.</p>

</div>
</div>

### releaseNode() {#a2d09c302c679e8cc5d2118123aed98ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConvergingVLIWScheduler::VLIWSchedBoundary::releaseNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, unsigned ReadyCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="#a82762ba9a6d9a67d70e532100f9512cb">Available</a>, <a href="#af46e7864fe409ea4ae6b1b56e8baa9a1">checkHazard</a>, <a href="#a7f6e6e08cf13bdeb2c3c2fb098245584">CurrCycle</a>, <a href="#a52cf937a31f5a9dff56918b97ed9a94b">MinReadyCycle</a> and <a href="#a3d16717178e1d9f2818eb8482ea3df91">Pending</a>.</p>

</div>
</div>

### releasePending() {#a7f64e612634009b7ced96fbf06f6b445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConvergingVLIWScheduler::VLIWSchedBoundary::releasePending ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Release pending ready nodes in to the available queue.</p>


<p>This makes them visible to heuristics.</p>


<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="#a82762ba9a6d9a67d70e532100f9512cb">Available</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aa1dfdcdc657e12c47e72d9dbe251ac85">llvm::SUnit::BotReadyCycle</a>, <a href="#af46e7864fe409ea4ae6b1b56e8baa9a1">checkHazard</a>, <a href="#a383ad990879424dc98e8c98d1739fa1c">CheckPending</a>, <a href="#a7f6e6e08cf13bdeb2c3c2fb098245584">CurrCycle</a>, <a href="#a4a6efc0e0ddae589abd29500051b42c9">isTop</a>, <a href="#a52cf937a31f5a9dff56918b97ed9a94b">MinReadyCycle</a>, <a href="#a3d16717178e1d9f2818eb8482ea3df91">Pending</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2a6f92b9c5aba34d3b07f3ebe229ccff">llvm::SUnit::TopReadyCycle</a>.</p>


<p>Referenced by <a href="#aa18aa1832f12c6ca7ee45d51101385c8">pickOnlyChoice</a>.</p>

</div>
</div>

### removeReady() {#a2dbbbc058a8845ce06066006b544f7c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConvergingVLIWScheduler::VLIWSchedBoundary::removeReady (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove SU from the ready set for this boundary.</p>

<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a82762ba9a6d9a67d70e532100f9512cb">Available</a> and <a href="#a3d16717178e1d9f2818eb8482ea3df91">Pending</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Available {#a82762ba9a6d9a67d70e532100f9512cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReadyQueue llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::Available</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#ae180e4a4ffc42220d0fd4b80db901fac">bumpCycle</a>, <a href="#a4a6efc0e0ddae589abd29500051b42c9">isTop</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aa641d58b022e9702656e1a58369931e5">llvm::ConvergingVLIWScheduler::pickNodeFromQueue</a>, <a href="#aa18aa1832f12c6ca7ee45d51101385c8">pickOnlyChoice</a>, <a href="#a2d09c302c679e8cc5d2118123aed98ca">releaseNode</a>, <a href="#a7f64e612634009b7ced96fbf06f6b445">releasePending</a>, <a href="#a2dbbbc058a8845ce06066006b544f7c5">removeReady</a> and <a href="#a2b9addafd0dbd0f989ed47c4cb88e704">VLIWSchedBoundary</a>.</p>

</div>
</div>

### CheckPending {#a383ad990879424dc98e8c98d1739fa1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::CheckPending = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#ae180e4a4ffc42220d0fd4b80db901fac">bumpCycle</a>, <a href="#aa18aa1832f12c6ca7ee45d51101385c8">pickOnlyChoice</a> and <a href="#a7f64e612634009b7ced96fbf06f6b445">releasePending</a>.</p>

</div>
</div>

### CriticalPathLength {#a229ab3226e55a829d946a051d016254d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::CriticalPathLength = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#aaa50af97a81760e0b9bca79b4812d3e5">init</a> and <a href="#a22fcbadc45fff4fab6990448ae152ee9">isLatencyBound</a>.</p>

</div>
</div>

### CurrCycle {#a7f6e6e08cf13bdeb2c3c2fb098245584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::CurrCycle = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#ae180e4a4ffc42220d0fd4b80db901fac">bumpCycle</a>, <a href="#a5049c1efdcf61c9406251e4c41db15e0">bumpNode</a>, <a href="#aaa50af97a81760e0b9bca79b4812d3e5">init</a>, <a href="#a22fcbadc45fff4fab6990448ae152ee9">isLatencyBound</a>, <a href="#a2d09c302c679e8cc5d2118123aed98ca">releaseNode</a> and <a href="#a7f64e612634009b7ced96fbf06f6b445">releasePending</a>.</p>

</div>
</div>

### DAG {#a8ef275178044762d05bab6fa2a2e8857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLIWMachineScheduler* llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::DAG = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#aaa50af97a81760e0b9bca79b4812d3e5">init</a>.</p>

</div>
</div>

### HazardRec {#a4d9b7da4f22279749e353a8cfd4ad687}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer* llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::HazardRec = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#ae180e4a4ffc42220d0fd4b80db901fac">bumpCycle</a>, <a href="#a5049c1efdcf61c9406251e4c41db15e0">bumpNode</a>, <a href="#af46e7864fe409ea4ae6b1b56e8baa9a1">checkHazard</a>, <a href="#aa18aa1832f12c6ca7ee45d51101385c8">pickOnlyChoice</a> and <a href="#a1b1cf07509151d119465a18a1c381ea3">~VLIWSchedBoundary</a>.</p>

</div>
</div>

### IssueCount {#a0154bd7be9607deec1be88b0c707c0f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::IssueCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#ae180e4a4ffc42220d0fd4b80db901fac">bumpCycle</a>, <a href="#a5049c1efdcf61c9406251e4c41db15e0">bumpNode</a>, <a href="#af46e7864fe409ea4ae6b1b56e8baa9a1">checkHazard</a> and <a href="#aaa50af97a81760e0b9bca79b4812d3e5">init</a>.</p>

</div>
</div>

### MaxMinLatency {#af8c871e37271deb3a0ea0f41f0c64347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::MaxMinLatency = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#aa18aa1832f12c6ca7ee45d51101385c8">pickOnlyChoice</a>.</p>

</div>
</div>

### MinReadyCycle {#a52cf937a31f5a9dff56918b97ed9a94b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::MinReadyCycle = std::numeric_limits&lt;unsigned&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MinReadyCycle - <a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> of the soonest available instruction.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#ae180e4a4ffc42220d0fd4b80db901fac">bumpCycle</a>, <a href="#a2d09c302c679e8cc5d2118123aed98ca">releaseNode</a> and <a href="#a7f64e612634009b7ced96fbf06f6b445">releasePending</a>.</p>

</div>
</div>

### Pending {#a3d16717178e1d9f2818eb8482ea3df91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReadyQueue llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::Pending</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#aa18aa1832f12c6ca7ee45d51101385c8">pickOnlyChoice</a>, <a href="#a2d09c302c679e8cc5d2118123aed98ca">releaseNode</a>, <a href="#a7f64e612634009b7ced96fbf06f6b445">releasePending</a>, <a href="#a2dbbbc058a8845ce06066006b544f7c5">removeReady</a> and <a href="#a2b9addafd0dbd0f989ed47c4cb88e704">VLIWSchedBoundary</a>.</p>

</div>
</div>

### ResourceModel {#a547811c189bc99f76bf3e59c8ac547d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLIWResourceModel* llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::ResourceModel = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a5049c1efdcf61c9406251e4c41db15e0">bumpNode</a>, <a href="#aa18aa1832f12c6ca7ee45d51101385c8">pickOnlyChoice</a> and <a href="#a1b1cf07509151d119465a18a1c381ea3">~VLIWSchedBoundary</a>.</p>

</div>
</div>

### SchedModel {#a151c9cb90050c235a96edc7bece4d6b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSchedModel* llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::SchedModel = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#ae180e4a4ffc42220d0fd4b80db901fac">bumpCycle</a>, <a href="#a5049c1efdcf61c9406251e4c41db15e0">bumpNode</a>, <a href="#af46e7864fe409ea4ae6b1b56e8baa9a1">checkHazard</a> and <a href="#aaa50af97a81760e0b9bca79b4812d3e5">init</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
