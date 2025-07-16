---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/openmpirbuilder/reductioninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ReductionInfo` Struct Reference

<p>Information about an OpenMP reduction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::OpenMPIRBuilder::ReductionInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">llvm/Frontend/OpenMP/OMPIRBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63ae5ded4ed861058caa4220c94cbdf8">ReductionInfo</a> (Type *ElementType, Value *Variable, Value *PrivateVariable, EvalKind EvaluationKind, ReductionGenCBTy ReductionGen, ReductionGenClangCBTy ReductionGenClang, ReductionGenAtomicCBTy AtomicReductionGen)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4af0772728af924cad5f22feb715537f">ReductionInfo</a> (Value *PrivateVariable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a808df20c6281c68ce8be2a89aaba392a">ElementType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reduction element type, must match pointee type of variable. <a href="#a808df20c6281c68ce8be2a89aaba392a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a2adb59d172175dafdc9466d436e198">Variable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reduction variable of pointer type. <a href="#a5a2adb59d172175dafdc9466d436e198">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63498704b583a96137c70ed7172f1ec3">PrivateVariable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Thread-private partial reduction variable. <a href="#a63498704b583a96137c70ed7172f1ec3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0f3b3f2ce3e462711213b2ecb34e904c">EvalKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29b6374efc73821625db25650244d87c">EvaluationKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reduction evaluation kind - scalar, complex or aggregate. <a href="#a29b6374efc73821625db25650244d87c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a3aadc019775907d5ff516545c5d2bfc8">ReductionGenCBTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fa70db8a68df256973daa02f87133b1">ReductionGen</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback for generating the reduction body. <a href="#a3fa70db8a68df256973daa02f87133b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a20304a012a6cc83d8114222bb0337228">ReductionGenClangCBTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a824a78a70fdb0c3b258f3d93ffa071">ReductionGenClang</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clang callback for generating the reduction body. <a href="#a6a824a78a70fdb0c3b258f3d93ffa071">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab81d602b13a50807afdda254fe16aecf">ReductionGenAtomicCBTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c969fa43d5f18e4237461ba967a16ae">AtomicReductionGen</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback for generating the atomic reduction body, may be null. <a href="#a3c969fa43d5f18e4237461ba967a16ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Information about an OpenMP reduction.</p>

<p>Definition at line 1335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ReductionInfo() {#a63ae5ded4ed861058caa4220c94cbdf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OpenMPIRBuilder::ReductionInfo::ReductionInfo (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Variable, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PrivateVariable, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0f3b3f2ce3e462711213b2ecb34e904c">EvalKind</a> EvaluationKind, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a3aadc019775907d5ff516545c5d2bfc8">ReductionGenCBTy</a> ReductionGen, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a20304a012a6cc83d8114222bb0337228">ReductionGenClangCBTy</a> ReductionGenClang, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab81d602b13a50807afdda254fe16aecf">ReductionGenAtomicCBTy</a> AtomicReductionGen)</td>
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



<p>Definition at line 1336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="#a3c969fa43d5f18e4237461ba967a16ae">AtomicReductionGen</a>, <a href="#a808df20c6281c68ce8be2a89aaba392a">ElementType</a>, <a href="#a29b6374efc73821625db25650244d87c">EvaluationKind</a>, <a href="#a63498704b583a96137c70ed7172f1ec3">PrivateVariable</a>, <a href="#a3fa70db8a68df256973daa02f87133b1">ReductionGen</a>, <a href="#a6a824a78a70fdb0c3b258f3d93ffa071">ReductionGenClang</a> and <a href="#a5a2adb59d172175dafdc9466d436e198">Variable</a>.</p>

</div>
</div>

### ReductionInfo() {#a4af0772728af924cad5f22feb715537f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OpenMPIRBuilder::ReductionInfo::ReductionInfo (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PrivateVariable)</td>
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



<p>Definition at line 1344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="#a3c969fa43d5f18e4237461ba967a16ae">AtomicReductionGen</a>, <a href="#a808df20c6281c68ce8be2a89aaba392a">ElementType</a>, <a href="#a29b6374efc73821625db25650244d87c">EvaluationKind</a>, <a href="#a63498704b583a96137c70ed7172f1ec3">PrivateVariable</a>, <a href="#a3fa70db8a68df256973daa02f87133b1">ReductionGen</a>, <a href="#a6a824a78a70fdb0c3b258f3d93ffa071">ReductionGenClang</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0f3b3f2ce3e462711213b2ecb34e904caf60357a8d17e45793298323f1b372a74">llvm::OpenMPIRBuilder::Scalar</a> and <a href="#a5a2adb59d172175dafdc9466d436e198">Variable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AtomicReductionGen {#a3c969fa43d5f18e4237461ba967a16ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReductionGenAtomicCBTy llvm::OpenMPIRBuilder::ReductionInfo::AtomicReductionGen</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback for generating the atomic reduction body, may be null.</p>


<p>The IR produced by this will be used to atomically combine two values during reduction. If null, the implementation will use the non-atomic version along with the appropriate synchronization mechanisms.</p>


<p>Definition at line 1375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab0996924f219129d8de3cc1b8830f768">llvm::OpenMPIRBuilder::createReductions</a>, <a href="#a63ae5ded4ed861058caa4220c94cbdf8">ReductionInfo</a> and <a href="#a4af0772728af924cad5f22feb715537f">ReductionInfo</a>.</p>

</div>
</div>

### ElementType {#a808df20c6281c68ce8be2a89aaba392a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::OpenMPIRBuilder::ReductionInfo::ElementType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reduction element type, must match pointee type of variable.</p>

<p>Definition at line 1350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab0996924f219129d8de3cc1b8830f768">llvm::OpenMPIRBuilder::createReductions</a>, <a href="#a63ae5ded4ed861058caa4220c94cbdf8">ReductionInfo</a> and <a href="#a4af0772728af924cad5f22feb715537f">ReductionInfo</a>.</p>

</div>
</div>

### EvaluationKind {#a29b6374efc73821625db25650244d87c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EvalKind llvm::OpenMPIRBuilder::ReductionInfo::EvaluationKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reduction evaluation kind - scalar, complex or aggregate.</p>

<p>Definition at line 1359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a63ae5ded4ed861058caa4220c94cbdf8">ReductionInfo</a> and <a href="#a4af0772728af924cad5f22feb715537f">ReductionInfo</a>.</p>

</div>
</div>

### PrivateVariable {#a63498704b583a96137c70ed7172f1ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::OpenMPIRBuilder::ReductionInfo::PrivateVariable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Thread-private partial reduction variable.</p>

<p>Definition at line 1356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab0996924f219129d8de3cc1b8830f768">llvm::OpenMPIRBuilder::createReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aaa655ca8bca40c564d0b7c81ebaf8ff9">llvm::OpenMPIRBuilder::createReductionsGPU</a>, <a href="#a63ae5ded4ed861058caa4220c94cbdf8">ReductionInfo</a> and <a href="#a4af0772728af924cad5f22feb715537f">ReductionInfo</a>.</p>

</div>
</div>

### ReductionGen {#a3fa70db8a68df256973daa02f87133b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReductionGenCBTy llvm::OpenMPIRBuilder::ReductionInfo::ReductionGen</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback for generating the reduction body.</p>


<p>The IR produced by this will be used to combine two values in a thread-safe context, e.g., under lock or within the same thread, and therefore need not be atomic.</p>


<p>Definition at line 1364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab0996924f219129d8de3cc1b8830f768">llvm::OpenMPIRBuilder::createReductions</a>, <a href="#a63ae5ded4ed861058caa4220c94cbdf8">ReductionInfo</a> and <a href="#a4af0772728af924cad5f22feb715537f">ReductionInfo</a>.</p>

</div>
</div>

### ReductionGenClang {#a6a824a78a70fdb0c3b258f3d93ffa071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReductionGenClangCBTy llvm::OpenMPIRBuilder::ReductionInfo::ReductionGenClang</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clang callback for generating the reduction body.</p>


<p>The IR produced by this will be used to combine two values in a thread-safe context, e.g., under lock or within the same thread, and therefore need not be atomic.</p>


<p>Definition at line 1369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aaa655ca8bca40c564d0b7c81ebaf8ff9">llvm::OpenMPIRBuilder::createReductionsGPU</a>, <a href="#a63ae5ded4ed861058caa4220c94cbdf8">ReductionInfo</a> and <a href="#a4af0772728af924cad5f22feb715537f">ReductionInfo</a>.</p>

</div>
</div>

### Variable {#a5a2adb59d172175dafdc9466d436e198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::OpenMPIRBuilder::ReductionInfo::Variable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reduction variable of pointer type.</p>

<p>Definition at line 1353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab0996924f219129d8de3cc1b8830f768">llvm::OpenMPIRBuilder::createReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aaa655ca8bca40c564d0b7c81ebaf8ff9">llvm::OpenMPIRBuilder::createReductionsGPU</a>, <a href="#a63ae5ded4ed861058caa4220c94cbdf8">ReductionInfo</a> and <a href="#a4af0772728af924cad5f22feb715537f">ReductionInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
