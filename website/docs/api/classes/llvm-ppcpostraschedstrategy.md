---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ppcpostraschedstrategy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PPCPostRASchedStrategy` Class Reference

<p>A <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> implementation for PowerPC post RA scheduling. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PPCPostRASchedStrategy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-h">Target/PowerPC/PPCMachineScheduler.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler">PostGenericScheduler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler">PostGenericScheduler</a> - Interface to the scheduling algorithm used by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a>. <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e58d5d92c66c85df7c89ead1f68b58f">PPCPostRASchedStrategy</a> (const MachineSchedContext *C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af00cbef0e1f01812d6b3ba8a3a05cddd">initialize</a> (ScheduleDAGMI *Dag) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the strategy after building the DAG for a new region. <a href="#af00cbef0e1f01812d6b3ba8a3a05cddd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a380e7f12bac02fcc58704de354b838dd">pickNode</a> (bool &amp;IsTopNode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick the next node to schedule. <a href="#a380e7f12bac02fcc58704de354b838dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ec1332d9323fdd938250ab78617b9e0">enterMBB</a> (MachineBasicBlock *MBB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tell the strategy that MBB is about to be processed. <a href="#a7ec1332d9323fdd938250ab78617b9e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac49589043856dffa0c7870bc64b458ec">leaveMBB</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tell the strategy that current MBB is done. <a href="#ac49589043856dffa0c7870bc64b458ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6664186ee0da2c7355def751d53a653">tryCandidate</a> (SchedCandidate &amp;Cand, SchedCandidate &amp;TryCand) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply a set of heuristics to a new candidate for PostRA scheduling. <a href="#aa6664186ee0da2c7355def751d53a653">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2370ffefd96bdadc456a51ff470f626">biasAddiCandidate</a> (SchedCandidate &amp;Cand, SchedCandidate &amp;TryCand) const</td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> implementation for PowerPC post RA scheduling.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-h">PPCMachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCPostRASchedStrategy() {#a5e58d5d92c66c85df7c89ead1f68b58f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PPCPostRASchedStrategy::PPCPostRASchedStrategy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-h">PPCMachineScheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#ac8d3e1ce009ee1e50dfd8897346404bb">llvm::PostGenericScheduler::PostGenericScheduler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### biasAddiCandidate() {#ab2370ffefd96bdadc456a51ff470f626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCPostRASchedStrategy::biasAddiCandidate (<a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; Cand, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; TryCand)</td>
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



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-h">PPCMachineScheduler.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-cpp">PPCMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-cpp/#a5bdd1463fadb9bffe0ea131df6285a62">EnableAddiHeuristic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-cpp/#a39cb081a14bceac85a10e7a987109c1f">isADDIInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ad9372964d55580636efe92281b42ad6c">llvm::GenericSchedulerBase::SchedCandidate::Reason</a> and <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3ab6aae8902e724a36ed16d537784777a2">llvm::GenericSchedulerBase::Stall</a>.</p>


<p>Referenced by <a href="#aa6664186ee0da2c7355def751d53a653">tryCandidate</a>.</p>

</div>
</div>

### enterMBB() {#a7ec1332d9323fdd938250ab78617b9e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCPostRASchedStrategy::enterMBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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

<p>Tell the strategy that MBB is about to be processed.</p>

<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-h">PPCMachineScheduler.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-cpp">PPCMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy/#a2ecebd8a29fabb301a5799dc4d034667">llvm::MachineSchedStrategy::enterMBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### initialize() {#af00cbef0e1f01812d6b3ba8a3a05cddd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCPostRASchedStrategy::initialize (<a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> * DAG)</td>
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

<p>Initialize the strategy after building the DAG for a new region.</p>

<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-h">PPCMachineScheduler.h</a>, definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-cpp">PPCMachineScheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a744ad04adf5ae507a33542ec18b0d97f">llvm::PostGenericScheduler::initialize</a>.</p>

</div>
</div>

### leaveMBB() {#ac49589043856dffa0c7870bc64b458ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCPostRASchedStrategy::leaveMBB ()</td>
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

<p>Tell the strategy that current MBB is done.</p>

<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-h">PPCMachineScheduler.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-cpp">PPCMachineScheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy/#a1767939c59515562b576fc23075ef7df">llvm::MachineSchedStrategy::leaveMBB</a>.</p>

</div>
</div>

### pickNode() {#a380e7f12bac02fcc58704de354b838dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * PPCPostRASchedStrategy::pickNode (bool &amp; IsTopNode)</td>
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

<p>Pick the next node to schedule.</p>

<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-h">PPCMachineScheduler.h</a>, definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-cpp">PPCMachineScheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#af8a37b0efa51cfd3f6b4729e3298de7f">llvm::PostGenericScheduler::pickNode</a>.</p>

</div>
</div>

### tryCandidate() {#aa6664186ee0da2c7355def751d53a653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCPostRASchedStrategy::tryCandidate (<a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; Cand, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; TryCand)</td>
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

<p>Apply a set of heuristics to a new candidate for PostRA scheduling.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Cand</td>
<td class="doxyParamItemDescription"><p>provides the policy and current best candidate.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TryCand</td>
<td class="doxyParamItemDescription"><p>refers to the next <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> candidate, otherwise uninitialized.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">true</span> if TryCand is better than Cand (Reason is NOT NoCand)</p></dd>
</dl>


<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-h">PPCMachineScheduler.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-cpp">PPCMachineScheduler.cpp</a>.</p>


<p>References <a href="#ab2370ffefd96bdadc456a51ff470f626">biasAddiCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a5a905614458af47ec4a5054a53d23e1b">llvm::GenericSchedulerBase::Cluster</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedresourcedelta/#a3ffd08e01bba20c9af1ae13630ed7acd">llvm::GenericSchedulerBase::SchedResourceDelta::CritResources</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a228f5e150e68f65407ed303218827a0a">llvm::PostGenericScheduler::DAG</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedresourcedelta/#ab660550157a92f83f7b4f2db2d2d9304">llvm::GenericSchedulerBase::SchedResourceDelta::DemandedResources</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#acdc733638a93dca6bb0eb290ec896271">llvm::GenericSchedulerBase::SchedCandidate::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a810d389a7def234e94c2631683ab0ece">llvm::GenericSchedulerBase::NoCand</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3aa00a8e5741a604eb07320e981473b4e7">llvm::GenericSchedulerBase::NodeOrder</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ae861d440b366cf033d7f2764b2b34be0">llvm::GenericSchedulerBase::SchedCandidate::Policy</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ad9372964d55580636efe92281b42ad6c">llvm::GenericSchedulerBase::SchedCandidate::Reason</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy/#acd9f1ecfaa9db2800e6fe15a385b4a6f">llvm::GenericSchedulerBase::CandPolicy::ReduceLatency</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ab86856838bf1e1577210f03d35273ccb">llvm::GenericSchedulerBase::SchedCandidate::ResDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a07409a8a5b9657af23f0a1c962f5c0c1">llvm::GenericSchedulerBase::ResourceDemand</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a56637d3435d7e1953a615371cfe4d5ec">llvm::GenericSchedulerBase::ResourceReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3ab6aae8902e724a36ed16d537784777a2">llvm::GenericSchedulerBase::Stall</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a310a170b7d2442d12634d53db262fb92">llvm::GenericSchedulerBase::SchedCandidate::SU</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a406dc33395b3fd7b56da9a33fbccdc82">llvm::PostGenericScheduler::Top</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab618de2b7dea1e1859018a1a7e8b3ee5">llvm::tryGreater</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9a83bf7b5f6e85f215ff07a31e0fbe">llvm::tryLatency</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae0fdc8ed1e4e4ae29b810aeffc13fb47">llvm::tryLess</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-cpp">PPCMachineScheduler.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-h">PPCMachineScheduler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
