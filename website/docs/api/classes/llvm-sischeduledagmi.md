---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sischeduledagmi
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SIScheduleDAGMI` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SIScheduleDAGMI { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">Target/AMDGPU/SIMachineScheduler.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a771c24fd27edfc5b9fdf7ae8422cc236">SIScheduleDAGMI</a> (MachineSchedContext *C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe716faf3c81cff4cf4e29422d1f0985">~SIScheduleDAGMI</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a543aa30430f7e566cc4baa20b271f377">schedule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> interface for scheduling a sequence of reorderable instructions. <a href="#a543aa30430f7e566cc4baa20b271f377">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6c5bda21b39ff9494fc2661de4aa974">initRPTracker</a> (RegPressureTracker &amp;RPTracker)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4ab68f9751f02633860848cb2e9b63d">getBB</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed7f9965b5fafd5e6f0dae05deb7c23">getCurrentTop</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7819978aa6afac57ceb568dc197ac8c3">getCurrentBottom</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cdf7bc92c67442fd90bd2dfaeae0383">getLIS</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c00bda859fc30b13be64312fd6cffc6">getMRI</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6da1408d8eb00d050466f094399b4b7">getTRI</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort">ScheduleDAGTopologicalSort</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62cf6ab44f7fd7435eca1db81c914664">GetTopo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eec08caac9b208bbb7bb95ed0e90f8f">getEntrySU</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fb8e9a77f63588d8ab5136847bbd7fc">getExitSU</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10557b7d33ea079f0523cac41ef279b8">restoreSULinksLeft</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename _Iterator&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a65716b8ea88f6ffb38b7f87fe4ee23ab">fillVgprSgprCost</a> (_Iterator First, _Iterator End, unsigned &amp;VgprUsage, unsigned &amp;SgprUsage)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad25ec135803e03e30ccb77c4b734cb">getInRegs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba5a6d4d063ef267e00c9e98494449f7">getOutRegs</a> ()</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acae99b0bface66886026b95384196342">topologicalSort</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a8283e7e162e3da862063f43e51172a">moveLowLatencies</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dbcf222026885cec7b4bd3e8e7653f2">IsLowLatencySU</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44bdc6a2e8f452060f03765f830a834b">LowLatencyOffset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3839c0faf9a49f67a183aaafe0cd7fe0">IsHighLatencySU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a470670a7d9cc41bc1d5ed1b244fffd11">TopDownIndex2SU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e9f5df7b765366ff598beafbe9ecd37">BottomUpIndex2SU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a730d9ec82c20b327023282beddf5bda8">SITII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2636f33628fa76385038baf984b1d7c">SITRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28f759bdd1762e2a9ffac96313aebad9">SUnitsLinksBackup</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bb5385287d4995f7f7d4ce7763a46c7">ScheduledSUnits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57eed2adc6ae4e58361b10c9b04111e8">ScheduledSUnitsInv</a></td>
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


<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIScheduleDAGMI() {#a771c24fd27edfc5b9fdf7ae8422cc236}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIScheduleDAGMI::SIScheduleDAGMI (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>, definition at line 1743 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp">SIMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a67da2c9a62e43ae7b66bc5ca91f55a05">llvm::ScheduleDAGMILive::ScheduleDAGMILive</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a348590624c488b04d0f9e227e6c3960e">llvm::ScheduleDAG::TII</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SIScheduleDAGMI() {#abe716faf3c81cff4cf4e29422d1f0985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIScheduleDAGMI::~SIScheduleDAGMI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### fillVgprSgprCost() {#a65716b8ea88f6ffb38b7f87fe4ee23ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename _Iterator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIScheduleDAGMI::fillVgprSgprCost (_Iterator First, _Iterator End, unsigned &amp; VgprUsage, unsigned &amp; SgprUsage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>, definition at line 1846 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp">SIMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/classes/llvm/psetiterator/#a7468f7aa9ad819d0d0294cc66da0c9e8">llvm::PSetIterator::getWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/psetiterator/#adca9aa81c4b0432673b64c7c42611df5">llvm::PSetIterator::isValid</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a1b09f4d9c91e25f7bc2ac60b3b929d11">llvm::ScheduleDAG::MRI</a>.</p>

</div>
</div>

### getBB() {#ab4ab68f9751f02633860848cb2e9b63d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::SIScheduleDAGMI::getBB ()</td>
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



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>.</p>

</div>
</div>

### getCurrentBottom() {#a7819978aa6afac57ceb568dc197ac8c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::SIScheduleDAGMI::getCurrentBottom ()</td>
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



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a7435e842606f5db4bca092e5829befc6">llvm::ScheduleDAGMI::CurrentBottom</a>.</p>

</div>
</div>

### getCurrentTop() {#a9ed7f9965b5fafd5e6f0dae05deb7c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::SIScheduleDAGMI::getCurrentTop ()</td>
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



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac8abe1b0d869087bd0c14a6637356dc0">llvm::ScheduleDAGMI::CurrentTop</a>.</p>

</div>
</div>

### getEntrySU() {#a0eec08caac9b208bbb7bb95ed0e90f8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit &amp; llvm::SIScheduleDAGMI::getEntrySU ()</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a521bf68518a92483130a58680716d153">llvm::ScheduleDAG::EntrySU</a>.</p>

</div>
</div>

### getExitSU() {#a9fb8e9a77f63588d8ab5136847bbd7fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit &amp; llvm::SIScheduleDAGMI::getExitSU ()</td>
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



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a>.</p>

</div>
</div>

### getInRegs() {#a1ad25ec135803e03e30ccb77c4b734cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt; Register &gt; llvm::SIScheduleDAGMI::getInRegs ()</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#abd3a9c68e31ad35d6468f200facdd0e3">llvm::ScheduleDAGMILive::RPTracker</a>.</p>

</div>
</div>

### getLIS() {#a5cdf7bc92c67442fd90bd2dfaeae0383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals * llvm::SIScheduleDAGMI::getLIS ()</td>
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



<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>.</p>

</div>
</div>

### getMRI() {#a6c00bda859fc30b13be64312fd6cffc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo * llvm::SIScheduleDAGMI::getMRI ()</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a1b09f4d9c91e25f7bc2ac60b3b929d11">llvm::ScheduleDAG::MRI</a>.</p>

</div>
</div>

### getOutRegs() {#aba5a6d4d063ef267e00c9e98494449f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt; unsigned &gt; llvm::SIScheduleDAGMI::getOutRegs ()</td>
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



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#abd3a9c68e31ad35d6468f200facdd0e3">llvm::ScheduleDAGMILive::RPTracker</a>.</p>

</div>
</div>

### GetTopo() {#a62cf6ab44f7fd7435eca1db81c914664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGTopologicalSort * llvm::SIScheduleDAGMI::GetTopo ()</td>
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



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a8cd3eede9e2a32c7139cc5c7c481e08b">llvm::ScheduleDAGInstrs::Topo</a>.</p>

</div>
</div>

### getTRI() {#ae6da1408d8eb00d050466f094399b4b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo * llvm::SIScheduleDAGMI::getTRI ()</td>
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



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>.</p>

</div>
</div>

### initRPTracker() {#ab6c5bda21b39ff9494fc2661de4aa974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SIScheduleDAGMI::initRPTracker (<a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> &amp; RPTracker)</td>
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



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a9539744d7a0c1681540a64e935b671dd">llvm::ScheduleDAGMILive::RegClassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae81ad8ece7681af658742f6d4e2fcfb1">llvm::ScheduleDAGInstrs::RegionBegin</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#abd3a9c68e31ad35d6468f200facdd0e3">llvm::ScheduleDAGMILive::RPTracker</a>.</p>

</div>
</div>

### restoreSULinksLeft() {#a10557b7d33ea079f0523cac41ef279b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIScheduleDAGMI::restoreSULinksLeft ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>, definition at line 1834 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp">SIMachineScheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>

</div>
</div>

### schedule() {#a543aa30430f7e566cc4baa20b271f377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIScheduleDAGMI::schedule ()</td>
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


<p>schedule - Called back from <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a8539983d1d0a8b07d92b91c16b9f7a5a">MachineScheduler::runOnMachineFunction</a> after setting up the current scheduling region.</p>


<p>[RegionBegin, RegionEnd) only includes instructions that have DAG nodes, not scheduling boundaries.</p>


<p>This is a skeletal driver, with all the functionality pushed into helpers, so that it can be easily extended by experimental schedulers. Generally, implementing <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> should be sufficient to implement a new scheduling algorithm. However, if a scheduler further subclasses <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive">ScheduleDAGMILive</a> then it will want to override this virtual method in order to update any specialized state.</p>


<p>Declaration at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>, definition at line 1865 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp">SIMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab50b64c518a7455daf3e0bc87aee5514">llvm::ScheduleDAGInstrs::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d977510474f80bfa4550c11b1b5b1c9a4c3e89a4ea7af492ea5504b88a3ea671">llvm::BlockLatencyRegUsage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d977510474f80bfa4550c11b1b5b1c9aba717031a1b21be60de55bdfcaa459a9">llvm::BlockRegUsage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d977510474f80bfa4550c11b1b5b1c9a647183744de9df06f83d3d4c23b0db07">llvm::BlockRegUsageLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a4be5ffcd4f76d433cc753be146a872b7">llvm::ScheduleDAGMILive::buildDAGWithRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a7435e842606f5db4bca092e5829befc6">llvm::ScheduleDAGMI::CurrentBottom</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac8abe1b0d869087bd0c14a6637356dc0">llvm::ScheduleDAGMI::CurrentTop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#add5e3e74f2db8e669b830ae35edc8c02">llvm::ScheduleDAGMILive::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a01b02e76c87211e7084ec17f18a2d16f">llvm::ScheduleDAGMI::dumpSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a6d0a0b4903e8d4d12c98b0f43fe83878">llvm::ScheduleDAGMI::findRootsAndBiasEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a3668b7c35103540be55d96cd68948f43">llvm::ScheduleDAGMILive::initQueues</a>, <a href="#a3839c0faf9a49f67a183aaafe0cd7fe0">IsHighLatencySU</a>, <a href="#a9dbcf222026885cec7b4bd3e8e7653f2">IsLowLatencySU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e37096a7413b5df71c0af49d15d6b9a477ab899a79ca5207be7eb9a80622b20">llvm::LatenciesAlone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e37096a7413b5df71c0af49d15d6b9a0771d39c819fa1008d7c0d2f7960a6d8">llvm::LatenciesAlonePlusConsecutive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e37096a7413b5df71c0af49d15d6b9a663331d0e885ceddf1aabe2754ca48b4">llvm::LatenciesGrouped</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a44bdc6a2e8f452060f03765f830a834b">LowLatencyOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/sischeduleblockresult/#a7e76c8d566e3f09c1b3ffe2add8562e1">llvm::SIScheduleBlockResult::MaxVGPRUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac2dafe98c88d43b256622413886e2152">llvm::ScheduleDAGMI::placeDebugValues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a2aa2eb6fd6a44ff6b9cbad960d446c7a">llvm::ScheduleDAGMI::postProcessDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e9fde7ed08fd233750d0a947147dfa1">llvm::PrintDAGs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae81ad8ece7681af658742f6d4e2fcfb1">llvm::ScheduleDAGInstrs::RegionBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a0318c90d99b85c47bc82d9e0844462f6">llvm::ScheduleDAGMI::SchedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a04a2c04f918397dbac27a79e58807136">llvm::ScheduleDAGMILive::scheduleMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a1c735bd46fe1e1b5f6f85a710d99e149">Scheduler</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>, <a href="/web-llvm/docs/api/structs/llvm/sischeduleblockresult/#afa48c69324d21c0d80e406f4731ed2ec">llvm::SIScheduleBlockResult::SUs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#af7781c87ae9e210811389a826d7d4835">llvm::ScheduleDAGMILive::TopRPTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a8b7babb023cad0842f5a177e7abe3651">llvm::ScheduleDAGMI::viewGraph</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5ec9cfe35d76125af923975fa0c1730a">llvm::ViewMISchedDAGs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### moveLowLatencies() {#a9a8283e7e162e3da862063f43e51172a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIScheduleDAGMI::moveLowLatencies ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>, definition at line 1767 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp">SIMachineScheduler.cpp</a>.</p>

</div>
</div>

### topologicalSort() {#acae99b0bface66886026b95384196342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIScheduleDAGMI::topologicalSort ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>, definition at line 1754 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp">SIMachineScheduler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BottomUpIndex2SU {#a1e9f5df7b765366ff598beafbe9ecd37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;int&gt; llvm::SIScheduleDAGMI::BottomUpIndex2SU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>

</div>
</div>

### IsHighLatencySU {#a3839c0faf9a49f67a183aaafe0cd7fe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::SIScheduleDAGMI::IsHighLatencySU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a543aa30430f7e566cc4baa20b271f377">schedule</a>.</p>

</div>
</div>

### IsLowLatencySU {#a9dbcf222026885cec7b4bd3e8e7653f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::SIScheduleDAGMI::IsLowLatencySU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a543aa30430f7e566cc4baa20b271f377">schedule</a>.</p>

</div>
</div>

### LowLatencyOffset {#a44bdc6a2e8f452060f03765f830a834b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::SIScheduleDAGMI::LowLatencyOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a543aa30430f7e566cc4baa20b271f377">schedule</a>.</p>

</div>
</div>

### TopDownIndex2SU {#a470670a7d9cc41bc1d5ed1b244fffd11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;int&gt; llvm::SIScheduleDAGMI::TopDownIndex2SU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ScheduledSUnits {#a1bb5385287d4995f7f7d4ce7763a46c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::SIScheduleDAGMI::ScheduledSUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>

</div>
</div>

### ScheduledSUnitsInv {#a57eed2adc6ae4e58361b10c9b04111e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::SIScheduleDAGMI::ScheduledSUnitsInv</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>

</div>
</div>

### SITII {#a730d9ec82c20b327023282beddf5bda8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo* llvm::SIScheduleDAGMI::SITII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>

</div>
</div>

### SITRI {#ac2636f33628fa76385038baf984b1d7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIRegisterInfo* llvm::SIScheduleDAGMI::SITRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>

</div>
</div>

### SUnitsLinksBackup {#a28f759bdd1762e2a9ffac96313aebad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SUnit&gt; llvm::SIScheduleDAGMI::SUnitsLinksBackup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp">SIMachineScheduler.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-h">SIMachineScheduler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
