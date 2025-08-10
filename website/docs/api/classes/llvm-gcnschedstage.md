---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcnschedstage
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GCNSchedStage` Class



## Declaration

<div class="doxyDeclaration">
class llvm::GCNSchedStage { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">Target/AMDGPU/GCNSchedStrategy.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/clusteredlowoccstage">ClusteredLowOccStage</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilpinitialschedulestage">ILPInitialScheduleStage</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryclauseinitialschedulestage">MemoryClauseInitialScheduleStage</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/occinitialschedulestage">OccInitialScheduleStage</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/prerarematstage">PreRARematStage</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage">UnclusteredHighRPStage</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad59ed5d84fb3a647d8572705f541e881">GCNSchedStage</a> (GCNSchedStageID StageID, GCNScheduleDAGMILive &amp;DAG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02b8c0beec1b20d90013e54dd87e101">~GCNSchedStage</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf59722e7890dda4515a601ddf65ce1a">initGCNSchedStage</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe70a14f7fe3a1883d731a8e399535b9">finalizeGCNSchedStage</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02add63fe5ce109718dea7e87b1db3c1">initGCNRegion</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae61160f05c56687090740404f3ce0862">setupNewBlock</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a999c9b7a7e0362970a608dca15f4c5e0">finalizeGCNRegion</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4200885c657056ba7d712d516e7d4b6">checkScheduling</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulemetrics">ScheduleMetrics</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a741c05e011507c0982568e68fa599a8c">getScheduleMetrics</a> (const std::vector&lt; SUnit &gt; &amp;InputSchedule)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulemetrics">ScheduleMetrics</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35ad2560fecc16262b15e21c9375cf3d">getScheduleMetrics</a> (const GCNScheduleDAGMILive &amp;DAG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaea2f970a2bbb337f3098d43c1fdfb8c">computeSUnitReadyCycle</a> (const SUnit &amp;SU, unsigned CurrCycle, DenseMap&lt; unsigned, unsigned &gt; &amp;ReadyCycles, const TargetSchedModel &amp;SM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac390d9a2fce4a940cbf643a47f699cd7">shouldRevertScheduling</a> (unsigned WavesAfter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5344e12321c46ea1f7e78aaaed43f984">isRegionWithExcessRP</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54723e4447ee0f07e7d3464b96a0c263">getRegionIdx</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a662bfd2df36d8694de75d5bfc3efcf5a">mayCauseSpilling</a> (unsigned WavesAfter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d32369a2a741e4657a7f65cfc32dcdf">revertScheduling</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadceba12093e6e2511da7330a96aaa89">advanceRegion</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnscheduledagmilive">GCNScheduleDAGMILive</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b1949efaeff587aabe24ae6865f9e1e">DAG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy">GCNSchedStrategy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f14a5fe09608fc5cce9e68e4f516a68">S</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a979d350534fac63dad98d8f2937bf5a7">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo">SIMachineFunctionInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa22f1a1dc2d882a5c94b02777ed9a878">MFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afce50f36ba47b66bbea271c232ac99e2">ST</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0">GCNSchedStageID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82cf0aa779669bf7afa305d3789618d1">StageID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af72ae40b5f2dbcbf6898d7420b1250c7">CurrentMBB</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7ee003eb6297edeab5ac83fb99711a0">RegionIdx</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a875f89663ff968a4a76625dd0dd804eb">Unsched</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30bb50e213057f1830b72558972019fa">PressureBefore</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a935e3a2cbb8d260bc1cc4dcf701db0ec">PressureAfter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9371d95e0cd8d242a9a3fe319105b54">SavedMutations</a></td>
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


<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### GCNSchedStage() {#ad59ed5d84fb3a647d8572705f541e881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNSchedStage::GCNSchedStage (<a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0">GCNSchedStageID</a> StageID, <a href="/web-llvm/docs/api/classes/llvm/gcnscheduledagmilive">GCNScheduleDAGMILive</a> &amp; DAG)</td>
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



<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1022 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="#a7b1949efaeff587aabe24ae6865f9e1e">DAG</a>, <a href="#a979d350534fac63dad98d8f2937bf5a7">MF</a>, <a href="#aa22f1a1dc2d882a5c94b02777ed9a878">MFI</a>, <a href="#a2f14a5fe09608fc5cce9e68e4f516a68">S</a>, <a href="#afce50f36ba47b66bbea271c232ac99e2">ST</a> and <a href="#a82cf0aa779669bf7afa305d3789618d1">StageID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/clusteredlowoccstage/#a7ccb50abfa3333f427291e6ea9077e11">llvm::ClusteredLowOccStage::ClusteredLowOccStage</a>, <a href="/web-llvm/docs/api/classes/llvm/ilpinitialschedulestage/#aa73313f4509874173bdd2a149cbe5bf4">llvm::ILPInitialScheduleStage::ILPInitialScheduleStage</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryclauseinitialschedulestage/#a85a197b9e08e18f2facc6d2882221704">llvm::MemoryClauseInitialScheduleStage::MemoryClauseInitialScheduleStage</a>, <a href="/web-llvm/docs/api/classes/llvm/occinitialschedulestage/#a6f3b4391620a006c58fb044432708792">llvm::OccInitialScheduleStage::OccInitialScheduleStage</a>, <a href="/web-llvm/docs/api/classes/llvm/prerarematstage/#a58bb7095351c91b4863f1b8cb5087b97">llvm::PreRARematStage::PreRARematStage</a> and <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a100e08f2d866d98e2ce6b12a0d31b174">llvm::UnclusteredHighRPStage::UnclusteredHighRPStage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~GCNSchedStage() {#ab02b8c0beec1b20d90013e54dd87e101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::GCNSchedStage::~GCNSchedStage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### advanceRegion() {#aadceba12093e6e2511da7330a96aaa89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GCNSchedStage::advanceRegion ()</td>
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



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Reference <a href="#aa7ee003eb6297edeab5ac83fb99711a0">RegionIdx</a>.</p>

</div>
</div>

### checkScheduling() {#aa4200885c657056ba7d712d516e7d4b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNSchedStage::checkScheduling ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="#a7b1949efaeff587aabe24ae6865f9e1e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a979d350534fac63dad98d8f2937bf5a7">MF</a>, <a href="#aa22f1a1dc2d882a5c94b02777ed9a878">MFI</a>, <a href="#a935e3a2cbb8d260bc1cc4dcf701db0ec">PressureAfter</a>, <a href="#a30bb50e213057f1830b72558972019fa">PressureBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>, <a href="#aa7ee003eb6297edeab5ac83fb99711a0">RegionIdx</a>, <a href="#a3d32369a2a741e4657a7f65cfc32dcdf">revertScheduling</a>, <a href="#a2f14a5fe09608fc5cce9e68e4f516a68">S</a>, <a href="#ac390d9a2fce4a940cbf643a47f699cd7">shouldRevertScheduling</a> and <a href="#afce50f36ba47b66bbea271c232ac99e2">ST</a>.</p>


<p>Referenced by <a href="#a999c9b7a7e0362970a608dca15f4c5e0">finalizeGCNRegion</a>.</p>

</div>
</div>

### computeSUnitReadyCycle() {#aaea2f970a2bbb337f3098d43c1fdfb8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNSchedStage::computeSUnitReadyCycle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; SU, unsigned CurrCycle, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt; &amp; ReadyCycles, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> &amp; SM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a7b1949efaeff587aabe24ae6865f9e1e">DAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a2d68d32ff95cd10b4899c2823ec28e97">llvm::Latency</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>.</p>


<p>Referenced by <a href="#a35ad2560fecc16262b15e21c9375cf3d">getScheduleMetrics</a> and <a href="#a741c05e011507c0982568e68fa599a8c">getScheduleMetrics</a>.</p>

</div>
</div>

### finalizeGCNRegion() {#a999c9b7a7e0362970a608dca15f4c5e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNSchedStage::finalizeGCNRegion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="#aa4200885c657056ba7d712d516e7d4b6">checkScheduling</a>, <a href="#a7b1949efaeff587aabe24ae6865f9e1e">DAG</a>, <a href="#aa7ee003eb6297edeab5ac83fb99711a0">RegionIdx</a>, <a href="#a2f14a5fe09608fc5cce9e68e4f516a68">S</a>, <a href="#ac9371d95e0cd8d242a9a3fe319105b54">SavedMutations</a>, <a href="#a82cf0aa779669bf7afa305d3789618d1">StageID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0a3199673fa17ebc25c0c9925028d225e0">llvm::UnclusteredHighRPReschedule</a>.</p>

</div>
</div>

### finalizeGCNSchedStage() {#abe70a14f7fe3a1883d731a8e399535b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNSchedStage::finalizeGCNSchedStage ()</td>
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



<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="#a7b1949efaeff587aabe24ae6865f9e1e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a82cf0aa779669bf7afa305d3789618d1">StageID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a439f8b8a746c9571e58e9aaaa6d60e2c">llvm::UnclusteredHighRPStage::finalizeGCNSchedStage</a>.</p>

</div>
</div>

### getRegionIdx() {#a54723e4447ee0f07e7d3464b96a0c263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSchedStage::getRegionIdx ()</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Reference <a href="#aa7ee003eb6297edeab5ac83fb99711a0">RegionIdx</a>.</p>

</div>
</div>

### getScheduleMetrics() {#a741c05e011507c0982568e68fa599a8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleMetrics GCNSchedStage::getScheduleMetrics (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &gt; &amp; InputSchedule)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="#aaea2f970a2bbb337f3098d43c1fdfb8c">computeSUnitReadyCycle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#a76923341fddafb3d1ed56aef0569ee68">printScheduleModel</a>, <a href="/web-llvm/docs/api/classes/llvm/schedulemetrics/#ad737e526fab5f750adfdbdd427a014fb">llvm::ScheduleMetrics::ScaleFactor</a> and <a href="#afce50f36ba47b66bbea271c232ac99e2">ST</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a6a4f926bc4da7d151b71ea78aa07f2e6">llvm::UnclusteredHighRPStage::shouldRevertScheduling</a>.</p>

</div>
</div>

### getScheduleMetrics() {#a35ad2560fecc16262b15e21c9375cf3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleMetrics GCNSchedStage::getScheduleMetrics (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnscheduledagmilive">GCNScheduleDAGMILive</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="#aaea2f970a2bbb337f3098d43c1fdfb8c">computeSUnitReadyCycle</a>, <a href="#a7b1949efaeff587aabe24ae6865f9e1e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#a76923341fddafb3d1ed56aef0569ee68">printScheduleModel</a>, <a href="/web-llvm/docs/api/classes/llvm/schedulemetrics/#ad737e526fab5f750adfdbdd427a014fb">llvm::ScheduleMetrics::ScaleFactor</a> and <a href="#afce50f36ba47b66bbea271c232ac99e2">ST</a>.</p>

</div>
</div>

### initGCNRegion() {#a02add63fe5ce109718dea7e87b1db3c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNSchedStage::initGCNRegion ()</td>
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



<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a38eb48765c2d3082354340365c747dd7">llvm::createIGroupLPDAGMutation</a>, <a href="#af72ae40b5f2dbcbf6898d7420b1250c7">CurrentMBB</a>, <a href="#a7b1949efaeff587aabe24ae6865f9e1e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a273ec9d4a470ecb7362abd00438e9b26">llvm::getRegPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0a6fc19a20667f6a2cc7adb83e3f67a487">llvm::ILPInitialSchedule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08a4f2a91e15af2631ff9424564b8a45fb2">llvm::AMDGPU::Initial</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#a4eadfed0a19cd148a823630f4d480939">isIGLPMutationOnly</a>, <a href="#a5344e12321c46ea1f7e78aaaed43f984">isRegionWithExcessRP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a979d350534fac63dad98d8f2937bf5a7">MF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0afc7d208fa38407036d4d3dfc7ac1ccff">llvm::OccInitialSchedule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08a4486548a86dbad26b3c2e8abd22c01d4">llvm::AMDGPU::PreRAReentry</a>, <a href="#a30bb50e213057f1830b72558972019fa">PressureBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="#aa7ee003eb6297edeab5ac83fb99711a0">RegionIdx</a>, <a href="#a2f14a5fe09608fc5cce9e68e4f516a68">S</a>, <a href="#ac9371d95e0cd8d242a9a3fe319105b54">SavedMutations</a>, <a href="#ae61160f05c56687090740404f3ce0862">setupNewBlock</a>, <a href="#a82cf0aa779669bf7afa305d3789618d1">StageID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0a3199673fa17ebc25c0c9925028d225e0">llvm::UnclusteredHighRPReschedule</a> and <a href="#a875f89663ff968a4a76625dd0dd804eb">Unsched</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/clusteredlowoccstage/#a251a257a2bc03ff04c73072f8d7eeb8d">llvm::ClusteredLowOccStage::initGCNRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/prerarematstage/#adaf8209252a511c74f8db1e37b572672">llvm::PreRARematStage::initGCNRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a2bb4889375018fd6bcc64fb3d3258d95">llvm::UnclusteredHighRPStage::initGCNRegion</a>.</p>

</div>
</div>

### initGCNSchedStage() {#abf59722e7890dda4515a601ddf65ce1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNSchedStage::initGCNSchedStage ()</td>
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



<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1026 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="#a7b1949efaeff587aabe24ae6865f9e1e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a82cf0aa779669bf7afa305d3789618d1">StageID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/clusteredlowoccstage/#a0bdb7b684aa1f51dc79bf9b7f9bf079f">llvm::ClusteredLowOccStage::initGCNSchedStage</a>, <a href="/web-llvm/docs/api/classes/llvm/prerarematstage/#aef3c65c6f9af28a14119e3fcee53f17a">llvm::PreRARematStage::initGCNSchedStage</a> and <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a2468e5cc789e17c8e2fb2b6102404e8f">llvm::UnclusteredHighRPStage::initGCNSchedStage</a>.</p>

</div>
</div>

### isRegionWithExcessRP() {#a5344e12321c46ea1f7e78aaaed43f984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNSchedStage::isRegionWithExcessRP ()</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>References <a href="#a7b1949efaeff587aabe24ae6865f9e1e">DAG</a> and <a href="#aa7ee003eb6297edeab5ac83fb99711a0">RegionIdx</a>.</p>


<p>Referenced by <a href="#a02add63fe5ce109718dea7e87b1db3c1">initGCNRegion</a>, <a href="#a662bfd2df36d8694de75d5bfc3efcf5a">mayCauseSpilling</a> and <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a6a4f926bc4da7d151b71ea78aa07f2e6">llvm::UnclusteredHighRPStage::shouldRevertScheduling</a>.</p>

</div>
</div>

### mayCauseSpilling() {#a662bfd2df36d8694de75d5bfc3efcf5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNSchedStage::mayCauseSpilling (unsigned WavesAfter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1540 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a5344e12321c46ea1f7e78aaaed43f984">isRegionWithExcessRP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a979d350534fac63dad98d8f2937bf5a7">MF</a>, <a href="#aa22f1a1dc2d882a5c94b02777ed9a878">MFI</a>, <a href="#a935e3a2cbb8d260bc1cc4dcf701db0ec">PressureAfter</a> and <a href="#a30bb50e213057f1830b72558972019fa">PressureBefore</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/clusteredlowoccstage/#a127448c080b34adaa6a570697e88ea41">llvm::ClusteredLowOccStage::shouldRevertScheduling</a>, <a href="/web-llvm/docs/api/classes/llvm/ilpinitialschedulestage/#a0ba423ecf423204880b387df3fc52c91">llvm::ILPInitialScheduleStage::shouldRevertScheduling</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryclauseinitialschedulestage/#a37d6eaa9ef6b28eb745bb086a076f5af">llvm::MemoryClauseInitialScheduleStage::shouldRevertScheduling</a>, <a href="/web-llvm/docs/api/classes/llvm/occinitialschedulestage/#a6059a5bf340a6ed8e1c76e25bebf5485">llvm::OccInitialScheduleStage::shouldRevertScheduling</a>, <a href="/web-llvm/docs/api/classes/llvm/prerarematstage/#a639de91c60044b41677c7f4b01c38a4c">llvm::PreRARematStage::shouldRevertScheduling</a> and <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a6a4f926bc4da7d151b71ea78aa07f2e6">llvm::UnclusteredHighRPStage::shouldRevertScheduling</a>.</p>

</div>
</div>

### revertScheduling() {#a3d32369a2a741e4657a7f65cfc32dcdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNSchedStage::revertScheduling ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1550 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a8affa4b2a934ff08aa04e63253a00126">llvm::RegisterOperands::adjustLaneLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a74e0a918c9705f23a1e5b66f68cc97e9">llvm::RegisterOperands::collect</a>, <a href="#a7b1949efaeff587aabe24ae6865f9e1e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#acee6dacd4d30da478f3ad67f7fc27142">llvm::RegisterOperands::detectDeadDefs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a30bb50e213057f1830b72558972019fa">PressureBefore</a>, <a href="#aa7ee003eb6297edeab5ac83fb99711a0">RegionIdx</a>, <a href="#a2f14a5fe09608fc5cce9e68e4f516a68">S</a>, <a href="#afce50f36ba47b66bbea271c232ac99e2">ST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0a3199673fa17ebc25c0c9925028d225e0">llvm::UnclusteredHighRPReschedule</a> and <a href="#a875f89663ff968a4a76625dd0dd804eb">Unsched</a>.</p>


<p>Referenced by <a href="#aa4200885c657056ba7d712d516e7d4b6">checkScheduling</a>.</p>

</div>
</div>

### setupNewBlock() {#ae61160f05c56687090740404f3ce0862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNSchedStage::setupNewBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="#af72ae40b5f2dbcbf6898d7420b1250c7">CurrentMBB</a>, <a href="#a7b1949efaeff587aabe24ae6865f9e1e">DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0a6fc19a20667f6a2cc7adb83e3f67a487">llvm::ILPInitialSchedule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0a414873aebe374e5386fe3382107061d8">llvm::MemoryClauseInitialSchedule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0afc7d208fa38407036d4d3dfc7ac1ccff">llvm::OccInitialSchedule</a>, <a href="#aa7ee003eb6297edeab5ac83fb99711a0">RegionIdx</a> and <a href="#a82cf0aa779669bf7afa305d3789618d1">StageID</a>.</p>


<p>Referenced by <a href="#a02add63fe5ce109718dea7e87b1db3c1">initGCNRegion</a>.</p>

</div>
</div>

### shouldRevertScheduling() {#ac390d9a2fce4a940cbf643a47f699cd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNSchedStage::shouldRevertScheduling (unsigned WavesAfter)</td>
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



<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1447 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>Reference <a href="#a7b1949efaeff587aabe24ae6865f9e1e">DAG</a>.</p>


<p>Referenced by <a href="#aa4200885c657056ba7d712d516e7d4b6">checkScheduling</a>, <a href="/web-llvm/docs/api/classes/llvm/clusteredlowoccstage/#a127448c080b34adaa6a570697e88ea41">llvm::ClusteredLowOccStage::shouldRevertScheduling</a>, <a href="/web-llvm/docs/api/classes/llvm/occinitialschedulestage/#a6059a5bf340a6ed8e1c76e25bebf5485">llvm::OccInitialScheduleStage::shouldRevertScheduling</a>, <a href="/web-llvm/docs/api/classes/llvm/prerarematstage/#a639de91c60044b41677c7f4b01c38a4c">llvm::PreRARematStage::shouldRevertScheduling</a> and <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a6a4f926bc4da7d151b71ea78aa07f2e6">llvm::UnclusteredHighRPStage::shouldRevertScheduling</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CurrentMBB {#af72ae40b5f2dbcbf6898d7420b1250c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::GCNSchedStage::CurrentMBB = nullptr</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#a02add63fe5ce109718dea7e87b1db3c1">initGCNRegion</a> and <a href="#ae61160f05c56687090740404f3ce0862">setupNewBlock</a>.</p>

</div>
</div>

### DAG {#a7b1949efaeff587aabe24ae6865f9e1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNScheduleDAGMILive&amp; llvm::GCNSchedStage::DAG</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#aa4200885c657056ba7d712d516e7d4b6">checkScheduling</a>, <a href="/web-llvm/docs/api/classes/llvm/clusteredlowoccstage/#a7ccb50abfa3333f427291e6ea9077e11">llvm::ClusteredLowOccStage::ClusteredLowOccStage</a>, <a href="#aaea2f970a2bbb337f3098d43c1fdfb8c">computeSUnitReadyCycle</a>, <a href="#a999c9b7a7e0362970a608dca15f4c5e0">finalizeGCNRegion</a>, <a href="#abe70a14f7fe3a1883d731a8e399535b9">finalizeGCNSchedStage</a>, <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a439f8b8a746c9571e58e9aaaa6d60e2c">llvm::UnclusteredHighRPStage::finalizeGCNSchedStage</a>, <a href="#ad59ed5d84fb3a647d8572705f541e881">GCNSchedStage</a>, <a href="#a35ad2560fecc16262b15e21c9375cf3d">getScheduleMetrics</a>, <a href="/web-llvm/docs/api/classes/llvm/ilpinitialschedulestage/#aa73313f4509874173bdd2a149cbe5bf4">llvm::ILPInitialScheduleStage::ILPInitialScheduleStage</a>, <a href="/web-llvm/docs/api/classes/llvm/clusteredlowoccstage/#a251a257a2bc03ff04c73072f8d7eeb8d">llvm::ClusteredLowOccStage::initGCNRegion</a>, <a href="#a02add63fe5ce109718dea7e87b1db3c1">initGCNRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/prerarematstage/#adaf8209252a511c74f8db1e37b572672">llvm::PreRARematStage::initGCNRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a2bb4889375018fd6bcc64fb3d3258d95">llvm::UnclusteredHighRPStage::initGCNRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/clusteredlowoccstage/#a0bdb7b684aa1f51dc79bf9b7f9bf079f">llvm::ClusteredLowOccStage::initGCNSchedStage</a>, <a href="#abf59722e7890dda4515a601ddf65ce1a">initGCNSchedStage</a>, <a href="/web-llvm/docs/api/classes/llvm/prerarematstage/#aef3c65c6f9af28a14119e3fcee53f17a">llvm::PreRARematStage::initGCNSchedStage</a>, <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a2468e5cc789e17c8e2fb2b6102404e8f">llvm::UnclusteredHighRPStage::initGCNSchedStage</a>, <a href="#a5344e12321c46ea1f7e78aaaed43f984">isRegionWithExcessRP</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryclauseinitialschedulestage/#a85a197b9e08e18f2facc6d2882221704">llvm::MemoryClauseInitialScheduleStage::MemoryClauseInitialScheduleStage</a>, <a href="/web-llvm/docs/api/classes/llvm/occinitialschedulestage/#a6f3b4391620a006c58fb044432708792">llvm::OccInitialScheduleStage::OccInitialScheduleStage</a>, <a href="/web-llvm/docs/api/classes/llvm/prerarematstage/#a58bb7095351c91b4863f1b8cb5087b97">llvm::PreRARematStage::PreRARematStage</a>, <a href="#a3d32369a2a741e4657a7f65cfc32dcdf">revertScheduling</a>, <a href="#ae61160f05c56687090740404f3ce0862">setupNewBlock</a>, <a href="#ac390d9a2fce4a940cbf643a47f699cd7">shouldRevertScheduling</a>, <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a6a4f926bc4da7d151b71ea78aa07f2e6">llvm::UnclusteredHighRPStage::shouldRevertScheduling</a> and <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a100e08f2d866d98e2ce6b12a0d31b174">llvm::UnclusteredHighRPStage::UnclusteredHighRPStage</a>.</p>

</div>
</div>

### MF {#a979d350534fac63dad98d8f2937bf5a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; llvm::GCNSchedStage::MF</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#aa4200885c657056ba7d712d516e7d4b6">checkScheduling</a>, <a href="#ad59ed5d84fb3a647d8572705f541e881">GCNSchedStage</a>, <a href="#a02add63fe5ce109718dea7e87b1db3c1">initGCNRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/prerarematstage/#aef3c65c6f9af28a14119e3fcee53f17a">llvm::PreRARematStage::initGCNSchedStage</a>, <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a2468e5cc789e17c8e2fb2b6102404e8f">llvm::UnclusteredHighRPStage::initGCNSchedStage</a> and <a href="#a662bfd2df36d8694de75d5bfc3efcf5a">mayCauseSpilling</a>.</p>

</div>
</div>

### MFI {#aa22f1a1dc2d882a5c94b02777ed9a878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIMachineFunctionInfo&amp; llvm::GCNSchedStage::MFI</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#aa4200885c657056ba7d712d516e7d4b6">checkScheduling</a>, <a href="#ad59ed5d84fb3a647d8572705f541e881">GCNSchedStage</a>, <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a2468e5cc789e17c8e2fb2b6102404e8f">llvm::UnclusteredHighRPStage::initGCNSchedStage</a> and <a href="#a662bfd2df36d8694de75d5bfc3efcf5a">mayCauseSpilling</a>.</p>

</div>
</div>

### PressureAfter {#a935e3a2cbb8d260bc1cc4dcf701db0ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNRegPressure llvm::GCNSchedStage::PressureAfter</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#aa4200885c657056ba7d712d516e7d4b6">checkScheduling</a>, <a href="#a662bfd2df36d8694de75d5bfc3efcf5a">mayCauseSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/clusteredlowoccstage/#a127448c080b34adaa6a570697e88ea41">llvm::ClusteredLowOccStage::shouldRevertScheduling</a> and <a href="/web-llvm/docs/api/classes/llvm/occinitialschedulestage/#a6059a5bf340a6ed8e1c76e25bebf5485">llvm::OccInitialScheduleStage::shouldRevertScheduling</a>.</p>

</div>
</div>

### PressureBefore {#a30bb50e213057f1830b72558972019fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNRegPressure llvm::GCNSchedStage::PressureBefore</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#aa4200885c657056ba7d712d516e7d4b6">checkScheduling</a>, <a href="#a02add63fe5ce109718dea7e87b1db3c1">initGCNRegion</a>, <a href="#a662bfd2df36d8694de75d5bfc3efcf5a">mayCauseSpilling</a>, <a href="#a3d32369a2a741e4657a7f65cfc32dcdf">revertScheduling</a>, <a href="/web-llvm/docs/api/classes/llvm/clusteredlowoccstage/#a127448c080b34adaa6a570697e88ea41">llvm::ClusteredLowOccStage::shouldRevertScheduling</a>, <a href="/web-llvm/docs/api/classes/llvm/occinitialschedulestage/#a6059a5bf340a6ed8e1c76e25bebf5485">llvm::OccInitialScheduleStage::shouldRevertScheduling</a> and <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a6a4f926bc4da7d151b71ea78aa07f2e6">llvm::UnclusteredHighRPStage::shouldRevertScheduling</a>.</p>

</div>
</div>

### RegionIdx {#aa7ee003eb6297edeab5ac83fb99711a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNSchedStage::RegionIdx = 0</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#aadceba12093e6e2511da7330a96aaa89">advanceRegion</a>, <a href="#aa4200885c657056ba7d712d516e7d4b6">checkScheduling</a>, <a href="#a999c9b7a7e0362970a608dca15f4c5e0">finalizeGCNRegion</a>, <a href="#a54723e4447ee0f07e7d3464b96a0c263">getRegionIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/clusteredlowoccstage/#a251a257a2bc03ff04c73072f8d7eeb8d">llvm::ClusteredLowOccStage::initGCNRegion</a>, <a href="#a02add63fe5ce109718dea7e87b1db3c1">initGCNRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/prerarematstage/#adaf8209252a511c74f8db1e37b572672">llvm::PreRARematStage::initGCNRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a2bb4889375018fd6bcc64fb3d3258d95">llvm::UnclusteredHighRPStage::initGCNRegion</a>, <a href="#a5344e12321c46ea1f7e78aaaed43f984">isRegionWithExcessRP</a>, <a href="#a3d32369a2a741e4657a7f65cfc32dcdf">revertScheduling</a> and <a href="#ae61160f05c56687090740404f3ce0862">setupNewBlock</a>.</p>

</div>
</div>

### S {#a2f14a5fe09608fc5cce9e68e4f516a68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNSchedStrategy&amp; llvm::GCNSchedStage::S</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#aa4200885c657056ba7d712d516e7d4b6">checkScheduling</a>, <a href="#a999c9b7a7e0362970a608dca15f4c5e0">finalizeGCNRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a439f8b8a746c9571e58e9aaaa6d60e2c">llvm::UnclusteredHighRPStage::finalizeGCNSchedStage</a>, <a href="#ad59ed5d84fb3a647d8572705f541e881">GCNSchedStage</a>, <a href="#a02add63fe5ce109718dea7e87b1db3c1">initGCNRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/prerarematstage/#aef3c65c6f9af28a14119e3fcee53f17a">llvm::PreRARematStage::initGCNSchedStage</a>, <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a2468e5cc789e17c8e2fb2b6102404e8f">llvm::UnclusteredHighRPStage::initGCNSchedStage</a>, <a href="#a3d32369a2a741e4657a7f65cfc32dcdf">revertScheduling</a> and <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a6a4f926bc4da7d151b71ea78aa07f2e6">llvm::UnclusteredHighRPStage::shouldRevertScheduling</a>.</p>

</div>
</div>

### SavedMutations {#ac9371d95e0cd8d242a9a3fe319105b54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;ScheduleDAGMutation&gt; &gt; llvm::GCNSchedStage::SavedMutations</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#a999c9b7a7e0362970a608dca15f4c5e0">finalizeGCNRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a439f8b8a746c9571e58e9aaaa6d60e2c">llvm::UnclusteredHighRPStage::finalizeGCNSchedStage</a>, <a href="#a02add63fe5ce109718dea7e87b1db3c1">initGCNRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a2468e5cc789e17c8e2fb2b6102404e8f">llvm::UnclusteredHighRPStage::initGCNSchedStage</a>.</p>

</div>
</div>

### ST {#afce50f36ba47b66bbea271c232ac99e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget&amp; llvm::GCNSchedStage::ST</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#aa4200885c657056ba7d712d516e7d4b6">checkScheduling</a>, <a href="#ad59ed5d84fb3a647d8572705f541e881">GCNSchedStage</a>, <a href="#a35ad2560fecc16262b15e21c9375cf3d">getScheduleMetrics</a>, <a href="#a741c05e011507c0982568e68fa599a8c">getScheduleMetrics</a>, <a href="/web-llvm/docs/api/classes/llvm/prerarematstage/#aef3c65c6f9af28a14119e3fcee53f17a">llvm::PreRARematStage::initGCNSchedStage</a>, <a href="#a3d32369a2a741e4657a7f65cfc32dcdf">revertScheduling</a> and <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a6a4f926bc4da7d151b71ea78aa07f2e6">llvm::UnclusteredHighRPStage::shouldRevertScheduling</a>.</p>

</div>
</div>

### StageID {#a82cf0aa779669bf7afa305d3789618d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSchedStageID llvm::GCNSchedStage::StageID</td>
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



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/clusteredlowoccstage/#a7ccb50abfa3333f427291e6ea9077e11">llvm::ClusteredLowOccStage::ClusteredLowOccStage</a>, <a href="#a999c9b7a7e0362970a608dca15f4c5e0">finalizeGCNRegion</a>, <a href="#abe70a14f7fe3a1883d731a8e399535b9">finalizeGCNSchedStage</a>, <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a439f8b8a746c9571e58e9aaaa6d60e2c">llvm::UnclusteredHighRPStage::finalizeGCNSchedStage</a>, <a href="#ad59ed5d84fb3a647d8572705f541e881">GCNSchedStage</a>, <a href="/web-llvm/docs/api/classes/llvm/ilpinitialschedulestage/#aa73313f4509874173bdd2a149cbe5bf4">llvm::ILPInitialScheduleStage::ILPInitialScheduleStage</a>, <a href="#a02add63fe5ce109718dea7e87b1db3c1">initGCNRegion</a>, <a href="#abf59722e7890dda4515a601ddf65ce1a">initGCNSchedStage</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryclauseinitialschedulestage/#a85a197b9e08e18f2facc6d2882221704">llvm::MemoryClauseInitialScheduleStage::MemoryClauseInitialScheduleStage</a>, <a href="/web-llvm/docs/api/classes/llvm/occinitialschedulestage/#a6f3b4391620a006c58fb044432708792">llvm::OccInitialScheduleStage::OccInitialScheduleStage</a>, <a href="/web-llvm/docs/api/classes/llvm/prerarematstage/#a58bb7095351c91b4863f1b8cb5087b97">llvm::PreRARematStage::PreRARematStage</a>, <a href="#ae61160f05c56687090740404f3ce0862">setupNewBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a100e08f2d866d98e2ce6b12a0d31b174">llvm::UnclusteredHighRPStage::UnclusteredHighRPStage</a>.</p>

</div>
</div>

### Unsched {#a875f89663ff968a4a76625dd0dd804eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineInstr *&gt; llvm::GCNSchedStage::Unsched</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#a02add63fe5ce109718dea7e87b1db3c1">initGCNRegion</a> and <a href="#a3d32369a2a741e4657a7f65cfc32dcdf">revertScheduling</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
