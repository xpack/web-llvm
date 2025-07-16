---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SchedulePostRATDList` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> for scheduling lists of <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66dc7adbddb415df7082c38835b96372">SchedulePostRATDList</a> (MachineFunction &amp;MF, MachineLoopInfo &amp;MLI, AliasAnalysis *AA, const RegisterClassInfo &amp;, TargetSubtargetInfo::AntiDepBreakMode AntiDepMode, SmallVectorImpl&lt; const TargetRegisterClass * &gt; &amp;CriticalPathRCs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab35f4f3a83755c356dba3527e7a71b02">~SchedulePostRATDList</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e1de828f5638a8e88f579d837540094">startBlock</a> (MachineBasicBlock *BB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>startBlock - Initialize register live-range state for scheduling in this block. <a href="#a6e1de828f5638a8e88f579d837540094">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60d27beb6c6ff38cc71f973781b4c0e9">setEndIndex</a> (unsigned EndIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a332194da83580c976d9259717176ae8c">enterRegion</a> (MachineBasicBlock *bb, MachineBasicBlock::iterator begin, MachineBasicBlock::iterator end, unsigned regioninstrs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the scheduler state for the next scheduling region. <a href="#a332194da83580c976d9259717176ae8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18002c24320d152edf319448c0f7843d">exitRegion</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notify that the scheduler has finished scheduling the current region. <a href="#a18002c24320d152edf319448c0f7843d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587988ffcc944147e5ba7da46bc77ef2">schedule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Schedule - Schedule the instruction range using list scheduling. <a href="#a587988ffcc944147e5ba7da46bc77ef2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9c7e76fda2b142c09da3ca892884acd">EmitSchedule</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba51eafab8a21f0a41f577a04f777cd8">Observe</a> (MachineInstr &amp;MI, unsigned Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Observe - Update liveness information to account for the current instruction, which will not be scheduled. <a href="#aba51eafab8a21f0a41f577a04f777cd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8e3f32817edf7fbf1d4f33cc204199b">finishBlock</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>finishBlock - Clean up register live-range state. <a href="#ac8e3f32817edf7fbf1d4f33cc204199b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4428e8a337f3d517e7a82af1fe4f9efe">postProcessDAG</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply each <a href="/web-llvm/docs/api/classes/llvm/scheduledagmutation">ScheduleDAGMutation</a> step in order. <a href="#a4428e8a337f3d517e7a82af1fe4f9efe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b6bb6091ca857630b00935594371c6c">ReleaseSucc</a> (SUnit *SU, SDep *SuccEdge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReleaseSucc - Decrement the NumPredsLeft count of a successor. <a href="#a3b6bb6091ca857630b00935594371c6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2ad1783cdd7d5abf6b3c2e071a9774d">ReleaseSuccessors</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReleaseSuccessors - Call ReleaseSucc on each of SU's successors. <a href="#af2ad1783cdd7d5abf6b3c2e071a9774d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae31a93cc422bbaa45a4ced2487e37e30">ScheduleNodeTopDown</a> (SUnit *SU, unsigned CurCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ScheduleNodeTopDown - Add the node to the schedule. <a href="#ae31a93cc422bbaa45a4ced2487e37e30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7d7b6efba6c1bb72cd94e5eb1768baa">ListScheduleTopDown</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ListScheduleTopDown - The main loop of list scheduling for top-down schedulers. <a href="#aa7d7b6efba6c1bb72cd94e5eb1768baa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa65dd66f1ae3acf7aa73ab479e5125ac">dumpSchedule</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dumpSchedule - dump the scheduled Sequence. <a href="#aa65dd66f1ae3acf7aa73ab479e5125ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00420b14ef66ef3997782ca767930070">emitNoop</a> (unsigned CurCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>emitNoop - Add a noop to the current instruction sequence. <a href="#a00420b14ef66ef3997782ca767930070">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/latencypriorityqueue">LatencyPriorityQueue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd96511ab071cdaa14ef7a7a0a0c0e46">AvailableQueue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AvailableQueue - The priority queue to use for the available SUnits. <a href="#abd96511ab071cdaa14ef7a7a0a0c0e46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7eae8248014797a2ad8e9e44b45f117">PendingQueue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PendingQueue - This contains all of the instructions whose operands have been issued, but their results are not ready yet (due to the latency of the operation). <a href="#ad7eae8248014797a2ad8e9e44b45f117">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76016cdd09bd6fc3be6f4b0abc276a04">HazardRec</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HazardRec - The hazard recognizer to use. <a href="#a76016cdd09bd6fc3be6f4b0abc276a04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/antidepbreaker">AntiDepBreaker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7d7ed6503c77733f83b101c4bb2b77e">AntiDepBreak</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AntiDepBreak - Anti-dependence breaking object, or NULL if none. <a href="#ae7d7ed6503c77733f83b101c4bb2b77e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b01e4748a801e2f6582d5e51bdcf17c">AA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AA - <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> for making memory reference queries. <a href="#a1b01e4748a801e2f6582d5e51bdcf17c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab22fae83a229ba4b918dbba7cc0a3088">Sequence</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The schedule. Null SUnit*'s represent noop instructions. <a href="#ab22fae83a229ba4b918dbba7cc0a3088">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/scheduledagmutation">ScheduleDAGMutation</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89f7c2ac66cdc3236fde6404124e61f5">Mutations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ordered list of DAG postprocessing steps. <a href="#a89f7c2ac66cdc3236fde6404124e61f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3c39fdcb3e35590532238ae0d2a51a9">EndIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index in BB of RegionEnd. <a href="#ae3c39fdcb3e35590532238ae0d2a51a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SchedulePostRATDList() {#a66dc7adbddb415df7082c38835b96372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::SchedulePostRATDList (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> &amp; MLI, <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> * AA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerclassinfo">RegisterClassInfo</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a20310fa71bf28c3b31d0eb7ec699d21b">TargetSubtargetInfo::AntiDepBreakMode</a> AntiDepMode, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * &gt; &amp; CriticalPathRCs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ad2b3e1939f6f39819ad55c714deefad6">llvm::ScheduleDAGInstrs::MLI</a>, <a href="#a66dc7adbddb415df7082c38835b96372">SchedulePostRATDList</a> and <a href="#a6e1de828f5638a8e88f579d837540094">startBlock</a>.</p>


<p>Referenced by <a href="#a66dc7adbddb415df7082c38835b96372">SchedulePostRATDList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SchedulePostRATDList() {#ab35f4f3a83755c356dba3527e7a71b02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedulePostRATDList::~SchedulePostRATDList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### EmitSchedule() {#ab9c7e76fda2b142c09da3ca892884acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedulePostRATDList::EmitSchedule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a6837fb2c08f4c8c986a4689a37ca93cf">llvm::ScheduleDAGInstrs::DbgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a25ae020b571d18d34d03097d91ca0f40">llvm::ScheduleDAGInstrs::FirstDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae81ad8ece7681af658742f6d4e2fcfb1">llvm::ScheduleDAGInstrs::RegionBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a3f74b283acf0dfb537bc387e49344f04">llvm::ScheduleDAGInstrs::RegionEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a348590624c488b04d0f9e227e6c3960e">llvm::ScheduleDAG::TII</a>.</p>

</div>
</div>

### enterRegion() {#a332194da83580c976d9259717176ae8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedulePostRATDList::enterRegion (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * bb, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> end, unsigned regioninstrs)</td>
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

<p>Initialize the scheduler state for the next scheduling region.</p>


<p>Initialize state associated with the next scheduling region.</p>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab50b64c518a7455daf3e0bc87aee5514">llvm::ScheduleDAGInstrs::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a21805259f54dab47c2b3da009216996a">llvm::ScheduleDAGInstrs::end</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae8727d434d20639d563849891f5ca1e1">llvm::ScheduleDAGInstrs::enterRegion</a>.</p>

</div>
</div>

### exitRegion() {#a18002c24320d152edf319448c0f7843d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedulePostRATDList::exitRegion ()</td>
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

<p>Notify that the scheduler has finished scheduling the current region.</p>


<p>Print the schedule before exiting the region.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#abc5a5c32ac78a99ee2633dbbeec20397">llvm::ScheduleDAGInstrs::exitRegion</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### finishBlock() {#ac8e3f32817edf7fbf1d4f33cc204199b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedulePostRATDList::finishBlock ()</td>
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

<p>finishBlock - Clean up register live-range state.</p>


<p>FinishBlock - Clean up register live-range state.</p>


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a1f9a4461e2c9ac06b97f55554f836d66">llvm::ScheduleDAGInstrs::finishBlock</a>.</p>

</div>
</div>

### Observe() {#aba51eafab8a21f0a41f577a04f777cd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedulePostRATDList::Observe (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Observe - Update liveness information to account for the current instruction, which will not be scheduled.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### schedule() {#a587988ffcc944147e5ba7da46bc77ef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedulePostRATDList::schedule ()</td>
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

<p>Schedule - Schedule the instruction range using list scheduling.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a20e10e20ded7655f844479a648aa0c66">llvm::ScheduleDAG::clearDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a6837fb2c08f4c8c986a4689a37ca93cf">llvm::ScheduleDAGInstrs::DbgValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a03503773241005f01b090b9862aad304">llvm::dump</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae81ad8ece7681af658742f6d4e2fcfb1">llvm::ScheduleDAGInstrs::RegionBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a3f74b283acf0dfb537bc387e49344f04">llvm::ScheduleDAGInstrs::RegionEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>

</div>
</div>

### setEndIndex() {#a60d27beb6c6ff38cc71f973781b4c0e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::setEndIndex (unsigned EndIdx)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

### startBlock() {#a6e1de828f5638a8e88f579d837540094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedulePostRATDList::startBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
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

<p>startBlock - Initialize register live-range state for scheduling in this block.</p>


<p>StartBlock - Initialize register live-range state for scheduling in this block.</p>


<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2822215b7634783aece96ef695a72f1d">llvm::ScheduleDAGInstrs::startBlock</a>.</p>


<p>Referenced by <a href="#a66dc7adbddb415df7082c38835b96372">SchedulePostRATDList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### dumpSchedule() {#aa65dd66f1ae3acf7aa73ab479e5125ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SchedulePostRATDList::dumpSchedule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>dumpSchedule - dump the scheduled Sequence.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

### emitNoop() {#a00420b14ef66ef3997782ca767930070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedulePostRATDList::emitNoop (unsigned CurCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>emitNoop - Add a noop to the current instruction sequence.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

### ListScheduleTopDown() {#aa7d7b6efba6c1bb72cd94e5eb1768baa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedulePostRATDList::ListScheduleTopDown ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ListScheduleTopDown - The main loop of list scheduling for top-down schedulers.</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

### postProcessDAG() {#a4428e8a337f3d517e7a82af1fe4f9efe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedulePostRATDList::postProcessDAG ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply each <a href="/web-llvm/docs/api/classes/llvm/scheduledagmutation">ScheduleDAGMutation</a> step in order.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

### ReleaseSucc() {#a3b6bb6091ca857630b00935594371c6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedulePostRATDList::ReleaseSucc (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> * SuccEdge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReleaseSucc - Decrement the NumPredsLeft count of a successor.</p>


<p>Add it to the PendingQueue if the count reaches zero.</p>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

### ReleaseSuccessors() {#af2ad1783cdd7d5abf6b3c2e071a9774d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedulePostRATDList::ReleaseSuccessors (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReleaseSuccessors - Call ReleaseSucc on each of SU's successors.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

### ScheduleNodeTopDown() {#ae31a93cc422bbaa45a4ced2487e37e30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SchedulePostRATDList::ScheduleNodeTopDown (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, unsigned CurCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ScheduleNodeTopDown - Add the node to the schedule.</p>


<p>Decrement the pending count of its successors. If a successor pending count is zero, add it to the Available queue.</p>


<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a1b01e4748a801e2f6582d5e51bdcf17c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis* anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AA - <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> for making memory reference queries.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

### AntiDepBreak {#ae7d7ed6503c77733f83b101c4bb2b77e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AntiDepBreaker* anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::AntiDepBreak</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AntiDepBreak - Anti-dependence breaking object, or NULL if none.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

### AvailableQueue {#abd96511ab071cdaa14ef7a7a0a0c0e46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LatencyPriorityQueue anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::AvailableQueue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AvailableQueue - The priority queue to use for the available SUnits.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

### EndIndex {#ae3c39fdcb3e35590532238ae0d2a51a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::EndIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index in BB of RegionEnd.</p>


<p>This is the instruction number from the top of the current block, not the <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>. It is only used by the <a href="/web-llvm/docs/api/classes/llvm/antidepbreaker">AntiDepBreaker</a>.</p>


<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

### HazardRec {#a76016cdd09bd6fc3be6f4b0abc276a04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer* anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::HazardRec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HazardRec - The hazard recognizer to use.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

### Mutations {#a89f7c2ac66cdc3236fde6404124e61f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;ScheduleDAGMutation&gt; &gt; anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::Mutations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Ordered list of DAG postprocessing steps.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

### PendingQueue {#ad7eae8248014797a2ad8e9e44b45f117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SUnit*&gt; anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::PendingQueue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PendingQueue - This contains all of the instructions whose operands have been issued, but their results are not ready yet (due to the latency of the operation).</p>


<p>Once the operands becomes available, the instruction is added to the AvailableQueue.</p>


<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

### Sequence {#ab22fae83a229ba4b918dbba7cc0a3088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SUnit*&gt; anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::Sequence</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The schedule. Null SUnit*'s represent noop instructions.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp">PostRASchedulerList.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
