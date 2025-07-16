---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-scheduledagvliw-cpp-/scheduledagvliw
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ScheduleDAGVLIW` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-scheduledagvliw-cpp-/scheduledagvliw">ScheduleDAGVLIW</a> - The actual DFA list scheduler implementation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{ScheduleDAGVLIW.cpp}::ScheduleDAGVLIW { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dc43d4af0801e27b6c6273882f2e417">ScheduleDAGVLIW</a> (MachineFunction &amp;MF, SchedulingPriorityQueue *AvailableQueue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a357c511d6df53c1cb8cb5a6f623fb629">~ScheduleDAGVLIW</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c7e5ab6f65268a493c98bdf5b7ada2f">Schedule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Schedule - Schedule the DAG using list scheduling. <a href="#a8c7e5ab6f65268a493c98bdf5b7ada2f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab821fd41ed170899d33452e3962329a2">releaseSucc</a> (SUnit *SU, const SDep &amp;D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>releaseSucc - Decrement the NumPredsLeft count of a successor. <a href="#ab821fd41ed170899d33452e3962329a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c080219fdf6cf5d9b956ea8b911532a">releaseSuccessors</a> (SUnit *SU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f45c321ff664229564d6e1e5bfae723">scheduleNodeTopDown</a> (SUnit *SU, unsigned CurCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>scheduleNodeTopDown - Add the node to the schedule. <a href="#a3f45c321ff664229564d6e1e5bfae723">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abee4ef408b37ae01aaf4c5f71c74849b">listScheduleTopDown</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>listScheduleTopDown - The main loop of list scheduling for top-down schedulers. <a href="#abee4ef408b37ae01aaf4c5f71c74849b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulingpriorityqueue">SchedulingPriorityQueue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b94c0572ad98c185bf37047e4e751dc">AvailableQueue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AvailableQueue - The priority queue to use for the available SUnits. <a href="#a6b94c0572ad98c185bf37047e4e751dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac61a0d65d30914923618b15ae3dec74d">PendingQueue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PendingQueue - This contains all of the instructions whose operands have been issued, but their results are not ready yet (due to the latency of the operation). <a href="#ac61a0d65d30914923618b15ae3dec74d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23588ab4cd151b6db968735faf551c0a">HazardRec</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HazardRec - The hazard recognizer to use. <a href="#a23588ab4cd151b6db968735faf551c0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-scheduledagvliw-cpp-/scheduledagvliw">ScheduleDAGVLIW</a> - The actual DFA list scheduler implementation.</p>


<p>This supports / top-down scheduling.</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagvliw-cpp">ScheduleDAGVLIW.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ScheduleDAGVLIW() {#a7dc43d4af0801e27b6c6273882f2e417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ScheduleDAGVLIW.cpp}::ScheduleDAGVLIW::ScheduleDAGVLIW (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/schedulingpriorityqueue">SchedulingPriorityQueue</a> * AvailableQueue)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagvliw-cpp">ScheduleDAGVLIW.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ad73652eab6e03e092e32bde82040c8c7">llvm::ScheduleDAGSDNodes::ScheduleDAGSDNodes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#adb76b7e73f1254d986893cab940b20c3">llvm::createVLIWDAGScheduler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ScheduleDAGVLIW() {#a357c511d6df53c1cb8cb5a6f623fb629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ScheduleDAGVLIW.cpp}::ScheduleDAGVLIW::~ScheduleDAGVLIW ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagvliw-cpp">ScheduleDAGVLIW.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Schedule() {#a8c7e5ab6f65268a493c98bdf5b7ada2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGVLIW::Schedule ()</td>
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

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagvliw-cpp">ScheduleDAGVLIW.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a9f718397926caadcb301ca1e00aaf68c">llvm::ScheduleDAGSDNodes::BB</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#aa88c65a5abb5774125c8d66a48d07adf">llvm::ScheduleDAGSDNodes::BuildSchedGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### listScheduleTopDown() {#abee4ef408b37ae01aaf4c5f71c74849b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGVLIW::listScheduleTopDown ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>listScheduleTopDown - The main loop of list scheduling for top-down schedulers.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagvliw-cpp">ScheduleDAGVLIW.cpp</a>.</p>

</div>
</div>

### releaseSucc() {#ab821fd41ed170899d33452e3962329a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGVLIW::releaseSucc (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>releaseSucc - Decrement the NumPredsLeft count of a successor.</p>


<p>Add it to the PendingQueue if the count reaches zero. Also update its cycle bound.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagvliw-cpp">ScheduleDAGVLIW.cpp</a>.</p>

</div>
</div>

### releaseSuccessors() {#a3c080219fdf6cf5d9b956ea8b911532a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGVLIW::releaseSuccessors (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagvliw-cpp">ScheduleDAGVLIW.cpp</a>.</p>

</div>
</div>

### scheduleNodeTopDown() {#a3f45c321ff664229564d6e1e5bfae723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGVLIW::scheduleNodeTopDown (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, unsigned CurCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>scheduleNodeTopDown - Add the node to the schedule.</p>


<p>Decrement the pending count of its successors. If a successor pending count is zero, add it to the Available queue.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagvliw-cpp">ScheduleDAGVLIW.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AvailableQueue {#a6b94c0572ad98c185bf37047e4e751dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedulingPriorityQueue* anonymous{ScheduleDAGVLIW.cpp}::ScheduleDAGVLIW::AvailableQueue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AvailableQueue - The priority queue to use for the available SUnits.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagvliw-cpp">ScheduleDAGVLIW.cpp</a>.</p>

</div>
</div>

### HazardRec {#a23588ab4cd151b6db968735faf551c0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer* anonymous{ScheduleDAGVLIW.cpp}::ScheduleDAGVLIW::HazardRec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HazardRec - The hazard recognizer to use.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagvliw-cpp">ScheduleDAGVLIW.cpp</a>.</p>

</div>
</div>

### PendingQueue {#ac61a0d65d30914923618b15ae3dec74d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SUnit*&gt; anonymous{ScheduleDAGVLIW.cpp}::ScheduleDAGVLIW::PendingQueue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PendingQueue - This contains all of the instructions whose operands have been issued, but their results are not ready yet (due to the latency of the operation).</p>


<p>Once the operands become available, the instruction is added to the AvailableQueue.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagvliw-cpp">ScheduleDAGVLIW.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagvliw-cpp">ScheduleDAGVLIW.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
