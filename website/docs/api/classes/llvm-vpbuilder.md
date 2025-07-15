---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VPBuilder` Class Reference

<p>VPlan-based builder utility analogous to <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">Transforms/Vectorize/LoopVectorizationPlanner.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0f19352a13a5eb9f4c9b05385dff290">VPBuilder</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a606019f284803c3bd2c1fc0844ed162a">VPBuilder</a> (VPBasicBlock *InsertBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8d33d559955251f16d4edfb09651204">VPBuilder</a> (VPRecipeBase *InsertPt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade3d711f8cf4dcbae687f85b6ce49315">VPBuilder</a> (VPBasicBlock *TheBB, VPBasicBlock::iterator IP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfa6751dfe3a3fb7462d62c3d06f6954">clearInsertionPoint</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the insertion point: created instructions will not be inserted into a block. <a href="#abfa6751dfe3a3fb7462d62c3d06f6954">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a85632d13a4a34fc9abb885d7d0b550">getInsertBlock</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2fc75e7b63babbf776ed29cfed87ae65">VPBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40184db12ba57b6b8ee938a31ce70bbe">getInsertPoint</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d69e480ca633efc5ee10248ab61d318">restoreIP</a> (VPInsertPoint IP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the current insert point to a previously-saved location. <a href="#a1d69e480ca633efc5ee10248ab61d318">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc190306945dd17129c24477566099ce">setInsertPoint</a> (VPBasicBlock *TheBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This specifies that created VPInstructions should be appended to the end of the specified block. <a href="#afc190306945dd17129c24477566099ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14418c70f1b5c9790db19902eb4429da">setInsertPoint</a> (VPBasicBlock *TheBB, VPBasicBlock::iterator IP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This specifies that created instructions should be inserted at the specified point. <a href="#a14418c70f1b5c9790db19902eb4429da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c5883e0be30cbd188280eec8941f6e">setInsertPoint</a> (VPRecipeBase *IP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This specifies that created instructions should be inserted at the specified point. <a href="#a16c5883e0be30cbd188280eec8941f6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accbbcc76f9eb947b3804ad96beb2bbd2">createNaryOp</a> (unsigned Opcode, ArrayRef&lt; VPValue * &gt; Operands, Instruction *Inst=nullptr, const Twine &amp;Name="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an N-ary operation with <span class="doxyComputerOutput">Opcode</span>, <span class="doxyComputerOutput">Operands</span> and set <span class="doxyComputerOutput">Inst</span> as its underlying <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="#accbbcc76f9eb947b3804ad96beb2bbd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85573e0f4a76b833f5c57beed6eb7a38">createNaryOp</a> (unsigned Opcode, ArrayRef&lt; VPValue * &gt; Operands, DebugLoc DL, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad317d7042dcaca782db6fe84324d6059">createNaryOp</a> (unsigned Opcode, std::initializer_list&lt; VPValue * &gt; Operands, std::optional&lt; FastMathFlags &gt; FMFs={}, DebugLoc DL={}, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3b191f35221f351f77883447fef4019">createOverflowingOp</a> (unsigned Opcode, std::initializer_list&lt; VPValue * &gt; Operands, VPRecipeWithIRFlags::WrapFlagsTy WrapFlags, DebugLoc DL={}, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf2cdb4ec71a22869d4c491e220d6f0b">createNot</a> (VPValue *Operand, DebugLoc DL={}, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab835ad7c89b7a82df8e51b83902f53b5">createAnd</a> (VPValue *LHS, VPValue *RHS, DebugLoc DL={}, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31ed5837f037c5ea5aadfb64bdb9b4c3">createOr</a> (VPValue *LHS, VPValue *RHS, DebugLoc DL={}, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad56e81b4de43098d552b6a166e56815d">createLogicalAnd</a> (VPValue *LHS, VPValue *RHS, DebugLoc DL={}, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebcef96452964d918ecdf28d1835115e">createSelect</a> (VPValue *Cond, VPValue *TrueVal, VPValue *FalseVal, DebugLoc DL={}, const Twine &amp;Name="", std::optional&lt; FastMathFlags &gt; FMFs=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b968ad86013a173bed6701425715dfb">createICmp</a> (CmpInst::Predicate Pred, VPValue *A, VPValue *B, DebugLoc DL={}, const Twine &amp;Name="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new ICmp <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> with predicate <span class="doxyComputerOutput">Pred</span> and operands <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span>. <a href="#a0b968ad86013a173bed6701425715dfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4098fdd65180c4601108d663dc6618c9">createPtrAdd</a> (VPValue *Ptr, VPValue *Offset, DebugLoc DL={}, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45751ee5beb1ca91ea687b5bc4489673">createInBoundsPtrAdd</a> (VPValue *Ptr, VPValue *Offset, DebugLoc DL={}, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe">VPDerivedIVRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d75b91bc4016f3078bab29877d8b68e">createDerivedIV</a> (InductionDescriptor::InductionKind Kind, FPMathOperator *FPBinOp, VPValue *Start, VPValue *Current, VPValue *Step, const Twine &amp;Name="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the input value <span class="doxyComputerOutput">Current</span> to the corresponding value of an induction with <span class="doxyComputerOutput">Start</span> and <span class="doxyComputerOutput">Step</span> values, using <span class="doxyComputerOutput">Start</span> + <span class="doxyComputerOutput">Current</span> * <span class="doxyComputerOutput">Step</span>. <a href="#a3d75b91bc4016f3078bab29877d8b68e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpscalarcastrecipe">VPScalarCastRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7651e884685052147f007e0e0fe0c774">createScalarCast</a> (Instruction::CastOps Opcode, VPValue *Op, Type *ResultTy, DebugLoc DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe">VPWidenCastRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab81f71333adc8bbb9c33ae65fe9eb337">createWidenCast</a> (Instruction::CastOps Opcode, VPValue *Op, Type *ResultTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe">VPScalarIVStepsRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bdebe594005618b27255ea3ea2d2cdb">createScalarIVSteps</a> (Instruction::BinaryOps InductionOpcode, FPMathOperator *FPBinOp, VPValue *IV, VPValue *Step)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aee9c3f345111abb9b84667ef4a36a5bb">tryInsertInstruction</a> (T *R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert <span class="doxyComputerOutput">VPI</span> in BB at InsertPt if BB is set. <a href="#aee9c3f345111abb9b84667ef4a36a5bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e93bb851af4fe9d8d0cfd24a9c75b7f">createInstruction</a> (unsigned Opcode, ArrayRef&lt; VPValue * &gt; Operands, DebugLoc DL, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f787528029e1dfd9746b82e2a2eb63">createInstruction</a> (unsigned Opcode, std::initializer_list&lt; VPValue * &gt; Operands, DebugLoc DL, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d3dacb666083f461c90b78df0b4065e">BB</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2fc75e7b63babbf776ed29cfed87ae65">VPBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea096086bef619f0047ebcfae762b419">InsertPt</a> = <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2fc75e7b63babbf776ed29cfed87ae65">VPBasicBlock::iterator</a>()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vpbuilder">VPBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84fe82982cb89a345442baaa710e949a">getToInsertAfter</a> (VPRecipeBase *R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/vpbuilder">VPBuilder</a> to insert after <span class="doxyComputerOutput">R</span>. <a href="#a84fe82982cb89a345442baaa710e949a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>VPlan-based builder utility analogous to <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VPBuilder() {#ad0f19352a13a5eb9f4c9b05385dff290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPBuilder::VPBuilder ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>Referenced by <a href="#a84fe82982cb89a345442baaa710e949a">getToInsertAfter</a> and <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/insertpointguard/#aa5804dc65f1760580e8b9cf1c4a1e075">llvm::VPBuilder::InsertPointGuard::InsertPointGuard</a>.</p>

</div>
</div>

### VPBuilder() {#a606019f284803c3bd2c1fc0844ed162a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPBuilder::VPBuilder (<a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * InsertBB)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>Reference <a href="#afc190306945dd17129c24477566099ce">setInsertPoint</a>.</p>

</div>
</div>

### VPBuilder() {#aa8d33d559955251f16d4edfb09651204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPBuilder::VPBuilder (<a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * InsertPt)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>Reference <a href="#afc190306945dd17129c24477566099ce">setInsertPoint</a>.</p>

</div>
</div>

### VPBuilder() {#ade3d711f8cf4dcbae687f85b6ce49315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPBuilder::VPBuilder (<a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * TheBB, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2fc75e7b63babbf776ed29cfed87ae65">VPBasicBlock::iterator</a> IP)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>Reference <a href="#afc190306945dd17129c24477566099ce">setInsertPoint</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearInsertionPoint() {#abfa6751dfe3a3fb7462d62c3d06f6954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBuilder::clearInsertionPoint ()</td>
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

<p>Clear the insertion point: created instructions will not be inserted into a block.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>Referenced by <a href="#a1d69e480ca633efc5ee10248ab61d318">restoreIP</a>.</p>

</div>
</div>

### createAnd() {#ab835ad7c89b7a82df8e51b83902f53b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPBuilder::createAnd (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### createDerivedIV() {#a3d75b91bc4016f3078bab29877d8b68e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPDerivedIVRecipe * llvm::VPBuilder::createDerivedIV (<a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#ac2d32589e2e153088b8a35db1a9eabcc">InductionDescriptor::InductionKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator">FPMathOperator</a> * FPBinOp, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Start, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Current, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Step, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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

<p>Convert the input value <span class="doxyComputerOutput">Current</span> to the corresponding value of an induction with <span class="doxyComputerOutput">Start</span> and <span class="doxyComputerOutput">Step</span> values, using <span class="doxyComputerOutput">Start</span> + <span class="doxyComputerOutput">Current</span> * <span class="doxyComputerOutput">Step</span>.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a20c2e870e2c105fbf0945df09a9a5c4d">addResumePhiRecipeForInduction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a3c91ec836b0d1e340e17bff8eec31390">createScalarIVSteps</a>.</p>

</div>
</div>

### createICmp() {#a0b968ad86013a173bed6701425715dfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPBuilder::createICmp (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * A, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * B, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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

<p>Create a new ICmp <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> with predicate <span class="doxyComputerOutput">Pred</span> and operands <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span>.</p>


<p>TODO: add createFCmp when needed.</p>


<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad16bff9364e25351de81704fe81fd229">llvm::VPlanTransforms::tryAddExplicitVectorLength</a>.</p>

</div>
</div>

### createInBoundsPtrAdd() {#a45751ee5beb1ca91ea687b5bc4489673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPBuilder::createInBoundsPtrAdd (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Offset, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### createLogicalAnd() {#ad56e81b4de43098d552b6a166e56815d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPBuilder::createLogicalAnd (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### createNaryOp() {#accbbcc76f9eb947b3804ad96beb2bbd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPInstruction * llvm::VPBuilder::createNaryOp (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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

<p>Create an N-ary operation with <span class="doxyComputerOutput">Opcode</span>, <span class="doxyComputerOutput">Operands</span> and set <span class="doxyComputerOutput">Inst</span> as its underlying <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a9739b6fa8242398fd51cb4e77a2447d7">llvm::VPValue::setUnderlyingValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a4d2a943e39c98ccce6fd53e8df9c5c2b">addCanonicalIVRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a453563e4ed7e249a7f3e92b98b9052df">addExitUsersForFirstOrderRecurrences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a20c2e870e2c105fbf0945df09a9a5c4d">addResumePhiRecipeForInduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a02106664ead4e0c4e755457dbac7f7b3">addScalarResumePhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5a9cb34d61fa4930ff585649d1d5b2ed">addVPLaneMaskPhiAndUpdateExitBranch</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae64d6953a1334207d9e7d9cd2587ee9f">llvm::VPlanTransforms::adjustFixedOrderRecurrences</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#ad326bf7574f239b4177d077e513403aa">llvm::VPIRInstruction::extractLastLaneOfOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a13368acf4fbb5816c3d82099b11519b1">preparePlanForMainVectorLoop</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad16bff9364e25351de81704fe81fd229">llvm::VPlanTransforms::tryAddExplicitVectorLength</a>.</p>

</div>
</div>

### createNaryOp() {#a85573e0f4a76b833f5c57beed6eb7a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPInstruction * llvm::VPBuilder::createNaryOp (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### createNaryOp() {#ad317d7042dcaca782db6fe84324d6059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPInstruction * llvm::VPBuilder::createNaryOp (unsigned Opcode, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> &gt; FMFs={}, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### createNot() {#acf2cdb4ec71a22869d4c491e220d6f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPBuilder::createNot (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Operand, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5a9cb34d61fa4930ff585649d1d5b2ed">addVPLaneMaskPhiAndUpdateExitBranch</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a>.</p>

</div>
</div>

### createOr() {#a31ed5837f037c5ea5aadfb64bdb9b4c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPBuilder::createOr (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### createOverflowingOp() {#ab3b191f35221f351f77883447fef4019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPInstruction * llvm::VPBuilder::createOverflowingOp (unsigned Opcode, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/structs/llvm/vprecipewithirflags/wrapflagsty">VPRecipeWithIRFlags::WrapFlagsTy</a> WrapFlags, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a4d2a943e39c98ccce6fd53e8df9c5c2b">addCanonicalIVRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5a9cb34d61fa4930ff585649d1d5b2ed">addVPLaneMaskPhiAndUpdateExitBranch</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa0f143b8d4693978b984f0639c90e508">llvm::VPlanTransforms::dropPoisonGeneratingRecipes</a>.</p>

</div>
</div>

### createPtrAdd() {#a4098fdd65180c4601108d663dc6618c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPInstruction * llvm::VPBuilder::createPtrAdd (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Offset, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a>.</p>

</div>
</div>

### createScalarCast() {#a7651e884685052147f007e0e0fe0c774}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPScalarCastRecipe * llvm::VPBuilder::createScalarCast (<a href="/web-llvm/docs/api/classes/llvm/instruction/#afa0b2fa29ba074f2b6ec9ac11163f2d9">Instruction::CastOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResultTy, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL)</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a20c2e870e2c105fbf0945df09a9a5c4d">addResumePhiRecipeForInduction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a3c91ec836b0d1e340e17bff8eec31390">createScalarIVSteps</a>.</p>

</div>
</div>

### createScalarIVSteps() {#a9bdebe594005618b27255ea3ea2d2cdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPScalarIVStepsRecipe * llvm::VPBuilder::createScalarIVSteps (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> InductionOpcode, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator">FPMathOperator</a> * FPBinOp, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * IV, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Step)</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#a8be4fec4d0b6071fb7d7520364fd5378">llvm::FPMathOperator::getFastMathFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a3c91ec836b0d1e340e17bff8eec31390">createScalarIVSteps</a>.</p>

</div>
</div>

### createSelect() {#aebcef96452964d918ecdf28d1835115e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPBuilder::createSelect (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * TrueVal, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * FalseVal, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> &gt; FMFs=std::nullopt)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad16bff9364e25351de81704fe81fd229">llvm::VPlanTransforms::tryAddExplicitVectorLength</a>.</p>

</div>
</div>

### createWidenCast() {#ab81f71333adc8bbb9c33ae65fe9eb337}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPWidenCastRecipe * llvm::VPBuilder::createWidenCast (<a href="/web-llvm/docs/api/classes/llvm/instruction/#afa0b2fa29ba074f2b6ec9ac11163f2d9">Instruction::CastOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResultTy)</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### getInsertBlock() {#a3a85632d13a4a34fc9abb885d7d0b550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock * llvm::VPBuilder::getInsertBlock ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/insertpointguard/#aa5804dc65f1760580e8b9cf1c4a1e075">llvm::VPBuilder::InsertPointGuard::InsertPointGuard</a>.</p>

</div>
</div>

### getInsertPoint() {#a40184db12ba57b6b8ee938a31ce70bbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock::iterator llvm::VPBuilder::getInsertPoint ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/insertpointguard/#aa5804dc65f1760580e8b9cf1c4a1e075">llvm::VPBuilder::InsertPointGuard::InsertPointGuard</a>.</p>

</div>
</div>

### restoreIP() {#a1d69e480ca633efc5ee10248ab61d318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBuilder::restoreIP (<a href="/web-llvm/docs/api/classes/llvm/vpbuilder/vpinsertpoint">VPInsertPoint</a> IP)</td>
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

<p>Sets the current insert point to a previously-saved location.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="#abfa6751dfe3a3fb7462d62c3d06f6954">clearInsertionPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/vpinsertpoint/#a7f1e9f3fe3476ef87547202d528f7856">llvm::VPBuilder::VPInsertPoint::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/vpinsertpoint/#abd4a2d7a7937cb33a6c8633d2ea925ba">llvm::VPBuilder::VPInsertPoint::getPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/vpinsertpoint/#ae0e62ac75002b8ed7ba22416fddc9a83">llvm::VPBuilder::VPInsertPoint::isSet</a> and <a href="#afc190306945dd17129c24477566099ce">setInsertPoint</a>.</p>

</div>
</div>

### setInsertPoint() {#afc190306945dd17129c24477566099ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBuilder::setInsertPoint (<a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * TheBB)</td>
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

<p>This specifies that created VPInstructions should be appended to the end of the specified block.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a4a7f4b8433e9a788149ffd94a0a07051">llvm::VPBasicBlock::end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5a9cb34d61fa4930ff585649d1d5b2ed">addVPLaneMaskPhiAndUpdateExitBranch</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae64d6953a1334207d9e7d9cd2587ee9f">llvm::VPlanTransforms::adjustFixedOrderRecurrences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a3c91ec836b0d1e340e17bff8eec31390">createScalarIVSteps</a>, <a href="#a1d69e480ca633efc5ee10248ab61d318">restoreIP</a>, <a href="#a606019f284803c3bd2c1fc0844ed162a">VPBuilder</a>, <a href="#ade3d711f8cf4dcbae687f85b6ce49315">VPBuilder</a> and <a href="#aa8d33d559955251f16d4edfb09651204">VPBuilder</a>.</p>

</div>
</div>

### setInsertPoint() {#a14418c70f1b5c9790db19902eb4429da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBuilder::setInsertPoint (<a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * TheBB, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2fc75e7b63babbf776ed29cfed87ae65">VPBasicBlock::iterator</a> IP)</td>
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

<p>This specifies that created instructions should be inserted at the specified point.</p>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### setInsertPoint() {#a16c5883e0be30cbd188280eec8941f6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPBuilder::setInsertPoint (<a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * IP)</td>
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

<p>This specifies that created instructions should be inserted at the specified point.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a6c88376daf23b16ad26b7ac6c224d21e">llvm::VPRecipeBase::getParent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createInstruction() {#a9e93bb851af4fe9d8d0cfd24a9c75b7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPInstruction * llvm::VPBuilder::createInstruction (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### createInstruction() {#aa8f787528029e1dfd9746b82e2a2eb63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPInstruction * llvm::VPBuilder::createInstruction (unsigned Opcode, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### tryInsertInstruction() {#aee9c3f345111abb9b84667ef4a36a5bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * llvm::VPBuilder::tryInsertInstruction (T * R)</td>
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

<p>Insert <span class="doxyComputerOutput">VPI</span> in BB at InsertPt if BB is set.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BB {#a2d3dacb666083f461c90b78df0b4065e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock* llvm::VPBuilder::BB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### InsertPt {#aea096086bef619f0047ebcfae762b419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock::iterator llvm::VPBuilder::InsertPt = <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2fc75e7b63babbf776ed29cfed87ae65">VPBasicBlock::iterator</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getToInsertAfter() {#a84fe82982cb89a345442baaa710e949a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBuilder llvm::VPBuilder::getToInsertAfter (<a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/vpbuilder">VPBuilder</a> to insert after <span class="doxyComputerOutput">R</span>.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#ad0f19352a13a5eb9f4c9b05385dff290">VPBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae1d2d60cd9edd9f7ca98c50789747c95">llvm::VPlanTransforms::addActiveLaneMask</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
