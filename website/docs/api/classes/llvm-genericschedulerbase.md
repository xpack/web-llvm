---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/genericschedulerbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GenericSchedulerBase` Class

<p>Base class for <a href="/web-llvm/docs/api/classes/llvm/genericscheduler">GenericScheduler</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GenericSchedulerBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">llvm/CodeGen/MachineScheduler.h</a>"
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/genericscheduler">GenericScheduler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/genericscheduler">GenericScheduler</a> shrinks the unscheduled zone using heuristics to balance the schedule. <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CandReason : uint8_t { <a href="#ae0da1bc94e326020069c0f44170a48d3">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represent the type of <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> found within a single queue. <a href="#ae0da1bc94e326020069c0f44170a48d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf7a31296b8d3ede091a25b7777c3a15">GenericSchedulerBase</a> (const MachineSchedContext *C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8668556014566994c07b21391762551b">setPolicy</a> (CandPolicy &amp;Policy, bool IsPostRA, SchedBoundary &amp;CurrZone, SchedBoundary *OtherZone)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy">CandPolicy</a> given a scheduling zone given the current resources and latencies inside and outside the zone. <a href="#a8668556014566994c07b21391762551b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy">MachineSchedPolicy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab29d166bcf9429b14ba2db21e948ac6d">getPolicy</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc28b204833d49b88dbeceb366b7439">traceCandidate</a> (const SchedCandidate &amp;Cand)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0460d556c22aeab1f569f865f217cd5">shouldReduceLatency</a> (const CandPolicy &amp;Policy, SchedBoundary &amp;CurrZone, bool ComputeRemLatency, unsigned &amp;RemLatency) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the current cycle plus remaning latency is greater than the critical path in the scheduling region. <a href="#ae0460d556c22aeab1f569f865f217cd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0f9f52bf2f7c54d9546cedd1c47ef45">Context</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9730ea0068843718868a8667f52e3680">SchedModel</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9476ffbc2f3f195a2116b13f3186194">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy">MachineSchedPolicy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e13153e8ed7676ddbba73dd9318d35e">RegionPolicy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/schedremainder">SchedRemainder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cab76d375dbb626e5179b96f84fd3dc">Rem</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9df77ae80f822b788cb2464992a05bc1">getReasonStr</a> (GenericSchedulerBase::CandReason Reason)</td>
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

<p>Base class for <a href="/web-llvm/docs/api/classes/llvm/genericscheduler">GenericScheduler</a>.</p>


<p>This class maintains information about scheduling candidates based on <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> making it easy to implement heuristics for either preRA or postRA scheduling.</p>


<p>Definition at line 1076 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### CandReason {#ae0da1bc94e326020069c0f44170a48d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::GenericSchedulerBase::CandReason : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represent the type of <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> found within a single queue.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoCand<a id="ae0da1bc94e326020069c0f44170a48d3a810d389a7def234e94c2631683ab0ece"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Only1<a id="ae0da1bc94e326020069c0f44170a48d3a3e5ec7d7634a70f61fd64c3ef22d02f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PhysReg<a id="ae0da1bc94e326020069c0f44170a48d3ab58c08e8fa9324ebf332e11601ec6c0d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegExcess<a id="ae0da1bc94e326020069c0f44170a48d3a01d264553167fb005aba23a6d2a6e9bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegCritical<a id="ae0da1bc94e326020069c0f44170a48d3a974161ce84e375b6d40bd8855c29dd7f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Stall<a id="ae0da1bc94e326020069c0f44170a48d3ab6aae8902e724a36ed16d537784777a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Cluster<a id="ae0da1bc94e326020069c0f44170a48d3a5a905614458af47ec4a5054a53d23e1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Weak<a id="ae0da1bc94e326020069c0f44170a48d3aed8b719fe1a669c2fed4bacc6f46e8df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegMax<a id="ae0da1bc94e326020069c0f44170a48d3a01ef8d8423fe645e50ad5a179b4f4483"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ResourceReduce<a id="ae0da1bc94e326020069c0f44170a48d3a56637d3435d7e1953a615371cfe4d5ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ResourceDemand<a id="ae0da1bc94e326020069c0f44170a48d3a07409a8a5b9657af23f0a1c962f5c0c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BotHeightReduce<a id="ae0da1bc94e326020069c0f44170a48d3a8ea4d71243c1b82d5e35065d580c1e49"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BotPathReduce<a id="ae0da1bc94e326020069c0f44170a48d3ad3c3c8a47c777d0f591ca18eaf7000d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TopDepthReduce<a id="ae0da1bc94e326020069c0f44170a48d3afb16e35278ff80f34d2ad9889213b406"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TopPathReduce<a id="ae0da1bc94e326020069c0f44170a48d3a768a7f66e30d6b2d2d81ab1af56bf6c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NextDefUse<a id="ae0da1bc94e326020069c0f44170a48d3af9d4eb6d4d0ca011ccbb24f139c9bf73"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NodeOrder<a id="ae0da1bc94e326020069c0f44170a48d3aa00a8e5741a604eb07320e981473b4e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>pickNodeBidirectional depends on these listed by decreasing priority.</p>


<p>Definition at line 1080 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### GenericSchedulerBase() {#abf7a31296b8d3ede091a25b7777c3a15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericSchedulerBase::GenericSchedulerBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
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



<p>Definition at line 1183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#ad0f9f52bf2f7c54d9546cedd1c47ef45">Context</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ae8dd2d1a734d828faa812af4a9a135e3">llvm::GenericScheduler::GenericScheduler</a> and <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#ac8d3e1ce009ee1e50dfd8897346404bb">llvm::PostGenericScheduler::PostGenericScheduler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getPolicy() {#ab29d166bcf9429b14ba2db21e948ac6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSchedPolicy llvm::GenericSchedulerBase::getPolicy ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a8e13153e8ed7676ddbba73dd9318d35e">RegionPolicy</a>.</p>

</div>
</div>

### setPolicy() {#a8668556014566994c07b21391762551b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GenericSchedulerBase::setPolicy (<a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy">CandPolicy</a> &amp; Policy, bool IsPostRA, <a href="/web-llvm/docs/api/classes/llvm/schedboundary">SchedBoundary</a> &amp; CurrZone, <a href="/web-llvm/docs/api/classes/llvm/schedboundary">SchedBoundary</a> * OtherZone)</td>
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

<p>Set the <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy">CandPolicy</a> given a scheduling zone given the current resources and latencies inside and outside the zone.</p>

<p>Declaration at line 1185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3034 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#aa49fbb78ca6f0a19a967f2f8fb70097d">llvm::SchedBoundary::Available</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a77e51ffc94a77ff8e4778e59a02e7b67">checkResourceLimit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a4d6bf176cc854701f61fba566b9dbf9b">computeRemLatency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy/#a61f080e69dc94a237cc49b7a3ca8c558">llvm::GenericSchedulerBase::CandPolicy::DemandResIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#acef1c37226a48a752d933063e8ba6f83">llvm::SchedBoundary::getCurrCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#ac90e8349a5117f988bbb4cf8bf8c5f9f">llvm::ReadyQueue::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a5af50e4260bb23b1035c52c186fdcc8b">llvm::SchedBoundary::getOtherResourceCount</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#ae98af615296b8adf67556301343d6ca2">llvm::SchedBoundary::getZoneCritResIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a2ec93f0e570be68d89930c8e4032ef83">llvm::SchedBoundary::isResourceLimited</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy/#acd9f1ecfaa9db2800e6fe15a385b4a6f">llvm::GenericSchedulerBase::CandPolicy::ReduceLatency</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy/#a413ba6a1fb7916faa6b5d34aa4397d9b">llvm::GenericSchedulerBase::CandPolicy::ReduceResIdx</a>, <a href="#a3cab76d375dbb626e5179b96f84fd3dc">Rem</a> and <a href="#a9730ea0068843718868a8667f52e3680">SchedModel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#af8a37b0efa51cfd3f6b4729e3298de7f">llvm::PostGenericScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a26b8231b39c104871f78b2da6dc1eff5">llvm::GCNSchedStrategy::pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#aef82bce77971408815c3b90979188d1e">llvm::GenericScheduler::pickNodeBidirectional</a> and <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#ae8950b6343e504e2112df60ee464603d">llvm::PostGenericScheduler::pickNodeBidirectional</a>.</p>

</div>
</div>

### traceCandidate() {#a0fc28b204833d49b88dbeceb366b7439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GenericSchedulerBase::traceCandidate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate">SchedCandidate</a> &amp; Cand)</td>
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



<p>Declaration at line 1191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3113 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#ae0da1bc94e326020069c0f44170a48d3a8ea4d71243c1b82d5e35065d580c1e49">BotHeightReduce</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3ad3c3c8a47c777d0f591ca18eaf7000d4">BotPathReduce</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a277da5755f2b30ebcebdba51d0de1acf">llvm::RegPressureDelta::CriticalMax</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a589e1a7e9a8a095d8d01ff8ba32b3d14">llvm::RegPressureDelta::CurrentMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy/#a61f080e69dc94a237cc49b7a3ca8c558">llvm::GenericSchedulerBase::CandPolicy::DemandResIdx</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#aff9c3b403c6d4af795dd8be1c9612240">llvm::RegPressureDelta::Excess</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8926b25df7254ba2730fa5d7ec139862">llvm::SUnit::getDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a582da862b28b876ef2235781392cffa6">llvm::SUnit::getHeight</a>, <a href="#a9df77ae80f822b788cb2464992a05bc1">getReasonStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a2d68d32ff95cd10b4899c2823ec28e97">llvm::Latency</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ae861d440b366cf033d7f2764b2b34be0">llvm::GenericSchedulerBase::SchedCandidate::Policy</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#ad9372964d55580636efe92281b42ad6c">llvm::GenericSchedulerBase::SchedCandidate::Reason</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy/#a413ba6a1fb7916faa6b5d34aa4397d9b">llvm::GenericSchedulerBase::CandPolicy::ReduceResIdx</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a974161ce84e375b6d40bd8855c29dd7f">RegCritical</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a01d264553167fb005aba23a6d2a6e9bb">RegExcess</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a01ef8d8423fe645e50ad5a179b4f4483">RegMax</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a07409a8a5b9657af23f0a1c962f5c0c1">ResourceDemand</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a56637d3435d7e1953a615371cfe4d5ec">ResourceReduce</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a81fbfdac1b8c1e736493b56b50853322">llvm::GenericSchedulerBase::SchedCandidate::RPDelta</a>, <a href="#a9730ea0068843718868a8667f52e3680">SchedModel</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a310a170b7d2442d12634d53db262fb92">llvm::GenericSchedulerBase::SchedCandidate::SU</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3afb16e35278ff80f34d2ad9889213b406">TopDepthReduce</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a768a7f66e30d6b2d2d81ab1af56bf6c4">TopPathReduce</a> and <a href="#ae9476ffbc2f3f195a2116b13f3186194">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a26b8231b39c104871f78b2da6dc1eff5">llvm::GCNSchedStrategy::pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#aef82bce77971408815c3b90979188d1e">llvm::GenericScheduler::pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#ae8950b6343e504e2112df60ee464603d">llvm::PostGenericScheduler::pickNodeBidirectional</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad9779ec3011b4547f9a509af82d87a6e">llvm::GenericScheduler::pickNodeFromQueue</a> and <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a5db5287f3514fcc23bb3f93d769b3e96">llvm::PostGenericScheduler::pickNodeFromQueue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### shouldReduceLatency() {#ae0460d556c22aeab1f569f865f217cd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GenericSchedulerBase::shouldReduceLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/candpolicy">CandPolicy</a> &amp; Policy, <a href="/web-llvm/docs/api/classes/llvm/schedboundary">SchedBoundary</a> &amp; CurrZone, bool ComputeRemLatency, unsigned &amp; RemLatency)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the current cycle plus remaning latency is greater than the critical path in the scheduling region.</p>

<p>Declaration at line 1195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3013 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Context {#ad0f9f52bf2f7c54d9546cedd1c47ef45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineSchedContext* llvm::GenericSchedulerBase::Context</td>
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



<p>Definition at line 1175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#abf7a31296b8d3ede091a25b7777c3a15">GenericSchedulerBase</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ab57c0b13438062a884d3e620300fbc03">llvm::GCNSchedStrategy::initialize</a> and <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ac8e2225e71c3b7d40575a2ab9bfffc78">llvm::GenericScheduler::initPolicy</a>.</p>

</div>
</div>

### RegionPolicy {#a8e13153e8ed7676ddbba73dd9318d35e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSchedPolicy llvm::GenericSchedulerBase::RegionPolicy</td>
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



<p>Definition at line 1179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a8329c2fe0a6267d1e0f94dc4aecc5892">llvm::GenericScheduler::dumpPolicy</a>, <a href="#ab29d166bcf9429b14ba2db21e948ac6d">getPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#aa8cddd2ea015f8177a8395035f87e332">llvm::GenericScheduler::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ac8e2225e71c3b7d40575a2ab9bfffc78">llvm::GenericScheduler::initPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a04711828471ee40bed1b0e0ae8584cf4">llvm::PostGenericScheduler::initPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#af3f3a45f145bc8538e160bc3177ffc8f">llvm::GCNSchedStrategy::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad4cc558b6cbcc4e9cea5df915c197e14">llvm::GenericScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#af8a37b0efa51cfd3f6b4729e3298de7f">llvm::PostGenericScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ada10b0f311c10e4c89f7449fdd38b965">llvm::GenericScheduler::shouldTrackLaneMasks</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ab1ad1eb71432f2b381687717ced8b052">llvm::GenericScheduler::shouldTrackPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### Rem {#a3cab76d375dbb626e5179b96f84fd3dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedRemainder llvm::GenericSchedulerBase::Rem</td>
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



<p>Definition at line 1181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a0aa33f27fbf7be1e7e53512ceb6de885">llvm::GenericScheduler::checkAcyclicLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#aa8cddd2ea015f8177a8395035f87e332">llvm::GenericScheduler::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a744ad04adf5ae507a33542ec18b0d97f">llvm::PostGenericScheduler::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ac047246e76df6b86564a6b62c2403aef">llvm::GenericScheduler::registerRoots</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#aee5ca47cbb46d1237ce496179411b03e">llvm::PostGenericScheduler::registerRoots</a>, <a href="#a8668556014566994c07b21391762551b">setPolicy</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### SchedModel {#a9730ea0068843718868a8667f52e3680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSchedModel* llvm::GenericSchedulerBase::SchedModel = nullptr</td>
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



<p>Definition at line 1176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a0aa33f27fbf7be1e7e53512ceb6de885">llvm::GenericScheduler::checkAcyclicLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#aa8cddd2ea015f8177a8395035f87e332">llvm::GenericScheduler::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a744ad04adf5ae507a33542ec18b0d97f">llvm::PostGenericScheduler::initialize</a>, <a href="/web-llvm/docs/api/structs/llvm/genericschedulerbase/schedcandidate/#a47cc8c89db10ac27483585cd61cf4f91">llvm::GenericSchedulerBase::SchedCandidate::initResourceDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad9779ec3011b4547f9a509af82d87a6e">llvm::GenericScheduler::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a5db5287f3514fcc23bb3f93d769b3e96">llvm::PostGenericScheduler::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ac047246e76df6b86564a6b62c2403aef">llvm::GenericScheduler::registerRoots</a>, <a href="#a8668556014566994c07b21391762551b">setPolicy</a>, <a href="#a0fc28b204833d49b88dbeceb366b7439">traceCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### TRI {#ae9476ffbc2f3f195a2116b13f3186194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::GenericSchedulerBase::TRI = nullptr</td>
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



<p>Definition at line 1177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ab0d12eb20352f092840f7f8df60abe26">llvm::GenericScheduler::initCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#aa8cddd2ea015f8177a8395035f87e332">llvm::GenericScheduler::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a744ad04adf5ae507a33542ec18b0d97f">llvm::PostGenericScheduler::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a>, <a href="#a0fc28b204833d49b88dbeceb366b7439">traceCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getReasonStr() {#a9df77ae80f822b788cb2464992a05bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * GenericSchedulerBase::getReasonStr (<a href="#ae0da1bc94e326020069c0f44170a48d3">GenericSchedulerBase::CandReason</a> Reason)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1086 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 3089 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="#ae0da1bc94e326020069c0f44170a48d3a8ea4d71243c1b82d5e35065d580c1e49">BotHeightReduce</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3ad3c3c8a47c777d0f591ca18eaf7000d4">BotPathReduce</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a5a905614458af47ec4a5054a53d23e1b">Cluster</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3af9d4eb6d4d0ca011ccbb24f139c9bf73">NextDefUse</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a810d389a7def234e94c2631683ab0ece">NoCand</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3aa00a8e5741a604eb07320e981473b4e7">NodeOrder</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a3e5ec7d7634a70f61fd64c3ef22d02f1">Only1</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3ab58c08e8fa9324ebf332e11601ec6c0d">PhysReg</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a974161ce84e375b6d40bd8855c29dd7f">RegCritical</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a01d264553167fb005aba23a6d2a6e9bb">RegExcess</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a01ef8d8423fe645e50ad5a179b4f4483">RegMax</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a07409a8a5b9657af23f0a1c962f5c0c1">ResourceDemand</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a56637d3435d7e1953a615371cfe4d5ec">ResourceReduce</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3ab6aae8902e724a36ed16d537784777a2">Stall</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3afb16e35278ff80f34d2ad9889213b406">TopDepthReduce</a>, <a href="#ae0da1bc94e326020069c0f44170a48d3a768a7f66e30d6b2d2d81ab1af56bf6c4">TopPathReduce</a> and <a href="#ae0da1bc94e326020069c0f44170a48d3aed8b719fe1a669c2fed4bacc6f46e8df">Weak</a>.</p>


<p>Referenced by <a href="#a0fc28b204833d49b88dbeceb366b7439">traceCandidate</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#a14c35b53586841aad69751a52b7d358a">tracePick</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
