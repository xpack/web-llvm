---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/systemzpostraschedstrategy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SystemZPostRASchedStrategy` Class

<p>A <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> implementation for <a href="/web-llvm/docs/api/namespaces/llvm/systemz">SystemZ</a> post RA scheduling. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SystemZPostRASchedStrategy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">Target/SystemZ/SystemZMachineScheduler.h</a>"
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer">SystemZHazardRecognizer</a> * &gt; <a href="#a5eef8c4ed9d544b55904e9d37d55ac63">MBB2HazRec</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maintain hazard recognizers for all blocks, so that the scheduler state can be maintained past BB boundaries when appropariate. <a href="#a5eef8c4ed9d544b55904e9d37d55ac63">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7cf55944f14abe03fa718a60f2fafe1">SystemZPostRASchedStrategy</a> (const MachineSchedContext *C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace31ed48b8ff510ab635bea47ee55e73">~SystemZPostRASchedStrategy</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a6e91fbf92378734b0dd9f1523bff19">initPolicy</a> (MachineBasicBlock::iterator Begin, MachineBasicBlock::iterator End, unsigned NumRegionInstrs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called for a region before scheduling. <a href="#a7a6e91fbf92378734b0dd9f1523bff19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00ffe74116346e7953817c0dcc730cad">shouldTrackPressure</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PostRA scheduling does not track pressure. <a href="#a00ffe74116346e7953817c0dcc730cad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae70b4df15c9db45746e75427d9a73975">doMBBSchedRegionsTopDown</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa527afd01941aa018dbb3edbad50e770">initialize</a> (ScheduleDAGMI *dag) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the strategy after building the DAG for a new region. <a href="#aa527afd01941aa018dbb3edbad50e770">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb12e569451bee60098c4608b8ca8fa5">enterMBB</a> (MachineBasicBlock *NextMBB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tell the strategy that MBB is about to be processed. <a href="#abb12e569451bee60098c4608b8ca8fa5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a183188c809d901aa875645e4398eb1f9">leaveMBB</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tell the strategy that current MBB is done. <a href="#a183188c809d901aa875645e4398eb1f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e0a14434477222a57a6e5e09b1f0f2f">pickNode</a> (bool &amp;IsTopNode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick the next node to schedule, or return NULL. <a href="#a0e0a14434477222a57a6e5e09b1f0f2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ee4cac33c533fe9bc0b5b0147475c38">schedNode</a> (SUnit *SU, bool IsTopNode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> has scheduled an instruction - tell HazardRec about it. <a href="#a9ee4cac33c533fe9bc0b5b0147475c38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe13e1e8b6cdaa6f0cd3a91d16a302f8">releaseTopNode</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SU has had all predecessor dependencies resolved. <a href="#afe13e1e8b6cdaa6f0cd3a91d16a302f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a199a79c029d6fc9c4b1f338083539bd1">releaseBottomNode</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Currently only scheduling top-down, so this method is empty. <a href="#a199a79c029d6fc9c4b1f338083539bd1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad971afa6f050bfaf3da785b9cbb1f756">advanceTo</a> (MachineBasicBlock::iterator NextBegin)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the scheduler state by emitting (non-scheduled) instructions up to, but not including, NextBegin. <a href="#ad971afa6f050bfaf3da785b9cbb1f756">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1fd645edb614a6bb4c71d350ad2bbbb">MLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo">SystemZInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadc368ac0e5d0fc6daa6aeda8cfe1364">TII</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac470f49c1090e8b33dd5290fba30c272">SchedModel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">SUSet</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3455a69960204e0b28d566e705c5270">Available</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of available SUs to schedule next. <a href="#ab3455a69960204e0b28d566e705c5270">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a278e83627d3b9adbf4192a762fcb3f6f">MBB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current MBB. <a href="#a278e83627d3b9adbf4192a762fcb3f6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">MBB2HazRec</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa4c87174015873c1751e671e79ae5e7">SchedStates</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer">SystemZHazardRecognizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8350c0c3ddcb1322ce2573895b6377a5">HazardRec</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the HazardRecognizer that tracks the scheduler state for the current region. <a href="#a8350c0c3ddcb1322ce2573895b6377a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> implementation for <a href="/web-llvm/docs/api/namespaces/llvm/systemz">SystemZ</a> post RA scheduling.</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### MBB2HazRec {#a5eef8c4ed9d544b55904e9d37d55ac63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::map&lt;MachineBasicBlock*, SystemZHazardRecognizer*&gt; llvm::SystemZPostRASchedStrategy::MBB2HazRec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maintain hazard recognizers for all blocks, so that the scheduler state can be maintained past BB boundaries when appropariate.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SystemZPostRASchedStrategy() {#ae7cf55944f14abe03fa718a60f2fafe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SystemZPostRASchedStrategy::SystemZPostRASchedStrategy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-cpp">SystemZMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SystemZPostRASchedStrategy() {#ace31ed48b8ff510ab635bea47ee55e73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SystemZPostRASchedStrategy::~SystemZPostRASchedStrategy ()</td>
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



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-cpp">SystemZMachineScheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doMBBSchedRegionsTopDown() {#ae70b4df15c9db45746e75427d9a73975}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SystemZPostRASchedStrategy::doMBBSchedRegionsTopDown ()</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>.</p>

</div>
</div>

### enterMBB() {#abb12e569451bee60098c4608b8ca8fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZPostRASchedStrategy::enterMBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NextMBB)</td>
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

<p>Tell the strategy that MBB is about to be processed.</p>

<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-cpp">SystemZMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-cpp/#a2ae98e15f35ee616bea08c594611d2d7">getSingleSchedPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>

</div>
</div>

### initialize() {#aa527afd01941aa018dbb3edbad50e770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZPostRASchedStrategy::initialize (<a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> * DAG)</td>
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

<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-cpp">SystemZMachineScheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### initPolicy() {#a7a6e91fbf92378734b0dd9f1523bff19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZPostRASchedStrategy::initPolicy (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> End, unsigned NumRegionInstrs)</td>
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

<p>Called for a region before scheduling.</p>

<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-cpp">SystemZMachineScheduler.cpp</a>.</p>

</div>
</div>

### leaveMBB() {#a183188c809d901aa875645e4398eb1f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZPostRASchedStrategy::leaveMBB ()</td>
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

<p>Tell the strategy that current MBB is done.</p>

<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-cpp">SystemZMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>

</div>
</div>

### pickNode() {#a0e0a14434477222a57a6e5e09b1f0f2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * SystemZPostRASchedStrategy::pickNode (bool &amp; IsTopNode)</td>
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

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-cpp">SystemZMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a582da862b28b876ef2235781392cffa6">llvm::SUnit::getHeight</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### releaseBottomNode() {#a199a79c029d6fc9c4b1f338083539bd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SystemZPostRASchedStrategy::releaseBottomNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>Currently only scheduling top-down, so this method is empty.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>.</p>

</div>
</div>

### releaseTopNode() {#afe13e1e8b6cdaa6f0cd3a91d16a302f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZPostRASchedStrategy::releaseTopNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>SU has had all predecessor dependencies resolved.</p>


<p>Put it into Available.</p>


<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-cpp">SystemZMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#a7faf5b0345dd1c2fd4b60d7f5108f3b5">llvm::SUnit::isScheduleHigh</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a4ac4d36cb59a4bbf5d93513dad0ff0e9">llvm::SUnit::isUnbuffered</a>.</p>

</div>
</div>

### schedNode() {#a9ee4cac33c533fe9bc0b5b0147475c38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZPostRASchedStrategy::schedNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, bool IsTopNode)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> has scheduled an instruction - tell HazardRec about it.</p>

<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-cpp">SystemZMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>.</p>

</div>
</div>

### shouldTrackPressure() {#a00ffe74116346e7953817c0dcc730cad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SystemZPostRASchedStrategy::shouldTrackPressure ()</td>
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

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### advanceTo() {#ad971afa6f050bfaf3da785b9cbb1f756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZPostRASchedStrategy::advanceTo (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> NextBegin)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the scheduler state by emitting (non-scheduled) instructions up to, but not including, NextBegin.</p>

<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-cpp">SystemZMachineScheduler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Available {#ab3455a69960204e0b28d566e705c5270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUSet llvm::SystemZPostRASchedStrategy::Available</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of available SUs to schedule next.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>.</p>

</div>
</div>

### HazardRec {#a8350c0c3ddcb1322ce2573895b6377a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SystemZHazardRecognizer* llvm::SystemZPostRASchedStrategy::HazardRec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to the HazardRecognizer that tracks the scheduler state for the current region.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>.</p>

</div>
</div>

### MBB {#a278e83627d3b9adbf4192a762fcb3f6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::SystemZPostRASchedStrategy::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current MBB.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>.</p>

</div>
</div>

### MLI {#ab1fd645edb614a6bb4c71d350ad2bbbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineLoopInfo* llvm::SystemZPostRASchedStrategy::MLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>.</p>

</div>
</div>

### SchedModel {#ac470f49c1090e8b33dd5290fba30c272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetSchedModel llvm::SystemZPostRASchedStrategy::SchedModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>.</p>

</div>
</div>

### SchedStates {#aaa4c87174015873c1751e671e79ae5e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MBB2HazRec llvm::SystemZPostRASchedStrategy::SchedStates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>.</p>

</div>
</div>

### TII {#aadc368ac0e5d0fc6daa6aeda8cfe1364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SystemZInstrInfo* llvm::SystemZPostRASchedStrategy::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-cpp">SystemZMachineScheduler.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzmachinescheduler-h">SystemZMachineScheduler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
