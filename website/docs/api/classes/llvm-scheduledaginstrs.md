---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scheduledaginstrs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ScheduleDAGInstrs` Class Reference

<p>A <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> for scheduling lists of <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ScheduleDAGInstrs { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">llvm/CodeGen/ScheduleDAGInstrs.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist">SchedulePostRATDList</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/defaultvliwscheduler">DefaultVLIWScheduler</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> is an implementation of <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> that simply schedules machine instructions according to the given <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> without much extra book-keeping. <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag">SwingSchedulerDAG</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class builds the dependence graph for the instructions in a loop, and attempts to schedule the instructions using the SMS algorithm. <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e1e9d0b1c64c405c0e99288f9225bd5">SUList</a> = std::list&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of SUnits, used in <a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap">Value2SUsMap</a>, during DAG construction. <a href="#a8e1e9d0b1c64c405c0e99288f9225bd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aeb725848d197181f722cec8aa21511">DbgValueVector</a> = std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">DumpDirection { <a href="#a8d1f67b9f6d31b169c0d4b1d2080b4e7">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The direction that should be used to dump the scheduled Sequence. <a href="#a8d1f67b9f6d31b169c0d4b1d2080b4e7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bcb745a3e78c329d1431608b1f51c25">ScheduleDAGInstrs</a> (MachineFunction &amp;mf, const MachineLoopInfo *mli, bool RemoveKillFlags=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55ec5f63fd13f77063e0fc05a722283a">~ScheduleDAGInstrs</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdb896a30eb0e9fc3143fe6c447570cb">setDumpDirection</a> (DumpDirection D)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f70979bd43329e7ad53ad796db8112f">getSchedModel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the machine model for instruction scheduling. <a href="#a3f70979bd43329e7ad53ad796db8112f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf5573660c55924d68b517a0e9b4554">getSchedClass</a> (SUnit *SU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolves and cache a resolved scheduling class for an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="#a4bf5573660c55924d68b517a0e9b4554">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa79589a56769cd108d08e21544be1420">IsReachable</a> (SUnit *SU, SUnit *TargetSU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsReachable - Checks if SU is reachable from TargetSU. <a href="#aa79589a56769cd108d08e21544be1420">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab50b64c518a7455daf3e0bc87aee5514">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator to the top of the current scheduling region. <a href="#ab50b64c518a7455daf3e0bc87aee5514">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21805259f54dab47c2b3da009216996a">end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator to the bottom of the current scheduling region. <a href="#a21805259f54dab47c2b3da009216996a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c497ec4b863f7d59aa3678740331c8e">newSUnit</a> (MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> and return a ptr to it. <a href="#a6c497ec4b863f7d59aa3678740331c8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab75cd37a7a0319d5a4c77189cca106ec">getSUnit</a> (MachineInstr *MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an existing <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> for this MI, or nullptr. <a href="#ab75cd37a7a0319d5a4c77189cca106ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af637149166f4dbc65315b9d6bd96e242">doMBBSchedRegionsTopDown</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this method returns true, handling of the scheduling regions themselves (in case of a scheduling boundary in MBB) will be done beginning with the topmost region of MBB. <a href="#af637149166f4dbc65315b9d6bd96e242">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2822215b7634783aece96ef695a72f1d">startBlock</a> (MachineBasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepares to perform scheduling in the given block. <a href="#a2822215b7634783aece96ef695a72f1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f9a4461e2c9ac06b97f55554f836d66">finishBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cleans up after scheduling in the given block. <a href="#a1f9a4461e2c9ac06b97f55554f836d66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8727d434d20639d563849891f5ca1e1">enterRegion</a> (MachineBasicBlock *bb, MachineBasicBlock::iterator begin, MachineBasicBlock::iterator end, unsigned regioninstrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the DAG and common scheduler state for a new scheduling region. <a href="#ae8727d434d20639d563849891f5ca1e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc5a5c32ac78a99ee2633dbbeec20397">exitRegion</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called when the scheduler has finished scheduling the current region. <a href="#abc5a5c32ac78a99ee2633dbbeec20397">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a> (AAResults *AA, RegPressureTracker *RPTracker=nullptr, PressureDiffs *PDiffs=nullptr, LiveIntervals *LIS=nullptr, bool TrackLaneMasks=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Builds SUnits for the current region. <a href="#ab580983de4f7b69ebcca992be9cb3223">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8625c1e6c9bc82f2eaef39d3fff65a8">addSchedBarrierDeps</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds dependencies from instructions in the current list of instructions being scheduled to scheduling barrier. <a href="#ae8625c1e6c9bc82f2eaef39d3fff65a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0cecc651db330128468e08794794f5c">schedule</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Orders nodes according to selected style. <a href="#ac0cecc651db330128468e08794794f5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c30ee6cdef3f4784c192654dcb9bab0">finalizeSchedule</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow targets to perform final scheduling actions at the level of the whole <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>. <a href="#a7c30ee6cdef3f4784c192654dcb9bab0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f22315c4064579fca6cd88fb36ea5a">dumpNode</a> (const SUnit &amp;SU) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea2d4ef1e00ee834ab155abd18a560e4">dump</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbb37cc24abd3ed381b0fd496351bd17">getGraphNodeLabel</a> (const SUnit *SU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a label for a DAG node that points to an instruction. <a href="#afbb37cc24abd3ed381b0fd496351bd17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23f7a6c4d1be0ca66f44eb4aa499075a">getDAGName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a label for the region of code covered by the DAG. <a href="#a23f7a6c4d1be0ca66f44eb4aa499075a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dc06d4fb42d48a6ade1958f76334826">fixupKills</a> (MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fixes register kill flags that scheduling has made invalid. <a href="#a4dc06d4fb42d48a6ade1958f76334826">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac384df17605ecce542a6d2567c7f1ee0">canAddEdge</a> (SUnit *SuccSU, SUnit *PredSU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if an edge can be added from PredSU to SuccSU without creating a cycle. <a href="#ac384df17605ecce542a6d2567c7f1ee0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86bfa4838cb7e42648615d27c94c8017">addEdge</a> (SUnit *SuccSU, const SDep &amp;PredDep)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a DAG edge to the given SU with the given predecessor dependence data. <a href="#a86bfa4838cb7e42648615d27c94c8017">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a954c0aedb37bd7682d2d586026c5c483">getAAForDep</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a (possibly null) pointer to the current <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a>. <a href="#a954c0aedb37bd7682d2d586026c5c483">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e28b826aaa73d2dacf89ba8f8c775d1">reduceHugeMemNodeMaps</a> (Value2SUsMap &amp;stores, Value2SUsMap &amp;loads, unsigned N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reduces maps in FIFO order, by N SUs. <a href="#a2e28b826aaa73d2dacf89ba8f8c775d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee33e06ea8865a2fb2bf229325c07194">addChainDependency</a> (SUnit *SUa, SUnit *SUb, unsigned Latency=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a chain edge between SUa and SUb, but only if both <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> and <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> fail to deny the dependency. <a href="#aee33e06ea8865a2fb2bf229325c07194">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48e69d6ef017966f2a55dbf4d1d0b193">addChainDependencies</a> (SUnit *SU, SUList &amp;SUs, unsigned Latency)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds dependencies as needed from all SUs in list to SU. <a href="#a48e69d6ef017966f2a55dbf4d1d0b193">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe11e438e3ecc0381047e0e01958fea0">addChainDependencies</a> (SUnit *SU, Value2SUsMap &amp;Val2SUsMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds dependencies as needed from all SUs in map, to SU. <a href="#afe11e438e3ecc0381047e0e01958fea0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14962363da4c4a48ad6646cb05f49b77">addChainDependencies</a> (SUnit *SU, Value2SUsMap &amp;Val2SUsMap, ValueType V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds dependencies as needed to SU, from all SUs mapped to V. <a href="#a14962363da4c4a48ad6646cb05f49b77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cfd9da0e5724aa91bf1767dc1e2515e">addBarrierChain</a> (Value2SUsMap &amp;map)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds barrier chain edges from all SUs in map, and then clear the map. <a href="#a2cfd9da0e5724aa91bf1767dc1e2515e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac483efdc6c5ab7a20f776b77f986b6cf">insertBarrierChain</a> (Value2SUsMap &amp;map)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts a barrier chain in a huge region, far below current SU. <a href="#ac483efdc6c5ab7a20f776b77f986b6cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a705a0975de8335b0b6bdbbae165e8f5c">initSUnits</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> for each real instruction, numbered in top-down topological order. <a href="#a705a0975de8335b0b6bdbbae165e8f5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56fbc3f460289602ce8a51538ebc1e26">addPhysRegDataDeps</a> (SUnit *SU, unsigned OperIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MO is an operand of SU's instruction that defines a physical register. <a href="#a56fbc3f460289602ce8a51538ebc1e26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e9425c046cf742bfbb9ebb96466d8e5">addPhysRegDeps</a> (SUnit *SU, unsigned OperIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds register dependencies (data, anti, and output) from this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> to following instructions in the same scheduling region that depend the physical register referenced at OperIdx. <a href="#a2e9425c046cf742bfbb9ebb96466d8e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10acc9310a21d9a8191d3d84916bdffb">addVRegDefDeps</a> (SUnit *SU, unsigned OperIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds register output and data dependencies from this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> to instructions that occur later in the same scheduling region if they read from or write to the virtual register defined at OperIdx. <a href="#a10acc9310a21d9a8191d3d84916bdffb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f958ee7dc9902af4093fe8fabbabd6e">addVRegUseDeps</a> (SUnit *SU, unsigned OperIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a register data dependency if the instruction that defines the virtual register used at OperIdx is mapped to an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="#a0f958ee7dc9902af4093fe8fabbabd6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a643ff7dd8c287dd58e75cbe79556e74c">getLaneMaskForMO</a> (const MachineOperand &amp;MO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a mask for which lanes get read/written by the given (register) machine operand. <a href="#a643ff7dd8c287dd58e75cbe79556e74c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb8c24d6929051d24b35af1ef0550e54">deadDefHasNoUse</a> (const MachineOperand &amp;MO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the def register in <span class="doxyComputerOutput">MO</span> has no uses. <a href="#afb8c24d6929051d24b35af1ef0550e54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2b3e1939f6f39819ad55c714deefad6">MLI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2cd9b498508774a2da120d08b8d67cc">MFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb11b650b88a61630eba2a1b2eaa6fd0">SchedModel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> provides an interface to the machine model. <a href="#abb11b650b88a61630eba2a1b2eaa6fd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf7cb9b8e5dda7b42273e79048f1b8b3">RemoveKillFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the DAG builder should remove kill flags (in preparation for rescheduling). <a href="#adf7cb9b8e5dda7b42273e79048f1b8b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ad332011e2040d133de24f33cf3f4cd">CanHandleTerminators</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The standard DAG builder does not normally include terminators as DAG nodes because it does not create the necessary dependencies to prevent reordering. <a href="#a2ad332011e2040d133de24f33cf3f4cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96bb77f51ee973b0613bf5083144fa69">TrackLaneMasks</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether lane masks should get tracked. <a href="#a96bb77f51ee973b0613bf5083144fa69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a254403f7804208ade3cb68086201cb7a">BB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The block in which to insert instructions. <a href="#a254403f7804208ade3cb68086201cb7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae81ad8ece7681af658742f6d4e2fcfb1">RegionBegin</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The beginning of the range to be scheduled. <a href="#ae81ad8ece7681af658742f6d4e2fcfb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f74b283acf0dfb537bc387e49344f04">RegionEnd</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The end of the range to be scheduled. <a href="#a3f74b283acf0dfb537bc387e49344f04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c8be2ff5fd8eab8091e6ffa40ded8d">NumRegionInstrs</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instructions in this region (distance(RegionBegin, RegionEnd)). <a href="#af1c8be2ff5fd8eab8091e6ffa40ded8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a077eef2c61ca462db1800cc506092d38">MISUnitMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After calling BuildSchedGraph, each machine instruction in the current scheduling region is mapped to an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="#a077eef2c61ca462db1800cc506092d38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a604a259f489e2cbeee4cf5b55015453f">RegUnit2SUnitsMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa916ccdc8e2490104520c6d65861e90">Defs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Defs, Uses - Remember where defs and uses of each register are as we iterate upward through the instructions. <a href="#aaa916ccdc8e2490104520c6d65861e90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a604a259f489e2cbeee4cf5b55015453f">RegUnit2SUnitsMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc7a356b097ebfec45c1f663a4e52575">Uses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a1d9cbced9f5f0b7402f69721fd99597c">VReg2SUnitMultiMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae8addb45cc64764371ace084b48dc51">CurrentVRegDefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tracks the last instruction(s) in this region defining each virtual register. <a href="#aae8addb45cc64764371ace084b48dc51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a6d2caa8eb834330a1f8d4dafeb9bb3d8">VReg2SUnitOperIdxMultiMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a417ece2bf0f001181401c6c6b210194a">CurrentVRegUses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tracks the last instructions in this region using each virtual register. <a href="#a417ece2bf0f001181401c6c6b210194a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae07229f0bfadc988528dbf976f65c0bb">AAForDep</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a948f446009b83c0bca40324131e27868">BarrierChain</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remember a generic side-effecting instruction as we proceed. <a href="#a948f446009b83c0bca40324131e27868">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8d1f67b9f6d31b169c0d4b1d2080b4e7">DumpDirection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3c913205add9c73e6bfe3540749737e">DumpDir</a> = <a href="#a8d1f67b9f6d31b169c0d4b1d2080b4e7a79bebac6c64e00c788ab9aff723c504a">NotSet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/undefvalue">UndefValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad4b383d6bf0b66dd1a20a81505788fd">UnknownValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For an unanalyzable memory access, this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is used in maps. <a href="#aad4b383d6bf0b66dd1a20a81505788fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort">ScheduleDAGTopologicalSort</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cd3eede9e2a32c7139cc5c7c481e08b">Topo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Topo - A topological ordering for SUnits which permits fast IsReachable and similar queries. <a href="#a8cd3eede9e2a32c7139cc5c7c481e08b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6aeb725848d197181f722cec8aa21511">DbgValueVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6837fb2c08f4c8c986a4689a37ca93cf">DbgValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remember instruction that precedes DBG_VALUE. <a href="#a6837fb2c08f4c8c986a4689a37ca93cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25ae020b571d18d34d03097d91ca0f40">FirstDbgValue</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00bf9ef6a0eb5cba9d3461711cbcc6a8">LiveRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of live physical registers for updating kill flags. <a href="#a00bf9ef6a0eb5cba9d3461711cbcc6a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> for scheduling lists of <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SUList {#a8e1e9d0b1c64c405c0e99288f9225bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ScheduleDAGInstrs::SUList =  std::list&lt;SUnit *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of SUnits, used in <a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap">Value2SUsMap</a>, during DAG construction.</p>


<p>Note: to gain speed it might be worth investigating an optimized implementation of this data structure, such as a singly linked list with a memory pool (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> was tried but slow and <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> is not applicable).</p>


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Typedefs

### DbgValueVector {#a6aeb725848d197181f722cec8aa21511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ScheduleDAGInstrs::DbgValueVector = 
        std::vector&lt;std::pair&lt;MachineInstr *, MachineInstr *&gt;&gt;</td>
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



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### DumpDirection {#a8d1f67b9f6d31b169c0d4b1d2080b4e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ScheduleDAGInstrs::DumpDirection </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The direction that should be used to dump the scheduled Sequence.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TopDown<a id="a8d1f67b9f6d31b169c0d4b1d2080b4e7a622f7d95cc7d6d2dc7a32b140559b680"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BottomUp<a id="a8d1f67b9f6d31b169c0d4b1d2080b4e7a3dac6c64382dc74b937892893d2595c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Bidirectional<a id="a8d1f67b9f6d31b169c0d4b1d2080b4e7a7aa4fbe53df8b2bf33ec065623b42e34"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NotSet<a id="a8d1f67b9f6d31b169c0d4b1d2080b4e7a79bebac6c64e00c788ab9aff723c504a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ScheduleDAGInstrs() {#a5bcb745a3e78c329d1431608b1f51c25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs::ScheduleDAGInstrs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> * mli, bool RemoveKillFlags=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="#a6837fb2c08f4c8c986a4689a37ca93cf">DbgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#af2cd9b498508774a2da120d08b8d67cc">MFI</a>, <a href="#ad2b3e1939f6f39819ad55c714deefad6">MLI</a>, <a href="#adf7cb9b8e5dda7b42273e79048f1b8b3">RemoveKillFlags</a>, <a href="#abb11b650b88a61630eba2a1b2eaa6fd0">SchedModel</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a8bdf35180225e74794f7d23399a3db22">llvm::ScheduleDAG::ScheduleDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>, <a href="#a8cd3eede9e2a32c7139cc5c7c481e08b">Topo</a> and <a href="#aad4b383d6bf0b66dd1a20a81505788fd">UnknownValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#ac186f04d2e32eb9be8028a51f1231fec">llvm::SwingSchedulerDAG::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/defaultvliwscheduler/#a7c1a62bfba2908fff478bff6b2242d23">llvm::DefaultVLIWScheduler::DefaultVLIWScheduler</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a629982ca3ef5632e63f32b5682fde927">llvm::ScheduleDAGMI::ScheduleDAGMI</a> and <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a682039af4aa49f562ba74775bc32b1c4">llvm::SwingSchedulerDAG::SwingSchedulerDAG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ScheduleDAGInstrs() {#a55ec5f63fd13f77063e0fc05a722283a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ScheduleDAGInstrs::~ScheduleDAGInstrs ()</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addEdge() {#a86bfa4838cb7e42648615d27c94c8017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScheduleDAGInstrs::addEdge (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SuccSU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; PredDep)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a DAG edge to the given SU with the given predecessor dependence data.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the edge may be added without creating a cycle OR if an equivalent edge already existed (false indicates failure).</p></dd>
</dl>


<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 1219 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#af92bf49ed4846e026e68c380d74d7b15">llvm::SUnit::addPred</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a75b245e9ae0e3d67d8485468580f360f">llvm::SDep::isArtificial</a> and <a href="#a8cd3eede9e2a32c7139cc5c7c481e08b">Topo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/callmutation/#a6cd9122ce8216f80dd0921f844f7b7e1">llvm::HexagonSubtarget::CallMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvvectormaskdagmutation/#aefb8f35660662022da36962fb6655058">llvm::RISCVVectorMaskDAGMutation::apply</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuexportclustering-cpp-/#a07b42c1e90cefebe812ba65deb791e95">anonymous{AMDGPUExportClustering.cpp}::buildCluster</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a54fbbf29fc459bb243a1a43fb2ab9c1a">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::clusterNeighboringMemOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a632225d89acaea2e95ea6f71b19d3ecf">llvm::fuseInstructionPair</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuexportclustering-cpp-/#ac88025eb8866478014f41b34cd29b593">anonymous{AMDGPUExportClustering.cpp}::removeExportDependencies</a>.</p>

</div>
</div>

### addSchedBarrierDeps() {#ae8625c1e6c9bc82f2eaef39d3fff65a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::addSchedBarrierDeps ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds dependencies from instructions in the current list of instructions being scheduled to scheduling barrier.</p>


<p>We want to make sure instructions which define registers that are either used by the terminator or are live-out are properly scheduled. This is especially important when the definition latency of the return value(s) are too high to be hidden by the branch or when the liveout registers used by instructions in the fallthrough block.</p>


<p>Declaration at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="#a0f958ee7dc9902af4093fe8fabbabd6e">addVRegUseDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a3daf8e155bf0aa3e65b5260bfe3698c5">llvm::MachineInstr::all_uses</a>, <a href="#a254403f7804208ade3cb68086201cb7a">BB</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a2dbc79cfed570a9127d2853385162bdf">llvm::MachineInstr::isBarrier</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a30e7d619f3195fd890116da8b3ed6bab">llvm::MachineInstr::isCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator/#a73b0d1192402b944dbc7aac0db77258d">llvm::MCRegUnitMaskIterator::isValid</a>, <a href="#ae81ad8ece7681af658742f6d4e2fcfb1">RegionBegin</a>, <a href="#a3f74b283acf0dfb537bc387e49344f04">RegionEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9256279285c60fce1b2eb1b928599461">llvm::skipDebugInstructionsBackward</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a> and <a href="#abc7a356b097ebfec45c1f663a4e52575">Uses</a>.</p>


<p>Referenced by <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>.</p>

</div>
</div>

### begin() {#ab50b64c518a7455daf3e0bc87aee5514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::ScheduleDAGInstrs::begin ()</td>
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

<p>Returns an iterator to the top of the current scheduling region.</p>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Reference <a href="#ae81ad8ece7681af658742f6d4e2fcfb1">RegionBegin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#af6b0c8c54226e0aafa107e5e92c813a2">anonymous{MachineScheduler.cpp}::CopyConstrain::apply</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a332194da83580c976d9259717176ae8c">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::enterRegion</a>, <a href="#ae8727d434d20639d563849891f5ca1e1">enterRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a78e3672daf3301153eac2266dbc32885">llvm::ScheduleDAGMI::enterRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a34481791fdd8f5d9131431cb0a1a0c01">llvm::ScheduleDAGMILive::enterRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a5d7e71cf32573e6b1762b5a1d82a1cf5">llvm::ScheduleDAGMI::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a1583ce23a69e8a1b4af8065e2019c75f">llvm::ScheduleDAGMILive::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>.</p>

</div>
</div>

### buildSchedGraph() {#ab580983de4f7b69ebcca992be9cb3223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::buildSchedGraph (<a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> * AA, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> * RPTracker=nullptr, <a href="/web-llvm/docs/api/classes/llvm/pressurediffs">PressureDiffs</a> * PDiffs=nullptr, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS=nullptr, bool TrackLaneMasks=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Builds SUnits for the current region.</p>


<p>If <span class="doxyComputerOutput">RPTracker</span> is non-null, compute register pressure as a side effect. The DAG builder is an efficient place to do it because it already visits operands.</p>


<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 735 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="#ae07229f0bfadc988528dbf976f65c0bb">AAForDep</a>, <a href="#a2cfd9da0e5724aa91bf1767dc1e2515e">addBarrierChain</a>, <a href="#a48e69d6ef017966f2a55dbf4d1d0b193">addChainDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurediffs/#aa61bffce687c1adbbd0a96f292496128">llvm::PressureDiffs::addInstruction</a>, <a href="#a2e9425c046cf742bfbb9ebb96466d8e5">addPhysRegDeps</a>, <a href="#ae8625c1e6c9bc82f2eaef39d3fff65a8">addSchedBarrierDeps</a>, <a href="#a10acc9310a21d9a8191d3d84916bdffb">addVRegDefDeps</a>, <a href="#a0f958ee7dc9902af4093fe8fabbabd6e">addVRegUseDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a8affa4b2a934ff08aa04e63253a00126">llvm::RegisterOperands::adjustLaneLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a551060cb0333d9d0cfdacd2576d817b9a8afafe9e6f4c2fb9744242a6b369a0f1">llvm::SDep::Artificial</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a948f446009b83c0bca40324131e27868">BarrierChain</a>, <a href="#a2ad332011e2040d133de24f33cf3f4cd">CanHandleTerminators</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a20e10e20ded7655f844479a648aa0c66">llvm::ScheduleDAG::clearDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a74e0a918c9705f23a1e5b66f68cc97e9">llvm::RegisterOperands::collect</a>, <a href="#aae8addb45cc64764371ace084b48dc51">CurrentVRegDefs</a>, <a href="#a417ece2bf0f001181401c6c6b210194a">CurrentVRegUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a6837fb2c08f4c8c986a4689a37ca93cf">DbgValues</a>, <a href="#aaa916ccdc8e2490104520c6d65861e90">Defs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a5a87a80da6ca662edcabf8f7edb780c4">EnableAASchedMI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a>, <a href="#a25ae020b571d18d34d03097d91ca0f40">FirstDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6f3043b29023d270fc4bc5062dff7cee">llvm::LiveIntervals::getInstructionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a8743b2c5c27035fa002ef69e9df50c72">llvm::RegPressureTracker::getPos</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a78ba5d2730fb5abfc232b99e30ad1a31">getReductionSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a26a2097fa7f267ce29202d37048c4a1c">getUnderlyingObjectsForInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a613d1bf0711c46bd9becb5c22e955567">HugeRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurediffs/#adc55f26c1bfbbe17074ded7275f3961c">llvm::PressureDiffs::init</a>, <a href="#a705a0975de8335b0b6bdbbae165e8f5c">initSUnits</a>, <a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap/#a0b589d5a5454606a0a9024a106844cf1">llvm::ScheduleDAGInstrs::Value2SUsMap::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a72e0568b7bf0e9a97260c34264a549a0">llvm::SUnit::Latency</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="#af2cd9b498508774a2da120d08b8d67cc">MFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a077eef2c61ca462db1800cc506092d38">MISUnitMap</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a1b09f4d9c91e25f7bc2ac60b3b929d11">llvm::ScheduleDAG::MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a1a6c1a29019b8f3fd988359ec5dd3d2f">llvm::SUnit::NumSuccs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3be9857a09c82046b77a71918b5e214f">llvm::MachineOperand::readsReg</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a20a8136fbbb55939ae03e734232ce942">llvm::RegPressureTracker::recede</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a354c230443b1586633f5697aec0bcd8e">llvm::RegPressureTracker::recedeSkipDebugValues</a>, <a href="#a2e28b826aaa73d2dacf89ba8f8c775d1">reduceHugeMemNodeMaps</a>, <a href="#ae81ad8ece7681af658742f6d4e2fcfb1">RegionBegin</a>, <a href="#a3f74b283acf0dfb537bc387e49344f04">RegionEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a148b76c8f993d4a3d95ac19c60e2ebe0">llvm::SDep::setLatency</a>, <a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap/#a877cc0c7417f2a791fc0d6db0ca39161">llvm::ScheduleDAGInstrs::Value2SUsMap::size</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a348590624c488b04d0f9e227e6c3960e">llvm::ScheduleDAG::TII</a>, <a href="#a8cd3eede9e2a32c7139cc5c7c481e08b">Topo</a>, <a href="#a96bb77f51ee973b0613bf5083144fa69">TrackLaneMasks</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>, <a href="#aad4b383d6bf0b66dd1a20a81505788fd">UnknownValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp/#ad59a2062ef349882aa9c631277e37a74">UseAA</a> and <a href="#abc7a356b097ebfec45c1f663a4e52575">Uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a4be5ffcd4f76d433cc753be146a872b7">llvm::ScheduleDAGMILive::buildDAGWithRegPressure</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a587988ffcc944147e5ba7da46bc77ef2">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/defaultvliwscheduler/#a72b9c4f9a9fe8ef321b387a3cfca73cd">llvm::DefaultVLIWScheduler::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a5d7e71cf32573e6b1762b5a1d82a1cf5">llvm::ScheduleDAGMI::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a87416d44c85818861fe0152759e9acb1">llvm::SwingSchedulerDAG::schedule</a>.</p>

</div>
</div>

### canAddEdge() {#ac384df17605ecce542a6d2567c7f1ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScheduleDAGInstrs::canAddEdge (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SuccSU, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * PredSU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if an edge can be added from PredSU to SuccSU without creating a cycle.</p>

<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 1215 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a> and <a href="#a8cd3eede9e2a32c7139cc5c7c481e08b">Topo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>.</p>

</div>
</div>

### doMBBSchedRegionsTopDown() {#af637149166f4dbc65315b9d6bd96e242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::ScheduleDAGInstrs::doMBBSchedRegionsTopDown ()</td>
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

<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>

</div>
</div>

### dump() {#aea2d4ef1e00ee834ab155abd18a560e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::dump ()</td>
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



<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 1186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a917f4d40ed0bbdaf4ab50e5df4de067b">llvm::ScheduleDAG::dumpNodeAll</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a521bf68518a92483130a58680716d153">llvm::ScheduleDAG::EntrySU</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smschedule/#aff7649124c08f77b72e5d539f2f8afdf">llvm::SMSchedule::finalizeSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a5d7e71cf32573e6b1762b5a1d82a1cf5">llvm::ScheduleDAGMI::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a87416d44c85818861fe0152759e9acb1">llvm::SwingSchedulerDAG::schedule</a>.</p>

</div>
</div>

### dumpNode() {#aa5f22315c4064579fca6cd88fb36ea5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::dumpNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; SU)</td>
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



<p>Declaration at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 1175 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#aa1dfdcdc657e12c47e72d9dbe251ac85">llvm::SUnit::BotReadyCycle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#accc60d2019e9dff57bb0918a94422ebb">llvm::MachineInstr::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#ac464b0883162724583f0f124c8be8157">llvm::ScheduleDAG::dumpNodeName</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#aeaac72a5f4bed72a0a3780a3cf53e2ed">SchedPrintCycles</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2a6f92b9c5aba34d3b07f3ebe229ccff">llvm::SUnit::TopReadyCycle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a01b02e76c87211e7084ec17f18a2d16f">llvm::ScheduleDAGMI::dumpSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1c51776d4e512a7f24d5b5d601c31016">llvm::ScheduleDAGMI::releasePred</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a90ffd918ef80c711049758b2064e15c4">llvm::ScheduleDAGMI::releaseSucc</a>.</p>

</div>
</div>

### end() {#a21805259f54dab47c2b3da009216996a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::ScheduleDAGInstrs::end ()</td>
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

<p>Returns an iterator to the bottom of the current scheduling region.</p>

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Reference <a href="#a3f74b283acf0dfb537bc387e49344f04">RegionEnd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#af6b0c8c54226e0aafa107e5e92c813a2">anonymous{MachineScheduler.cpp}::CopyConstrain::apply</a>, <a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap/#a849f288acb6b68b0987cb598bc36472e">llvm::ScheduleDAGInstrs::Value2SUsMap::clearList</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a332194da83580c976d9259717176ae8c">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::enterRegion</a>, <a href="#ae8727d434d20639d563849891f5ca1e1">enterRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a78e3672daf3301153eac2266dbc32885">llvm::ScheduleDAGMI::enterRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a34481791fdd8f5d9131431cb0a1a0c01">llvm::ScheduleDAGMILive::enterRegion</a>.</p>

</div>
</div>

### enterRegion() {#ae8727d434d20639d563849891f5ca1e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::enterRegion (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * bb, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> end, unsigned regioninstrs)</td>
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

<p>Initialize the DAG and common scheduler state for a new scheduling region.</p>


<p>This does not actually create the DAG, only clears it. The scheduling driver may call BuildSchedGraph multiple times per scheduling region.</p>


<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a254403f7804208ade3cb68086201cb7a">BB</a>, <a href="#ab50b64c518a7455daf3e0bc87aee5514">begin</a>, <a href="#a21805259f54dab47c2b3da009216996a">end</a>, <a href="#af1c8be2ff5fd8eab8091e6ffa40ded8d">NumRegionInstrs</a>, <a href="#ae81ad8ece7681af658742f6d4e2fcfb1">RegionBegin</a> and <a href="#a3f74b283acf0dfb537bc387e49344f04">RegionEnd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a332194da83580c976d9259717176ae8c">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::enterRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a78e3672daf3301153eac2266dbc32885">llvm::ScheduleDAGMI::enterRegion</a>.</p>

</div>
</div>

### exitRegion() {#abc5a5c32ac78a99ee2633dbbeec20397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::exitRegion ()</td>
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

<p>Called when the scheduler has finished scheduling the current region.</p>

<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a18002c24320d152edf319448c0f7843d">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::exitRegion</a>.</p>

</div>
</div>

### finalizeSchedule() {#a7c30ee6cdef3f4784c192654dcb9bab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ScheduleDAGInstrs::finalizeSchedule ()</td>
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

<p>Allow targets to perform final scheduling actions at the level of the whole <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>.</p>


<p>By default does nothing.</p>


<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnpostscheduledagmilive/#a2573535a1fb6914feb4615e6f6e1ef5d">llvm::GCNPostScheduleDAGMILive::finalizeSchedule</a>.</p>

</div>
</div>

### finishBlock() {#a1f9a4461e2c9ac06b97f55554f836d66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::finishBlock ()</td>
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

<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>Reference <a href="#a254403f7804208ade3cb68086201cb7a">BB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#ac8e3f32817edf7fbf1d4f33cc204199b">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::finishBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9ca687b69b34efab1604af98db151cbf">llvm::ScheduleDAGMI::finishBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a47f63b6ab42a97ca3b5346b6c7093b09">llvm::SwingSchedulerDAG::finishBlock</a>.</p>

</div>
</div>

### fixupKills() {#a4dc06d4fb42d48a6ade1958f76334826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::fixupKills (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fixes register kill flags that scheduling has made invalid.</p>

<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 1124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ae6876d59aeec5bc210b359fbdcf6c1ad">llvm::MachineOperand::getRegMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a55fdcb2a9df9a69067eed1bc17a0b927">llvm::MachineOperand::isRegMask</a>, <a href="#a00bf9ef6a0eb5cba9d3461711cbcc6a8">LiveRegs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a1b09f4d9c91e25f7bc2ac60b3b929d11">llvm::ScheduleDAG::MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a16297e722f8be82ffae1552bde33d061">toggleKills</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>.</p>

</div>
</div>

### getDAGName() {#a23f7a6c4d1be0ca66f44eb4aa499075a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string ScheduleDAGInstrs::getDAGName ()</td>
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

<p>Returns a label for the region of code covered by the DAG.</p>


<p>Return the basic block label.</p>


<p>It is not necessarily unique because a block contains multiple scheduling regions. But it is fine for visualization.</p>


<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 1211 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>Reference <a href="#a254403f7804208ade3cb68086201cb7a">BB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a8b7babb023cad0842f5a177e7abe3651">llvm::ScheduleDAGMI::viewGraph</a>.</p>

</div>
</div>

### getGraphNodeLabel() {#afbb37cc24abd3ed381b0fd496351bd17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string ScheduleDAGInstrs::getGraphNodeLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>Returns a label for a DAG node that points to an instruction.</p>

<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 1197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a521bf68518a92483130a58680716d153">llvm::ScheduleDAG::EntrySU</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab419785650ef9728b5305d220179017c">llvm::MachineInstr::print</a>.</p>

</div>
</div>

### getSchedClass() {#a4bf5573660c55924d68b517a0e9b4554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSchedClassDesc * llvm::ScheduleDAGInstrs::getSchedClass (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>Resolves and cache a resolved scheduling class for an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2b2c6049e5141829267f4f9193b475d4">llvm::SUnit::SchedClass</a> and <a href="#abb11b650b88a61630eba2a1b2eaa6fd0">SchedModel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a942d716003056c037d46a4144e9cf885">llvm::ScheduleDAGMI::dumpScheduleTraceBottomUp</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a3010c4b89284791284aa6e2ec510501b">llvm::ScheduleDAGMI::dumpScheduleTraceTopDown</a>, <a href="/web-llvm/docs/api/structs/llvm/schedremainder/#a55cad625d59b0f4452d893b4a25c66b6">llvm::SchedRemainder::init</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a47cc8c89db10ac27483585cd61cf4f91">llvm::GenericSchedulerBase::SchedCandidate::initResourceDelta</a> and <a href="#a705a0975de8335b0b6bdbbae165e8f5c">initSUnits</a>.</p>

</div>
</div>

### getSchedModel() {#a3f70979bd43329e7ad53ad796db8112f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSchedModel * llvm::ScheduleDAGInstrs::getSchedModel ()</td>
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

<p>Gets the machine model for instruction scheduling.</p>

<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Reference <a href="#abb11b650b88a61630eba2a1b2eaa6fd0">SchedModel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/igrouplpdagmutation/#a80af98abec842dd9dd5261853ec76735">anonymous{AMDGPUIGroupLP.cpp}::IGroupLPDAGMutation::apply</a>.</p>

</div>
</div>

### getSUnit() {#ab75cd37a7a0319d5a4c77189cca106ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * llvm::ScheduleDAGInstrs::getSUnit (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Returns an existing <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> for this MI, or nullptr.</p>

<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a077eef2c61ca462db1800cc506092d38">MISUnitMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuexportclustering-cpp-/exportclustering/#a3432dbdb86f0a5f40c9d3bcfd8633b28">anonymous{AMDGPUExportClustering.cpp}::ExportClustering::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a3fa089137317e93276cab5774d4bf11f">llvm::SwingSchedulerDAG::applyInstrChange</a>, <a href="/web-llvm/docs/api/classes/llvm/windowscheduler/#a5722fabe6420b0f87a3eb1160979e5f7">llvm::WindowScheduler::calculateMaxCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a01b02e76c87211e7084ec17f18a2d16f">llvm::ScheduleDAGMI::dumpSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a942d716003056c037d46a4144e9cf885">llvm::ScheduleDAGMI::dumpScheduleTraceBottomUp</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a3010c4b89284791284aa6e2ec510501b">llvm::ScheduleDAGMI::dumpScheduleTraceTopDown</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae6911f11b05121e2c0deb7e45a6de110">llvm::SMSchedule::isLoopCarried</a> and <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a87416d44c85818861fe0152759e9acb1">llvm::SwingSchedulerDAG::schedule</a>.</p>

</div>
</div>

### IsReachable() {#aa79589a56769cd108d08e21544be1420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScheduleDAGInstrs::IsReachable (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * TargetSU)</td>
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

<p>IsReachable - Checks if SU is reachable from TargetSU.</p>

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Reference <a href="#a8cd3eede9e2a32c7139cc5c7c481e08b">Topo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a54fbbf29fc459bb243a1a43fb2ab9c1a">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::clusterNeighboringMemOps</a>.</p>

</div>
</div>

### newSUnit() {#a6c497ec4b863f7d59aa3678740331c8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * llvm::ScheduleDAGInstrs::newSUnit (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Creates a new <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> and return a ptr to it.</p>

<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>


<p>Referenced by <a href="#a705a0975de8335b0b6bdbbae165e8f5c">initSUnits</a>.</p>

</div>
</div>

### schedule() {#ac0cecc651db330128468e08794794f5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ScheduleDAGInstrs::schedule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Orders nodes according to selected style.</p>


<p>Typically, a scheduling algorithm will implement <a href="#ac0cecc651db330128468e08794794f5c">schedule()</a> without overriding <a href="#ae8727d434d20639d563849891f5ca1e1">enterRegion()</a> or <a href="#abc5a5c32ac78a99ee2633dbbeec20397">exitRegion()</a>.</p>


<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>

</div>
</div>

### setDumpDirection() {#afdb896a30eb0e9fc3143fe6c447570cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ScheduleDAGInstrs::setDumpDirection (<a href="#a8d1f67b9f6d31b169c0d4b1d2080b4e7">DumpDirection</a> D)</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="#ab3c913205add9c73e6bfe3540749737e">DumpDir</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a78e3672daf3301153eac2266dbc32885">llvm::ScheduleDAGMI::enterRegion</a>.</p>

</div>
</div>

### startBlock() {#a2822215b7634783aece96ef695a72f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::startBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
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

<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>Reference <a href="#a254403f7804208ade3cb68086201cb7a">BB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a6e1de828f5638a8e88f579d837540094">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::startBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a19c5e2b675721f465bc85a5f58e7c084">llvm::ScheduleDAGMI::startBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addBarrierChain() {#a2cfd9da0e5724aa91bf1767dc1e2515e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::addBarrierChain (<a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap">Value2SUsMap</a> &amp; map)</td>
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

<p>Adds barrier chain edges from all SUs in map, and then clear the map.</p>


<p>This is equivalent to <a href="#ac483efdc6c5ab7a20f776b77f986b6cf">insertBarrierChain()</a>, but optimized for the common case where the new BarrierChain (a global memory object) has a higher NodeNum than all SUs in map. It is assumed BarrierChain has been set before calling this.</p>


<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 691 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a948f446009b83c0bca40324131e27868">BarrierChain</a> and <a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap/#a62b8ec9cd0b46fe7a2a1d3cb3f9e6cf5">llvm::ScheduleDAGInstrs::Value2SUsMap::clear</a>.</p>


<p>Referenced by <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>.</p>

</div>
</div>

### addChainDependencies() {#a48e69d6ef017966f2a55dbf4d1d0b193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ScheduleDAGInstrs::addChainDependencies (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="#a8e1e9d0b1c64c405c0e99288f9225bd5">SUList</a> &amp; SUs, unsigned Latency)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds dependencies as needed from all SUs in list to SU.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>References <a href="#aee33e06ea8865a2fb2bf229325c07194">addChainDependency</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a2d68d32ff95cd10b4899c2823ec28e97">llvm::Latency</a>.</p>


<p>Referenced by <a href="#afe11e438e3ecc0381047e0e01958fea0">addChainDependencies</a>, <a href="#a14962363da4c4a48ad6646cb05f49b77">addChainDependencies</a> and <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>.</p>

</div>
</div>

### addChainDependencies() {#afe11e438e3ecc0381047e0e01958fea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::addChainDependencies (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap">Value2SUsMap</a> &amp; Val2SUsMap)</td>
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

<p>Adds dependencies as needed from all SUs in map, to SU.</p>

<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="#a48e69d6ef017966f2a55dbf4d1d0b193">addChainDependencies</a>, <a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap/#adff804a02fa1af4d4192309a8d4df8eb">llvm::ScheduleDAGInstrs::Value2SUsMap::getTrueMemOrderLatency</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### addChainDependencies() {#a14962363da4c4a48ad6646cb05f49b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::addChainDependencies (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap">Value2SUsMap</a> &amp; Val2SUsMap, <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a> V)</td>
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

<p>Adds dependencies as needed to SU, from all SUs mapped to V.</p>

<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 682 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="#a48e69d6ef017966f2a55dbf4d1d0b193">addChainDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a0881334358ff6ff7ff8cea5562c7988e">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a6b0c3e15c351ba9682837c29b0a141b6">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::find</a> and <a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap/#adff804a02fa1af4d4192309a8d4df8eb">llvm::ScheduleDAGInstrs::Value2SUsMap::getTrueMemOrderLatency</a>.</p>

</div>
</div>

### addChainDependency() {#aee33e06ea8865a2fb2bf229325c07194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::addChainDependency (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SUa, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SUb, unsigned Latency=0)</td>
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

<p>Adds a chain edge between SUa and SUb, but only if both <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> and <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> fail to deny the dependency.</p>

<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#af92bf49ed4846e026e68c380d74d7b15">llvm::SUnit::addPred</a>, <a href="#a954c0aedb37bd7682d2d586026c5c483">getAAForDep</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a2d68d32ff95cd10b4899c2823ec28e97">llvm::Latency</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a3da773a37ef4e3325379dd6718317b74">llvm::MachineInstr::mayAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a551060cb0333d9d0cfdacd2576d817b9aa34e7b539ffb2975952fd58cbb2b75c2">llvm::SDep::MayAliasMem</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a148b76c8f993d4a3d95ac19c60e2ebe0">llvm::SDep::setLatency</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a85e6100733f4ae2c0946eeab33a9086c">UseTBAA</a>.</p>


<p>Referenced by <a href="#a48e69d6ef017966f2a55dbf4d1d0b193">addChainDependencies</a>.</p>

</div>
</div>

### addPhysRegDataDeps() {#a56fbc3f460289602ce8a51538ebc1e26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::addPhysRegDataDeps (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, unsigned OperIdx)</td>
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

<p>MO is an operand of SU's instruction that defines a physical register.</p>


<p>Adds data dependencies from SU to any uses of the physical register.</p>


<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#af92bf49ed4846e026e68c380d74d7b15">llvm::SUnit::addPred</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a551060cb0333d9d0cfdacd2576d817b9a8afafe9e6f4c2fb9744242a6b369a0f1">llvm::SDep::Artificial</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a75a5f7e3b3d4ec79610b4e556d2f35ce">llvm::MachineInstr::getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0ca904e64ee29c8812ed34e632d3c947">llvm::MCInstrDesc::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#aff7ca9d0ebf8c95da4ddd5bf28ac2e0a">llvm::MCInstrDesc::hasImplicitDefOfPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#ae5ac9abaa969c4e2801c8c4cdf1dde72">llvm::MCInstrDesc::hasImplicitUseOfPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a9d9a8b8d5225f85cecbbada4ce4406b0">llvm::SUnit::hasPhysRegDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="#abb11b650b88a61630eba2a1b2eaa6fd0">SchedModel</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a148b76c8f993d4a3d95ac19c60e2ebe0">llvm::SDep::setLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a02230ca194a9c8e52170cc7c426decb2">UseReg</a> and <a href="#abc7a356b097ebfec45c1f663a4e52575">Uses</a>.</p>


<p>Referenced by <a href="#a2e9425c046cf742bfbb9ebb96466d8e5">addPhysRegDeps</a>.</p>

</div>
</div>

### addPhysRegDeps() {#a2e9425c046cf742bfbb9ebb96466d8e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::addPhysRegDeps (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, unsigned OperIdx)</td>
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

<p>Adds register dependencies (data, anti, and output) from this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> to following instructions in the same scheduling region that depend the physical register referenced at OperIdx.</p>

<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="#a56fbc3f460289602ce8a51538ebc1e26">addPhysRegDataDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#af92bf49ed4846e026e68c380d74d7b15">llvm::SUnit::addPred</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">llvm::SDep::Anti</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aaa916ccdc8e2490104520c6d65861e90">Defs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#adc4d8df3725fd70ffbaffeead756025c">llvm::SUnit::hasPhysRegUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a0be1f84d53e90c247d75f2ed63636761">llvm::SUnit::isCall</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a1b09f4d9c91e25f7bc2ac60b3b929d11">llvm::ScheduleDAG::MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732a011a1d87822a7f70efee9e430a7ccc36">llvm::SDep::Output</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#adf7cb9b8e5dda7b42273e79048f1b8b3">RemoveKillFlags</a>, <a href="#abb11b650b88a61630eba2a1b2eaa6fd0">SchedModel</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8a82683fccdef8a5ef772ef03277aee7">llvm::MachineOperand::setIsKill</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a148b76c8f993d4a3d95ac19c60e2ebe0">llvm::SDep::setLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a> and <a href="#abc7a356b097ebfec45c1f663a4e52575">Uses</a>.</p>


<p>Referenced by <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>.</p>

</div>
</div>

### addVRegDefDeps() {#a10acc9310a21d9a8191d3d84916bdffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::addVRegDefDeps (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, unsigned OperIdx)</td>
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

<p>Adds register output and data dependencies from this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> to instructions that occur later in the same scheduling region if they read from or write to the virtual register defined at OperIdx.</p>


<p>TODO: Hoist loop induction variable increments. This has to be reevaluated. Generally, IV scheduling should be done before coalescing.</p>


<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#af92bf49ed4846e026e68c380d74d7b15">llvm::SUnit::addPred</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a72988cca7ab2262ef68fdd0c5ae54940">llvm::LaneBitmask::any</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aae8addb45cc64764371ace084b48dc51">CurrentVRegDefs</a>, <a href="#a417ece2bf0f001181401c6c6b210194a">CurrentVRegUses</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="#afb8c24d6929051d24b35af1ef0550e54">deadDefHasNoUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="#a643ff7dd8c287dd58e75cbe79556e74c">getLaneMaskForMO</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a1b09f4d9c91e25f7bc2ac60b3b929d11">llvm::ScheduleDAG::MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64stacktagging-cpp/#a8e818224d2d1de9b995783ff897b0083ab7e4e0120a041dbe6528b050c04269e0">none</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732a011a1d87822a7f70efee9e430a7ccc36">llvm::SDep::Output</a>, <a href="#abb11b650b88a61630eba2a1b2eaa6fd0">SchedModel</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab979122f21b7fa46d3d2d9b21983068b">llvm::MachineOperand::setIsUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a148b76c8f993d4a3d95ac19c60e2ebe0">llvm::SDep::setLatency</a> and <a href="#a96bb77f51ee973b0613bf5083144fa69">TrackLaneMasks</a>.</p>


<p>Referenced by <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>.</p>

</div>
</div>

### addVRegUseDeps() {#a0f958ee7dc9902af4093fe8fabbabd6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::addVRegUseDeps (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, unsigned OperIdx)</td>
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

<p>Adds a register data dependency if the instruction that defines the virtual register used at OperIdx is mapped to an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>


<p>Add a register antidependency from this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> to instructions that occur later in the same scheduling region if they write the virtual register.</p>


<p>TODO: Handle ExitSU "uses" properly.</p>


<p>Declaration at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">llvm::SDep::Anti</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aae8addb45cc64764371ace084b48dc51">CurrentVRegDefs</a>, <a href="#a417ece2bf0f001181401c6c6b210194a">CurrentVRegUses</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="#a643ff7dd8c287dd58e75cbe79556e74c">getLaneMaskForMO</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64stacktagging-cpp/#a8e818224d2d1de9b995783ff897b0083ab7e4e0120a041dbe6528b050c04269e0">none</a> and <a href="#a96bb77f51ee973b0613bf5083144fa69">TrackLaneMasks</a>.</p>


<p>Referenced by <a href="#ae8625c1e6c9bc82f2eaef39d3fff65a8">addSchedBarrierDeps</a> and <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>.</p>

</div>
</div>

### deadDefHasNoUse() {#afb8c24d6929051d24b35af1ef0550e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScheduleDAGInstrs::deadDefHasNoUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
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

<p>Returns true if the def register in <span class="doxyComputerOutput">MO</span> has no uses.</p>

<p>Declaration at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="#a417ece2bf0f001181401c6c6b210194a">CurrentVRegUses</a>, <a href="#a643ff7dd8c287dd58e75cbe79556e74c">getLaneMaskForMO</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>.</p>


<p>Referenced by <a href="#a10acc9310a21d9a8191d3d84916bdffb">addVRegDefDeps</a>.</p>

</div>
</div>

### getAAForDep() {#a954c0aedb37bd7682d2d586026c5c483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BatchAAResults * llvm::ScheduleDAGInstrs::getAAForDep ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a (possibly null) pointer to the current <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a>.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Reference <a href="#ae07229f0bfadc988528dbf976f65c0bb">AAForDep</a>.</p>


<p>Referenced by <a href="#aee33e06ea8865a2fb2bf229325c07194">addChainDependency</a>.</p>

</div>
</div>

### getLaneMaskForMO() {#a643ff7dd8c287dd58e75cbe79556e74c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask ScheduleDAGInstrs::getLaneMaskForMO (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
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

<p>Returns a mask for which lanes get read/written by the given (register) machine operand.</p>

<p>Declaration at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#ac4b4e4e2660b0fcd4f92c1d35c29d1c0">llvm::TargetRegisterClass::getLaneMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a5f091eb46b984dbf525c6ac041f6af95">llvm::TargetRegisterClass::HasDisjunctSubRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a1b09f4d9c91e25f7bc2ac60b3b929d11">llvm::ScheduleDAG::MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>.</p>


<p>Referenced by <a href="#a10acc9310a21d9a8191d3d84916bdffb">addVRegDefDeps</a>, <a href="#a0f958ee7dc9902af4093fe8fabbabd6e">addVRegUseDeps</a> and <a href="#afb8c24d6929051d24b35af1ef0550e54">deadDefHasNoUse</a>.</p>

</div>
</div>

### initSUnits() {#a705a0975de8335b0b6bdbbae165e8f5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::initSUnits ()</td>
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

<p>Creates an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> for each real instruction, numbered in top-down topological order.</p>


<p>The instruction order A &lt; B, implies that no edge exists from B to A.</p>


<p>Map each real instruction to its <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>


<p>After initSUnits, the SUnits vector cannot be resized and the scheduler may hang onto <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> pointers. We may relax this in the future by using <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> IDs instead of pointers.</p>


<p>MachineScheduler relies on initSUnits numbering the nodes by their order in the original instruction list.</p>


<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="#a4bf5573660c55924d68b517a0e9b4554">getSchedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ab76e4a602699ddc57019efaba62a92b6">llvm::SUnit::hasReservedResource</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a0be1f84d53e90c247d75f2ed63636761">llvm::SUnit::isCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ace667b502d54c947cf2f3a4c5d60f734">llvm::SUnit::isCommutable</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a4ac4d36cb59a4bbf5d93513dad0ff0e9">llvm::SUnit::isUnbuffered</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a72e0568b7bf0e9a97260c34264a549a0">llvm::SUnit::Latency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a077eef2c61ca462db1800cc506092d38">MISUnitMap</a>, <a href="#a6c497ec4b863f7d59aa3678740331c8e">newSUnit</a>, <a href="#af1c8be2ff5fd8eab8091e6ffa40ded8d">NumRegionInstrs</a>, <a href="#ae81ad8ece7681af658742f6d4e2fcfb1">RegionBegin</a>, <a href="#a3f74b283acf0dfb537bc387e49344f04">RegionEnd</a>, <a href="#abb11b650b88a61630eba2a1b2eaa6fd0">SchedModel</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>


<p>Referenced by <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>.</p>

</div>
</div>

### insertBarrierChain() {#ac483efdc6c5ab7a20f776b77f986b6cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::insertBarrierChain (<a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap">Value2SUsMap</a> &amp; map)</td>
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

<p>Inserts a barrier chain in a huge region, far below current SU.</p>


<p>Adds barrier chain edges from all SUs in map with higher NodeNums than this new BarrierChain, and remove them from map. It is assumed BarrierChain has been set before calling this.</p>


<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a948f446009b83c0bca40324131e27868">BarrierChain</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#aa610cab7ee61e36a6d1d122fc252c278">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a0881334358ff6ff7ff8cea5562c7988e">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap/#a033628dbd3a02473543d533b5987f538">llvm::ScheduleDAGInstrs::Value2SUsMap::reComputeSize</a> and <a href="/web-llvm/docs/api/classes/llvm/mapvector/#aaf31a8aa98ad9fb33f2aeb5af238012f">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::remove_if</a>.</p>


<p>Referenced by <a href="#a2e28b826aaa73d2dacf89ba8f8c775d1">reduceHugeMemNodeMaps</a>.</p>

</div>
</div>

### reduceHugeMemNodeMaps() {#a2e28b826aaa73d2dacf89ba8f8c775d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGInstrs::reduceHugeMemNodeMaps (<a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap">Value2SUsMap</a> &amp; stores, <a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap">Value2SUsMap</a> &amp; loads, unsigned N)</td>
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

<p>Reduces maps in FIFO order, by N SUs.</p>


<p>This is better than turning every Nth memory SU into BarrierChain in <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph()</a>, since it avoids unnecessary edges between seen SUs above the new BarrierChain, and those below it.</p>


<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>, definition at line 1055 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a948f446009b83c0bca40324131e27868">BarrierChain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac483efdc6c5ab7a20f776b77f986b6cf">insertBarrierChain</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloadstorewidening-cpp/#a5414f76815c8f01cd360c99ff6fb27a7">loads</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloadstorewidening-cpp/#a7d2c711a42f51c1f7b3ce3f8f560fa74">stores</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>


<p>Referenced by <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AAForDep {#ae07229f0bfadc988528dbf976f65c0bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;BatchAAResults&gt; llvm::ScheduleDAGInstrs::AAForDep</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a> and <a href="#a954c0aedb37bd7682d2d586026c5c483">getAAForDep</a>.</p>

</div>
</div>

### BarrierChain {#a948f446009b83c0bca40324131e27868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit* llvm::ScheduleDAGInstrs::BarrierChain = nullptr</td>
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

<p>Remember a generic side-effecting instruction as we proceed.</p>


<p>No other SU ever gets scheduled around it (except in the special case of a huge region that gets reduced).</p>


<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#a2cfd9da0e5724aa91bf1767dc1e2515e">addBarrierChain</a>, <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>, <a href="#ac483efdc6c5ab7a20f776b77f986b6cf">insertBarrierChain</a> and <a href="#a2e28b826aaa73d2dacf89ba8f8c775d1">reduceHugeMemNodeMaps</a>.</p>

</div>
</div>

### BB {#a254403f7804208ade3cb68086201cb7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::ScheduleDAGInstrs::BB = nullptr</td>
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

<p>The block in which to insert instructions.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#ae8625c1e6c9bc82f2eaef39d3fff65a8">addSchedBarrierDeps</a>, <a href="/web-llvm/docs/api/classes/gcniterativescheduler/builddag/#a87dad70f563f1f17bc834fe2a70cb209">llvm::GCNIterativeScheduler::BuildDAG::BuildDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a4be5ffcd4f76d433cc753be146a872b7">llvm::ScheduleDAGMILive::buildDAGWithRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a942d716003056c037d46a4144e9cf885">llvm::ScheduleDAGMI::dumpScheduleTraceBottomUp</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a3010c4b89284791284aa6e2ec510501b">llvm::ScheduleDAGMI::dumpScheduleTraceTopDown</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#ab9c7e76fda2b142c09da3ca892884acd">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a0fdf731113f2b02fd779a07e4d433717">llvm::GCNIterativeScheduler::enterRegion</a>, <a href="#ae8727d434d20639d563849891f5ca1e1">enterRegion</a>, <a href="#a1f9a4461e2c9ac06b97f55554f836d66">finishBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#ab4ab68f9751f02633860848cb2e9b63d">llvm::SIScheduleDAGMI::getBB</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#a7c141a62b7a2ca52832410d948ada2c0">llvm::VLIWMachineScheduler::getBBSize</a>, <a href="#a23f7a6c4d1be0ca66f44eb4aa499075a">getDAGName</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a86daf2b1fb72fdd9a8785a4042ac1457">llvm::ScheduleDAGMILive::initRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#ab6c5bda21b39ff9494fc2661de4aa974">llvm::SIScheduleDAGMI::initRPTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a2209b15a069023499cc665b373e67703">llvm::ScheduleDAGMI::moveInstruction</a>, <a href="/web-llvm/docs/api/classes/gcniterativescheduler/overridelegacystrategy/#af81b98ad3eb158abad6175391f4ed6c3">llvm::GCNIterativeScheduler::OverrideLegacyStrategy::OverrideLegacyStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac2dafe98c88d43b256622413886e2152">llvm::ScheduleDAGMI::placeDebugValues</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a66dc7adbddb415df7082c38835b96372">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::SchedulePostRATDList</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ad899858c4b90e464815c32a7f9c4bb26">llvm::GCNIterativeScheduler::scheduleRegion</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a6e1de828f5638a8e88f579d837540094">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::startBlock</a>, <a href="#a2822215b7634783aece96ef695a72f1d">startBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a91251ec06d557b21578095955b7b7fa7">llvm::ScheduleDAGMILive::updatePressureDiffs</a>.</p>

</div>
</div>

### CanHandleTerminators {#a2ad332011e2040d133de24f33cf3f4cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScheduleDAGInstrs::CanHandleTerminators = false</td>
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

<p>The standard DAG builder does not normally include terminators as DAG nodes because it does not create the necessary dependencies to prevent reordering.</p>


<p>A specialized scheduler can override <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ad071e937f4986e51fd3fd54b10888894">TargetInstrInfo::isSchedulingBoundary</a> then enable this flag to indicate it has taken responsibility for scheduling the terminator correctly.</p>


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a> and <a href="/web-llvm/docs/api/classes/llvm/defaultvliwscheduler/#a7c1a62bfba2908fff478bff6b2242d23">llvm::DefaultVLIWScheduler::DefaultVLIWScheduler</a>.</p>

</div>
</div>

### CurrentVRegDefs {#aae8addb45cc64764371ace084b48dc51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VReg2SUnitMultiMap llvm::ScheduleDAGInstrs::CurrentVRegDefs</td>
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

<p>Tracks the last instruction(s) in this region defining each virtual register.</p>


<p>There may be multiple current definitions for a register with disjunct lanemasks.</p>


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#a10acc9310a21d9a8191d3d84916bdffb">addVRegDefDeps</a>, <a href="#a0f958ee7dc9902af4093fe8fabbabd6e">addVRegUseDeps</a> and <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>.</p>

</div>
</div>

### CurrentVRegUses {#a417ece2bf0f001181401c6c6b210194a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VReg2SUnitOperIdxMultiMap llvm::ScheduleDAGInstrs::CurrentVRegUses</td>
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

<p>Tracks the last instructions in this region using each virtual register.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#a10acc9310a21d9a8191d3d84916bdffb">addVRegDefDeps</a>, <a href="#a0f958ee7dc9902af4093fe8fabbabd6e">addVRegUseDeps</a>, <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a> and <a href="#afb8c24d6929051d24b35af1ef0550e54">deadDefHasNoUse</a>.</p>

</div>
</div>

### DbgValues {#a6837fb2c08f4c8c986a4689a37ca93cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgValueVector llvm::ScheduleDAGInstrs::DbgValues</td>
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

<p>Remember instruction that precedes DBG_VALUE.</p>


<p>These are generated by buildSchedGraph but persist so they can be referenced when emitting the final schedule.</p>


<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#af7c58c4a38a2148e0a6eec44b8749bbb">llvm::GCNIterativeScheduler::detachSchedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#ab9c7e76fda2b142c09da3ca892884acd">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac2dafe98c88d43b256622413886e2152">llvm::ScheduleDAGMI::placeDebugValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a587988ffcc944147e5ba7da46bc77ef2">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::schedule</a> and <a href="#a5bcb745a3e78c329d1431608b1f51c25">ScheduleDAGInstrs</a>.</p>

</div>
</div>

### Defs {#aaa916ccdc8e2490104520c6d65861e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegUnit2SUnitsMap llvm::ScheduleDAGInstrs::Defs</td>
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

<p>Defs, Uses - Remember where defs and uses of each register are as we iterate upward through the instructions.</p>


<p>This is allocated here instead of inside BuildSchedGraph to avoid the need for it to be initialized and destructed for each block.</p>


<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#a2e9425c046cf742bfbb9ebb96466d8e5">addPhysRegDeps</a> and <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>.</p>

</div>
</div>

### DumpDir {#ab3c913205add9c73e6bfe3540749737e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DumpDirection llvm::ScheduleDAGInstrs::DumpDir = <a href="#a8d1f67b9f6d31b169c0d4b1d2080b4e7a79bebac6c64e00c788ab9aff723c504a">NotSet</a></td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a01b02e76c87211e7084ec17f18a2d16f">llvm::ScheduleDAGMI::dumpSchedule</a> and <a href="#afdb896a30eb0e9fc3143fe6c447570cb">setDumpDirection</a>.</p>

</div>
</div>

### FirstDbgValue {#a25ae020b571d18d34d03097d91ca0f40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* llvm::ScheduleDAGInstrs::FirstDbgValue = nullptr</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#af7c58c4a38a2148e0a6eec44b8749bbb">llvm::GCNIterativeScheduler::detachSchedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#ab9c7e76fda2b142c09da3ca892884acd">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::EmitSchedule</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac2dafe98c88d43b256622413886e2152">llvm::ScheduleDAGMI::placeDebugValues</a>.</p>

</div>
</div>

### LiveRegs {#a00bf9ef6a0eb5cba9d3461711cbcc6a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegUnits llvm::ScheduleDAGInstrs::LiveRegs</td>
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

<p>Set of live physical registers for updating kill flags.</p>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#a4dc06d4fb42d48a6ade1958f76334826">fixupKills</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a16297e722f8be82ffae1552bde33d061">toggleKills</a>.</p>

</div>
</div>

### MFI {#af2cd9b498508774a2da120d08b8d67cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFrameInfo&amp; llvm::ScheduleDAGInstrs::MFI</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>, <a href="#a5bcb745a3e78c329d1431608b1f51c25">ScheduleDAGInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a424a74f8852d22b010e48f8f6d0c748d">llvm::GCNIterativeScheduler::scheduleILP</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a9d479174d357214e5ea495943b55fdd2">llvm::GCNIterativeScheduler::scheduleLegacyMaxOccupancy</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ab7d457cdee60c23701eca3d110a4862f">llvm::GCNIterativeScheduler::scheduleMinReg</a> and <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a6fd0550f564608fec7c5d7f25817ddef">llvm::GCNIterativeScheduler::tryMaximizeOccupancy</a>.</p>

</div>
</div>

### MISUnitMap {#a077eef2c61ca462db1800cc506092d38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineInstr*, SUnit*&gt; llvm::ScheduleDAGInstrs::MISUnitMap</td>
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

<p>After calling BuildSchedGraph, each machine instruction in the current scheduling region is mapped to an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a3fa089137317e93276cab5774d4bf11f">llvm::SwingSchedulerDAG::applyInstrChange</a>, <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a51bda1806219d879123625c8d4ae3fbc">llvm::SwingSchedulerDAG::fixupRegisterOverlaps</a>, <a href="#ab75cd37a7a0319d5a4c77189cca106ec">getSUnit</a> and <a href="#a705a0975de8335b0b6bdbbae165e8f5c">initSUnits</a>.</p>

</div>
</div>

### MLI {#ad2b3e1939f6f39819ad55c714deefad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineLoopInfo* llvm::ScheduleDAGInstrs::MLI = nullptr</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/defaultvliwscheduler/#a7c1a62bfba2908fff478bff6b2242d23">llvm::DefaultVLIWScheduler::DefaultVLIWScheduler</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>, <a href="#a5bcb745a3e78c329d1431608b1f51c25">ScheduleDAGInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a629982ca3ef5632e63f32b5682fde927">llvm::ScheduleDAGMI::ScheduleDAGMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a66dc7adbddb415df7082c38835b96372">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::SchedulePostRATDList</a> and <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a682039af4aa49f562ba74775bc32b1c4">llvm::SwingSchedulerDAG::SwingSchedulerDAG</a>.</p>

</div>
</div>

### NumRegionInstrs {#af1c8be2ff5fd8eab8091e6ffa40ded8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScheduleDAGInstrs::NumRegionInstrs = 0</td>
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

<p>Instructions in this region (distance(RegionBegin, RegionEnd)).</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a0fdf731113f2b02fd779a07e4d433717">llvm::GCNIterativeScheduler::enterRegion</a>, <a href="#ae8727d434d20639d563849891f5ca1e1">enterRegion</a> and <a href="#a705a0975de8335b0b6bdbbae165e8f5c">initSUnits</a>.</p>

</div>
</div>

### RegionBegin {#ae81ad8ece7681af658742f6d4e2fcfb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::ScheduleDAGInstrs::RegionBegin</td>
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

<p>The beginning of the range to be scheduled.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#ae8625c1e6c9bc82f2eaef39d3fff65a8">addSchedBarrierDeps</a>, <a href="#ab50b64c518a7455daf3e0bc87aee5514">begin</a>, <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#ab9c7e76fda2b142c09da3ca892884acd">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::EmitSchedule</a>, <a href="#ae8727d434d20639d563849891f5ca1e1">enterRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1f98694f104d052d71ed74ade38d69f0">llvm::ScheduleDAGMI::initQueues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a3668b7c35103540be55d96cd68948f43">llvm::ScheduleDAGMILive::initQueues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a86daf2b1fb72fdd9a8785a4042ac1457">llvm::ScheduleDAGMILive::initRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#ab6c5bda21b39ff9494fc2661de4aa974">llvm::SIScheduleDAGMI::initRPTracker</a>, <a href="#a705a0975de8335b0b6bdbbae165e8f5c">initSUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a2209b15a069023499cc665b373e67703">llvm::ScheduleDAGMI::moveInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac2dafe98c88d43b256622413886e2152">llvm::ScheduleDAGMI::placeDebugValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a587988ffcc944147e5ba7da46bc77ef2">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ab201710a9597b0df54c12a848d4804d9">llvm::GCNIterativeScheduler::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnscheduledagmilive/#a3c1701146006f98eaa57e38932060160">llvm::GCNScheduleDAGMILive::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ad899858c4b90e464815c32a7f9c4bb26">llvm::GCNIterativeScheduler::scheduleRegion</a>.</p>

</div>
</div>

### RegionEnd {#a3f74b283acf0dfb537bc387e49344f04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::ScheduleDAGInstrs::RegionEnd</td>
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

<p>The end of the range to be scheduled.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#ae8625c1e6c9bc82f2eaef39d3fff65a8">addSchedBarrierDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a4be5ffcd4f76d433cc753be146a872b7">llvm::ScheduleDAGMILive::buildDAGWithRegPressure</a>, <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#ab9c7e76fda2b142c09da3ca892884acd">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::EmitSchedule</a>, <a href="#a21805259f54dab47c2b3da009216996a">end</a>, <a href="#ae8727d434d20639d563849891f5ca1e1">enterRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a34481791fdd8f5d9131431cb0a1a0c01">llvm::ScheduleDAGMILive::enterRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1f98694f104d052d71ed74ade38d69f0">llvm::ScheduleDAGMI::initQueues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a86daf2b1fb72fdd9a8785a4042ac1457">llvm::ScheduleDAGMILive::initRegPressure</a>, <a href="#a705a0975de8335b0b6bdbbae165e8f5c">initSUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac2dafe98c88d43b256622413886e2152">llvm::ScheduleDAGMI::placeDebugValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a587988ffcc944147e5ba7da46bc77ef2">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ab201710a9597b0df54c12a848d4804d9">llvm::GCNIterativeScheduler::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnscheduledagmilive/#a3c1701146006f98eaa57e38932060160">llvm::GCNScheduleDAGMILive::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ad899858c4b90e464815c32a7f9c4bb26">llvm::GCNIterativeScheduler::scheduleRegion</a>.</p>

</div>
</div>

### RemoveKillFlags {#adf7cb9b8e5dda7b42273e79048f1b8b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScheduleDAGInstrs::RemoveKillFlags</td>
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

<p>True if the DAG builder should remove kill flags (in preparation for rescheduling).</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#a2e9425c046cf742bfbb9ebb96466d8e5">addPhysRegDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnpostscheduledagmilive/#ac1db9853e3ddfa9a2177147d8c03eacb">llvm::GCNPostScheduleDAGMILive::GCNPostScheduleDAGMILive</a>, <a href="#a5bcb745a3e78c329d1431608b1f51c25">ScheduleDAGInstrs</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a629982ca3ef5632e63f32b5682fde927">llvm::ScheduleDAGMI::ScheduleDAGMI</a>.</p>

</div>
</div>

### SchedModel {#abb11b650b88a61630eba2a1b2eaa6fd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetSchedModel llvm::ScheduleDAGInstrs::SchedModel</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> provides an interface to the machine model.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#a56fbc3f460289602ce8a51538ebc1e26">addPhysRegDataDeps</a>, <a href="#a2e9425c046cf742bfbb9ebb96466d8e5">addPhysRegDeps</a>, <a href="#a10acc9310a21d9a8191d3d84916bdffb">addVRegDefDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#add5e3e74f2db8e669b830ae35edc8c02">llvm::ScheduleDAGMILive::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a942d716003056c037d46a4144e9cf885">llvm::ScheduleDAGMI::dumpScheduleTraceBottomUp</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a3010c4b89284791284aa6e2ec510501b">llvm::ScheduleDAGMI::dumpScheduleTraceTopDown</a>, <a href="#a4bf5573660c55924d68b517a0e9b4554">getSchedClass</a>, <a href="#a3f70979bd43329e7ad53ad796db8112f">getSchedModel</a>, <a href="#a705a0975de8335b0b6bdbbae165e8f5c">initSUnits</a> and <a href="#a5bcb745a3e78c329d1431608b1f51c25">ScheduleDAGInstrs</a>.</p>

</div>
</div>

### Topo {#a8cd3eede9e2a32c7139cc5c7c481e08b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGTopologicalSort llvm::ScheduleDAGInstrs::Topo</td>
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

<p>Topo - A topological ordering for SUnits which permits fast IsReachable and similar queries.</p>

<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#a86bfa4838cb7e42648615d27c94c8017">addEdge</a>, <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>, <a href="#ac384df17605ecce542a6d2567c7f1ee0">canAddEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a62cf6ab44f7fd7435eca1db81c914664">llvm::SIScheduleDAGMI::GetTopo</a>, <a href="#aa79589a56769cd108d08e21544be1420">IsReachable</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a> and <a href="#a5bcb745a3e78c329d1431608b1f51c25">ScheduleDAGInstrs</a>.</p>

</div>
</div>

### TrackLaneMasks {#a96bb77f51ee973b0613bf5083144fa69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScheduleDAGInstrs::TrackLaneMasks = false</td>
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

<p>Whether lane masks should get tracked.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#a10acc9310a21d9a8191d3d84916bdffb">addVRegDefDeps</a>, <a href="#a0f958ee7dc9902af4093fe8fabbabd6e">addVRegUseDeps</a>, <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a920652e64042f72e913f81f9660b4f2f">llvm::ScheduleDAGMILive::collectVRegUses</a>.</p>

</div>
</div>

### UnknownValue {#aad4b383d6bf0b66dd1a20a81505788fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UndefValue* llvm::ScheduleDAGInstrs::UnknownValue</td>
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

<p>For an unanalyzable memory access, this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is used in maps.</p>

<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a> and <a href="#a5bcb745a3e78c329d1431608b1f51c25">ScheduleDAGInstrs</a>.</p>

</div>
</div>

### Uses {#abc7a356b097ebfec45c1f663a4e52575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegUnit2SUnitsMap llvm::ScheduleDAGInstrs::Uses</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a>.</p>


<p>Referenced by <a href="#a56fbc3f460289602ce8a51538ebc1e26">addPhysRegDataDeps</a>, <a href="#a2e9425c046cf742bfbb9ebb96466d8e5">addPhysRegDeps</a>, <a href="#ae8625c1e6c9bc82f2eaef39d3fff65a8">addSchedBarrierDeps</a> and <a href="#ab580983de4f7b69ebcca992be9cb3223">buildSchedGraph</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledaginstrs-h">ScheduleDAGInstrs.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
