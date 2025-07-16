---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcnmaxmemoryclauseschedstrategy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GCNMaxMemoryClauseSchedStrategy` Class Reference

<p>The goal of this scheduling strategy is to maximize memory clause for a single wave. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GCNMaxMemoryClauseSchedStrategy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">Target/AMDGPU/GCNSchedStrategy.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy">GCNSchedStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a minimal scheduler strategy. <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5dff5cf85f1ae74f4b05b1c7638d694">GCNMaxMemoryClauseSchedStrategy</a> (const MachineSchedContext *C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eba23f1b8a103c8e88a2ca6227d97b3">tryCandidate</a> (SchedCandidate &amp;Cand, SchedCandidate &amp;TryCand, SchedBoundary *Zone) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy">GCNMaxMemoryClauseSchedStrategy</a> tries best to clause memory instructions as much as possible. <a href="#a9eba23f1b8a103c8e88a2ca6227d97b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The goal of this scheduling strategy is to maximize memory clause for a single wave.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GCNMaxMemoryClauseSchedStrategy() {#ae5dff5cf85f1ae74f4b05b1c7638d694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNMaxMemoryClauseSchedStrategy::GCNMaxMemoryClauseSchedStrategy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a14f3300bee7a18474eb2f103afa3ea22">llvm::GCNSchedStrategy::GCNSchedStrategy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0a414873aebe374e5386fe3382107061d8">llvm::MemoryClauseInitialSchedule</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a1736ffcc1fcc46c9c47748d5a9a04c4b">llvm::GCNSchedStrategy::SchedStages</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### tryCandidate() {#a9eba23f1b8a103c8e88a2ca6227d97b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNMaxMemoryClauseSchedStrategy::tryCandidate (<a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; Cand, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; TryCand, <a href="/web-llvm/docs/api/classes/llvm/schedboundary">SchedBoundary</a> * Zone)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy">GCNMaxMemoryClauseSchedStrategy</a> tries best to clause memory instructions as much as possible.</p>


<p>This is achieved by:</p>


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
<tr class="doxyParamItem">
<td class="doxyParamItemName">Zone</td>
<td class="doxyParamItemDescription"><p>describes the scheduled zone that we are extending, or nullptr if Cand is from a different zone than TryCand.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">true</span> if TryCand is better than Cand (Reason is NOT NoCand)</p></dd>
</dl>


<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a87328c4ecbb87961dd2c970d343b9ca0">llvm::GenericSchedulerBase::SchedCandidate::AtTop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb4b9423201406d79ba16481c90cb6cb">llvm::biasPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a5a905614458af47ec4a5054a53d23e1b">llvm::GenericSchedulerBase::Cluster</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a277da5755f2b30ebcebdba51d0de1acf">llvm::RegPressureDelta::CriticalMax</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedresourcedelta/#a3ffd08e01bba20c9af1ae13630ed7acd">llvm::GenericSchedulerBase::SchedResourceDelta::CritResources</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a589e1a7e9a8a095d8d01ff8ba32b3d14">llvm::RegPressureDelta::CurrentMax</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a75edfd9bb13c765b11b0b400cbe2aaed">llvm::GenericScheduler::DAG</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedresourcedelta/#ab660550157a92f83f7b4f2db2d2d9304">llvm::GenericSchedulerBase::SchedResourceDelta::DemandedResources</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#aff9c3b403c6d4af795dd8be1c9612240">llvm::RegPressureDelta::Excess</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#ac984b92ac3a64875c7f2908ef617584d">llvm::SchedBoundary::getCurrMOps</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a4a674627365b72b17a9b2e0a99d40ce1">llvm::SchedBoundary::getLatencyStallCycles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a13933f8ac2f5e1a34cf53b2c1e1bdc5b">llvm::getWeakLeft</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a47cc8c89db10ac27483585cd61cf4f91">llvm::GenericSchedulerBase::SchedCandidate::initResourceDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a274909b1f31ad2d3d3379de55467d377">llvm::SUnit::isInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a589e51a1ef960a2b6aaa3854ce04d77a">llvm::SchedBoundary::isTop</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#acdc733638a93dca6bb0eb290ec896271">llvm::GenericSchedulerBase::SchedCandidate::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a72e0568b7bf0e9a97260c34264a549a0">llvm::SUnit::Latency</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a682028ac4a06c9e3550fa8e6e1909fa9">llvm::MachineInstr::mayLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06af9883480b45663348fb5529c563fd6f2">llvm::NoCand</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a31669aae44fa7e6414dd5cd81e2b16f8">llvm::NodeOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3ab58c08e8fa9324ebf332e11601ec6c0d">llvm::GenericSchedulerBase::PhysReg</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ae861d440b366cf033d7f2764b2b34be0">llvm::GenericSchedulerBase::SchedCandidate::Policy</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ad9372964d55580636efe92281b42ad6c">llvm::GenericSchedulerBase::SchedCandidate::Reason</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy/#acd9f1ecfaa9db2800e6fe15a385b4a6f">llvm::GenericSchedulerBase::CandPolicy::ReduceLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a974161ce84e375b6d40bd8855c29dd7f">llvm::GenericSchedulerBase::RegCritical</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a01d264553167fb005aba23a6d2a6e9bb">llvm::GenericSchedulerBase::RegExcess</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8e13153e8ed7676ddbba73dd9318d35e">llvm::GenericSchedulerBase::RegionPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a01ef8d8423fe645e50ad5a179b4f4483">llvm::GenericSchedulerBase::RegMax</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a3cab76d375dbb626e5179b96f84fd3dc">llvm::GenericSchedulerBase::Rem</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ab86856838bf1e1577210f03d35273ccb">llvm::GenericSchedulerBase::SchedCandidate::ResDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a07409a8a5b9657af23f0a1c962f5c0c1">llvm::GenericSchedulerBase::ResourceDemand</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a56637d3435d7e1953a615371cfe4d5ec">llvm::GenericSchedulerBase::ResourceReduce</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a81fbfdac1b8c1e736493b56b50853322">llvm::GenericSchedulerBase::SchedCandidate::RPDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a9730ea0068843718868a8667f52e3680">llvm::GenericSchedulerBase::SchedModel</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3ab6aae8902e724a36ed16d537784777a2">llvm::GenericSchedulerBase::Stall</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a310a170b7d2442d12634d53db262fb92">llvm::GenericSchedulerBase::SchedCandidate::SU</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae9476ffbc2f3f195a2116b13f3186194">llvm::GenericSchedulerBase::TRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab618de2b7dea1e1859018a1a7e8b3ee5">llvm::tryGreater</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9a83bf7b5f6e85f215ff07a31e0fbe">llvm::tryLatency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae0fdc8ed1e4e4ae29b810aeffc13fb47">llvm::tryLess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62cf34ac18c5612524978166788b5c80">llvm::tryPressure</a> and <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3aed8b719fe1a669c2fed4bacc6f46e8df">llvm::GenericSchedulerBase::Weak</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
