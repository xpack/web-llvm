---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/occinitialschedulestage
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OccInitialScheduleStage` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::OccInitialScheduleStage { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f3b4391620a006c58fb044432708792">OccInitialScheduleStage</a> (GCNSchedStageID StageID, GCNScheduleDAGMILive &amp;DAG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6059a5bf340a6ed8e1c76e25bebf5485">shouldRevertScheduling</a> (unsigned WavesAfter) override</td>
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


<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OccInitialScheduleStage() {#a6f3b4391620a006c58fb044432708792}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OccInitialScheduleStage::OccInitialScheduleStage (<a href="/web-llvm/docs/api/namespaces/llvm/#a66b412ba6b33cdefeb59dde7139dc8b0">GCNSchedStageID</a> StageID, <a href="/web-llvm/docs/api/classes/llvm/gcnscheduledagmilive">GCNScheduleDAGMILive</a> &amp; DAG)</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a7b1949efaeff587aabe24ae6865f9e1e">llvm::GCNSchedStage::DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#ad59ed5d84fb3a647d8572705f541e881">llvm::GCNSchedStage::GCNSchedStage</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a82cf0aa779669bf7afa305d3789618d1">llvm::GCNSchedStage::StageID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### shouldRevertScheduling() {#a6059a5bf340a6ed8e1c76e25bebf5485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OccInitialScheduleStage::shouldRevertScheduling (unsigned WavesAfter)</td>
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



<p>Declaration at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>, definition at line 1454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp">GCNSchedStrategy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a662bfd2df36d8694de75d5bfc3efcf5a">llvm::GCNSchedStage::mayCauseSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a935e3a2cbb8d260bc1cc4dcf701db0ec">llvm::GCNSchedStage::PressureAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a30bb50e213057f1830b72558972019fa">llvm::GCNSchedStage::PressureBefore</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#ac390d9a2fce4a940cbf643a47f699cd7">llvm::GCNSchedStage::shouldRevertScheduling</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
