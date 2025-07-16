---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/schedboundary
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SchedBoundary` Class Reference

<p>Each Scheduling boundary is associated with ready queues. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SchedBoundary { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">llvm/CodeGen/MachineScheduler.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a5add3632690537688eb93db2b4613b70">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sunit/#a26a3c0b6567d1e8cf9ac8492e6e5f62f">SUnit::NodeQueueId</a>: 0 (none), 1 (top), 2 (bot), 3 (both) <a href="#a5add3632690537688eb93db2b4613b70">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a794b66ab6a101286bc422e08fc6e9fff">SchedBoundary</a> (unsigned ID, const Twine &amp;Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pending queues extend the ready queues with the same <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and the PendingFlag set. <a href="#a794b66ab6a101286bc422e08fc6e9fff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c095bc668c91fc2d3a4df68a944793e">SchedBoundary</a> (const SchedBoundary &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ec89d1b58602018ae4e1f98f980501e">~SchedBoundary</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedboundary">SchedBoundary</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33649209a9098af177f974f2ee41faf">operator=</a> (const SchedBoundary &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4863d625621382105fd66cd82810588">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab0971160b7ebc9ee2581f651a3b7f01">init</a> (ScheduleDAGMI *dag, const TargetSchedModel *smodel, SchedRemainder *rem)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a589e51a1ef960a2b6aaa3854ce04d77a">isTop</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acef1c37226a48a752d933063e8ba6f83">getCurrCycle</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of cycles to issue the instructions scheduled in this zone. <a href="#acef1c37226a48a752d933063e8ba6f83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac984b92ac3a64875c7f2908ef617584d">getCurrMOps</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Micro-ops issued in the current cycle. <a href="#ac984b92ac3a64875c7f2908ef617584d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24bc7ce4ae7f1bc672ee20aaefcce30b">getDependentLatency</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29ef846d6fac7aa275808c8866035968">getScheduledLatency</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of latency cycles "covered" by the scheduled instructions. <a href="#a29ef846d6fac7aa275808c8866035968">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7a9c62acba4010b5c47f12f458eaf00">getUnscheduledLatency</a> (SUnit *SU) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab873e76ca432b2280dad3ffc130b6515">getResourceCount</a> (unsigned ResIdx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f3130b70563722e1dc6ddbf616e3e77">getCriticalCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the scaled count of scheduled micro-ops and resources, including executed resources. <a href="#a6f3130b70563722e1dc6ddbf616e3e77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42aaa1b48f61e21b104a0aab30142385">getExecutedCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a scaled count for the minimum execution time of the scheduled micro-ops that are ready to execute by getExecutedCount. <a href="#a42aaa1b48f61e21b104a0aab30142385">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae98af615296b8adf67556301343d6ca2">getZoneCritResIdx</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ec93f0e570be68d89930c8e4032ef83">isResourceLimited</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a674627365b72b17a9b2e0a99d40ce1">getLatencyStallCycles</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the difference between the given <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>'s ready time and the current cycle. <a href="#a4a674627365b72b17a9b2e0a99d40ce1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b30387e76d2b5a34988ed566a3e5188">getNextResourceCycleByInstance</a> (unsigned InstanceIndex, unsigned ReleaseAtCycle, unsigned AcquireAtCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the next cycle at which the given processor resource unit can be scheduled. <a href="#a0b30387e76d2b5a34988ed566a3e5188">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfca67c9b359b7ad02ab497632bd6b74">getNextResourceCycle</a> (const MCSchedClassDesc *SC, unsigned PIdx, unsigned ReleaseAtCycle, unsigned AcquireAtCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the next cycle at which the given processor resource can be scheduled. <a href="#adfca67c9b359b7ad02ab497632bd6b74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa00ca9cf2d191f3ae5e93a8cd3ddeb60">isUnbufferedGroup</a> (unsigned PIdx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb8558f52662b83fe081b34b1f31fb20">checkHazard</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this SU have a hazard within the current instruction group. <a href="#adb8558f52662b83fe081b34b1f31fb20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e57bf16f8ed97dbbdc4d48655455b3c">findMaxLatency</a> (ArrayRef&lt; SUnit * &gt; ReadySUs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5af50e4260bb23b1035c52c186fdcc8b">getOtherResourceCount</a> (unsigned &amp;OtherCritIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a751090565ab555f2738aec07bc1a350c">releaseNode</a> (SUnit *SU, unsigned ReadyCycle, bool InPQueue, unsigned Idx=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release SU to make it ready. <a href="#a751090565ab555f2738aec07bc1a350c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb74f3d3a30e2ae598ec8a782d9031e8">bumpCycle</a> (unsigned NextCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move the boundary of scheduled code by one cycle. <a href="#abb74f3d3a30e2ae598ec8a782d9031e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e4f8d7ebc77cdaa0241f46d01e7375b">incExecutedResources</a> (unsigned PIdx, unsigned Count)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7776303c35c1b064126b7b310b546be0">countResource</a> (const MCSchedClassDesc *SC, unsigned PIdx, unsigned Cycles, unsigned ReadyCycle, unsigned StartAtCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the given processor resource to this scheduled zone. <a href="#a7776303c35c1b064126b7b310b546be0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b1771cf492495f8f82727657c68e571">bumpNode</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move the boundary of scheduled code by one <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="#a6b1771cf492495f8f82727657c68e571">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a155166a788cfe0d992af6f2e21e6118e">releasePending</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release pending ready nodes in to the available queue. <a href="#a155166a788cfe0d992af6f2e21e6118e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae28da0579ee268c38eb2a5ababa222fa">removeReady</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove SU from the ready set for this boundary. <a href="#ae28da0579ee268c38eb2a5ababa222fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a744d69baffaf2903667eb65cf07a6814">pickOnlyChoice</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call this before applying any other heuristics to the Available queue. <a href="#a744d69baffaf2903667eb65cf07a6814">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53bfc0f964240b77c4569bea523c2b39">dumpReservedCycles</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the state of the information that tracks resource usage. <a href="#a53bfc0f964240b77c4569bea523c2b39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae01f950d577dadad26a49baa47d10d66">dumpScheduledState</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f3e434b23939cec7a3c61b45071a017">DAG</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/schedremainder">SchedRemainder</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64b3464e46fb663d1c409fd21a0fa97b">Rem</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa49fbb78ca6f0a19a967f2f8fb70097d">Available</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3f102348942e4ca3ec057e895138609">Pending</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b96d44ad4639ec8e5840e97cc4654e5">HazardRec</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1dfbedaeb755dbf1de70e584b23abeb">CheckPending</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the pending Q should be checked/updated before scheduling another instruction. <a href="#ae1dfbedaeb755dbf1de70e584b23abeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a370b818f3bb1f36ec91caf31cc95dbd9">CurrCycle</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of cycles it takes to issue the instructions scheduled in this zone. <a href="#a370b818f3bb1f36ec91caf31cc95dbd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab97c65c159cdb647eefe5b081b648333">CurrMOps</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Micro-ops issued in the current cycle. <a href="#ab97c65c159cdb647eefe5b081b648333">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e245aba8e8f34d21fcb0b7578c87fb3">MinReadyCycle</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MinReadyCycle - <a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> of the soonest available instruction. <a href="#a2e245aba8e8f34d21fcb0b7578c87fb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11791567b6935f8a6b995176c8467974">ExpectedLatency</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9e6ffa51f8f3ed9969dbb1a1e599ba8">DependentLatency</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22549ab287b950d591dc90dbbdddc7f5">RetiredMOps</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Count the scheduled (issued) micro-ops that can be retired by time=CurrCycle assuming the first scheduled instr is retired at time=0. <a href="#a22549ab287b950d591dc90dbbdddc7f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff26435a05ab0d28d6e260eb3696790a">ExecutedResCounts</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af18bc8be4817bfa15f2889ac261fe31f">MaxExecutedResCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache the max count for a single resource. <a href="#af18bc8be4817bfa15f2889ac261fe31f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a768f14ab09f9ffc1e8760a4cbd063781">ZoneCritResIdx</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a69de3a676bd84823ac7f3ee424a3f4">IsResourceLimited</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/resourcesegments">ResourceSegments</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30ba79cae0c4a51e6e1b4b7fb83705e3">ReservedResourceSegments</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> how resources have been allocated across the cycles of the execution. <a href="#a30ba79cae0c4a51e6e1b4b7fb83705e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a715f2a77767bd26a183a7fadc77887bb">ReservedCycles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0e3134959c28004f015b8f031464263">ReservedCyclesIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each PIdx, stores first index into ReservedResourceSegments that corresponds to it. <a href="#ae0e3134959c28004f015b8f031464263">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f26751117ede798319fa824d4041803">ResourceGroupSubUnitMasks</a></td>
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


<p>It tracks the current cycle in the direction of movement, and maintains the state of "hazards" and other interlocks at the current cycle.</p>


<p>Definition at line 841 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a5add3632690537688eb93db2b4613b70}

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
<td class="doxyEnumItemName">TopQID<a id="a5add3632690537688eb93db2b4613b70a59084ad51c6205811ea250f40b1a1605"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BotQID<a id="a5add3632690537688eb93db2b4613b70ad5d95226ee8fc3cd039ff3f950559d53"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LogMaxQID<a id="a5add3632690537688eb93db2b4613b70a24eeb4fd34e859a116303de7c456f7d6"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 844 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SchedBoundary() {#a794b66ab6a101286bc422e08fc6e9fff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SchedBoundary::SchedBoundary (unsigned ID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
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

<p>Definition at line 952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="#aa49fbb78ca6f0a19a967f2f8fb70097d">Available</a>, <a href="#a5add3632690537688eb93db2b4613b70a24eeb4fd34e859a116303de7c456f7d6">LogMaxQID</a>, <a href="#ad3f102348942e4ca3ec057e895138609">Pending</a> and <a href="#ad4863d625621382105fd66cd82810588">reset</a>.</p>


<p>Referenced by <a href="#ab33649209a9098af177f974f2ee41faf">operator=</a> and <a href="#a4c095bc668c91fc2d3a4df68a944793e">SchedBoundary</a>.</p>

</div>
</div>

### SchedBoundary() {#a4c095bc668c91fc2d3a4df68a944793e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SchedBoundary::SchedBoundary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/schedboundary">SchedBoundary</a> &amp; other)</td>
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



<p>Definition at line 957 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#ac7752c64c2d688b882808f06328ad521">rem</a> and <a href="#a794b66ab6a101286bc422e08fc6e9fff">SchedBoundary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SchedBoundary() {#a8ec89d1b58602018ae4e1f98f980501e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedBoundary::~SchedBoundary ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 958 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2228 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>Reference <a href="#a9b96d44ad4639ec8e5840e97cc4654e5">HazardRec</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ab33649209a9098af177f974f2ee41faf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedBoundary &amp; llvm::SchedBoundary::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/schedboundary">SchedBoundary</a> &amp; other)</td>
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



<p>Definition at line 956 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a794b66ab6a101286bc422e08fc6e9fff">SchedBoundary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### bumpCycle() {#abb74f3d3a30e2ae598ec8a782d9031e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedBoundary::bumpCycle (unsigned NextCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move the boundary of scheduled code by one cycle.</p>

<p>Declaration at line 1049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2584 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa49fbb78ca6f0a19a967f2f8fb70097d">Available</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a77e51ffc94a77ff8e4778e59a02e7b67">checkResourceLimit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a6f3130b70563722e1dc6ddbf616e3e77">getCriticalCount</a>, <a href="#a29ef846d6fac7aa275808c8866035968">getScheduledLatency</a>, <a href="#a9b96d44ad4639ec8e5840e97cc4654e5">HazardRec</a>, <a href="#a589e51a1ef960a2b6aaa3854ce04d77a">isTop</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a>.</p>


<p>Referenced by <a href="#a6b1771cf492495f8f82727657c68e571">bumpNode</a> and <a href="#a744d69baffaf2903667eb65cf07a6814">pickOnlyChoice</a>.</p>

</div>
</div>

### bumpNode() {#a6b1771cf492495f8f82727657c68e571}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedBoundary::bumpNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move the boundary of scheduled code by one <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>

<p>Declaration at line 1057 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2675 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa49fbb78ca6f0a19a967f2f8fb70097d">Available</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aa1dfdcdc657e12c47e72d9dbe251ac85">llvm::SUnit::BotReadyCycle</a>, <a href="#abb74f3d3a30e2ae598ec8a782d9031e8">bumpCycle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a77e51ffc94a77ff8e4778e59a02e7b67">checkResourceLimit</a>, <a href="#a7776303c35c1b064126b7b310b546be0">countResource</a>, <a href="#a4f3e434b23939cec7a3c61b45071a017">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ae01f950d577dadad26a49baa47d10d66">dumpScheduledState</a>, <a href="#a6f3130b70563722e1dc6ddbf616e3e77">getCriticalCount</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8926b25df7254ba2730fa5d7ec139862">llvm::SUnit::getDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a582da862b28b876ef2235781392cffa6">llvm::SUnit::getHeight</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="#adfca67c9b359b7ad02ab497632bd6b74">getNextResourceCycle</a>, <a href="#ab873e76ca432b2280dad3ffc130b6515">getResourceCount</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcesegments/#a46315c932ddcacb368f78ecc39a96fe3">llvm::ResourceSegments::getResourceIntervalBottom</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcesegments/#ad0173019797b2f865e64a85377cb3bd5">llvm::ResourceSegments::getResourceIntervalTop</a>, <a href="#a29ef846d6fac7aa275808c8866035968">getScheduledLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ab76e4a602699ddc57019efaba62a92b6">llvm::SUnit::hasReservedResource</a>, <a href="#a9b96d44ad4639ec8e5840e97cc4654e5">HazardRec</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a0be1f84d53e90c247d75f2ed63636761">llvm::SUnit::isCall</a>, <a href="#a589e51a1ef960a2b6aaa3854ce04d77a">isTop</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a4ac4d36cb59a4bbf5d93513dad0ff0e9">llvm::SUnit::isUnbuffered</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#ae812475cdb74bfae4780368f4ff01ccf">MIResourceCutOff</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="#a64b3464e46fb663d1c409fd21a0fa97b">Rem</a>, <a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2a6f92b9c5aba34d3b07f3ebe229ccff">llvm::SUnit::TopReadyCycle</a>.</p>

</div>
</div>

### checkHazard() {#adb8558f52662b83fe081b34b1f31fb20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SchedBoundary::checkHazard (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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


<p>Declaration at line 1032 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2454 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a4f3e434b23939cec7a3c61b45071a017">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="#adfca67c9b359b7ad02ab497632bd6b74">getNextResourceCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ab76e4a602699ddc57019efaba62a92b6">llvm::SUnit::hasReservedResource</a>, <a href="#a9b96d44ad4639ec8e5840e97cc4654e5">HazardRec</a>, <a href="#a589e51a1ef960a2b6aaa3854ce04d77a">isTop</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267a4e42ac50bfd060349e49904842121cf1">llvm::ScheduleHazardRecognizer::NoHazard</a> and <a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a>.</p>


<p>Referenced by <a href="#a744d69baffaf2903667eb65cf07a6814">pickOnlyChoice</a> and <a href="#a751090565ab555f2738aec07bc1a350c">releaseNode</a>.</p>

</div>
</div>

### countResource() {#a7776303c35c1b064126b7b310b546be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SchedBoundary::countResource (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SC, unsigned PIdx, unsigned ReleaseAtCycle, unsigned NextCycle, unsigned AcquireAtCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the given processor resource to this scheduled zone.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReleaseAtCycle</td>
<td class="doxyParamItemDescription"><p>indicates the number of consecutive (non-pipelined) cycles during which this resource is released.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AcquireAtCycle</td>
<td class="doxyParamItemDescription"><p>indicates the number of consecutive (non-pipelined) cycles at which the resource is aquired after issue (assuming no stalls).</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the next cycle at which the instruction may execute without oversubscribing resources.</p></dd>
</dl>


<p>Declaration at line 1053 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2638 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a6f3130b70563722e1dc6ddbf616e3e77">getCriticalCount</a>, <a href="#adfca67c9b359b7ad02ab497632bd6b74">getNextResourceCycle</a>, <a href="#ab873e76ca432b2280dad3ffc130b6515">getResourceCount</a>, <a href="#a2e4f8d7ebc77cdaa0241f46d01e7375b">incExecutedResources</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a64b3464e46fb663d1c409fd21a0fa97b">Rem</a> and <a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a>.</p>


<p>Referenced by <a href="#a6b1771cf492495f8f82727657c68e571">bumpNode</a>.</p>

</div>
</div>

### dumpReservedCycles() {#a53bfc0f964240b77c4569bea523c2b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SchedBoundary::dumpReservedCycles ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the state of the information that tracks resource usage.</p>


<p>Dump the content of the ReservedCycles vector for the resources that are used in the basic block.</p>


<p>Declaration at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2914 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a>.</p>


<p>Referenced by <a href="#ae01f950d577dadad26a49baa47d10d66">dumpScheduledState</a> and <a href="#adfca67c9b359b7ad02ab497632bd6b74">getNextResourceCycle</a>.</p>

</div>
</div>

### dumpScheduledState() {#ae01f950d577dadad26a49baa47d10d66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SchedBoundary::dumpScheduledState ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1070 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2940 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#aa49fbb78ca6f0a19a967f2f8fb70097d">Available</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a53bfc0f964240b77c4569bea523c2b39">dumpReservedCycles</a>, <a href="#a42aaa1b48f61e21b104a0aab30142385">getExecutedCount</a>, <a href="#ab873e76ca432b2280dad3ffc130b6515">getResourceCount</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f253389931150fd73bfae4cd61c3ae6">llvm::MISchedDumpReservedCycles</a> and <a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a>.</p>


<p>Referenced by <a href="#a6b1771cf492495f8f82727657c68e571">bumpNode</a>.</p>

</div>
</div>

### findMaxLatency() {#a4e57bf16f8ed97dbbdc4d48655455b3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SchedBoundary::findMaxLatency (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; ReadySUs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2503 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#aa49fbb78ca6f0a19a967f2f8fb70097d">Available</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#af7a9c62acba4010b5c47f12f458eaf00">getUnscheduledLatency</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a4d6bf176cc854701f61fba566b9dbf9b">computeRemLatency</a>.</p>

</div>
</div>

### getCriticalCount() {#a6f3130b70563722e1dc6ddbf616e3e77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::getCriticalCount ()</td>
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

<p>Get the scaled count of scheduled micro-ops and resources, including executed resources.</p>

<p>Definition at line 995 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="#ab873e76ca432b2280dad3ffc130b6515">getResourceCount</a> and <a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a>.</p>


<p>Referenced by <a href="#abb74f3d3a30e2ae598ec8a782d9031e8">bumpCycle</a>, <a href="#a6b1771cf492495f8f82727657c68e571">bumpNode</a> and <a href="#a7776303c35c1b064126b7b310b546be0">countResource</a>.</p>

</div>
</div>

### getCurrCycle() {#acef1c37226a48a752d933063e8ba6f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::getCurrCycle ()</td>
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

<p>Number of cycles to issue the instructions scheduled in this zone.</p>

<p>Definition at line 970 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8668556014566994c07b21391762551b">llvm::GenericSchedulerBase::setPolicy</a>.</p>

</div>
</div>

### getCurrMOps() {#ac984b92ac3a64875c7f2908ef617584d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::getCurrMOps ()</td>
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

<p>Micro-ops issued in the current cycle.</p>

<p>Definition at line 973 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### getDependentLatency() {#a24bc7ce4ae7f1bc672ee20aaefcce30b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::getDependentLatency ()</td>
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



<p>Definition at line 976 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a4d6bf176cc854701f61fba566b9dbf9b">computeRemLatency</a>.</p>

</div>
</div>

### getExecutedCount() {#a42aaa1b48f61e21b104a0aab30142385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::getExecutedCount ()</td>
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

<p>Get a scaled count for the minimum execution time of the scheduled micro-ops that are ready to execute by getExecutedCount.</p>


<p>Notice the feedback loop.</p>


<p>Definition at line 1004 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a>.</p>


<p>Referenced by <a href="#ae01f950d577dadad26a49baa47d10d66">dumpScheduledState</a>.</p>

</div>
</div>

### getLatencyStallCycles() {#a4a674627365b72b17a9b2e0a99d40ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SchedBoundary::getLatencyStallCycles (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the difference between the given <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>'s ready time and the current cycle.</p>


<p>Compute the stall cycles based on this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>'s ready time.</p>


<p>Heuristics treat these "soft stalls" differently than the hard stall cycles based on CPU resources and computed by <a href="#adb8558f52662b83fe081b34b1f31fb20">checkHazard()</a>. A fully in-order model (MicroOpBufferSize==0) will not make use of this since instructions are not available for scheduling until they are ready. However, a weaker in-order model may use this for heuristics. For example, if a processor has in-order behavior when reading certain resources, this may come into play.</p>


<p>Declaration at line 1016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2335 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#aa1dfdcdc657e12c47e72d9dbe251ac85">llvm::SUnit::BotReadyCycle</a>, <a href="#a589e51a1ef960a2b6aaa3854ce04d77a">isTop</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a4ac4d36cb59a4bbf5d93513dad0ff0e9">llvm::SUnit::isUnbuffered</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2a6f92b9c5aba34d3b07f3ebe229ccff">llvm::SUnit::TopReadyCycle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### getNextResourceCycle() {#adfca67c9b359b7ad02ab497632bd6b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, unsigned &gt; SchedBoundary::getNextResourceCycle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SC, unsigned PIdx, unsigned ReleaseAtCycle, unsigned AcquireAtCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the next cycle at which the given processor resource can be scheduled.</p>


<p>Returns the next cycle and the index of the processor resource instance in the reserved cycles vector.</p>


<p>Declaration at line 1022 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2373 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a53bfc0f964240b77c4569bea523c2b39">dumpReservedCycles</a>, <a href="#adfca67c9b359b7ad02ab497632bd6b74">getNextResourceCycle</a>, <a href="#a0b30387e76d2b5a34988ed566a3e5188">getNextResourceCycleByInstance</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a2876d288bd148637a0e8d79ce3f0f3fb">InvalidCycle</a>, <a href="#aa00ca9cf2d191f3ae5e93a8cd3ddeb60">isUnbufferedGroup</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaad94654d336ce094254a1c694ee4e5">llvm::MischedDetailResourceBooking</a> and <a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a>.</p>


<p>Referenced by <a href="#a6b1771cf492495f8f82727657c68e571">bumpNode</a>, <a href="#adb8558f52662b83fe081b34b1f31fb20">checkHazard</a>, <a href="#a7776303c35c1b064126b7b310b546be0">countResource</a> and <a href="#adfca67c9b359b7ad02ab497632bd6b74">getNextResourceCycle</a>.</p>

</div>
</div>

### getNextResourceCycleByInstance() {#a0b30387e76d2b5a34988ed566a3e5188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SchedBoundary::getNextResourceCycleByInstance (unsigned InstanceIndex, unsigned ReleaseAtCycle, unsigned AcquireAtCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the next cycle at which the given processor resource unit can be scheduled.</p>

<p>Declaration at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a2876d288bd148637a0e8d79ce3f0f3fb">InvalidCycle</a>, <a href="#a589e51a1ef960a2b6aaa3854ce04d77a">isTop</a> and <a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a>.</p>


<p>Referenced by <a href="#adfca67c9b359b7ad02ab497632bd6b74">getNextResourceCycle</a>.</p>

</div>
</div>

### getOtherResourceCount() {#a5af50e4260bb23b1035c52c186fdcc8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SchedBoundary::getOtherResourceCount (unsigned &amp; OtherCritIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1036 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2524 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#aa49fbb78ca6f0a19a967f2f8fb70097d">Available</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ab873e76ca432b2280dad3ffc130b6515">getResourceCount</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a64b3464e46fb663d1c409fd21a0fa97b">Rem</a> and <a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8668556014566994c07b21391762551b">llvm::GenericSchedulerBase::setPolicy</a>.</p>

</div>
</div>

### getResourceCount() {#ab873e76ca432b2280dad3ffc130b6515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::getResourceCount (unsigned ResIdx)</td>
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



<p>Definition at line 989 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a6b1771cf492495f8f82727657c68e571">bumpNode</a>, <a href="#a7776303c35c1b064126b7b310b546be0">countResource</a>, <a href="#ae01f950d577dadad26a49baa47d10d66">dumpScheduledState</a>, <a href="#a6f3130b70563722e1dc6ddbf616e3e77">getCriticalCount</a> and <a href="#a5af50e4260bb23b1035c52c186fdcc8b">getOtherResourceCount</a>.</p>

</div>
</div>

### getScheduledLatency() {#a29ef846d6fac7aa275808c8866035968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::getScheduledLatency ()</td>
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

<p>Get the number of latency cycles "covered" by the scheduled instructions.</p>


<p>This is the larger of the critical path within the zone and the number of cycles required to issue the instructions.</p>


<p>Definition at line 981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#abb74f3d3a30e2ae598ec8a782d9031e8">bumpCycle</a>, <a href="#a6b1771cf492495f8f82727657c68e571">bumpNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9a83bf7b5f6e85f215ff07a31e0fbe">llvm::tryLatency</a>.</p>

</div>
</div>

### getUnscheduledLatency() {#af7a9c62acba4010b5c47f12f458eaf00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::getUnscheduledLatency (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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



<p>Definition at line 985 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8926b25df7254ba2730fa5d7ec139862">llvm::SUnit::getDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a582da862b28b876ef2235781392cffa6">llvm::SUnit::getHeight</a> and <a href="#a589e51a1ef960a2b6aaa3854ce04d77a">isTop</a>.</p>


<p>Referenced by <a href="#a4e57bf16f8ed97dbbdc4d48655455b3c">findMaxLatency</a>.</p>

</div>
</div>

### getZoneCritResIdx() {#ae98af615296b8adf67556301343d6ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::getZoneCritResIdx ()</td>
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



<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8668556014566994c07b21391762551b">llvm::GenericSchedulerBase::setPolicy</a>.</p>

</div>
</div>

### incExecutedResources() {#a2e4f8d7ebc77cdaa0241f46d01e7375b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedBoundary::incExecutedResources (unsigned PIdx, unsigned Count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1051 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2622 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>.</p>


<p>Referenced by <a href="#a7776303c35c1b064126b7b310b546be0">countResource</a>.</p>

</div>
</div>

### init() {#aab0971160b7ebc9ee2581f651a3b7f01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedBoundary::init (<a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> * dag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> * smodel, <a href="/web-llvm/docs/api/structs/llvm/schedremainder">SchedRemainder</a> * rem)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 962 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2301 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a4f3e434b23939cec7a3c61b45071a017">DAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a2876d288bd148637a0e8d79ce3f0f3fb">InvalidCycle</a>, <a href="#aa00ca9cf2d191f3ae5e93a8cd3ddeb60">isUnbufferedGroup</a>, <a href="#a64b3464e46fb663d1c409fd21a0fa97b">Rem</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#ac7752c64c2d688b882808f06328ad521">rem</a>, <a href="#ad4863d625621382105fd66cd82810588">reset</a> and <a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a>.</p>

</div>
</div>

### isResourceLimited() {#a2ec93f0e570be68d89930c8e4032ef83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SchedBoundary::isResourceLimited ()</td>
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



<p>Definition at line 1012 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8668556014566994c07b21391762551b">llvm::GenericSchedulerBase::setPolicy</a>.</p>

</div>
</div>

### isTop() {#a589e51a1ef960a2b6aaa3854ce04d77a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SchedBoundary::isTop ()</td>
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



<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="#aa49fbb78ca6f0a19a967f2f8fb70097d">Available</a> and <a href="#a5add3632690537688eb93db2b4613b70a59084ad51c6205811ea250f40b1a1605">TopQID</a>.</p>


<p>Referenced by <a href="#abb74f3d3a30e2ae598ec8a782d9031e8">bumpCycle</a>, <a href="#a6b1771cf492495f8f82727657c68e571">bumpNode</a>, <a href="#adb8558f52662b83fe081b34b1f31fb20">checkHazard</a>, <a href="#a4a674627365b72b17a9b2e0a99d40ce1">getLatencyStallCycles</a>, <a href="#a0b30387e76d2b5a34988ed566a3e5188">getNextResourceCycleByInstance</a>, <a href="#af7a9c62acba4010b5c47f12f458eaf00">getUnscheduledLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad9779ec3011b4547f9a509af82d87a6e">llvm::GenericScheduler::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a5db5287f3514fcc23bb3f93d769b3e96">llvm::PostGenericScheduler::pickNodeFromQueue</a>, <a href="#a155166a788cfe0d992af6f2e21e6118e">releasePending</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9a83bf7b5f6e85f215ff07a31e0fbe">llvm::tryLatency</a>.</p>

</div>
</div>

### isUnbufferedGroup() {#aa00ca9cf2d191f3ae5e93a8cd3ddeb60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SchedBoundary::isUnbufferedGroup (unsigned PIdx)</td>
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



<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a>.</p>


<p>Referenced by <a href="#adfca67c9b359b7ad02ab497632bd6b74">getNextResourceCycle</a> and <a href="#aab0971160b7ebc9ee2581f651a3b7f01">init</a>.</p>

</div>
</div>

### pickOnlyChoice() {#a744d69baffaf2903667eb65cf07a6814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * SchedBoundary::pickOnlyChoice ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Call this before applying any other heuristics to the Available queue.</p>


<p>If this queue only has one ready candidate, return it.</p>


<p>Updates the Available/Pending Q's if necessary and returns the single available instruction, or NULL if there are multiple candidates.</p>


<p>As a side effect, defer any nodes that now hit a hazard, and advance the cycle until at least one node is ready. If multiple instructions are ready, return NULL.</p>


<p>Declaration at line 1066 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2879 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#aa49fbb78ca6f0a19a967f2f8fb70097d">Available</a>, <a href="#abb74f3d3a30e2ae598ec8a782d9031e8">bumpCycle</a>, <a href="#adb8558f52662b83fe081b34b1f31fb20">checkHazard</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ad3f102348942e4ca3ec057e895138609">Pending</a> and <a href="#a155166a788cfe0d992af6f2e21e6118e">releasePending</a>.</p>

</div>
</div>

### releaseNode() {#a751090565ab555f2738aec07bc1a350c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedBoundary::releaseNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, unsigned ReadyCycle, bool InPQueue, unsigned Idx=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Release SU to make it ready.</p>


<p>If it's not in hazard, remove it from pending queue (if already in) and push into available queue. Otherwise, push the SU into pending queue.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">SU</td>
<td class="doxyParamItemDescription"><p>The unit to be released.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReadyCycle</td>
<td class="doxyParamItemDescription"><p>Until which cycle the unit is ready.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InPQueue</td>
<td class="doxyParamItemDescription"><p>Whether SU is already in pending queue.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Idx</td>
<td class="doxyParamItemDescription"><p>Position offset in pending queue (if in it).</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1046 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2550 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa49fbb78ca6f0a19a967f2f8fb70097d">Available</a>, <a href="#adb8558f52662b83fe081b34b1f31fb20">checkHazard</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="#ad3f102348942e4ca3ec057e895138609">Pending</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#af040ecdbfbf801186c7941597cc793a6">ReadyListLimit</a> and <a href="#a3e9e2fcb68f7063b63e67dd34b8fa00f">SchedModel</a>.</p>


<p>Referenced by <a href="#a155166a788cfe0d992af6f2e21e6118e">releasePending</a>.</p>

</div>
</div>

### releasePending() {#a155166a788cfe0d992af6f2e21e6118e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedBoundary::releasePending ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Release pending ready nodes in to the available queue.</p>


<p>This makes them visible to heuristics.</p>


<p>Declaration at line 1059 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2840 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#aa49fbb78ca6f0a19a967f2f8fb70097d">Available</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aa1dfdcdc657e12c47e72d9dbe251ac85">llvm::SUnit::BotReadyCycle</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a589e51a1ef960a2b6aaa3854ce04d77a">isTop</a>, <a href="#ad3f102348942e4ca3ec057e895138609">Pending</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#af040ecdbfbf801186c7941597cc793a6">ReadyListLimit</a>, <a href="#a751090565ab555f2738aec07bc1a350c">releaseNode</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2a6f92b9c5aba34d3b07f3ebe229ccff">llvm::SUnit::TopReadyCycle</a>.</p>


<p>Referenced by <a href="#a744d69baffaf2903667eb65cf07a6814">pickOnlyChoice</a>.</p>

</div>
</div>

### removeReady() {#ae28da0579ee268c38eb2a5ababa222fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedBoundary::removeReady (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove SU from the ready set for this boundary.</p>

<p>Declaration at line 1061 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2867 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa49fbb78ca6f0a19a967f2f8fb70097d">Available</a> and <a href="#ad3f102348942e4ca3ec057e895138609">Pending</a>.</p>

</div>
</div>

### reset() {#ad4863d625621382105fd66cd82810588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedBoundary::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 960 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2243 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa49fbb78ca6f0a19a967f2f8fb70097d">Available</a>, <a href="#a9b96d44ad4639ec8e5840e97cc4654e5">HazardRec</a> and <a href="#ad3f102348942e4ca3ec057e895138609">Pending</a>.</p>


<p>Referenced by <a href="#aab0971160b7ebc9ee2581f651a3b7f01">init</a> and <a href="#a794b66ab6a101286bc422e08fc6e9fff">SchedBoundary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Available {#aa49fbb78ca6f0a19a967f2f8fb70097d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReadyQueue llvm::SchedBoundary::Available</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 854 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#abb74f3d3a30e2ae598ec8a782d9031e8">bumpCycle</a>, <a href="#a6b1771cf492495f8f82727657c68e571">bumpNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a4d6bf176cc854701f61fba566b9dbf9b">computeRemLatency</a>, <a href="#ae01f950d577dadad26a49baa47d10d66">dumpScheduledState</a>, <a href="#a4e57bf16f8ed97dbbdc4d48655455b3c">findMaxLatency</a>, <a href="#a5af50e4260bb23b1035c52c186fdcc8b">getOtherResourceCount</a>, <a href="#a589e51a1ef960a2b6aaa3854ce04d77a">isTop</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad9779ec3011b4547f9a509af82d87a6e">llvm::GenericScheduler::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a5db5287f3514fcc23bb3f93d769b3e96">llvm::PostGenericScheduler::pickNodeFromQueue</a>, <a href="#a744d69baffaf2903667eb65cf07a6814">pickOnlyChoice</a>, <a href="#a751090565ab555f2738aec07bc1a350c">releaseNode</a>, <a href="#a155166a788cfe0d992af6f2e21e6118e">releasePending</a>, <a href="#ae28da0579ee268c38eb2a5ababa222fa">removeReady</a>, <a href="#ad4863d625621382105fd66cd82810588">reset</a>, <a href="#a794b66ab6a101286bc422e08fc6e9fff">SchedBoundary</a> and <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8668556014566994c07b21391762551b">llvm::GenericSchedulerBase::setPolicy</a>.</p>

</div>
</div>

### DAG {#a4f3e434b23939cec7a3c61b45071a017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGMI* llvm::SchedBoundary::DAG = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a6b1771cf492495f8f82727657c68e571">bumpNode</a>, <a href="#adb8558f52662b83fe081b34b1f31fb20">checkHazard</a>, <a href="#aab0971160b7ebc9ee2581f651a3b7f01">init</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a>.</p>

</div>
</div>

### HazardRec {#a9b96d44ad4639ec8e5840e97cc4654e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer* llvm::SchedBoundary::HazardRec = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#abb74f3d3a30e2ae598ec8a782d9031e8">bumpCycle</a>, <a href="#a6b1771cf492495f8f82727657c68e571">bumpNode</a>, <a href="#adb8558f52662b83fe081b34b1f31fb20">checkHazard</a>, <a href="#ad4863d625621382105fd66cd82810588">reset</a> and <a href="#a8ec89d1b58602018ae4e1f98f980501e">~SchedBoundary</a>.</p>

</div>
</div>

### Pending {#ad3f102348942e4ca3ec057e895138609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReadyQueue llvm::SchedBoundary::Pending</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 855 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a4d6bf176cc854701f61fba566b9dbf9b">computeRemLatency</a>, <a href="#a744d69baffaf2903667eb65cf07a6814">pickOnlyChoice</a>, <a href="#a751090565ab555f2738aec07bc1a350c">releaseNode</a>, <a href="#a155166a788cfe0d992af6f2e21e6118e">releasePending</a>, <a href="#ae28da0579ee268c38eb2a5ababa222fa">removeReady</a>, <a href="#ad4863d625621382105fd66cd82810588">reset</a> and <a href="#a794b66ab6a101286bc422e08fc6e9fff">SchedBoundary</a>.</p>

</div>
</div>

### Rem {#a64b3464e46fb663d1c409fd21a0fa97b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedRemainder* llvm::SchedBoundary::Rem = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 852 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a6b1771cf492495f8f82727657c68e571">bumpNode</a>, <a href="#a7776303c35c1b064126b7b310b546be0">countResource</a>, <a href="#a5af50e4260bb23b1035c52c186fdcc8b">getOtherResourceCount</a> and <a href="#aab0971160b7ebc9ee2581f651a3b7f01">init</a>.</p>

</div>
</div>

### SchedModel {#a3e9e2fcb68f7063b63e67dd34b8fa00f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSchedModel* llvm::SchedBoundary::SchedModel = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 851 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#abb74f3d3a30e2ae598ec8a782d9031e8">bumpCycle</a>, <a href="#a6b1771cf492495f8f82727657c68e571">bumpNode</a>, <a href="#adb8558f52662b83fe081b34b1f31fb20">checkHazard</a>, <a href="#a7776303c35c1b064126b7b310b546be0">countResource</a>, <a href="#a53bfc0f964240b77c4569bea523c2b39">dumpReservedCycles</a>, <a href="#ae01f950d577dadad26a49baa47d10d66">dumpScheduledState</a>, <a href="#a6f3130b70563722e1dc6ddbf616e3e77">getCriticalCount</a>, <a href="#a42aaa1b48f61e21b104a0aab30142385">getExecutedCount</a>, <a href="#adfca67c9b359b7ad02ab497632bd6b74">getNextResourceCycle</a>, <a href="#a0b30387e76d2b5a34988ed566a3e5188">getNextResourceCycleByInstance</a>, <a href="#a5af50e4260bb23b1035c52c186fdcc8b">getOtherResourceCount</a>, <a href="#aab0971160b7ebc9ee2581f651a3b7f01">init</a>, <a href="#aa00ca9cf2d191f3ae5e93a8cd3ddeb60">isUnbufferedGroup</a> and <a href="#a751090565ab555f2738aec07bc1a350c">releaseNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CheckPending {#ae1dfbedaeb755dbf1de70e584b23abeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SchedBoundary::CheckPending</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the pending Q should be checked/updated before scheduling another instruction.</p>

<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### CurrCycle {#a370b818f3bb1f36ec91caf31cc95dbd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::CurrCycle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of cycles it takes to issue the instructions scheduled in this zone.</p>


<p>It is defined as: scheduled-micro-ops / issue-width + stalls. See getStalls().</p>


<p>Definition at line 867 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### CurrMOps {#ab97c65c159cdb647eefe5b081b648333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::CurrMOps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Micro-ops issued in the current cycle.</p>

<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### DependentLatency {#ab9e6ffa51f8f3ed9969dbb1a1e599ba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::DependentLatency</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### ExecutedResCounts {#aff26435a05ab0d28d6e260eb3696790a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 16&gt; llvm::SchedBoundary::ExecutedResCounts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### ExpectedLatency {#a11791567b6935f8a6b995176c8467974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::ExpectedLatency</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### IsResourceLimited {#a3a69de3a676bd84823ac7f3ee424a3f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SchedBoundary::IsResourceLimited</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 901 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### MaxExecutedResCount {#af18bc8be4817bfa15f2889ac261fe31f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::MaxExecutedResCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache the max count for a single resource.</p>

<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### MinReadyCycle {#a2e245aba8e8f34d21fcb0b7578c87fb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::MinReadyCycle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MinReadyCycle - <a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> of the soonest available instruction.</p>

<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### ReservedCycles {#a715f2a77767bd26a183a7fadc77887bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::SchedBoundary::ReservedCycles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 908 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### ReservedCyclesIndex {#ae0e3134959c28004f015b8f031464263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 16&gt; llvm::SchedBoundary::ReservedCyclesIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For each PIdx, stores first index into ReservedResourceSegments that corresponds to it.</p>


<p>For example, consider the following 3 resources (ResourceCount = 3):</p>


<p>+---------—+-----—+ |ResourceName|NumUnits| +---------—+-----—+ | X | 2 | +---------—+-----—+ | Y | 3 | +---------—+-----—+ | Z | 1 | +---------—+-----—+</p>


<p>In this case, the total number of resource instances is 6. The vector ReservedResourceSegments will have a slot for each instance. The vector ReservedCyclesIndex will track at what index the first instance of the resource is found in the vector of ReservedResourceSegments:</p>



<pre><code>                         Indexes of instances in
                         ReservedResourceSegments

                         0   1   2   3   4  5
</code></pre>


<p>ReservedCyclesIndex[0] = 0; [X0, X1, ReservedCyclesIndex[1] = 2; Y0, Y1, Y2 ReservedCyclesIndex[2] = 5; Z</p>


<p>Definition at line 938 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### ReservedResourceSegments {#a30ba79cae0c4a51e6e1b4b7fb83705e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, ResourceSegments&gt; llvm::SchedBoundary::ReservedResourceSegments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> how resources have been allocated across the cycles of the execution.</p>

<p>Definition at line 907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### ResourceGroupSubUnitMasks {#a0f26751117ede798319fa824d4041803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;APInt, 16&gt; llvm::SchedBoundary::ResourceGroupSubUnitMasks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### RetiredMOps {#a22549ab287b950d591dc90dbbdddc7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::RetiredMOps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Count the scheduled (issued) micro-ops that can be retired by time=CurrCycle assuming the first scheduled instr is retired at time=0.</p>

<p>Definition at line 885 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### ZoneCritResIdx {#a768f14ab09f9ffc1e8760a4cbd063781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SchedBoundary::ZoneCritResIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
