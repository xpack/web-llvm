---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-scheduledagfast-cpp-/scheduledagfast
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ScheduleDAGFast` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-scheduledagfast-cpp-/scheduledagfast">ScheduleDAGFast</a> - The actual "fast" list scheduler implementation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{ScheduleDAGFast.cpp}::ScheduleDAGFast { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes">ScheduleDAGSDNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes">ScheduleDAGSDNodes</a> - A <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> for scheduling SDNode-based DAGs. <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af97d213ca57d730de14afcd88f5cb70d">ScheduleDAGFast</a> (MachineFunction &amp;mf)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a28e48e75f92766aa6a1c3b628536c3">Schedule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Schedule - Schedule the DAG using list scheduling. <a href="#a9a28e48e75f92766aa6a1c3b628536c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92723fbc9b5347da67a06b63043fcff9">AddPred</a> (SUnit *SU, const SDep &amp;D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddPred - adds a predecessor edge to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> SU. <a href="#a92723fbc9b5347da67a06b63043fcff9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0a1220d91f44079aa52746ac160c2e4">RemovePred</a> (SUnit *SU, const SDep &amp;D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RemovePred - removes a predecessor edge from <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> SU. <a href="#ae0a1220d91f44079aa52746ac160c2e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587eb65d0fe7bef68098262d703f71ef">ReleasePred</a> (SUnit *SU, SDep *PredEdge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReleasePred - Decrement the NumSuccsLeft count of a predecessor. <a href="#a587eb65d0fe7bef68098262d703f71ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a523cfb82932bec98df513dd3950cd86f">ReleasePredecessors</a> (SUnit *SU, unsigned CurCycle)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8485c937bdd6416ba66de66af67163eb">ScheduleNodeBottomUp</a> (SUnit *, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ScheduleNodeBottomUp - Add the node to the schedule. <a href="#a8485c937bdd6416ba66de66af67163eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa70c548f9195f5af4d601e1053158fe5">CopyAndMoveSuccessors</a> (SUnit *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CopyAndMoveSuccessors - Clone the specified node and move its scheduled successors to the newly created node. <a href="#aa70c548f9195f5af4d601e1053158fe5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2255ae2c3b37f461e8def09e88eba42">InsertCopiesAndMoveSuccs</a> (SUnit *, unsigned, const TargetRegisterClass *, const TargetRegisterClass *, SmallVectorImpl&lt; SUnit * &gt; &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InsertCopiesAndMoveSuccs - Insert register copies and move all scheduled successors of the given <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> to the last copy. <a href="#af2255ae2c3b37f461e8def09e88eba42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73d00d78e3b10f9130e2264d507f1746">DelayForLiveRegsBottomUp</a> (SUnit *, SmallVectorImpl&lt; unsigned &gt; &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DelayForLiveRegsBottomUp - Returns true if it is necessary to delay scheduling of the given node to satisfy live physical register dependencies. <a href="#a73d00d78e3b10f9130e2264d507f1746">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4b36f7c14afd20df950f5a4706f015f">ListScheduleBottomUp</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ListScheduleBottomUp - The main loop of list scheduling for bottom-up schedulers. <a href="#ad4b36f7c14afd20df950f5a4706f015f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab1ece22ae8314ba4e2f47d990ed84d3">forceUnitLatencies</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>forceUnitLatencies - The fast scheduler doesn't care about real latencies. <a href="#aab1ece22ae8314ba4e2f47d990ed84d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-scheduledagfast-cpp-/fastpriorityqueue">FastPriorityQueue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb566b736fcb926f249bf140e6876ba">AvailableQueue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AvailableQueue - The priority queue to use for the available SUnits. <a href="#a8bb566b736fcb926f249bf140e6876ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0275bee49a81f2a89ec727f824119f23">NumLiveRegs</a> = 0u</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LiveRegDefs - A set of physical registers and their definition that are "live". <a href="#a0275bee49a81f2a89ec727f824119f23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5467d8cb7c07e7583a9f8a65b8a9702e">LiveRegDefs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c41f535dd074c1d9d65f33b0f4a995d">LiveRegCycles</a></td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-scheduledagfast-cpp-/scheduledagfast">ScheduleDAGFast</a> - The actual "fast" list scheduler implementation.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ScheduleDAGFast() {#af97d213ca57d730de14afcd88f5cb70d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ScheduleDAGFast.cpp}::ScheduleDAGFast::ScheduleDAGFast (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ad73652eab6e03e092e32bde82040c8c7">llvm::ScheduleDAGSDNodes::ScheduleDAGSDNodes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb006d4183da30e88fa2a4e160c03d3">llvm::createFastDAGScheduler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddPred() {#a92723fbc9b5347da67a06b63043fcff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ScheduleDAGFast.cpp}::ScheduleDAGFast::AddPred (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; D)</td>
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

<p>AddPred - adds a predecessor edge to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> SU.</p>


<p>This returns true if this is a new predecessor.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#af92bf49ed4846e026e68c380d74d7b15">llvm::SUnit::addPred</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>.</p>

</div>
</div>

### RemovePred() {#ae0a1220d91f44079aa52746ac160c2e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ScheduleDAGFast.cpp}::ScheduleDAGFast::RemovePred (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; D)</td>
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

<p>RemovePred - removes a predecessor edge from <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> SU.</p>


<p>This returns true if an edge was removed.</p>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a6d3233165db1e6be5c44060cd4a95461">llvm::SUnit::removePred</a>.</p>

</div>
</div>

### Schedule() {#a9a28e48e75f92766aa6a1c3b628536c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGFast::Schedule ()</td>
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

<p>Schedule - Schedule the DAG using list scheduling.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#aa88c65a5abb5774125c8d66a48d07adf">llvm::ScheduleDAGSDNodes::BuildSchedGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a03503773241005f01b090b9862aad304">llvm::dump</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### CopyAndMoveSuccessors() {#aa70c548f9195f5af4d601e1053158fe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * ScheduleDAGFast::CopyAndMoveSuccessors (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CopyAndMoveSuccessors - Clone the specified node and move its scheduled successors to the newly created node.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

### DelayForLiveRegsBottomUp() {#a73d00d78e3b10f9130e2264d507f1746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScheduleDAGFast::DelayForLiveRegsBottomUp (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; LRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DelayForLiveRegsBottomUp - Returns true if it is necessary to delay scheduling of the given node to satisfy live physical register dependencies.</p>


<p>If the specific node is the last one that's available to schedule, do whatever is necessary (i.e. backtracking or cloning) to make it possible.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

### forceUnitLatencies() {#aab1ece22ae8314ba4e2f47d990ed84d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ScheduleDAGFast.cpp}::ScheduleDAGFast::forceUnitLatencies ()</td>
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

<p>forceUnitLatencies - The fast scheduler doesn't care about real latencies.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

### InsertCopiesAndMoveSuccs() {#af2255ae2c3b37f461e8def09e88eba42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGFast::InsertCopiesAndMoveSuccs (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, unsigned Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * DestRC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SrcRC, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; &amp; Copies)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>InsertCopiesAndMoveSuccs - Insert register copies and move all scheduled successors of the given <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> to the last copy.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

### ListScheduleBottomUp() {#ad4b36f7c14afd20df950f5a4706f015f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGFast::ListScheduleBottomUp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ListScheduleBottomUp - The main loop of list scheduling for bottom-up schedulers.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

### ReleasePred() {#a587eb65d0fe7bef68098262d703f71ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGFast::ReleasePred (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> * PredEdge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReleasePred - Decrement the NumSuccsLeft count of a predecessor.</p>


<p>Add it to the AvailableQueue if the count reaches zero. Also update its cycle bound.</p>


<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

### ReleasePredecessors() {#a523cfb82932bec98df513dd3950cd86f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGFast::ReleasePredecessors (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, unsigned CurCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

### ScheduleNodeBottomUp() {#a8485c937bdd6416ba66de66af67163eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGFast::ScheduleNodeBottomUp (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, unsigned CurCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ScheduleNodeBottomUp - Add the node to the schedule.</p>


<p>Decrement the pending count of its predecessors. If a predecessor pending count is zero, add it to the Available queue.</p>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AvailableQueue {#a8bb566b736fcb926f249bf140e6876ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastPriorityQueue anonymous{ScheduleDAGFast.cpp}::ScheduleDAGFast::AvailableQueue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AvailableQueue - The priority queue to use for the available SUnits.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

### LiveRegCycles {#a8c41f535dd074c1d9d65f33b0f4a995d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; anonymous{ScheduleDAGFast.cpp}::ScheduleDAGFast::LiveRegCycles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

### LiveRegDefs {#a5467d8cb7c07e7583a9f8a65b8a9702e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SUnit*&gt; anonymous{ScheduleDAGFast.cpp}::ScheduleDAGFast::LiveRegDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

### NumLiveRegs {#a0275bee49a81f2a89ec727f824119f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ScheduleDAGFast.cpp}::ScheduleDAGFast::NumLiveRegs = 0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LiveRegDefs - A set of physical registers and their definition that are "live".</p>


<p>These nodes must be scheduled before any other nodes that modifies the registers can be scheduled.</p>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
