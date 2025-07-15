---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scheduledagmi
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ScheduleDAGMI` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> is an implementation of <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> that simply schedules machine instructions according to the given <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> without much extra book-keeping. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ScheduleDAGMI { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">llvm/CodeGen/MachineScheduler.h</a>"
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnpostscheduledagmilive">GCNPostScheduleDAGMILive</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive">ScheduleDAGMILive</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive">ScheduleDAGMILive</a> is an implementation of <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> that schedules machine instructions while updating <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> and tracking regpressure. <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a629982ca3ef5632e63f32b5682fde927">ScheduleDAGMI</a> (MachineSchedContext *C, std::unique_ptr&lt; MachineSchedStrategy &gt; S, bool RemoveKillFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a967aa1a22992b66fb06b83323ddccaa7">~ScheduleDAGMI</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75acfc66aaac7201dc55a66df9940a37">doMBBSchedRegionsTopDown</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this method returns true, handling of the scheduling regions themselves (in case of a scheduling boundary in MBB) will be done beginning with the topmost region of MBB. <a href="#a75acfc66aaac7201dc55a66df9940a37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dcf5173867549aff2a8cdcc70dd2800">getLIS</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78c0f3feb8a81ca338f843494cff564e">hasVRegLiveness</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this DAG supports VReg liveness and RegPressure. <a href="#a78c0f3feb8a81ca338f843494cff564e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2002164aea6fabe20598e0526746b1fa">addMutation</a> (std::unique_ptr&lt; ScheduleDAGMutation &gt; Mutation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a postprocessing step to the DAG builder. <a href="#a2002164aea6fabe20598e0526746b1fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bcc40c244c6a33d738b3e4f1d490ca3">top</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70e4bd877aac0a63c10463277c9a52c5">bottom</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78e3672daf3301153eac2266dbc32885">enterRegion</a> (MachineBasicBlock *bb, MachineBasicBlock::iterator begin, MachineBasicBlock::iterator end, unsigned regioninstrs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement the <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> interface for handling the next scheduling region. <a href="#a78e3672daf3301153eac2266dbc32885">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> interface for scheduling a sequence of reorderable instructions. <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19c5e2b675721f465bc85a5f58e7c084">startBlock</a> (MachineBasicBlock *bb) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepares to perform scheduling in the given block. <a href="#a19c5e2b675721f465bc85a5f58e7c084">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ca687b69b34efab1604af98db151cbf">finishBlock</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cleans up after scheduling in the given block. <a href="#a9ca687b69b34efab1604af98db151cbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2209b15a069023499cc665b373e67703">moveInstruction</a> (MachineInstr *MI, MachineBasicBlock::iterator InsertPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the position of an instruction within the basic block and update live ranges and region boundary iterators. <a href="#a2209b15a069023499cc665b373e67703">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8704e1dcdf62f3ac74e67280c029f5e">getNextClusterPred</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adde3720b0af5350a55fdd0eba84566a8">getNextClusterSucc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8181ae26c7912b2ae6214be22c4f6cf5">viewGraph</a> (const Twine &amp;Name, const Twine &amp;Title) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>viewGraph - Pop up a ghostview window with the reachable parts of the DAG rendered using 'dot'. <a href="#a8181ae26c7912b2ae6214be22c4f6cf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b7babb023cad0842f5a177e7abe3651">viewGraph</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Out-of-line implementation with no arguments is handy for gdb. <a href="#a8b7babb023cad0842f5a177e7abe3651">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa2eb6fd6a44ff6b9cbad960d446c7a">postProcessDAG</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply each <a href="/web-llvm/docs/api/classes/llvm/scheduledagmutation">ScheduleDAGMutation</a> step in order. <a href="#a2aa2eb6fd6a44ff6b9cbad960d446c7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f98694f104d052d71ed74ade38d69f0">initQueues</a> (ArrayRef&lt; SUnit * &gt; TopRoots, ArrayRef&lt; SUnit * &gt; BotRoots)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release ExitSU predecessors and setup scheduler queues. <a href="#a1f98694f104d052d71ed74ade38d69f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfdd9a95217810c69b2557060a130318">updateQueues</a> (SUnit *SU, bool IsTopNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update scheduler DAG and queues after scheduling an instruction. <a href="#abfdd9a95217810c69b2557060a130318">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2dafe98c88d43b256622413886e2152">placeDebugValues</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reinsert debug_values recorded in <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a6837fb2c08f4c8c986a4689a37ca93cf">ScheduleDAGInstrs::DbgValues</a>. <a href="#ac2dafe98c88d43b256622413886e2152">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01b02e76c87211e7084ec17f18a2d16f">dumpSchedule</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dump the scheduled Sequence. <a href="#a01b02e76c87211e7084ec17f18a2d16f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3010c4b89284791284aa6e2ec510501b">dumpScheduleTraceTopDown</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print execution trace of the schedule top-down or bottom-up. <a href="#a3010c4b89284791284aa6e2ec510501b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942d716003056c037d46a4144e9cf885">dumpScheduleTraceBottomUp</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a569fc4139bec0217794e9f830d6ba852">checkSchedLimit</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d0a0b4903e8d4d12c98b0f43fe83878">findRootsAndBiasEdges</a> (SmallVectorImpl&lt; SUnit * &gt; &amp;TopRoots, SmallVectorImpl&lt; SUnit * &gt; &amp;BotRoots)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90ffd918ef80c711049758b2064e15c4">releaseSucc</a> (SUnit *SU, SDep *SuccEdge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReleaseSucc - Decrement the NumPredsLeft count of a successor. <a href="#a90ffd918ef80c711049758b2064e15c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf56d667066b39177a3c0f134d759d98">releaseSuccessors</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>releaseSuccessors - Call releaseSucc on each of SU's successors. <a href="#acf56d667066b39177a3c0f134d759d98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c51776d4e512a7f24d5b5d601c31016">releasePred</a> (SUnit *SU, SDep *PredEdge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReleasePred - Decrement the NumSuccsLeft count of a predecessor. <a href="#a1c51776d4e512a7f24d5b5d601c31016">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f9975b56fe38f7a8bb4d10b7f6f5ea">releasePredecessors</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>releasePredecessors - Call releasePred on each of SU's predecessors. <a href="#a25f9975b56fe38f7a8bb4d10b7f6f5ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b8428bb41e16b71ae2bb0139bce5eb">AA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d67b1cafa36e90d7060d1da84907885">LIS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0318c90d99b85c47bc82d9e0844462f6">SchedImpl</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/scheduledagmutation">ScheduleDAGMutation</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed362d97300c9cd91f179f9c6c31c9ac">Mutations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ordered list of DAG postprocessing steps. <a href="#aed362d97300c9cd91f179f9c6c31c9ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8abe1b0d869087bd0c14a6637356dc0">CurrentTop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The top of the unscheduled zone. <a href="#ac8abe1b0d869087bd0c14a6637356dc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7435e842606f5db4bca092e5829befc6">CurrentBottom</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The bottom of the unscheduled zone. <a href="#a7435e842606f5db4bca092e5829befc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33503949e135cad03fa91fde0c005649">NextClusterPred</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the next node in a scheduled cluster. <a href="#a33503949e135cad03fa91fde0c005649">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa5cb48ee16ded1b263483026d08894">NextClusterSucc</a> = nullptr</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> is an implementation of <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> that simply schedules machine instructions according to the given <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> without much extra book-keeping.</p>


<p>This is the common functionality between PreRA and PostRA MachineScheduler.</p>


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ScheduleDAGMI() {#a629982ca3ef5632e63f32b5682fde927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ScheduleDAGMI::ScheduleDAGMI (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> &gt; S, bool RemoveKillFlags)</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="#a79b8428bb41e16b71ae2bb0139bce5eb">AA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a9d67b1cafa36e90d7060d1da84907885">LIS</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ad2b3e1939f6f39819ad55c714deefad6">llvm::ScheduleDAGInstrs::MLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#adf7cb9b8e5dda7b42273e79048f1b8b3">llvm::ScheduleDAGInstrs::RemoveKillFlags</a>, <a href="#a0318c90d99b85c47bc82d9e0844462f6">SchedImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a5bcb745a3e78c329d1431608b1f51c25">llvm::ScheduleDAGInstrs::ScheduleDAGInstrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnpostscheduledagmilive/#ac1db9853e3ddfa9a2177147d8c03eacb">llvm::GCNPostScheduleDAGMILive::GCNPostScheduleDAGMILive</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a67da2c9a62e43ae7b66bc5ca91f55a05">llvm::ScheduleDAGMILive::ScheduleDAGMILive</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ScheduleDAGMI() {#a967aa1a22992b66fb06b83323ddccaa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGMI::~ScheduleDAGMI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addMutation() {#a2002164aea6fabe20598e0526746b1fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ScheduleDAGMI::addMutation (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/scheduledagmutation">ScheduleDAGMutation</a> &gt; Mutation)</td>
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

<p>Add a postprocessing step to the DAG builder.</p>


<p>Mutations are applied in the order that they are added after normal DAG building and before <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> initialization.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> takes ownership of the Mutation object.</p>


<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a> and <a href="#aed362d97300c9cd91f179f9c6c31c9ac">Mutations</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a2f08c3354af71da1c6f857e74e7a32a0">createGCNMaxILPMachineScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5365898dd1deb10d065e288a2babd511">llvm::createGenericSchedLive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa2f0c2f2a077d67dc0bcb24bc31e3b05">llvm::createGenericSchedPostRA</a>, <a href="/web-llvm/docs/api/classes/anonymous-armtargetmachine-cpp-/armpassconfig/#a15ce7a7c1ccf1dc7b69a05bb3620e0cb">anonymous{ARMTargetMachine.cpp}::ARMPassConfig::createMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a407041e55fa1f623a4ffa56436b5606b">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86targetmachine-cpp-/x86passconfig/#acc00aa28a4021e0ef7b45384a0e160bb">anonymous{X86TargetMachine.cpp}::X86PassConfig::createMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#abc91f335d0788469b44e409f15109585">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createPostMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-armtargetmachine-cpp-/armpassconfig/#a8476d8c446d2e88bdbb66ccd25ad46b7">anonymous{ARMTargetMachine.cpp}::ARMPassConfig::createPostMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a981486e15f588bdbce922588c8efc899">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createPostMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86targetmachine-cpp-/x86passconfig/#abc9c01f8c6c6a81d28dee4e1d973c839">anonymous{X86TargetMachine.cpp}::X86PassConfig::createPostMachineScheduler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#aab77d912a7ea86c5c77bc6eacb9adca6">createVLIWMachineSched</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnpostscheduledagmilive/#ab0fcaad7b05dc36681c5abeabca7991c">llvm::GCNPostScheduleDAGMILive::schedule</a>.</p>

</div>
</div>

### bottom() {#a70e4bd877aac0a63c10463277c9a52c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::ScheduleDAGMI::bottom ()</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a7435e842606f5db4bca092e5829befc6">CurrentBottom</a>.</p>

</div>
</div>

### doMBBSchedRegionsTopDown() {#a75acfc66aaac7201dc55a66df9940a37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScheduleDAGMI::doMBBSchedRegionsTopDown ()</td>
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

<p>If this method returns true, handling of the scheduling regions themselves (in case of a scheduling boundary in MBB) will be done beginning with the topmost region of MBB.</p>

<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a0318c90d99b85c47bc82d9e0844462f6">SchedImpl</a>.</p>

</div>
</div>

### enterRegion() {#a78e3672daf3301153eac2266dbc32885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::enterRegion (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * bb, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> end, unsigned regioninstrs)</td>
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


<p>enterRegion - Called back from <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#ab1dc85fd08ff7aa2a4057683e7a4dc8f">PostMachineScheduler::runOnMachineFunction</a> after crossing a scheduling boundary.</p>


<p>This covers all instructions in a block, while <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule()</a> may only cover a subset.</p>


<p>[begin, end) includes all instructions in the region, including the boundary itself and single-instruction regions that don't get scheduled.</p>


<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 775 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab50b64c518a7455daf3e0bc87aee5514">llvm::ScheduleDAGInstrs::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a8d1f67b9f6d31b169c0d4b1d2080b4e7a7aa4fbe53df8b2bf33ec065623b42e34">llvm::ScheduleDAGInstrs::Bidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a8d1f67b9f6d31b169c0d4b1d2080b4e7a3dac6c64382dc74b937892893d2595c6">llvm::ScheduleDAGInstrs::BottomUp</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a21805259f54dab47c2b3da009216996a">llvm::ScheduleDAGInstrs::end</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae8727d434d20639d563849891f5ca1e1">llvm::ScheduleDAGInstrs::enterRegion</a>, <a href="#a0318c90d99b85c47bc82d9e0844462f6">SchedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#afdb896a30eb0e9fc3143fe6c447570cb">llvm::ScheduleDAGInstrs::setDumpDirection</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a8d1f67b9f6d31b169c0d4b1d2080b4e7a622f7d95cc7d6d2dc7a32b140559b680">llvm::ScheduleDAGInstrs::TopDown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a34481791fdd8f5d9131431cb0a1a0c01">llvm::ScheduleDAGMILive::enterRegion</a>.</p>

</div>
</div>

### finishBlock() {#a9ca687b69b34efab1604af98db151cbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::finishBlock ()</td>
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

<p>Cleans up after scheduling in the given block.</p>

<p>Declaration at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 766 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a1f9a4461e2c9ac06b97f55554f836d66">llvm::ScheduleDAGInstrs::finishBlock</a> and <a href="#a0318c90d99b85c47bc82d9e0844462f6">SchedImpl</a>.</p>

</div>
</div>

### getLIS() {#a7dcf5173867549aff2a8cdcc70dd2800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals * llvm::ScheduleDAGMI::getLIS ()</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a9d67b1cafa36e90d7060d1da84907885">LIS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#af6b0c8c54226e0aafa107e5e92c813a2">anonymous{MachineScheduler.cpp}::CopyConstrain::apply</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>.</p>

</div>
</div>

### getNextClusterPred() {#ab8704e1dcdf62f3ac74e67280c029f5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SUnit * llvm::ScheduleDAGMI::getNextClusterPred ()</td>
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



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a33503949e135cad03fa91fde0c005649">NextClusterPred</a>.</p>

</div>
</div>

### getNextClusterSucc() {#adde3720b0af5350a55fdd0eba84566a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SUnit * llvm::ScheduleDAGMI::getNextClusterSucc ()</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a2aa5cb48ee16ded1b263483026d08894">NextClusterSucc</a>.</p>

</div>
</div>

### hasVRegLiveness() {#a78c0f3feb8a81ca338f843494cff564e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::ScheduleDAGMI::hasVRegLiveness ()</td>
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

<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#af6b0c8c54226e0aafa107e5e92c813a2">anonymous{MachineScheduler.cpp}::CopyConstrain::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a7e340b4e4b4412f6808ff4270bfa6999">llvm::ARMBaseInstrInfo::CreateTargetMIHazardRecognizer</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a4ab6232188433548694ea1a9a98d542f">llvm::SIInstrInfo::CreateTargetMIHazardRecognizer</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-3e4d2beef0711eb028dcc7799677e405/#aeec5b7bbdeddc6e81486c44f34c5975a">llvm::DOTGraphTraits&lt; ScheduleDAGMI * &gt;::getNodeAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-3e4d2beef0711eb028dcc7799677e405/#a9e281d4b0718506e4ec5596a06ae36dd">llvm::DOTGraphTraits&lt; ScheduleDAGMI * &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/ilpscheduler/#a6fc742f69804969334c5298829787a0d">anonymous{MachineScheduler.cpp}::ILPScheduler::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#aa8cddd2ea015f8177a8395035f87e332">llvm::GenericScheduler::initialize</a> and <a href="/web-llvm/docs/api/classes/llvm/r600schedstrategy/#a2c1760a96cdc9e6f584b99740060fcee">llvm::R600SchedStrategy::initialize</a>.</p>

</div>
</div>

### moveInstruction() {#a2209b15a069023499cc665b373e67703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::moveInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertPos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change the position of an instruction within the basic block and update live ranges and region boundary iterators.</p>


<p>This is normally called from the main scheduler loop but may also be invoked by the scheduling strategy to perform additional code motion.</p>


<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>, <a href="#a9d67b1cafa36e90d7060d1da84907885">LIS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae81ad8ece7681af658742f6d4e2fcfb1">llvm::ScheduleDAGInstrs::RegionBegin</a>.</p>


<p>Referenced by <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a04a2c04f918397dbac27a79e58807136">llvm::ScheduleDAGMILive::scheduleMI</a>.</p>

</div>
</div>

### schedule() {#a5d7e71cf32573e6b1762b5a1d82a1cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::schedule ()</td>
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


<p>Per-region scheduling driver, called back from <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#ab1dc85fd08ff7aa2a4057683e7a4dc8f">PostMachineScheduler::runOnMachineFunction</a>.</p>


<p>This is a simplified driver that does not consider liveness or register pressure. It is useful for PostRA scheduling and potentially other custom schedulers.</p>


<p>Declaration at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 830 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a79b8428bb41e16b71ae2bb0139bce5eb">AA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab50b64c518a7455daf3e0bc87aee5514">llvm::ScheduleDAGInstrs::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="#a569fc4139bec0217794e9f830d6ba852">checkSchedLimit</a>, <a href="#a7435e842606f5db4bca092e5829befc6">CurrentBottom</a>, <a href="#ac8abe1b0d869087bd0c14a6637356dc0">CurrentTop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aea2d4ef1e00ee834ab155abd18a560e4">llvm::ScheduleDAGInstrs::dump</a>, <a href="#a01b02e76c87211e7084ec17f18a2d16f">dumpSchedule</a>, <a href="#a6d0a0b4903e8d4d12c98b0f43fe83878">findRootsAndBiasEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="#a1f98694f104d052d71ed74ade38d69f0">initQueues</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ac198a5fb130b4c09836ba20e01b4290d">llvm::SUnit::isBottomReady</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae0b8da4dfde85d4ddc32359ca52dc493">llvm::SUnit::isTopReady</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a2209b15a069023499cc665b373e67703">moveInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a1c8a9363a3eb113ca42064a03636b135">nextIfDebug</a>, <a href="#ac2dafe98c88d43b256622413886e2152">placeDebugValues</a>, <a href="#a2aa2eb6fd6a44ff6b9cbad960d446c7a">postProcessDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e9fde7ed08fd233750d0a947147dfa1">llvm::PrintDAGs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a459acab05344caa836aa036f1829c928">priorNonDebug</a>, <a href="#a0318c90d99b85c47bc82d9e0844462f6">SchedImpl</a>, <a href="#abfdd9a95217810c69b2557060a130318">updateQueues</a>, <a href="#a8b7babb023cad0842f5a177e7abe3651">viewGraph</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5ec9cfe35d76125af923975fa0c1730a">llvm::ViewMISchedDAGs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnpostscheduledagmilive/#ab0fcaad7b05dc36681c5abeabca7991c">llvm::GCNPostScheduleDAGMILive::schedule</a>.</p>

</div>
</div>

### startBlock() {#a19c5e2b675721f465bc85a5f58e7c084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::startBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
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

<p>Prepares to perform scheduling in the given block.</p>

<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a0318c90d99b85c47bc82d9e0844462f6">SchedImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2822215b7634783aece96ef695a72f1d">llvm::ScheduleDAGInstrs::startBlock</a>.</p>

</div>
</div>

### top() {#a5bcc40c244c6a33d738b3e4f1d490ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::ScheduleDAGMI::top ()</td>
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



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#ac8abe1b0d869087bd0c14a6637356dc0">CurrentTop</a>.</p>

</div>
</div>

### viewGraph() {#a8181ae26c7912b2ae6214be22c4f6cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::viewGraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Title)</td>
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

<p>viewGraph - Pop up a ghostview window with the reachable parts of the DAG rendered using 'dot'.</p>

<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 4452 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab8635363d4287c93f64c55ad5567fcf0">llvm::ViewGraph</a>.</p>


<p>Referenced by <a href="#a8b7babb023cad0842f5a177e7abe3651">viewGraph</a>.</p>

</div>
</div>

### viewGraph() {#a8b7babb023cad0842f5a177e7abe3651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::viewGraph ()</td>
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

<p>Out-of-line implementation with no arguments is handy for gdb.</p>

<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 4462 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a23f7a6c4d1be0ca66f44eb4aa499075a">llvm::ScheduleDAGInstrs::getDAGName</a> and <a href="#a8181ae26c7912b2ae6214be22c4f6cf5">viewGraph</a>.</p>


<p>Referenced by <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a1583ce23a69e8a1b4af8065e2019c75f">llvm::ScheduleDAGMILive::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### checkSchedLimit() {#a569fc4139bec0217794e9f830d6ba852}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScheduleDAGMI::checkSchedLimit ()</td>
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



<p>Declaration at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 815 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a7435e842606f5db4bca092e5829befc6">CurrentBottom</a>, <a href="#ac8abe1b0d869087bd0c14a6637356dc0">CurrentTop</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a533a172b0f7e2e6d667464a68c6f30ea">MISchedCutoff</a>.</p>


<p>Referenced by <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a1583ce23a69e8a1b4af8065e2019c75f">llvm::ScheduleDAGMILive::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>.</p>

</div>
</div>

### dumpSchedule() {#a01b02e76c87211e7084ec17f18a2d16f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ScheduleDAGMI::dumpSchedule ()</td>
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

<p>dump the scheduled Sequence.</p>

<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a8d1f67b9f6d31b169c0d4b1d2080b4e7a7aa4fbe53df8b2bf33ec065623b42e34">llvm::ScheduleDAGInstrs::Bidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a8d1f67b9f6d31b169c0d4b1d2080b4e7a3dac6c64382dc74b937892893d2595c6">llvm::ScheduleDAGInstrs::BottomUp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab3c913205add9c73e6bfe3540749737e">llvm::ScheduleDAGInstrs::DumpDir</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aa5f22315c4064579fca6cd88fb36ea5a">llvm::ScheduleDAGInstrs::dumpNode</a>, <a href="#a942d716003056c037d46a4144e9cf885">dumpScheduleTraceBottomUp</a>, <a href="#a3010c4b89284791284aa6e2ec510501b">dumpScheduleTraceTopDown</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab75cd37a7a0319d5a4c77189cca106ec">llvm::ScheduleDAGInstrs::getSUnit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#afc178c1fabdc9ea75b2e47e85c12e3df">MISchedDumpScheduleTrace</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a8d1f67b9f6d31b169c0d4b1d2080b4e7a622f7d95cc7d6d2dc7a32b140559b680">llvm::ScheduleDAGInstrs::TopDown</a>.</p>


<p>Referenced by <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a1583ce23a69e8a1b4af8065e2019c75f">llvm::ScheduleDAGMILive::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>.</p>

</div>
</div>

### dumpScheduleTraceBottomUp() {#a942d716003056c037d46a4144e9cf885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ScheduleDAGMI::dumpScheduleTraceBottomUp ()</td>
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



<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 1074 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aa1dfdcdc657e12c47e72d9dbe251ac85">llvm::SUnit::BotReadyCycle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#aa0067e3bf6cee38792f2749e1d16fff4">ColWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a4bf5573660c55924d68b517a0e9b4554">llvm::ScheduleDAGInstrs::getSchedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab75cd37a7a0319d5a4c77189cca106ec">llvm::ScheduleDAGInstrs::getSUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a6523b0d71574a464a78e2e05bd67b543">HeaderColWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5b1b4e94f62050dd1bccb48141ef4b9">llvm::left_justify</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a2d7fe448a57a131b2533e439fd6eae1e">MISchedSortResourcesInTrace</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c6d735dfe8fc13a113405c1dda2991e">llvm::right_justify</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#abb11b650b88a61630eba2a1b2eaa6fd0">llvm::ScheduleDAGInstrs::SchedModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#aaae6594fa7ded6088910716df9f47553">scheduleTableLegend</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>.</p>


<p>Referenced by <a href="#a01b02e76c87211e7084ec17f18a2d16f">dumpSchedule</a>.</p>

</div>
</div>

### dumpScheduleTraceTopDown() {#a3010c4b89284791284aa6e2ec510501b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ScheduleDAGMI::dumpScheduleTraceTopDown ()</td>
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

<p>Print execution trace of the schedule top-down or bottom-up.</p>

<p>Declaration at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 993 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#aa0067e3bf6cee38792f2749e1d16fff4">ColWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a4bf5573660c55924d68b517a0e9b4554">llvm::ScheduleDAGInstrs::getSchedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab75cd37a7a0319d5a4c77189cca106ec">llvm::ScheduleDAGInstrs::getSUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a6523b0d71574a464a78e2e05bd67b543">HeaderColWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5b1b4e94f62050dd1bccb48141ef4b9">llvm::left_justify</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a2d7fe448a57a131b2533e439fd6eae1e">MISchedSortResourcesInTrace</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c6d735dfe8fc13a113405c1dda2991e">llvm::right_justify</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#abb11b650b88a61630eba2a1b2eaa6fd0">llvm::ScheduleDAGInstrs::SchedModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#aaae6594fa7ded6088910716df9f47553">scheduleTableLegend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2a6f92b9c5aba34d3b07f3ebe229ccff">llvm::SUnit::TopReadyCycle</a>.</p>


<p>Referenced by <a href="#a01b02e76c87211e7084ec17f18a2d16f">dumpSchedule</a>.</p>

</div>
</div>

### findRootsAndBiasEdges() {#a6d0a0b4903e8d4d12c98b0f43fe83878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::findRootsAndBiasEdges (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; &amp; TopRoots, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; &amp; BotRoots)</td>
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



<p>Declaration at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 910 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>


<p>Referenced by <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a1583ce23a69e8a1b4af8065e2019c75f">llvm::ScheduleDAGMILive::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>.</p>

</div>
</div>

### initQueues() {#a1f98694f104d052d71ed74ade38d69f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::initQueues (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; TopRoots, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; BotRoots)</td>
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


<p>Identify DAG roots and setup scheduler queues.</p>


<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 929 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a7435e842606f5db4bca092e5829befc6">CurrentBottom</a>, <a href="#ac8abe1b0d869087bd0c14a6637356dc0">CurrentTop</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a521bf68518a92483130a58680716d153">llvm::ScheduleDAG::EntrySU</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a33503949e135cad03fa91fde0c005649">NextClusterPred</a>, <a href="#a2aa5cb48ee16ded1b263483026d08894">NextClusterSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a1c8a9363a3eb113ca42064a03636b135">nextIfDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebe6da1ab4a07020669f3d6148c0b559">llvm::ArrayRef&lt; T &gt;::rbegin</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae81ad8ece7681af658742f6d4e2fcfb1">llvm::ScheduleDAGInstrs::RegionBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a3f74b283acf0dfb537bc387e49344f04">llvm::ScheduleDAGInstrs::RegionEnd</a>, <a href="#a25f9975b56fe38f7a8bb4d10b7f6f5ea">releasePredecessors</a>, <a href="#acf56d667066b39177a3c0f134d759d98">releaseSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a709f5d7f042648ec20197939d9a6805f">llvm::ArrayRef&lt; T &gt;::rend</a> and <a href="#a0318c90d99b85c47bc82d9e0844462f6">SchedImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a3668b7c35103540be55d96cd68948f43">llvm::ScheduleDAGMILive::initQueues</a> and <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule</a>.</p>

</div>
</div>

### placeDebugValues() {#ac2dafe98c88d43b256622413886e2152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::placeDebugValues ()</td>
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

<p>Reinsert debug_values recorded in <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a6837fb2c08f4c8c986a4689a37ca93cf">ScheduleDAGInstrs::DbgValues</a>.</p>


<p>Reinsert any remaining debug_values, just like the PostRA scheduler.</p>


<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 970 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a6837fb2c08f4c8c986a4689a37ca93cf">llvm::ScheduleDAGInstrs::DbgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a25ae020b571d18d34d03097d91ca0f40">llvm::ScheduleDAGInstrs::FirstDbgValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae81ad8ece7681af658742f6d4e2fcfb1">llvm::ScheduleDAGInstrs::RegionBegin</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a3f74b283acf0dfb537bc387e49344f04">llvm::ScheduleDAGInstrs::RegionEnd</a>.</p>


<p>Referenced by <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a1583ce23a69e8a1b4af8065e2019c75f">llvm::ScheduleDAGMILive::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ad899858c4b90e464815c32a7f9c4bb26">llvm::GCNIterativeScheduler::scheduleRegion</a>.</p>

</div>
</div>

### postProcessDAG() {#a2aa2eb6fd6a44ff6b9cbad960d446c7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::postProcessDAG ()</td>
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

<p>Apply each <a href="/web-llvm/docs/api/classes/llvm/scheduledagmutation">ScheduleDAGMutation</a> step in order.</p>


<p>This allows different instances of <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> to perform custom DAG postprocessing.</p>


<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 904 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>Reference <a href="#aed362d97300c9cd91f179f9c6c31c9ac">Mutations</a>.</p>


<p>Referenced by <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a1583ce23a69e8a1b4af8065e2019c75f">llvm::ScheduleDAGMILive::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>.</p>

</div>
</div>

### releasePred() {#a1c51776d4e512a7f24d5b5d601c31016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::releasePred (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> * PredEdge)</td>
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

<p>ReleasePred - Decrement the NumSuccsLeft count of a predecessor.</p>


<p>When NumSuccsLeft reaches zero, release the predecessor node.</p>


<p>FIXME: Adjust PredSU height based on MinLatency.</p>


<p>Declaration at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#aa1dfdcdc657e12c47e72d9dbe251ac85">llvm::SUnit::BotReadyCycle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aa5f22315c4064579fca6cd88fb36ea5a">llvm::ScheduleDAGInstrs::dumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a521bf68518a92483130a58680716d153">llvm::ScheduleDAG::EntrySU</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a5eca2019521fd47b79fe5ef66d02fd43">llvm::SDep::getLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#ac2a5a158ff2d2bbbadae7accc72e7c51">llvm::SDep::isCluster</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a21e3367f21a2b07ce6e344fc6a2ed078">llvm::SDep::isWeak</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a33503949e135cad03fa91fde0c005649">NextClusterPred</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a40c2dfbd170941dd4d20ee9b60c9d49d">llvm::SUnit::NumSuccsLeft</a>, <a href="#a0318c90d99b85c47bc82d9e0844462f6">SchedImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae75d620ee809eaf50970a833f4a3ace9">llvm::SUnit::WeakSuccsLeft</a>.</p>


<p>Referenced by <a href="#a25f9975b56fe38f7a8bb4d10b7f6f5ea">releasePredecessors</a>.</p>

</div>
</div>

### releasePredecessors() {#a25f9975b56fe38f7a8bb4d10b7f6f5ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::releasePredecessors (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>releasePredecessors - Call releasePred on each of SU's predecessors.</p>

<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 756 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a> and <a href="#a1c51776d4e512a7f24d5b5d601c31016">releasePred</a>.</p>


<p>Referenced by <a href="#a1f98694f104d052d71ed74ade38d69f0">initQueues</a> and <a href="#abfdd9a95217810c69b2557060a130318">updateQueues</a>.</p>

</div>
</div>

### releaseSucc() {#a90ffd918ef80c711049758b2064e15c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::releaseSucc (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> * SuccEdge)</td>
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

<p>ReleaseSucc - Decrement the NumPredsLeft count of a successor.</p>


<p>When NumPredsLeft reaches zero, release the successor node.</p>


<p>FIXME: Adjust SuccSU height based on MinLatency.</p>


<p>Declaration at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 691 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aa5f22315c4064579fca6cd88fb36ea5a">llvm::ScheduleDAGInstrs::dumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a5eca2019521fd47b79fe5ef66d02fd43">llvm::SDep::getLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#ac2a5a158ff2d2bbbadae7accc72e7c51">llvm::SDep::isCluster</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a21e3367f21a2b07ce6e344fc6a2ed078">llvm::SDep::isWeak</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a2aa5cb48ee16ded1b263483026d08894">NextClusterSucc</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a94f78042fbba3ea4cd1004353daa46aa">llvm::SUnit::NumPredsLeft</a>, <a href="#a0318c90d99b85c47bc82d9e0844462f6">SchedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2a6f92b9c5aba34d3b07f3ebe229ccff">llvm::SUnit::TopReadyCycle</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#ab9e02660290b9557b547b57870133467">llvm::SUnit::WeakPredsLeft</a>.</p>


<p>Referenced by <a href="#acf56d667066b39177a3c0f134d759d98">releaseSuccessors</a>.</p>

</div>
</div>

### releaseSuccessors() {#acf56d667066b39177a3c0f134d759d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::releaseSuccessors (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>releaseSuccessors - Call releaseSucc on each of SU's successors.</p>

<p>Declaration at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#a90ffd918ef80c711049758b2064e15c4">releaseSucc</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a>.</p>


<p>Referenced by <a href="#a1f98694f104d052d71ed74ade38d69f0">initQueues</a> and <a href="#abfdd9a95217810c69b2557060a130318">updateQueues</a>.</p>

</div>
</div>

### updateQueues() {#abfdd9a95217810c69b2557060a130318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGMI::updateQueues (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, bool IsTopNode)</td>
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

<p>Update scheduler DAG and queues after scheduling an instruction.</p>


<p>Update scheduler queues after scheduling an instruction.</p>


<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 959 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>, <a href="#a25f9975b56fe38f7a8bb4d10b7f6f5ea">releasePredecessors</a> and <a href="#acf56d667066b39177a3c0f134d759d98">releaseSuccessors</a>.</p>


<p>Referenced by <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a1583ce23a69e8a1b4af8065e2019c75f">llvm::ScheduleDAGMILive::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AA {#a79b8428bb41e16b71ae2bb0139bce5eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults* llvm::ScheduleDAGMI::AA</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a4be5ffcd4f76d433cc753be146a872b7">llvm::ScheduleDAGMILive::buildDAGWithRegPressure</a>, <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule</a> and <a href="#a629982ca3ef5632e63f32b5682fde927">ScheduleDAGMI</a>.</p>

</div>
</div>

### CurrentBottom {#a7435e842606f5db4bca092e5829befc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::ScheduleDAGMI::CurrentBottom</td>
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

<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a70e4bd877aac0a63c10463277c9a52c5">bottom</a>, <a href="#a569fc4139bec0217794e9f830d6ba852">checkSchedLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a7819978aa6afac57ceb568dc197ac8c3">llvm::SIScheduleDAGMI::getCurrentBottom</a>, <a href="#a1f98694f104d052d71ed74ade38d69f0">initQueues</a>, <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a1583ce23a69e8a1b4af8065e2019c75f">llvm::ScheduleDAGMILive::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a04a2c04f918397dbac27a79e58807136">llvm::ScheduleDAGMILive::scheduleMI</a>.</p>

</div>
</div>

### CurrentTop {#ac8abe1b0d869087bd0c14a6637356dc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::ScheduleDAGMI::CurrentTop</td>
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

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a569fc4139bec0217794e9f830d6ba852">checkSchedLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a9ed7f9965b5fafd5e6f0dae05deb7c23">llvm::SIScheduleDAGMI::getCurrentTop</a>, <a href="#a1f98694f104d052d71ed74ade38d69f0">initQueues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a3668b7c35103540be55d96cd68948f43">llvm::ScheduleDAGMILive::initQueues</a>, <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a1583ce23a69e8a1b4af8065e2019c75f">llvm::ScheduleDAGMILive::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a04a2c04f918397dbac27a79e58807136">llvm::ScheduleDAGMILive::scheduleMI</a> and <a href="#a5bcc40c244c6a33d738b3e4f1d490ca3">top</a>.</p>

</div>
</div>

### LIS {#a9d67b1cafa36e90d7060d1da84907885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals* llvm::ScheduleDAGMI::LIS</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a4be5ffcd4f76d433cc753be146a872b7">llvm::ScheduleDAGMILive::buildDAGWithRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a6ca77a3ca62633e1f7f4ed2ff3be6d81">llvm::GCNIterativeScheduler::GCNIterativeScheduler</a>, <a href="#a7dcf5173867549aff2a8cdcc70dd2800">getLIS</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a5cdf7bc92c67442fd90bd2dfaeae0383">llvm::SIScheduleDAGMI::getLIS</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#abeb32a2045204d56bbf623bec5da25b3">llvm::GCNIterativeScheduler::getRegionPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ab7703967e4547dc33bde51d360068021">llvm::GCNIterativeScheduler::getSchedulePressure</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a86daf2b1fb72fdd9a8785a4042ac1457">llvm::ScheduleDAGMILive::initRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#ab6c5bda21b39ff9494fc2661de4aa974">llvm::SIScheduleDAGMI::initRPTracker</a>, <a href="#a2209b15a069023499cc665b373e67703">moveInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a70f01da7bffd10dc0686e3ca4286eac8">llvm::GCNIterativeScheduler::printRegions</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a6e84e2872d922dee85f4511ac0326f64">llvm::GCNIterativeScheduler::printSchedResult</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ab201710a9597b0df54c12a848d4804d9">llvm::GCNIterativeScheduler::schedule</a>, <a href="#a629982ca3ef5632e63f32b5682fde927">ScheduleDAGMI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a04a2c04f918397dbac27a79e58807136">llvm::ScheduleDAGMILive::scheduleMI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ad899858c4b90e464815c32a7f9c4bb26">llvm::GCNIterativeScheduler::scheduleRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a6fd0550f564608fec7c5d7f25817ddef">llvm::GCNIterativeScheduler::tryMaximizeOccupancy</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a91251ec06d557b21578095955b7b7fa7">llvm::ScheduleDAGMILive::updatePressureDiffs</a>.</p>

</div>
</div>

### Mutations {#aed362d97300c9cd91f179f9c6c31c9ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;ScheduleDAGMutation&gt; &gt; llvm::ScheduleDAGMI::Mutations</td>
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

<p>Ordered list of DAG postprocessing steps.</p>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a2002164aea6fabe20598e0526746b1fa">addMutation</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnpostscheduledagmilive/#a2573535a1fb6914feb4615e6f6e1ef5d">llvm::GCNPostScheduleDAGMILive::finalizeSchedule</a>, <a href="#a2aa2eb6fd6a44ff6b9cbad960d446c7a">postProcessDAG</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnpostscheduledagmilive/#ab0fcaad7b05dc36681c5abeabca7991c">llvm::GCNPostScheduleDAGMILive::schedule</a>.</p>

</div>
</div>

### NextClusterPred {#a33503949e135cad03fa91fde0c005649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SUnit* llvm::ScheduleDAGMI::NextClusterPred = nullptr</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the next node in a scheduled cluster.</p>

<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#ab8704e1dcdf62f3ac74e67280c029f5e">getNextClusterPred</a>, <a href="#a1f98694f104d052d71ed74ade38d69f0">initQueues</a> and <a href="#a1c51776d4e512a7f24d5b5d601c31016">releasePred</a>.</p>

</div>
</div>

### NextClusterSucc {#a2aa5cb48ee16ded1b263483026d08894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SUnit* llvm::ScheduleDAGMI::NextClusterSucc = nullptr</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#adde3720b0af5350a55fdd0eba84566a8">getNextClusterSucc</a>, <a href="#a1f98694f104d052d71ed74ade38d69f0">initQueues</a> and <a href="#a90ffd918ef80c711049758b2064e15c4">releaseSucc</a>.</p>

</div>
</div>

### SchedImpl {#a0318c90d99b85c47bc82d9e0844462f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MachineSchedStrategy&gt; llvm::ScheduleDAGMI::SchedImpl</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a75acfc66aaac7201dc55a66df9940a37">doMBBSchedRegionsTopDown</a>, <a href="#a78e3672daf3301153eac2266dbc32885">enterRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a34481791fdd8f5d9131431cb0a1a0c01">llvm::ScheduleDAGMILive::enterRegion</a>, <a href="#a9ca687b69b34efab1604af98db151cbf">finishBlock</a>, <a href="#a1f98694f104d052d71ed74ade38d69f0">initQueues</a>, <a href="/web-llvm/docs/api/classes/gcniterativescheduler/overridelegacystrategy/#af81b98ad3eb158abad6175391f4ed6c3">llvm::GCNIterativeScheduler::OverrideLegacyStrategy::OverrideLegacyStrategy</a>, <a href="#a1c51776d4e512a7f24d5b5d601c31016">releasePred</a>, <a href="#a90ffd918ef80c711049758b2064e15c4">releaseSucc</a>, <a href="#a5d7e71cf32573e6b1762b5a1d82a1cf5">schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a1583ce23a69e8a1b4af8065e2019c75f">llvm::ScheduleDAGMILive::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>, <a href="#a629982ca3ef5632e63f32b5682fde927">ScheduleDAGMI</a> and <a href="#a19c5e2b675721f465bc85a5f58e7c084">startBlock</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
