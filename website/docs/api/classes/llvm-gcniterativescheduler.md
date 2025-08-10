---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcniterativescheduler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GCNIterativeScheduler` Class



## Declaration

<div class="doxyDeclaration">
class llvm::GCNIterativeScheduler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">Target/AMDGPU/GCNIterativeScheduler.h</a>"
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abec99f440ac68fa7bf59a142fa6e8c7d">ScheduleRef</a> = <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1b83eb7dc54fa7d2b6a4c4db7c53035">BaseClass</a> = <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive">ScheduleDAGMILive</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">StrategyKind { <a href="#a8f50e93e5644e2551f440ae6efd60014">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca77a3ca62633e1f7f4ed2ff3be6d81">GCNIterativeScheduler</a> (MachineSchedContext *C, StrategyKind S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab201710a9597b0df54c12a848d4804d9">schedule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Orders nodes according to selected style. <a href="#ab201710a9597b0df54c12a848d4804d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fdf731113f2b02fd779a07e4d433717">enterRegion</a> (MachineBasicBlock *BB, MachineBasicBlock::iterator Begin, MachineBasicBlock::iterator End, unsigned RegionInstrs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the DAG and common scheduler state for a new scheduling region. <a href="#a0fdf731113f2b02fd779a07e4d433717">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d0ff8af24f7c66a107ce5695a1149dd">finalizeSchedule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow targets to perform final scheduling actions at the level of the whole <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>. <a href="#a9d0ff8af24f7c66a107ce5695a1149dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Range&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gcnregpressure">GCNRegPressure</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab7703967e4547dc33bde51d360068021">getSchedulePressure</a> (const Region &amp;R, Range &amp;&amp;Schedule) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gcnregpressure">GCNRegPressure</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeb32a2045204d56bbf623bec5da25b3">getRegionPressure</a> (MachineBasicBlock::iterator Begin, MachineBasicBlock::iterator End) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gcnregpressure">GCNRegPressure</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae026fc83e46ea2999953bd2b728ea4c7">getRegionPressure</a> (const Region &amp;R) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f9d10fa98c86d22e17258c86701191a">setBestSchedule</a> (Region &amp;R, ScheduleRef Schedule, const GCNRegPressure &amp;MaxRP=GCNRegPressure())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51ca74535c09b1424af0a32c4a5b9b1f">scheduleBest</a> (Region &amp;R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7c58c4a38a2148e0a6eec44b8749bbb">detachSchedule</a> (ScheduleRef Schedule) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19e2ffc6c8269a09ca18d5255ec2345a">sortRegionsByPressure</a> (unsigned TargetOcc)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Range&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad899858c4b90e464815c32a7f9c4bb26">scheduleRegion</a> (Region &amp;R, Range &amp;&amp;Schedule, const GCNRegPressure &amp;MaxRP=GCNRegPressure())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd0550f564608fec7c5d7f25817ddef">tryMaximizeOccupancy</a> (unsigned TargetOcc=std::numeric_limits&lt; unsigned &gt;::max())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d479174d357214e5ea495943b55fdd2">scheduleLegacyMaxOccupancy</a> (bool TryMaximizeOccupancy=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d457cdee60c23701eca3d110a4862f">scheduleMinReg</a> (bool force=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a424a74f8852d22b010e48f8f6d0c748d">scheduleILP</a> (bool TryMaximizeOccupancy=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70f01da7bffd10dc0686e3ca4286eac8">printRegions</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e84e2872d922dee85f4511ac0326f64">printSchedResult</a> (raw_ostream &amp;OS, const Region *R, const GCNRegPressure &amp;RP) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cb97aff651ff2a97a061183a62dfc01">printSchedRP</a> (raw_ostream &amp;OS, const GCNRegPressure &amp;Before, const GCNRegPressure &amp;After) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gcniterativescheduler/region">Region</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06dac9854e08794893d4ee5238929c21">Alloc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/gcniterativescheduler/region">Region</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a420cc28ee66403c57d35de57e0d5b6">Regions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c1486e176ff1b7209c9647bb7b2ff0d">Context</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a8f50e93e5644e2551f440ae6efd60014">StrategyKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adee265df6741b5fdd6f8729d32853ad7">Strategy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker">GCNUpwardRPTracker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b98b84a6cc834ba657c411f1ae53d10">UPTracker</a></td>
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


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### ScheduleRef {#abec99f440ac68fa7bf59a142fa6e8c7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GCNIterativeScheduler::ScheduleRef =  ArrayRef&lt;const SUnit *&gt;</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### BaseClass {#ab1b83eb7dc54fa7d2b6a4c4db7c53035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GCNIterativeScheduler::BaseClass =  ScheduleDAGMILive</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### StrategyKind {#a8f50e93e5644e2551f440ae6efd60014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::GCNIterativeScheduler::StrategyKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCHEDULE_MINREGONLY<a id="a8f50e93e5644e2551f440ae6efd60014adfb47441ee2e798bb69902c033beecfc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCHEDULE_MINREGFORCED<a id="a8f50e93e5644e2551f440ae6efd60014a22b41edb7c96fd84528ddc72ab613c99"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCHEDULE_LEGACYMAXOCCUPANCY<a id="a8f50e93e5644e2551f440ae6efd60014a8052712f5608a83be17855aa8f395caa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCHEDULE_ILP<a id="a8f50e93e5644e2551f440ae6efd60014a7c8395842f648353057eff8923dfcc3c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GCNIterativeScheduler() {#a6ca77a3ca62633e1f7f4ed2ff3be6d81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNIterativeScheduler::GCNIterativeScheduler (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C, <a href="#a8f50e93e5644e2551f440ae6efd60014">StrategyKind</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a5c1486e176ff1b7209c9647bb7b2ff0d">Context</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>, <a href="#adee265df6741b5fdd6f8729d32853ad7">Strategy</a> and <a href="#a4b98b84a6cc834ba657c411f1ae53d10">UPTracker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/gcniterativescheduler/builddag/#a87dad70f563f1f17bc834fe2a70cb209">llvm::GCNIterativeScheduler::BuildDAG::BuildDAG</a> and <a href="/web-llvm/docs/api/classes/gcniterativescheduler/overridelegacystrategy/#af81b98ad3eb158abad6175391f4ed6c3">llvm::GCNIterativeScheduler::OverrideLegacyStrategy::OverrideLegacyStrategy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### enterRegion() {#a0fdf731113f2b02fd779a07e4d433717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNIterativeScheduler::enterRegion (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * bb, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> end, unsigned regioninstrs)</td>
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


<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="#a06dac9854e08794893d4ee5238929c21">Alloc</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a34481791fdd8f5d9131431cb0a1a0c01">llvm::ScheduleDAGMILive::enterRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#af1c8be2ff5fd8eab8091e6ffa40ded8d">llvm::ScheduleDAGInstrs::NumRegionInstrs</a> and <a href="#a2a420cc28ee66403c57d35de57e0d5b6">Regions</a>.</p>

</div>
</div>

### finalizeSchedule() {#a9d0ff8af24f7c66a107ce5695a1149dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNIterativeScheduler::finalizeSchedule ()</td>
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

<p>Allow targets to perform final scheduling actions at the level of the whole <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>.</p>


<p>By default does nothing.</p>


<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="#a2a420cc28ee66403c57d35de57e0d5b6">Regions</a>, <a href="#a8f50e93e5644e2551f440ae6efd60014a7c8395842f648353057eff8923dfcc3c">SCHEDULE_ILP</a>, <a href="#a8f50e93e5644e2551f440ae6efd60014a8052712f5608a83be17855aa8f395caa">SCHEDULE_LEGACYMAXOCCUPANCY</a>, <a href="#a8f50e93e5644e2551f440ae6efd60014a22b41edb7c96fd84528ddc72ab613c99">SCHEDULE_MINREGFORCED</a>, <a href="#a8f50e93e5644e2551f440ae6efd60014adfb47441ee2e798bb69902c033beecfc">SCHEDULE_MINREGONLY</a>, <a href="#a424a74f8852d22b010e48f8f6d0c748d">scheduleILP</a>, <a href="#a9d479174d357214e5ea495943b55fdd2">scheduleLegacyMaxOccupancy</a>, <a href="#ab7d457cdee60c23701eca3d110a4862f">scheduleMinReg</a> and <a href="#adee265df6741b5fdd6f8729d32853ad7">Strategy</a>.</p>

</div>
</div>

### schedule() {#ab201710a9597b0df54c12a848d4804d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNIterativeScheduler::schedule ()</td>
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

<p>Orders nodes according to selected style.</p>


<p>Typically, a scheduling algorithm will implement <a href="#ab201710a9597b0df54c12a848d4804d9">schedule()</a> without overriding <a href="#a0fdf731113f2b02fd779a07e4d433717">enterRegion()</a> or <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#abc5a5c32ac78a99ee2633dbbeec20397">exitRegion()</a>.</p>


<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp/#a993feb386f5feed5e9180fd504e0a72a">printLivenessInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae81ad8ece7681af658742f6d4e2fcfb1">llvm::ScheduleDAGInstrs::RegionBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a3f74b283acf0dfb537bc387e49344f04">llvm::ScheduleDAGInstrs::RegionEnd</a> and <a href="#a2a420cc28ee66403c57d35de57e0d5b6">Regions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### detachSchedule() {#af7c58c4a38a2148e0a6eec44b8749bbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; MachineInstr * &gt; GCNIterativeScheduler::detachSchedule (<a href="#abec99f440ac68fa7bf59a142fa6e8c7d">ScheduleRef</a> Schedule)</td>
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



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a6837fb2c08f4c8c986a4689a37ca93cf">llvm::ScheduleDAGInstrs::DbgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a25ae020b571d18d34d03097d91ca0f40">llvm::ScheduleDAGInstrs::FirstDbgValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a8f9d10fa98c86d22e17258c86701191a">setBestSchedule</a>.</p>

</div>
</div>

### getRegionPressure() {#abeb32a2045204d56bbf623bec5da25b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNRegPressure GCNIterativeScheduler::getRegionPressure (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> End)</td>
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



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp/#aee855b0219feb9c43b2f228481a9a010">printRegion</a> and <a href="#a4b98b84a6cc834ba657c411f1ae53d10">UPTracker</a>.</p>


<p>Referenced by <a href="#ae026fc83e46ea2999953bd2b728ea4c7">getRegionPressure</a>, <a href="#a9d479174d357214e5ea495943b55fdd2">scheduleLegacyMaxOccupancy</a> and <a href="#ad899858c4b90e464815c32a7f9c4bb26">scheduleRegion</a>.</p>

</div>
</div>

### getRegionPressure() {#ae026fc83e46ea2999953bd2b728ea4c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNRegPressure llvm::GCNIterativeScheduler::getRegionPressure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gcniterativescheduler/region">Region</a> &amp; R)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>.</p>


<p>Reference <a href="#abeb32a2045204d56bbf623bec5da25b3">getRegionPressure</a>.</p>

</div>
</div>

### getSchedulePressure() {#ab7703967e4547dc33bde51d360068021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Range&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNRegPressure GCNIterativeScheduler::getSchedulePressure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gcniterativescheduler/region">Region</a> &amp; R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> &amp;&amp; Schedule)</td>
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



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp/#ad6ff3262d4ae2e34ffe43edacef3e074">getMachineInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#abd3a9c68e31ad35d6468f200facdd0e3">llvm::ScheduleDAGMILive::RPTracker</a>.</p>


<p>Referenced by <a href="#a424a74f8852d22b010e48f8f6d0c748d">scheduleILP</a>, <a href="#ab7d457cdee60c23701eca3d110a4862f">scheduleMinReg</a>, <a href="#ad899858c4b90e464815c32a7f9c4bb26">scheduleRegion</a> and <a href="#a6fd0550f564608fec7c5d7f25817ddef">tryMaximizeOccupancy</a>.</p>

</div>
</div>

### printRegions() {#a70f01da7bffd10dc0686e3ca4286eac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void GCNIterativeScheduler::printRegions (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp/#a993feb386f5feed5e9180fd504e0a72a">printLivenessInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp/#aee855b0219feb9c43b2f228481a9a010">printRegion</a> and <a href="#a2a420cc28ee66403c57d35de57e0d5b6">Regions</a>.</p>

</div>
</div>

### printSchedResult() {#a6e84e2872d922dee85f4511ac0326f64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void GCNIterativeScheduler::printSchedResult (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gcniterativescheduler/region">Region</a> * R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure">GCNRegPressure</a> &amp; RP)</td>
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



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp/#aee855b0219feb9c43b2f228481a9a010">printRegion</a> and <a href="#a0cb97aff651ff2a97a061183a62dfc01">printSchedRP</a>.</p>


<p>Referenced by <a href="#a424a74f8852d22b010e48f8f6d0c748d">scheduleILP</a> and <a href="#ab7d457cdee60c23701eca3d110a4862f">scheduleMinReg</a>.</p>

</div>
</div>

### printSchedRP() {#a0cb97aff651ff2a97a061183a62dfc01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void GCNIterativeScheduler::printSchedRP (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure">GCNRegPressure</a> &amp; Before, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure">GCNRegPressure</a> &amp; After)</td>
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



<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa7bfcadb5535fe8aad5032762b7bfe159">After</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>.</p>


<p>Referenced by <a href="#a6e84e2872d922dee85f4511ac0326f64">printSchedResult</a>, <a href="#a424a74f8852d22b010e48f8f6d0c748d">scheduleILP</a>, <a href="#a9d479174d357214e5ea495943b55fdd2">scheduleLegacyMaxOccupancy</a> and <a href="#a6fd0550f564608fec7c5d7f25817ddef">tryMaximizeOccupancy</a>.</p>

</div>
</div>

### scheduleBest() {#a51ca74535c09b1424af0a32c4a5b9b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNIterativeScheduler::scheduleBest (<a href="/web-llvm/docs/api/structs/llvm/gcniterativescheduler/region">Region</a> &amp; R)</td>
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



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad899858c4b90e464815c32a7f9c4bb26">scheduleRegion</a>.</p>


<p>Referenced by <a href="#a424a74f8852d22b010e48f8f6d0c748d">scheduleILP</a> and <a href="#a9d479174d357214e5ea495943b55fdd2">scheduleLegacyMaxOccupancy</a>.</p>

</div>
</div>

### scheduleILP() {#a424a74f8852d22b010e48f8f6d0c748d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNIterativeScheduler::scheduleILP (bool TryMaximizeOccupancy=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/gcniterativescheduler/builddag/#a2eac22839b22ca277e0fb8f652f04a24">llvm::GCNIterativeScheduler::BuildDAG::getBottomRoots</a>, <a href="#ab7703967e4547dc33bde51d360068021">getSchedulePressure</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd99b47094ca017035a5489746ed592d">llvm::makeGCNILPScheduler</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#af2cd9b498508774a2da120d08b8d67cc">llvm::ScheduleDAGInstrs::MFI</a>, <a href="#a6e84e2872d922dee85f4511ac0326f64">printSchedResult</a>, <a href="#a0cb97aff651ff2a97a061183a62dfc01">printSchedRP</a>, <a href="#a2a420cc28ee66403c57d35de57e0d5b6">Regions</a>, <a href="#a51ca74535c09b1424af0a32c4a5b9b1f">scheduleBest</a>, <a href="#ad899858c4b90e464815c32a7f9c4bb26">scheduleRegion</a>, <a href="#a19e2ffc6c8269a09ca18d5255ec2345a">sortRegionsByPressure</a> and <a href="#a6fd0550f564608fec7c5d7f25817ddef">tryMaximizeOccupancy</a>.</p>


<p>Referenced by <a href="#a9d0ff8af24f7c66a107ce5695a1149dd">finalizeSchedule</a>.</p>

</div>
</div>

### scheduleLegacyMaxOccupancy() {#a9d479174d357214e5ea495943b55fdd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNIterativeScheduler::scheduleLegacyMaxOccupancy (bool TryMaximizeOccupancy=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5c1486e176ff1b7209c9647bb7b2ff0d">Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#abeb32a2045204d56bbf623bec5da25b3">getRegionPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#af2cd9b498508774a2da120d08b8d67cc">llvm::ScheduleDAGInstrs::MFI</a>, <a href="#a0cb97aff651ff2a97a061183a62dfc01">printSchedRP</a>, <a href="#a2a420cc28ee66403c57d35de57e0d5b6">Regions</a>, <a href="/web-llvm/docs/api/classes/gcniterativescheduler/overridelegacystrategy/#ab193072c8af05e47953c55bcf98e9588">llvm::GCNIterativeScheduler::OverrideLegacyStrategy::restoreOrder</a>, <a href="/web-llvm/docs/api/classes/gcniterativescheduler/overridelegacystrategy/#a852cc4b011f735e6a5669781f98664dd">llvm::GCNIterativeScheduler::OverrideLegacyStrategy::schedule</a>, <a href="#a51ca74535c09b1424af0a32c4a5b9b1f">scheduleBest</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ad79aeb604df3043f82a984f37d9511be">llvm::GCNSchedStrategy::setTargetOccupancy</a>, <a href="#a19e2ffc6c8269a09ca18d5255ec2345a">sortRegionsByPressure</a> and <a href="#a6fd0550f564608fec7c5d7f25817ddef">tryMaximizeOccupancy</a>.</p>


<p>Referenced by <a href="#a9d0ff8af24f7c66a107ce5695a1149dd">finalizeSchedule</a>.</p>

</div>
</div>

### scheduleMinReg() {#ab7d457cdee60c23701eca3d110a4862f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNIterativeScheduler::scheduleMinReg (bool force=false)</td>
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



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ab7703967e4547dc33bde51d360068021">getSchedulePressure</a>, <a href="/web-llvm/docs/api/classes/gcniterativescheduler/builddag/#a48671dab59d61b065c55c44e2116a726">llvm::GCNIterativeScheduler::BuildDAG::getTopRoots</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc6d011d8fad7ac779d8da19213b2301">llvm::makeMinRegSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#af2cd9b498508774a2da120d08b8d67cc">llvm::ScheduleDAGInstrs::MFI</a>, <a href="#a6e84e2872d922dee85f4511ac0326f64">printSchedResult</a>, <a href="#a2a420cc28ee66403c57d35de57e0d5b6">Regions</a>, <a href="#ad899858c4b90e464815c32a7f9c4bb26">scheduleRegion</a> and <a href="#a19e2ffc6c8269a09ca18d5255ec2345a">sortRegionsByPressure</a>.</p>


<p>Referenced by <a href="#a9d0ff8af24f7c66a107ce5695a1149dd">finalizeSchedule</a>.</p>

</div>
</div>

### scheduleRegion() {#ad899858c4b90e464815c32a7f9c4bb26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Range&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNIterativeScheduler::scheduleRegion (<a href="/web-llvm/docs/api/structs/llvm/gcniterativescheduler/region">Region</a> &amp; R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> &amp;&amp; Schedule, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure">GCNRegPressure</a> &amp; MaxRP=<a href="/web-llvm/docs/api/structs/llvm/gcnregpressure">GCNRegPressure</a>())</td>
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



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a8affa4b2a934ff08aa04e63253a00126">llvm::RegisterOperands::adjustLaneLiveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a254403f7804208ade3cb68086201cb7a">llvm::ScheduleDAGInstrs::BB</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a74e0a918c9705f23a1e5b66f68cc97e9">llvm::RegisterOperands::collect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure/#a4b2b440a65af9fa351d2f37fcfcad35b">llvm::GCNRegPressure::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp/#ad6ff3262d4ae2e34ffe43edacef3e074">getMachineInstr</a>, <a href="#abeb32a2045204d56bbf623bec5da25b3">getRegionPressure</a>, <a href="#ab7703967e4547dc33bde51d360068021">getSchedulePressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a1b09f4d9c91e25f7bc2ac60b3b929d11">llvm::ScheduleDAG::MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#ac2dafe98c88d43b256622413886e2152">llvm::ScheduleDAGMI::placeDebugValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae81ad8ece7681af658742f6d4e2fcfb1">llvm::ScheduleDAGInstrs::RegionBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a3f74b283acf0dfb537bc387e49344f04">llvm::ScheduleDAGInstrs::RegionEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>.</p>


<p>Referenced by <a href="#a51ca74535c09b1424af0a32c4a5b9b1f">scheduleBest</a>, <a href="#a424a74f8852d22b010e48f8f6d0c748d">scheduleILP</a> and <a href="#ab7d457cdee60c23701eca3d110a4862f">scheduleMinReg</a>.</p>

</div>
</div>

### setBestSchedule() {#a8f9d10fa98c86d22e17258c86701191a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNIterativeScheduler::setBestSchedule (<a href="/web-llvm/docs/api/structs/llvm/gcniterativescheduler/region">Region</a> &amp; R, <a href="#abec99f440ac68fa7bf59a142fa6e8c7d">ScheduleRef</a> Schedule, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure">GCNRegPressure</a> &amp; MaxRP=<a href="/web-llvm/docs/api/structs/llvm/gcnregpressure">GCNRegPressure</a>())</td>
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



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>Reference <a href="#af7c58c4a38a2148e0a6eec44b8749bbb">detachSchedule</a>.</p>


<p>Referenced by <a href="#a6fd0550f564608fec7c5d7f25817ddef">tryMaximizeOccupancy</a>.</p>

</div>
</div>

### sortRegionsByPressure() {#a19e2ffc6c8269a09ca18d5255ec2345a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNIterativeScheduler::sortRegionsByPressure (unsigned TargetOcc)</td>
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



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/gcniterativescheduler/region/#a8b3a361ed51a19f59699dbdf5534a043">llvm::GCNIterativeScheduler::Region::MaxPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>, <a href="#a2a420cc28ee66403c57d35de57e0d5b6">Regions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#a424a74f8852d22b010e48f8f6d0c748d">scheduleILP</a>, <a href="#a9d479174d357214e5ea495943b55fdd2">scheduleLegacyMaxOccupancy</a> and <a href="#ab7d457cdee60c23701eca3d110a4862f">scheduleMinReg</a>.</p>

</div>
</div>

### tryMaximizeOccupancy() {#a6fd0550f564608fec7c5d7f25817ddef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNIterativeScheduler::tryMaximizeOccupancy (unsigned TargetOcc=std::numeric_limits&lt; unsigned &gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>())</td>
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



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>, definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ab7703967e4547dc33bde51d360068021">getSchedulePressure</a>, <a href="/web-llvm/docs/api/classes/gcniterativescheduler/builddag/#a48671dab59d61b065c55c44e2116a726">llvm::GCNIterativeScheduler::BuildDAG::getTopRoots</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a9d67b1cafa36e90d7060d1da84907885">llvm::ScheduleDAGMI::LIS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc6d011d8fad7ac779d8da19213b2301">llvm::makeMinRegSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a5a3d3d075a208011a24a0918b58d7daa">llvm::ScheduleDAG::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#af2cd9b498508774a2da120d08b8d67cc">llvm::ScheduleDAGInstrs::MFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp/#a993feb386f5feed5e9180fd504e0a72a">printLivenessInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp/#aee855b0219feb9c43b2f228481a9a010">printRegion</a>, <a href="#a0cb97aff651ff2a97a061183a62dfc01">printSchedRP</a>, <a href="#a2a420cc28ee66403c57d35de57e0d5b6">Regions</a> and <a href="#a8f9d10fa98c86d22e17258c86701191a">setBestSchedule</a>.</p>


<p>Referenced by <a href="#a424a74f8852d22b010e48f8f6d0c748d">scheduleILP</a> and <a href="#a9d479174d357214e5ea495943b55fdd2">scheduleLegacyMaxOccupancy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Alloc {#a06dac9854e08794893d4ee5238929c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;Region&gt; llvm::GCNIterativeScheduler::Alloc</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>.</p>


<p>Referenced by <a href="#a0fdf731113f2b02fd779a07e4d433717">enterRegion</a>.</p>

</div>
</div>

### Context {#a5c1486e176ff1b7209c9647bb7b2ff0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSchedContext* llvm::GCNIterativeScheduler::Context</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>.</p>


<p>Referenced by <a href="#a6ca77a3ca62633e1f7f4ed2ff3be6d81">GCNIterativeScheduler</a> and <a href="#a9d479174d357214e5ea495943b55fdd2">scheduleLegacyMaxOccupancy</a>.</p>

</div>
</div>

### Regions {#a2a420cc28ee66403c57d35de57e0d5b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Region*&gt; llvm::GCNIterativeScheduler::Regions</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>.</p>


<p>Referenced by <a href="#a0fdf731113f2b02fd779a07e4d433717">enterRegion</a>, <a href="#a9d0ff8af24f7c66a107ce5695a1149dd">finalizeSchedule</a>, <a href="#a70f01da7bffd10dc0686e3ca4286eac8">printRegions</a>, <a href="#ab201710a9597b0df54c12a848d4804d9">schedule</a>, <a href="#a424a74f8852d22b010e48f8f6d0c748d">scheduleILP</a>, <a href="#a9d479174d357214e5ea495943b55fdd2">scheduleLegacyMaxOccupancy</a>, <a href="#ab7d457cdee60c23701eca3d110a4862f">scheduleMinReg</a>, <a href="#a19e2ffc6c8269a09ca18d5255ec2345a">sortRegionsByPressure</a> and <a href="#a6fd0550f564608fec7c5d7f25817ddef">tryMaximizeOccupancy</a>.</p>

</div>
</div>

### Strategy {#adee265df6741b5fdd6f8729d32853ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StrategyKind llvm::GCNIterativeScheduler::Strategy</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>.</p>


<p>Referenced by <a href="#a9d0ff8af24f7c66a107ce5695a1149dd">finalizeSchedule</a> and <a href="#a6ca77a3ca62633e1f7f4ed2ff3be6d81">GCNIterativeScheduler</a>.</p>

</div>
</div>

### UPTracker {#a4b98b84a6cc834ba657c411f1ae53d10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNUpwardRPTracker llvm::GCNIterativeScheduler::UPTracker</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a>.</p>


<p>Referenced by <a href="#a6ca77a3ca62633e1f7f4ed2ff3be6d81">GCNIterativeScheduler</a> and <a href="#abeb32a2045204d56bbf623bec5da25b3">getRegionPressure</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp">GCNIterativeScheduler.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-h">GCNIterativeScheduler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
