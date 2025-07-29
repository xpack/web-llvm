---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scheduledagsdnodes/regdefiter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RegDefIter` Class

<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/regdefiter">RegDefIter</a> - In place iteration over the values defined by an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ScheduleDAGSDNodes::RegDefIter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">CodeGen/SelectionDAG/ScheduleDAGSDNodes.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e7a3b904f789436ffa4c1d046e03f60">RegDefIter</a> (const SUnit *SU, const ScheduleDAGSDNodes *SD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d2c4562087d2d84212d353d42ecafa8">IsValid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2720a50e71371835b268cb14938e718">GetValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af29b074e10471b61ef7de6b8bf0a1766">GetNode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fe4cd2a914e4522e20f197108436102">GetIdx</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89d82bc3e4d32e5387f6632c5cff4cd3">Advance</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c3ac2d2cfc04eb24d956cd73281823d">InitNodeNumDefs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes">ScheduleDAGSDNodes</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace3d8d5bf10ad3969de220a79fa0ad85">SchedDAG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6bb52275c75fa28e8f9446ae20455cf">Node</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef7080d25acf68a5aaadddc576e87355">DefIdx</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19732c141eea9f01f1cf20031f995757">NodeNumDefs</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c615e54f692bb1fe5f348bebe0c0d34">ValueType</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/regdefiter">RegDefIter</a> - In place iteration over the values defined by an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>


<p>This does not need copies of the iterator or any other STLisms. The iterator creates itself, rather than being provided by the SchedDAG.</p>


<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegDefIter() {#a6e7a3b904f789436ffa4c1d046e03f60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGSDNodes::RegDefIter::RegDefIter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes">ScheduleDAGSDNodes</a> * SD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a>, definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp">ScheduleDAGSDNodes.cpp</a>.</p>


<p>References <a href="#a89d82bc3e4d32e5387f6632c5cff4cd3">Advance</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp/#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ad73652eab6e03e092e32bde82040c8c7">llvm::ScheduleDAGSDNodes::ScheduleDAGSDNodes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Advance() {#a89d82bc3e4d32e5387f6632c5cff4cd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGSDNodes::RegDefIter::Advance ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a>, definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp">ScheduleDAGSDNodes.cpp</a>.</p>


<p>Referenced by <a href="#a6e7a3b904f789436ffa4c1d046e03f60">RegDefIter</a>.</p>

</div>
</div>

### GetIdx() {#a0fe4cd2a914e4522e20f197108436102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScheduleDAGSDNodes::RegDefIter::GetIdx ()</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a75eb4d99ebf26777f16034567505166b">GetCostForDef</a>.</p>

</div>
</div>

### GetNode() {#af29b074e10471b61ef7de6b8bf0a1766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDNode * llvm::ScheduleDAGSDNodes::RegDefIter::GetNode ()</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a75eb4d99ebf26777f16034567505166b">GetCostForDef</a>.</p>

</div>
</div>

### GetValue() {#af2720a50e71371835b268cb14938e718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::ScheduleDAGSDNodes::RegDefIter::GetValue ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a8d2c4562087d2d84212d353d42ecafa8">IsValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a75eb4d99ebf26777f16034567505166b">GetCostForDef</a>.</p>

</div>
</div>

### IsValid() {#a8d2c4562087d2d84212d353d42ecafa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScheduleDAGSDNodes::RegDefIter::IsValid ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a>.</p>


<p>Referenced by <a href="#af2720a50e71371835b268cb14938e718">GetValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#aab14bf8331cae31c80d8cc29dff5e9bb">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::HighRegPressure</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a1b480aa4515358bac44d9281c7f74471">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::RegPressureDiff</a> and <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6ccdfe5633d79d327d704b14f7b83235">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::scheduledNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### InitNodeNumDefs() {#a1c3ac2d2cfc04eb24d956cd73281823d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGSDNodes::RegDefIter::InitNodeNumDefs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp">ScheduleDAGSDNodes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DefIdx {#aef7080d25acf68a5aaadddc576e87355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScheduleDAGSDNodes::RegDefIter::DefIdx = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a>.</p>

</div>
</div>

### Node {#ab6bb52275c75fa28e8f9446ae20455cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDNode* llvm::ScheduleDAGSDNodes::RegDefIter::Node</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a>.</p>

</div>
</div>

### NodeNumDefs {#a19732c141eea9f01f1cf20031f995757}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScheduleDAGSDNodes::RegDefIter::NodeNumDefs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a>.</p>

</div>
</div>

### SchedDAG {#ace3d8d5bf10ad3969de220a79fa0ad85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ScheduleDAGSDNodes* llvm::ScheduleDAGSDNodes::RegDefIter::SchedDAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a>.</p>

</div>
</div>

### ValueType {#a2c615e54f692bb1fe5f348bebe0c0d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::ScheduleDAGSDNodes::RegDefIter::ValueType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp">ScheduleDAGSDNodes.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-h">ScheduleDAGSDNodes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
