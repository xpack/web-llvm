---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/unclusteredhighrpstage
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `UnclusteredHighRPStage` Class



## Declaration

<div class="doxyDeclaration">
class llvm::UnclusteredHighRPStage { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">Target/AMDGPU/GCNSchedStrategy.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnschedstage">GCNSchedStage</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a100e08f2d866d98e2ce6b12a0d31b174">UnclusteredHighRPStage</a> (GCNSchedStageID StageID, GCNScheduleDAGMILive &amp;DAG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2468e5cc789e17c8e2fb2b6102404e8f">initGCNSchedStage</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a439f8b8a746c9571e58e9aaaa6d60e2c">finalizeGCNSchedStage</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb4889375018fd6bcc64fb3d3258d95">initGCNRegion</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a4f926bc4da7d151b71ea78aa07f2e6">shouldRevertScheduling</a> (unsigned WavesAfter) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5bb9f7d1ded428cd02cf6e75f3ba546">InitialOccupancy</a></td>
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


<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UnclusteredHighRPStage() {#a100e08f2d866d98e2ce6b12a0d31b174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::UnclusteredHighRPStage::UnclusteredHighRPStage (<a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0">GCNSchedStageID</a> StageID, <a href="/web-llvm/docs/api/classes/llvm/gcnscheduledagmilive">GCNScheduleDAGMILive</a> &amp; DAG)</td>
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



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a7b1949efaeff587aabe24ae6865f9e1e">llvm::GCNSchedStage::DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#ad59ed5d84fb3a647d8572705f541e881">llvm::GCNSchedStage::GCNSchedStage</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a82cf0aa779669bf7afa305d3789618d1">llvm::GCNSchedStage::StageID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finalizeGCNSchedStage() {#a439f8b8a746c9571e58e9aaaa6d60e2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnclusteredHighRPStage::finalizeGCNSchedStage ()</td>
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



<p>Declaration at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a7b1949efaeff587aabe24ae6865f9e1e">llvm::GCNSchedStage::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#abe70a14f7fe3a1883d731a8e399535b9">llvm::GCNSchedStage::finalizeGCNSchedStage</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a2f14a5fe09608fc5cce9e68e4f516a68">llvm::GCNSchedStage::S</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#ac9371d95e0cd8d242a9a3fe319105b54">llvm::GCNSchedStage::SavedMutations</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a82cf0aa779669bf7afa305d3789618d1">llvm::GCNSchedStage::StageID</a>.</p>

</div>
</div>

### initGCNRegion() {#a2bb4889375018fd6bcc64fb3d3258d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool UnclusteredHighRPStage::initGCNRegion ()</td>
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



<p>Declaration at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a7b1949efaeff587aabe24ae6865f9e1e">llvm::GCNSchedStage::DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a02add63fe5ce109718dea7e87b1db3c1">llvm::GCNSchedStage::initGCNRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#aa7ee003eb6297edeab5ac83fb99711a0">llvm::GCNSchedStage::RegionIdx</a>.</p>

</div>
</div>

### initGCNSchedStage() {#a2468e5cc789e17c8e2fb2b6102404e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool UnclusteredHighRPStage::initGCNSchedStage ()</td>
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



<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1034 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a38eb48765c2d3082354340365c747dd7">llvm::createIGroupLPDAGMutation</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a7b1949efaeff587aabe24ae6865f9e1e">llvm::GCNSchedStage::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#a6ae238df4eeb83d36a53d78f3f3e373d">DisableUnclusterHighRP</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#abf59722e7890dda4515a601ddf65ce1a">llvm::GCNSchedStage::initGCNSchedStage</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a979d350534fac63dad98d8f2937bf5a7">llvm::GCNSchedStage::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#aa22f1a1dc2d882a5c94b02777ed9a878">llvm::GCNSchedStage::MFI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08a4486548a86dbad26b3c2e8abd22c01d4">llvm::AMDGPU::PreRAReentry</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a2f14a5fe09608fc5cce9e68e4f516a68">llvm::GCNSchedStage::S</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#ac9371d95e0cd8d242a9a3fe319105b54">llvm::GCNSchedStage::SavedMutations</a>.</p>

</div>
</div>

### shouldRevertScheduling() {#a6a4f926bc4da7d151b71ea78aa07f2e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool UnclusteredHighRPStage::shouldRevertScheduling (unsigned WavesAfter)</td>
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



<p>Declaration at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1467 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a7b1949efaeff587aabe24ae6865f9e1e">llvm::GCNSchedStage::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/schedulemetrics/#ae07936418f440db324ca02542a0fa200">llvm::ScheduleMetrics::getMetric</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a741c05e011507c0982568e68fa599a8c">llvm::GCNSchedStage::getScheduleMetrics</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a5344e12321c46ea1f7e78aaaed43f984">llvm::GCNSchedStage::isRegionWithExcessRP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a662bfd2df36d8694de75d5bfc3efcf5a">llvm::GCNSchedStage::mayCauseSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a30bb50e213057f1830b72558972019fa">llvm::GCNSchedStage::PressureBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a2f14a5fe09608fc5cce9e68e4f516a68">llvm::GCNSchedStage::S</a>, <a href="/web-llvm/docs/api/classes/llvm/schedulemetrics/#ad737e526fab5f750adfdbdd427a014fb">llvm::ScheduleMetrics::ScaleFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#af808ad46889f1cea7143a9e6a53c0872">ScheduleMetricBias</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#ac390d9a2fce4a940cbf643a47f699cd7">llvm::GCNSchedStage::shouldRevertScheduling</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#afce50f36ba47b66bbea271c232ac99e2">llvm::GCNSchedStage::ST</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InitialOccupancy {#ab5bb9f7d1ded428cd02cf6e75f3ba546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::UnclusteredHighRPStage::InitialOccupancy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>

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
