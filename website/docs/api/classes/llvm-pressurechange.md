---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pressurechange
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PressureChange` Class Reference

<p>Capture a change in pressure for a single pressure set. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PressureChange { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">llvm/CodeGen/RegisterPressure.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cc3404c1d3dfcbccbd103421f1e5a59">PressureChange</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac7528a7d1fa84b8c643a2de33403b7c">PressureChange</a> (unsigned id)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a673b0c67d98e87c5ada243dddbff2df0">operator==</a> (const PressureChange &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a488d33ac015981b0f8e2086fcbd49db2">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad47247ae6eaa7104e4d4ef6e002840f9">getPSet</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2914e3c0dd7cb72d6d1eb4343a0bd6c9">getPSetOrMax</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eef24878593ee0080b20b96ce3eb4c4">getUnitInc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b74a0d0d1bc2e22fa7376eda3fdd85f">setUnitInc</a> (int Inc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a403007f54c31c2c26d7b0cd651d62e20">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acffdb87e05bb5de516aa23c757f9b101">PSetID</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c6ee68fdbf9d7825b0312938b4cd7e1">UnitInc</a> = 0</td>
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

<p>Capture a change in pressure for a single pressure set.</p>


<p>UnitInc may be expressed in terms of upward or downward pressure depending on the client and will be dynamically adjusted for current liveness.</p>


<p>Pressure increments are tiny, typically 1-2 units, and this is only for heuristics, so we don't check UnitInc overflow. Instead, we may have a higher level assert that pressure is consistent within a region. We also effectively ignore dead defs which don't affect heuristics much.</p>


<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PressureChange() {#a8cc3404c1d3dfcbccbd103421f1e5a59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PressureChange::PressureChange ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="#a673b0c67d98e87c5ada243dddbff2df0">operator==</a>.</p>

</div>
</div>

### PressureChange() {#aac7528a7d1fa84b8c643a2de33403b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PressureChange::PressureChange (unsigned id)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#a673b0c67d98e87c5ada243dddbff2df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PressureChange::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pressurechange">PressureChange</a> &amp; RHS)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>References <a href="#a8cc3404c1d3dfcbccbd103421f1e5a59">PressureChange</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a403007f54c31c2c26d7b0cd651d62e20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void PressureChange::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a2914e3c0dd7cb72d6d1eb4343a0bd6c9">getPSetOrMax</a> and <a href="#a1eef24878593ee0080b20b96ce3eb4c4">getUnitInc</a>.</p>

</div>
</div>

### getPSet() {#ad47247ae6eaa7104e4d4ef6e002840f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PressureChange::getPSet ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a488d33ac015981b0f8e2086fcbd49db2">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pressurediff/#a86962b61c920a437e06eda5dafd929d5">llvm::PressureDiff::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a41a3118fb6bd46e397256b3c9794b61c">llvm::RegPressureTracker::getMaxUpwardPressureDelta</a> and <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ab0d12eb20352f092840f7f8df60abe26">llvm::GenericScheduler::initCandidate</a>.</p>

</div>
</div>

### getPSetOrMax() {#a2914e3c0dd7cb72d6d1eb4343a0bd6c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PressureChange::getPSetOrMax ()</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="#a403007f54c31c2c26d7b0cd651d62e20">dump</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a62cf34ac18c5612524978166788b5c80">llvm::tryPressure</a>.</p>

</div>
</div>

### getUnitInc() {#a1eef24878593ee0080b20b96ce3eb4c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::PressureChange::getUnitInc ()</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="#a403007f54c31c2c26d7b0cd651d62e20">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurediff/#a86962b61c920a437e06eda5dafd929d5">llvm::PressureDiff::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a972fa38378a3d49a9bb48ca584621438">llvm::RegPressureTracker::getMaxDownwardPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a41a3118fb6bd46e397256b3c9794b61c">llvm::RegPressureTracker::getMaxUpwardPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ab0d12eb20352f092840f7f8df60abe26">llvm::GenericScheduler::initCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a62cf34ac18c5612524978166788b5c80">llvm::tryPressure</a>.</p>

</div>
</div>

### isValid() {#a488d33ac015981b0f8e2086fcbd49db2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PressureChange::isValid ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pressurediffs/#aa61bffce687c1adbbd0a96f292496128">llvm::PressureDiffs::addInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurediff/#aae6716327eea2325dc426c98cbcc74b4">llvm::PressureDiff::addPressureChange</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a822aec28298cd2dc8f346d4753a4154b">computeMaxPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurediff/#a86962b61c920a437e06eda5dafd929d5">llvm::PressureDiff::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a41a3118fb6bd46e397256b3c9794b61c">llvm::RegPressureTracker::getMaxUpwardPressureDelta</a>, <a href="#ad47247ae6eaa7104e4d4ef6e002840f9">getPSet</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#af7a0688faef62284ad684e70f342b3da">llvm::RegPressureTracker::getUpwardPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ab0d12eb20352f092840f7f8df60abe26">llvm::GenericScheduler::initCandidate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a62cf34ac18c5612524978166788b5c80">llvm::tryPressure</a>.</p>

</div>
</div>

### setUnitInc() {#a4b74a0d0d1bc2e22fa7376eda3fdd85f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PressureChange::setUnitInc (int Inc)</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a013f10c0323064cf28c1aed647c0b478">computeExcessPressureDelta</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a822aec28298cd2dc8f346d4753a4154b">computeMaxPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#af7a0688faef62284ad684e70f342b3da">llvm::RegPressureTracker::getUpwardPressureDelta</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#ad173097d2f6789c7d00843386252855e">llvm::GCNSchedStrategy::initCandidate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### PSetID {#acffdb87e05bb5de516aa23c757f9b101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::PressureChange::PSetID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### UnitInc {#a9c6ee68fdbf9d7825b0312938b4cd7e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int16_t llvm::PressureChange::UnitInc = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
