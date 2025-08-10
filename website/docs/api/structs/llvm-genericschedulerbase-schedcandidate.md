---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/genericschedulerbase/schedcandidate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SchedCandidate` Struct

<p>Store the state used by <a href="/web-llvm/docs/api/classes/llvm/genericscheduler">GenericScheduler</a> heuristics, required for the lifetime of one invocation of <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy/#ab8f81fac35fcedf80a58ef268409d328">pickNode()</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::GenericSchedulerBase::SchedCandidate { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">llvm/CodeGen/MachineScheduler.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e5a4b29e0495447584f298d55df3ec9">SchedCandidate</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1546dba06e2d0308402b02b6cc8db22f">SchedCandidate</a> (const CandPolicy &amp;Policy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a361fa10c095c303e093021c6a1d04e75">reset</a> (const CandPolicy &amp;NewPolicy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdc733638a93dca6bb0eb290ec896271">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a294e77c4f7245940981e5e259045c7c0">setBest</a> (SchedCandidate &amp;Best)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47cc8c89db10ac27483585cd61cf4f91">initResourceDelta</a> (const ScheduleDAGMI *DAG, const TargetSchedModel *SchedModel)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy">CandPolicy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae861d440b366cf033d7f2764b2b34be0">Policy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a310a170b7d2442d12634d53db262fb92">SU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3">CandReason</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9372964d55580636efe92281b42ad6c">Reason</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87328c4ecbb87961dd2c970d343b9ca0">AtTop</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/regpressuredelta">RegPressureDelta</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81fbfdac1b8c1e736493b56b50853322">RPDelta</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedresourcedelta">SchedResourceDelta</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab86856838bf1e1577210f03d35273ccb">ResDelta</a></td>
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

<p>Store the state used by <a href="/web-llvm/docs/api/classes/llvm/genericscheduler">GenericScheduler</a> heuristics, required for the lifetime of one invocation of <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy/#ab8f81fac35fcedf80a58ef268409d328">pickNode()</a>.</p>

<p>Definition at line 1128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SchedCandidate() {#a6e5a4b29e0495447584f298d55df3ec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericSchedulerBase::SchedCandidate::SchedCandidate ()</td>
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



<p>Definition at line 1146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a361fa10c095c303e093021c6a1d04e75">reset</a>.</p>


<p>Referenced by <a href="#a294e77c4f7245940981e5e259045c7c0">setBest</a>.</p>

</div>
</div>

### SchedCandidate() {#a1546dba06e2d0308402b02b6cc8db22f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericSchedulerBase::SchedCandidate::SchedCandidate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy">CandPolicy</a> &amp; Policy)</td>
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



<p>Definition at line 1147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="#ae861d440b366cf033d7f2764b2b34be0">Policy</a> and <a href="#a361fa10c095c303e093021c6a1d04e75">reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### initResourceDelta() {#a47cc8c89db10ac27483585cd61cf4f91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GenericSchedulerBase::SchedCandidate::initResourceDelta (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a> * DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> * SchedModel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 2970 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a4bf5573660c55924d68b517a0e9b4554">llvm::ScheduleDAGInstrs::getSchedClass</a>, <a href="#ae861d440b366cf033d7f2764b2b34be0">Policy</a>, <a href="#ab86856838bf1e1577210f03d35273ccb">ResDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a9730ea0068843718868a8667f52e3680">llvm::GenericSchedulerBase::SchedModel</a> and <a href="#a310a170b7d2442d12634d53db262fb92">SU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad9779ec3011b4547f9a509af82d87a6e">llvm::GenericScheduler::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a5db5287f3514fcc23bb3f93d769b3e96">llvm::PostGenericScheduler::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### isValid() {#acdc733638a93dca6bb0eb290ec896271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericSchedulerBase::SchedCandidate::isValid ()</td>
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



<p>Definition at line 1158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a310a170b7d2442d12634d53db262fb92">SU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64postraschedstrategy/#a13b69f0a0d56eb5e0802e40b938136a6">llvm::AArch64PostRASchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a09835bd12a7088d224f84e7899946040">llvm::PostGenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcpostraschedstrategy/#aa6664186ee0da2c7355def751d53a653">llvm::PPCPostRASchedStrategy::tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### reset() {#a361fa10c095c303e093021c6a1d04e75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericSchedulerBase::SchedCandidate::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy">CandPolicy</a> &amp; NewPolicy)</td>
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



<p>Definition at line 1149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="#a87328c4ecbb87961dd2c970d343b9ca0">AtTop</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a810d389a7def234e94c2631683ab0ece">llvm::GenericSchedulerBase::NoCand</a>, <a href="#ae861d440b366cf033d7f2764b2b34be0">Policy</a>, <a href="#ad9372964d55580636efe92281b42ad6c">Reason</a>, <a href="#ab86856838bf1e1577210f03d35273ccb">ResDelta</a>, <a href="#a81fbfdac1b8c1e736493b56b50853322">RPDelta</a> and <a href="#a310a170b7d2442d12634d53db262fb92">SU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a26b8231b39c104871f78b2da6dc1eff5">llvm::GCNSchedStrategy::pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#aef82bce77971408815c3b90979188d1e">llvm::GenericScheduler::pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#ae8950b6343e504e2112df60ee464603d">llvm::PostGenericScheduler::pickNodeBidirectional</a>, <a href="#a6e5a4b29e0495447584f298d55df3ec9">SchedCandidate</a> and <a href="#a1546dba06e2d0308402b02b6cc8db22f">SchedCandidate</a>.</p>

</div>
</div>

### setBest() {#a294e77c4f7245940981e5e259045c7c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericSchedulerBase::SchedCandidate::setBest (<a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; Best)</td>
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



<p>Definition at line 1161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a87328c4ecbb87961dd2c970d343b9ca0">AtTop</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#ae0da1bc94e326020069c0f44170a48d3a810d389a7def234e94c2631683ab0ece">llvm::GenericSchedulerBase::NoCand</a>, <a href="#ad9372964d55580636efe92281b42ad6c">Reason</a>, <a href="#ab86856838bf1e1577210f03d35273ccb">ResDelta</a>, <a href="#a81fbfdac1b8c1e736493b56b50853322">RPDelta</a>, <a href="#a6e5a4b29e0495447584f298d55df3ec9">SchedCandidate</a> and <a href="#a310a170b7d2442d12634d53db262fb92">SU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#aef82bce77971408815c3b90979188d1e">llvm::GenericScheduler::pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#ae8950b6343e504e2112df60ee464603d">llvm::PostGenericScheduler::pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad9779ec3011b4547f9a509af82d87a6e">llvm::GenericScheduler::pickNodeFromQueue</a> and <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a5db5287f3514fcc23bb3f93d769b3e96">llvm::PostGenericScheduler::pickNodeFromQueue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AtTop {#a87328c4ecbb87961dd2c970d343b9ca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericSchedulerBase::SchedCandidate::AtTop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ad173097d2f6789c7d00843386252855e">llvm::GCNSchedStrategy::initCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ab0d12eb20352f092840f7f8df60abe26">llvm::GenericScheduler::initCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#aef82bce77971408815c3b90979188d1e">llvm::GenericScheduler::pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#ae8950b6343e504e2112df60ee464603d">llvm::PostGenericScheduler::pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad9779ec3011b4547f9a509af82d87a6e">llvm::GenericScheduler::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a5db5287f3514fcc23bb3f93d769b3e96">llvm::PostGenericScheduler::pickNodeFromQueue</a>, <a href="#a361fa10c095c303e093021c6a1d04e75">reset</a>, <a href="#a294e77c4f7245940981e5e259045c7c0">setBest</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a3352d36ab68528af960439073f22b304">tracePick</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a09835bd12a7088d224f84e7899946040">llvm::PostGenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a62cf34ac18c5612524978166788b5c80">llvm::tryPressure</a>.</p>

</div>
</div>

### Policy {#ae861d440b366cf033d7f2764b2b34be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CandPolicy llvm::GenericSchedulerBase::SchedCandidate::Policy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a47cc8c89db10ac27483585cd61cf4f91">initResourceDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a5db5287f3514fcc23bb3f93d769b3e96">llvm::PostGenericScheduler::pickNodeFromQueue</a>, <a href="#a361fa10c095c303e093021c6a1d04e75">reset</a>, <a href="#a1546dba06e2d0308402b02b6cc8db22f">SchedCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a09835bd12a7088d224f84e7899946040">llvm::PostGenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcpostraschedstrategy/#aa6664186ee0da2c7355def751d53a653">llvm::PPCPostRASchedStrategy::tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### Reason {#ad9372964d55580636efe92281b42ad6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CandReason llvm::GenericSchedulerBase::SchedCandidate::Reason</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcpostraschedstrategy/#ab2370ffefd96bdadc456a51ff470f626">llvm::PPCPostRASchedStrategy::biasAddiCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a>, <a href="#a361fa10c095c303e093021c6a1d04e75">reset</a>, <a href="#a294e77c4f7245940981e5e259045c7c0">setBest</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a3352d36ab68528af960439073f22b304">tracePick</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64postraschedstrategy/#a13b69f0a0d56eb5e0802e40b938136a6">llvm::AArch64PostRASchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a09835bd12a7088d224f84e7899946040">llvm::PostGenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcpostraschedstrategy/#aa6664186ee0da2c7355def751d53a653">llvm::PPCPostRASchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab618de2b7dea1e1859018a1a7e8b3ee5">llvm::tryGreater</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae0fdc8ed1e4e4ae29b810aeffc13fb47">llvm::tryLess</a>.</p>

</div>
</div>

### ResDelta {#ab86856838bf1e1577210f03d35273ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedResourceDelta llvm::GenericSchedulerBase::SchedCandidate::ResDelta</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a47cc8c89db10ac27483585cd61cf4f91">initResourceDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad9779ec3011b4547f9a509af82d87a6e">llvm::GenericScheduler::pickNodeFromQueue</a>, <a href="#a361fa10c095c303e093021c6a1d04e75">reset</a>, <a href="#a294e77c4f7245940981e5e259045c7c0">setBest</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a09835bd12a7088d224f84e7899946040">llvm::PostGenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcpostraschedstrategy/#aa6664186ee0da2c7355def751d53a653">llvm::PPCPostRASchedStrategy::tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### RPDelta {#a81fbfdac1b8c1e736493b56b50853322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegPressureDelta llvm::GenericSchedulerBase::SchedCandidate::RPDelta</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ad173097d2f6789c7d00843386252855e">llvm::GCNSchedStrategy::initCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ab0d12eb20352f092840f7f8df60abe26">llvm::GenericScheduler::initCandidate</a>, <a href="#a361fa10c095c303e093021c6a1d04e75">reset</a>, <a href="#a294e77c4f7245940981e5e259045c7c0">setBest</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### SU {#a310a170b7d2442d12634d53db262fb92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit* llvm::GenericSchedulerBase::SchedCandidate::SU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ad173097d2f6789c7d00843386252855e">llvm::GCNSchedStrategy::initCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ab0d12eb20352f092840f7f8df60abe26">llvm::GenericScheduler::initCandidate</a>, <a href="#a47cc8c89db10ac27483585cd61cf4f91">initResourceDelta</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-cpp/#a39cb081a14bceac85a10e7a987109c1f">isADDIInstr</a>, <a href="#acdc733638a93dca6bb0eb290ec896271">isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a26b8231b39c104871f78b2da6dc1eff5">llvm::GCNSchedStrategy::pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#aef82bce77971408815c3b90979188d1e">llvm::GenericScheduler::pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#ae8950b6343e504e2112df60ee464603d">llvm::PostGenericScheduler::pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a5db5287f3514fcc23bb3f93d769b3e96">llvm::PostGenericScheduler::pickNodeFromQueue</a>, <a href="#a361fa10c095c303e093021c6a1d04e75">reset</a>, <a href="#a294e77c4f7245940981e5e259045c7c0">setBest</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64postraschedstrategy/#a13b69f0a0d56eb5e0802e40b938136a6">llvm::AArch64PostRASchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a09835bd12a7088d224f84e7899946040">llvm::PostGenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcpostraschedstrategy/#aa6664186ee0da2c7355def751d53a653">llvm::PPCPostRASchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9a83bf7b5f6e85f215ff07a31e0fbe">llvm::tryLatency</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
