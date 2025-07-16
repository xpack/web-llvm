---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/inductiondescriptor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InductionDescriptor` Class Reference

<p>A struct for saving information about induction variables. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InductionDescriptor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">llvm/Analysis/IVDescriptors.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">InductionKind { <a href="#ac2d32589e2e153088b8a35db1a9eabcc">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This enum represents the kinds of inductions that we support. <a href="#ac2d32589e2e153088b8a35db1a9eabcc">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee6cc57cbb39719ac22af0e2e0b8bc16">InductionDescriptor</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor - creates an invalid induction. <a href="#aee6cc57cbb39719ac22af0e2e0b8bc16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74297a267cac4019c40b58a976d503ac">InductionDescriptor</a> (Value *Start, InductionKind K, const SCEV *Step, BinaryOperator *InductionBinOp=nullptr, SmallVectorImpl&lt; Instruction * &gt; *Casts=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Private constructor - used by <span class="doxyComputerOutput">isInductionPHI</span>. <a href="#a74297a267cac4019c40b58a976d503ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea63dae61a488e20e237f5f517ed1491">getStartValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac2d32589e2e153088b8a35db1a9eabcc">InductionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030aa2f43766c22713ac127f66f296b2">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83b5b65084a0c1de3a76f36f198b1b0c">getStep</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02906e4d107570bd0727048a4b0df9a5">getInductionBinOp</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af27bf00d939332f3d6ef27ea34440487">getConstIntStepValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee5a5c8071e7352a9ec7199bca954882">getExactFPMathInst</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns floating-point induction operator that does not allow reassociation (transforming the induction requires an override of normal floating-point rules). <a href="#aee5a5c8071e7352a9ec7199bca954882">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc4aaaf8ba6ab1a510c593a6c6370499">getInductionOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns binary opcode of the induction operator. <a href="#adc4aaaf8ba6ab1a510c593a6c6370499">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e8084b6da14960ba7c5b2cb7bd5f66">getCastInsts</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the type cast instructions in the induction update chain, that are redundant when guarded with a runtime <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> overflow check. <a href="#ae7e8084b6da14960ba7c5b2cb7bd5f66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/trackingvh">TrackingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c9556300965422f39597470f5c84b5c">StartValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start value. <a href="#a4c9556300965422f39597470f5c84b5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac2d32589e2e153088b8a35db1a9eabcc">InductionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ef7e0f36cfb3171141eb5b6b6b8f184">IK</a> = <a href="#ac2d32589e2e153088b8a35db1a9eabcca85d6fca1e5ba292e9d884797aa73f545">IK_NoInduction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Induction kind. <a href="#a4ef7e0f36cfb3171141eb5b6b6b8f184">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69b8f48bf5b23c5e58cab1f0c3f96453">Step</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Step value. <a href="#a69b8f48bf5b23c5e58cab1f0c3f96453">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d16b6201048febcd830404e62638dbb">InductionBinOp</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeba4181b033077d5152303f6b171959">RedundantCasts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdb97daf1829f811db20dff44887fe9e">isInductionPHI</a> (PHINode *Phi, const Loop *L, ScalarEvolution *SE, InductionDescriptor &amp;D, const SCEV *Expr=nullptr, SmallVectorImpl&lt; Instruction * &gt; *CastsToIgnore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">Phi</span> is an induction in the loop <span class="doxyComputerOutput">L</span>. <a href="#acdb97daf1829f811db20dff44887fe9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb1a03152610d15e008c2fdcb93602ed">isFPInductionPHI</a> (PHINode *Phi, const Loop *L, ScalarEvolution *SE, InductionDescriptor &amp;D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">Phi</span> is a floating point induction in the loop <span class="doxyComputerOutput">L</span>. <a href="#adb1a03152610d15e008c2fdcb93602ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ed1bebb4f59394ccf2d92d0d73336bf">isInductionPHI</a> (PHINode *Phi, const Loop *L, PredicatedScalarEvolution &amp;PSE, InductionDescriptor &amp;D, bool Assume=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">Phi</span> is a loop <span class="doxyComputerOutput">L</span> induction, in the context associated with the run-time predicate of PSE. <a href="#a5ed1bebb4f59394ccf2d92d0d73336bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A struct for saving information about induction variables.</p>

<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### InductionKind {#ac2d32589e2e153088b8a35db1a9eabcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::InductionDescriptor::InductionKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This enum represents the kinds of inductions that we support.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_NoInduction<a id="ac2d32589e2e153088b8a35db1a9eabcca85d6fca1e5ba292e9d884797aa73f545"></a></td>
<td class="doxyEnumItemDescription">Not an induction variable</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_IntInduction<a id="ac2d32589e2e153088b8a35db1a9eabccaf0191e822c9708e106d7bb58aa9ec947"></a></td>
<td class="doxyEnumItemDescription">Integer induction variable. Step = C</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_PtrInduction<a id="ac2d32589e2e153088b8a35db1a9eabccab61689ca7d0a024fc4ff52a74d691ae2"></a></td>
<td class="doxyEnumItemDescription">Pointer induction var. Step = C</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_FpInduction<a id="ac2d32589e2e153088b8a35db1a9eabccab0b71801de025f26b088a8cb22825f79"></a></td>
<td class="doxyEnumItemDescription">Floating point induction variable</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InductionDescriptor() {#aee6cc57cbb39719ac22af0e2e0b8bc16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InductionDescriptor::InductionDescriptor ()</td>
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

<p>Default constructor - creates an invalid induction.</p>

<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="#adb1a03152610d15e008c2fdcb93602ed">isFPInductionPHI</a>, <a href="#a5ed1bebb4f59394ccf2d92d0d73336bf">isInductionPHI</a> and <a href="#acdb97daf1829f811db20dff44887fe9e">isInductionPHI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### InductionDescriptor() {#a74297a267cac4019c40b58a976d503ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InductionDescriptor::InductionDescriptor (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Start, <a href="#ac2d32589e2e153088b8a35db1a9eabcc">InductionKind</a> K, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Step, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * InductionBinOp=nullptr, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; * Casts=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Private constructor - used by <span class="doxyComputerOutput">isInductionPHI</span>.</p>

<p>Declaration at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 1269 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCastInsts() {#ae7e8084b6da14960ba7c5b2cb7bd5f66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; Instruction * &gt; &amp; llvm::InductionDescriptor::getCastInsts ()</td>
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

<p>Returns a reference to the type cast instructions in the induction update chain, that are redundant when guarded with a runtime <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> overflow check.</p>

<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a0ac5df8f0304981180d602dacb13512c">llvm::LoopVectorizationCostModel::collectValuesToIgnore</a>.</p>

</div>
</div>

### getConstIntStepValue() {#af27bf00d939332f3d6ef27ea34440487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantInt * InductionDescriptor::getConstIntStepValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 1305 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loop/#a01f94a30e706065eb238b74f57c497ee">llvm::Loop::isCanonical</a>.</p>

</div>
</div>

### getExactFPMathInst() {#aee5a5c8071e7352a9ec7199bca954882}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::InductionDescriptor::getExactFPMathInst ()</td>
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

<p>Returns floating-point induction operator that does not allow reassociation (transforming the induction requires an override of normal floating-point rules).</p>

<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Reference <a href="#ac2d32589e2e153088b8a35db1a9eabccab0b71801de025f26b088a8cb22825f79">IK_FpInduction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a552a158f5a673da0a26461d1471cea41">llvm::LoopVectorizationLegality::canVectorizeFPMath</a>.</p>

</div>
</div>

### getInductionBinOp() {#a02906e4d107570bd0727048a4b0df9a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::InductionDescriptor::getInductionBinOp ()</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds/#a075be8282fe6debdda46c86d24a07684">llvm::Loop::LoopBounds::getBounds</a>.</p>

</div>
</div>

### getInductionOpcode() {#adc4aaaf8ba6ab1a510c593a6c6370499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction::BinaryOps llvm::InductionDescriptor::getInductionOpcode ()</td>
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

<p>Returns binary opcode of the induction operator.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loop/#afe702618f56478e67eb0f705efb648b6">llvm::Loop::isAuxiliaryInductionVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/loop/#a01f94a30e706065eb238b74f57c497ee">llvm::Loop::isCanonical</a>.</p>

</div>
</div>

### getKind() {#a030aa2f43766c22713ac127f66f296b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InductionKind llvm::InductionDescriptor::getKind ()</td>
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



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

### getStartValue() {#aea63dae61a488e20e237f5f517ed1491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::InductionDescriptor::getStartValue ()</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a9336eb7b4fbcee561dbb8c52d9eabe64">createWidenInductionRecipes</a>, <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds/#a075be8282fe6debdda46c86d24a07684">llvm::Loop::LoopBounds::getBounds</a> and <a href="/web-llvm/docs/api/classes/llvm/loop/#a01f94a30e706065eb238b74f57c497ee">llvm::Loop::isCanonical</a>.</p>

</div>
</div>

### getStep() {#a83b5b65084a0c1de3a76f36f198b1b0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::InductionDescriptor::getStep ()</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a9336eb7b4fbcee561dbb8c52d9eabe64">createWidenInductionRecipes</a>, <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds/#a075be8282fe6debdda46c86d24a07684">llvm::Loop::LoopBounds::getBounds</a> and <a href="/web-llvm/docs/api/classes/llvm/loop/#afe702618f56478e67eb0f705efb648b6">llvm::Loop::isAuxiliaryInductionVariable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IK {#a4ef7e0f36cfb3171141eb5b6b6b8f184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InductionKind llvm::InductionDescriptor::IK = <a href="#ac2d32589e2e153088b8a35db1a9eabcca85d6fca1e5ba292e9d884797aa73f545">IK_NoInduction</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Induction kind.</p>

<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

### InductionBinOp {#a5d16b6201048febcd830404e62638dbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator* llvm::InductionDescriptor::InductionBinOp = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

### RedundantCasts {#abeba4181b033077d5152303f6b171959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 2&gt; llvm::InductionDescriptor::RedundantCasts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

### StartValue {#a4c9556300965422f39597470f5c84b5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrackingVH&lt;Value&gt; llvm::InductionDescriptor::StartValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Start value.</p>

<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

### Step {#a69b8f48bf5b23c5e58cab1f0c3f96453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV* llvm::InductionDescriptor::Step = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Step value.</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isFPInductionPHI() {#adb1a03152610d15e008c2fdcb93602ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InductionDescriptor::isFPInductionPHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor">InductionDescriptor</a> &amp; D)</td>
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

<p>Returns true if <span class="doxyComputerOutput">Phi</span> is a floating point induction in the loop <span class="doxyComputerOutput">L</span>.</p>


<p>If <span class="doxyComputerOutput">Phi</span> is an induction, the induction descriptor <span class="doxyComputerOutput">D</span> will contain the data describing this induction.</p>


<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 1311 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad8e4f5b2ced08ad7d138b598aefdd338">llvm::ScalarEvolution::getUnknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac2d32589e2e153088b8a35db1a9eabccab0b71801de025f26b088a8cb22825f79">IK_FpInduction</a> and <a href="#aee6cc57cbb39719ac22af0e2e0b8bc16">InductionDescriptor</a>.</p>


<p>Referenced by <a href="#a5ed1bebb4f59394ccf2d92d0d73336bf">isInductionPHI</a>.</p>

</div>
</div>

### isInductionPHI() {#acdb97daf1829f811db20dff44887fe9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InductionDescriptor::isInductionPHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor">InductionDescriptor</a> &amp; D, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Expr=nullptr, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; * CastsToIgnore=nullptr)</td>
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

<p>Returns true if <span class="doxyComputerOutput">Phi</span> is an induction in the loop <span class="doxyComputerOutput">L</span>.</p>


<p>If <span class="doxyComputerOutput">Phi</span> is an induction, the induction descriptor <span class="doxyComputerOutput">D</span> will contain the data describing this induction. Since Induction Phis can only be present inside loop headers, the function will assert if it is passed a Phi whose parent is not the loop header. If by some other means the caller has a better <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression for <span class="doxyComputerOutput">Phi</span> than the one returned by the <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> analysis, it can be passed through <span class="doxyComputerOutput">Expr</span>. If the def-use chain associated with the phi includes casts (that we know we can ignore under proper runtime checks), they are passed through <span class="doxyComputerOutput">CastsToIgnore</span>.</p>


<p>Declaration at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 1513 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a30bd18ac905eacf3601bc6a553a9ff49">llvm::ScalarEvolution::getSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a4049f7040a4628b15f182c3c9aaf802a">llvm::SCEVAddRecExpr::getStepRecurrence</a>, <a href="#ac2d32589e2e153088b8a35db1a9eabccaf0191e822c9708e106d7bb58aa9ec947">IK_IntInduction</a>, <a href="#ac2d32589e2e153088b8a35db1a9eabccab61689ca7d0a024fc4ff52a74d691ae2">IK_PtrInduction</a>, <a href="#aee6cc57cbb39719ac22af0e2e0b8bc16">InductionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5a19768af81df7e5fe571bc08dcd48b3">llvm::ScalarEvolution::isLoopInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a6d8769a72303e2b06ef63129cb231855">llvm::ScalarEvolution::isSCEVable</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#aaa061922b1e4ea5e3dab5f468f004859">checkIsIndPhi</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality/#a4664ad33bbb85ca296ac1a1d74dffc1f">anonymous{LoopInterchange.cpp}::LoopInterchangeLegality::findInductions</a>, <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds/#a075be8282fe6debdda46c86d24a07684">llvm::Loop::LoopBounds::getBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a87b4fb592be76abb594711e92bb35e5c">llvm::Loop::getInductionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#ab05e97728516fbeeaa9426496257c800">llvm::Loop::getInductionVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#afe702618f56478e67eb0f705efb648b6">llvm::Loop::isAuxiliaryInductionVariable</a>, <a href="#a5ed1bebb4f59394ccf2d92d0d73336bf">isInductionPHI</a> and <a href="/web-llvm/docs/api/classes/anonymous-canonicalizefreezeinloops-cpp-/canonicalizefreezeinloopsimpl/#aff534de0962628bba1821ef3c0821308">anonymous{CanonicalizeFreezeInLoops.cpp}::CanonicalizeFreezeInLoopsImpl::run</a>.</p>

</div>
</div>

### isInductionPHI() {#a5ed1bebb4f59394ccf2d92d0d73336bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InductionDescriptor::isInductionPHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor">InductionDescriptor</a> &amp; D, bool Assume=false)</td>
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

<p>Returns true if <span class="doxyComputerOutput">Phi</span> is a loop <span class="doxyComputerOutput">L</span> induction, in the context associated with the run-time predicate of PSE.</p>


<p>If <span class="doxyComputerOutput">Assume</span> is true, this can add further <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates to <span class="doxyComputerOutput">PSE</span> in order to prove that <span class="doxyComputerOutput">Phi</span> is an induction. If <span class="doxyComputerOutput">Phi</span> is an induction, <span class="doxyComputerOutput">D</span> will contain the data describing this induction.</p>


<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 1469 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#aa364810e8fe30937277d9dd8a301c4c9">llvm::PredicatedScalarEvolution::getAsAddRec</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#a1890db236ee0485fd31d3d99d6ad09b5">getCastsForInductionPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#ae0994d8207b94ad22ecebc1a6bc580f1">llvm::PredicatedScalarEvolution::getSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a10ca5eacc61b5669880de2f8b0cff33c">llvm::PredicatedScalarEvolution::getSE</a>, <a href="#aee6cc57cbb39719ac22af0e2e0b8bc16">InductionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa0fd6bf3d33236279db7b707bba755f4">llvm::Type::isDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3ffc75c3a4cb82ba307a3334483eb4ac">llvm::Type::isFloatTy</a>, <a href="#adb1a03152610d15e008c2fdcb93602ed">isFPInductionPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a8cf1f36cc41c466e66d6467e40554841">llvm::Type::isHalfTy</a>, <a href="#acdb97daf1829f811db20dff44887fe9e">isInductionPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
