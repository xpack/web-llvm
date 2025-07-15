---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `InstCombineShifts.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionsimplify-h">llvm/Analysis/InstructionSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">llvm/Transforms/InstCombine/InstCombiner.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b6c32da7b6a47b962a5bdce5a3bbc75">canTryToConstantAddTwoShiftAmounts</a> (Value *Sh0, Value *ShAmt0, Value *Sh1, Value *ShAmt1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33e48dd73f38cb005f9a57fa3965879e">dropRedundantMaskingOfLeftShiftInput</a> (BinaryOperator *OuterShift, const SimplifyQuery &amp;Q, InstCombiner::BuilderTy &amp;Builder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c6c4745f22f8389f28f74c4e6db01f">foldShiftOfShiftedBinOp</a> (BinaryOperator &amp;I, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we have a shift-by-constant of a bin op (bitwise logic op or add/sub w/ shl) that itself has a shift-by-constant operand with identical opcode, we may be able to convert that into 2 independent shifts followed by the logic op. <a href="#a94c6c4745f22f8389f28f74c4e6db01f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaba35705ce5c614a4b4d1a6ed6e8bb57">canEvaluateShiftedShift</a> (unsigned OuterShAmt, bool IsOuterShl, Instruction *InnerShift, InstCombinerImpl &amp;IC, Instruction *CxtI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we can simplify two logical (either left or right) shifts that have constant shift amounts: OuterShift (InnerShift X, C1), C2. <a href="#aaba35705ce5c614a4b4d1a6ed6e8bb57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74691e0259fabde06f09a8f8076a6517">canEvaluateShifted</a> (Value *V, unsigned NumBits, bool IsLeftShift, InstCombinerImpl &amp;IC, Instruction *CxtI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if we can compute the specified value, but shifted logically to the left or right by some number of bits. <a href="#a74691e0259fabde06f09a8f8076a6517">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04e846746dd1839f88b9a39847f5d643">foldShiftedShift</a> (BinaryOperator *InnerShift, unsigned OuterShAmt, bool IsOuterShl, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fold OuterShift (InnerShift X, C1), C2. <a href="#a04e846746dd1839f88b9a39847f5d643">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2d3d519ed327a47cba69f5523785d2d">getShiftedValue</a> (Value *V, unsigned NumBits, bool isLeftShift, InstCombinerImpl &amp;IC, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When <a href="#a74691e0259fabde06f09a8f8076a6517">canEvaluateShifted()</a> returns true for an expression, this function inserts the new computation that produces the shifted value. <a href="#ab2d3d519ed327a47cba69f5523785d2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af31783f53ca1f5cd62dc80d2729530b0">canShiftBinOpWithConstantRHS</a> (BinaryOperator &amp;Shift, BinaryOperator *BO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056e5a535ce9d93f9c20adcce79b519f">setShiftFlags</a> (BinaryOperator &amp;I, const SimplifyQuery &amp;Q)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"instcombine"</td>
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


<div class="doxySectionDef">

## Functions

### canEvaluateShifted() {#a74691e0259fabde06f09a8f8076a6517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canEvaluateShifted (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned NumBits, bool IsLeftShift, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl">InstCombinerImpl</a> &amp; IC, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI)</td>
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

<p>See if we can compute the specified value, but shifted logically to the left or right by some number of bits.</p>


<p>This should return true if the expression can be computed for the same cost as the current expression tree. This is used to eliminate extraneous shifting from things like: C = shl i128 A, 64 D = shl i128 B, 96 E = or i128 C, D F = lshr i128 E, 64 where the client will ask if E can be computed shifted right by 64-bits. If this succeeds, <a href="#ab2d3d519ed327a47cba69f5523785d2d">getShiftedValue()</a> will be called to produce the value.</p>


<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp">InstCombineShifts.cpp</a>.</p>


<p>References <a href="#a74691e0259fabde06f09a8f8076a6517">canEvaluateShifted</a>, <a href="#aaba35705ce5c614a4b4d1a6ed6e8bb57">canEvaluateShiftedShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83c7c9008ba213687483b60a658b4a13">llvm::APInt::countr_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a1f0ff79b64a40d383b891f1baba89c6b">llvm::PHINode::incoming_values</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1b6b4785fa27be394cf040e543d9fe7c">llvm::APInt::isNegatedPowerOf2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5f6c38f6f64c2118341c829f97e26396">llvm::PatternMatch::m_ImmConstant</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#a74691e0259fabde06f09a8f8076a6517">canEvaluateShifted</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>.</p>

</div>
</div>

### canEvaluateShiftedShift() {#aaba35705ce5c614a4b4d1a6ed6e8bb57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canEvaluateShiftedShift (unsigned OuterShAmt, bool IsOuterShl, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InnerShift, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl">InstCombinerImpl</a> &amp; IC, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI)</td>
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

<p>Return true if we can simplify two logical (either left or right) shifts that have constant shift amounts: OuterShift (InnerShift X, C1), C2.</p>

<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp">InstCombineShifts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aadb443634ecdb8f3e6aa001e6d436122">llvm::Instruction::isLogicalShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ae506e7be0a7aaf9001e31d5fca5f2fbc">llvm::InstCombiner::MaskedValueIsZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#af999327aaf208e1dcb5c3c60d6c2452c">MaskShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a46a7cbf3724080a5f4f4c7e7a4551e26">llvm::APInt::ugt</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a>.</p>


<p>Referenced by <a href="#a74691e0259fabde06f09a8f8076a6517">canEvaluateShifted</a>.</p>

</div>
</div>

### canShiftBinOpWithConstantRHS() {#af31783f53ca1f5cd62dc80d2729530b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canShiftBinOpWithConstantRHS (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; Shift, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * BO)</td>
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



<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp">InstCombineShifts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aadb443634ecdb8f3e6aa001e6d436122">llvm::Instruction::isLogicalShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>.</p>

</div>
</div>

### canTryToConstantAddTwoShiftAmounts() {#a7b6c32da7b6a47b962a5bdce5a3bbc75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canTryToConstantAddTwoShiftAmounts (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Sh0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ShAmt0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Sh1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ShAmt1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp">InstCombineShifts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargettransforminfo-cpp/#a69eeffbc38c079195008fbfb5aaad0b9">getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a>.</p>


<p>Referenced by <a href="#a33e48dd73f38cb005f9a57fa3965879e">dropRedundantMaskingOfLeftShiftInput</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4b2e9167fd714396a473ee5493c1350b">llvm::InstCombinerImpl::reassociateShiftAmtsOfTwoSameDirectionShifts</a>.</p>

</div>
</div>

### dropRedundantMaskingOfLeftShiftInput() {#a33e48dd73f38cb005f9a57fa3965879e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * dropRedundantMaskingOfLeftShiftInput (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * OuterShift, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, InstCombiner::BuilderTy &amp; Builder)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp">InstCombineShifts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7b6c32da7b6a47b962a5bdce5a3bbc75">canTryToConstantAddTwoShiftAmounts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a964455f36837281d37f2a44e2fcb4cca">llvm::ConstantFoldBinaryOpOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf77c90e2fb57af4d4d4aab084f7052">llvm::ConstantFoldCastOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac59306eb826e349ac7429736b1506432">llvm::Type::getExtendedType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a5b43a866f0fca605556f0f69f70c522a">llvm::ConstantExpr::getNot</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a554ab77949b0a16670a83ec3307501eb">llvm::ConstantExpr::getSub</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af238147cf5453729781a0fcc7322e1c6">llvm::ConstantExpr::getTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8ef25defccf4817608a13e7a9db4000d">llvm::IRBuilderBase::Insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ef056813d120034e387417e9cde341">llvm::PatternMatch::m_AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0c94f3ca4234f78cf22840e79087f3f2">llvm::PatternMatch::m_AShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1981217907f3dfb1d21e902d0396fb4d">llvm::PatternMatch::m_c_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a469c3ed35e782000933c996ccd2d2333">llvm::PatternMatch::m_CombineAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#afc43bc5ec4b20c7c5d663bef90da6066">llvm::PatternMatch::m_CombineOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a53fc7d443cf6412add6dfddd11652e5d">llvm::PatternMatch::m_Deferred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab8546ee1aaa68d6f4990e6241e24464c">llvm::PatternMatch::m_LShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3b3d2d8c64a7881acb82bc7467569aa9">llvm::PatternMatch::m_One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aba80fdc6570c5a40cecd27fd7a06c858">llvm::PatternMatch::m_Shift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ac1c7b78fe67245930be18441b77de500">llvm::PatternMatch::m_Shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a310fbeb4d6c1b137dfd8713d354f3d76">llvm::PatternMatch::m_Shr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1b8442c10c9ed6e0e07160b54541450e">llvm::PatternMatch::m_Trunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a248676bc479d793526b2ebe1ba88e2f1">llvm::PatternMatch::m_ZExtOrSelf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a205029ee514828d0fb4988399ef3ece4a6864311f985d160ad4bd46a9fbe4a4d4">llvm::Masked</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a174c8fd19771468c53842a7fde8ddce1">llvm::Constant::replaceUndefsWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e0af1b16cab9e0efc63a6ce9de2b9cc">llvm::simplifyAddInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5942ddc4393a8ef081555f9a938c86e9">llvm::simplifySubInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>.</p>

</div>
</div>

### foldShiftedShift() {#a04e846746dd1839f88b9a39847f5d643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldShiftedShift (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * InnerShift, unsigned OuterShAmt, bool IsOuterShl, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>Fold OuterShift (InnerShift X, C1), C2.</p>


<p>See <a href="#aaba35705ce5c614a4b4d1a6ed6e8bb57">canEvaluateShiftedShift()</a> for the constraints on these instructions.</p>


<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp">InstCombineShifts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adcb96bd09d7c75c7669fa5f9d1190899">llvm::APInt::getHighBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4166b451a572b1e5d3fea7250af53653">llvm::Instruction::setHasNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0c03b71c79206ec41270dc3788183e0d">llvm::Instruction::setHasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ac01940f561517355e394911c203bcedf">llvm::Instruction::setIsExact</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a>.</p>


<p>Referenced by <a href="#ab2d3d519ed327a47cba69f5523785d2d">getShiftedValue</a>.</p>

</div>
</div>

### foldShiftOfShiftedBinOp() {#a94c6c4745f22f8389f28f74c4e6db01f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * foldShiftOfShiftedBinOp (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>If we have a shift-by-constant of a bin op (bitwise logic op or add/sub w/ shl) that itself has a shift-by-constant operand with identical opcode, we may be able to convert that into 2 independent shifts followed by the logic op.</p>


<p>This eliminates a use of an intermediate value (reduces dependency chain).</p>


<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp">InstCombineShifts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae6f1c15034bc5515033874630a8ecce6">llvm::ConstantExpr::getAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0698afabe907d2d3b87889d2e0349d47">llvm::PatternMatch::m_BinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a16be5fe0cce90e51f8c0e0c4d6c589f6">llvm::PatternMatch::m_Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5f6c38f6f64c2118341c829f97e26396">llvm::PatternMatch::m_ImmConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#afd8ce417d0ae1bee23037a373487fe42">llvm::PatternMatch::m_SpecificInt_ICMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa831d259fa5719e16927b5f4877988db">llvm::InstCombinerImpl::commonShiftTransforms</a>.</p>

</div>
</div>

### getShiftedValue() {#ab2d3d519ed327a47cba69f5523785d2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * getShiftedValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned NumBits, bool isLeftShift, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl">InstCombinerImpl</a> &amp; IC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>When <a href="#a74691e0259fabde06f09a8f8076a6517">canEvaluateShifted()</a> returns true for an expression, this function inserts the new computation that produces the shifted value.</p>

<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp">InstCombineShifts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ab86d58ae73173328360a32cbbb0d5b14">llvm::InstCombiner::addToWorklist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ae1d331bc844ecb92bdeb0b706ae04396">llvm::InstCombiner::Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a17c16c797477788dba165b1d6e8e862d">llvm::BinaryOperator::CreateNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a04e846746dd1839f88b9a39847f5d643">foldShiftedShift</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">llvm::PHINode::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a>, <a href="#ab2d3d519ed327a47cba69f5523785d2d">getShiftedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#a7ce29ca36c91b8c790b0f8b2560c3033">llvm::InstCombiner::InsertNewInstWith</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/phinode/#a88cdefb709309eddc6e5daca0be6a7b4">llvm::PHINode::setIncomingValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a> and <a href="#ab2d3d519ed327a47cba69f5523785d2d">getShiftedValue</a>.</p>

</div>
</div>

### setShiftFlags() {#a056e5a535ce9d93f9c20adcce79b519f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool setShiftFlags (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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



<p>Definition at line 982 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp">InstCombineShifts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a928ce56952772d0e0f43cab3a489a6fe">llvm::SimplifyQuery::AC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad46ed333b920b20e78d948610366254c">llvm::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a7f47812e8e75b0616a97d7004e5fb909">llvm::KnownBits::countMinLeadingZeros</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a10303a2ffd5366402dfdb65bc55fcff1">llvm::KnownBits::countMinSignBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a1eeff70353694cb360b2893553c18e7d">llvm::KnownBits::countMinTrailingZeros</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a4776fa0f5a726bd5a8a444981c283c69">llvm::SimplifyQuery::DT</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a4fdc09049a61f952b5d52788dbd2f69b">llvm::KnownBits::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab01d8694a759a934e01f1c558c3ce862">llvm::APInt::getLimitedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a825476b2436eb817b735fdd34ee521c4">llvm::KnownBits::getMaxValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ac1c7b78fe67245930be18441b77de500">llvm::PatternMatch::m_Shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a612d91fe0858006abe73d7b62821da0c">llvm::InstCombinerImpl::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"instcombine"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp">InstCombineShifts.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
