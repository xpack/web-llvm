---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/branchinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BranchInst` Class Reference

<p>Conditional or Unconditional Branch instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BranchInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87273cb892a8182f137567e6b631695e">Instruction</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0dc4dcd803741b389bf766fe750df24">BranchInst</a> (const BranchInst &amp;BI, AllocInfo AllocInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ops list - Branches are strange. <a href="#ac0dc4dcd803741b389bf766fe750df24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0daa623f56fd8f3d0ab87b491e162f95">BranchInst</a> (BasicBlock *IfTrue, AllocInfo AllocInfo, InsertPosition InsertBefore)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f02e107e377c9f6d06c92668406f48">BranchInst</a> (BasicBlock *IfTrue, BasicBlock *IfFalse, Value *Cond, AllocInfo AllocInfo, InsertPosition InsertBefore)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15c12c62063c41b5dc31efa378b49618">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a> (Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transparently provide more efficient getOperand methods. <a href="#a15c12c62063c41b5dc31efa378b49618">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad56f6a9b5cd05940017c4544df48bc30">isUnconditional</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e4be8b16fbd68c9045a388904044e01">isConditional</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebd4af5642453ce3169094f08dd3d7b8">getCondition</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3505dab06f59c36142a234321cdc3411">setCondition</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b8f11f6f21ca0321294669dab83b35">getNumSuccessors</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa05da2b94b366573d1651d5b163c521e">getSuccessor</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc5e7f9c460c68455e826783d77f9a99">setSuccessor</a> (unsigned idx, BasicBlock *NewSucc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6550fe5bd437c1c3c6e237d726e36b90">swapSuccessors</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Swap the successors of this branch instruction. <a href="#a6550fe5bd437c1c3c6e237d726e36b90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/branchinst/succ-op-iterator">succ_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a254b2cfabe80269ee4f53f6698452db6">successors</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/branchinst/const-succ-op-iterator">const_succ_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1b864f41057ebc4d889b1b31f71bc18">successors</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6caa25d916f318fa81a44bdbbf51fcd4">cloneImpl</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96fa91c0c8bc1268c0f62d538b974428">AssertOK</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f40e42226cee617c16cb1c447b115c5">Create</a> (BasicBlock *IfTrue, InsertPosition InsertBefore=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33901f0ae7fea18fad9358970e01eeb3">Create</a> (BasicBlock *IfTrue, BasicBlock *IfFalse, Value *Cond, InsertPosition InsertBefore=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ff84228c4e41f31dd35e8aac9654468">classof</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ec14a6005aa968e8e71c48c1936a2f9">classof</a> (const Value *V)</td>
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

<p>Conditional or Unconditional Branch instruction.</p>

<p>Definition at line 3016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Instruction {#a87273cb892a8182f137567e6b631695e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></td>
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


<p>Definition at line 3040 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a6caa25d916f318fa81a44bdbbf51fcd4">cloneImpl</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a4ff84228c4e41f31dd35e8aac9654468">classof</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### BranchInst() {#ac0dc4dcd803741b389bf766fe750df24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchInst::BranchInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> &amp; BI, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo">AllocInfo</a> AllocInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Ops list - Branches are strange.</p>


<p>The operands are ordered: [Cond, FalseDest,] TrueDest. This makes some accessors faster because they don't have to check for cond/uncond branchness. These are mostly accessed relative from <a href="/web-llvm/docs/api/classes/llvm/user/#af41f58e730804d10b91fcff39b035f74">op_end()</a>.</p>


<p>Declaration at line 3021 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1153 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

### BranchInst() {#a0daa623f56fd8f3d0ab87b491e162f95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchInst::BranchInst (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * IfTrue, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo">AllocInfo</a> AllocInfo, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 3031 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1132 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

### BranchInst() {#a29f02e107e377c9f6d06c92668406f48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchInst::BranchInst (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * IfTrue, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * IfFalse, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo">AllocInfo</a> AllocInfo, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 3033 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1140 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### DECLARE\_TRANSPARENT\_OPERAND\_ACCESSORS() {#a15c12c62063c41b5dc31efa378b49618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BranchInst::DECLARE_TRANSPARENT_OPERAND_ACCESSORS (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transparently provide more efficient getOperand methods.</p>

<p>Definition at line 3087 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### getCondition() {#aebd4af5642453ce3169094f08dd3d7b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::BranchInst::getCondition ()</td>
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



<p>Definition at line 3092 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7e4be8b16fbd68c9045a388904044e01">isConditional</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a341358b4e9c3ffb463182ea3280b2016">BrPHIToSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a465bf95ad9ca82a4541555d837aec85f">llvm::canSplitLoopBound</a>, <a href="/web-llvm/docs/api/classes/anonymous-codemoverutils-cpp-/controlconditions/#a866163a9dbd27133c221fc2569333ddb">anonymous{CodeMoverUtils.cpp}::ControlConditions::collectControlConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#ade155905429b0a259a1030f418c04ad9">computeUnlikelySuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a0775987674a0fc922481db1966a5fdf5">llvm::VPRecipeBuilder::createEdgeMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#abba5b02b3dfb44e87915fcf6af38e3fb">createFoldedExitCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a741f7bb1cc23d5c9d8917e1c7970c732">createInvariantCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a52374e76082ee94158724e5695a88a02">findBestNonTrivialUnswitchCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a6ff25bdf0db077015fe35d4a82b4b6dc">FlattenLoopPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad600d9077d7e1eadff1334ee14f7f25a">llvm::foldBranchToCommonDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#af0e4d9315f1815020f42edec6a27ad1f">getBranchCondString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad3e63520dcd2b8f8aa1b2e66e734a575">getBranchWeights</a>, <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds/#acfa250dd5ec97448681f9833e22d50cf">llvm::Loop::LoopBounds::getCanonicalPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#a410517ee51b91e86b7908a3895138054">getInnerLoopGuardCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#afb9fd1f991a7503fe4fd7dc16bda6f30">getKnownValueOnEdge</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/controlflowhoister/#ac2231bda91f0fdd79e476cb36e48d33b">anonymous{LICM.cpp}::ControlFlowHoister::getOrCreateHoistedBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#a1324f8c4f6c399fbb6c4fae0404a47ca">getOuterLoopLatchCmp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a3aaf79ae3bce520f7cb4d573292922e9">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70cdc32fcfc8ba3feaf026f4959e2c2a">llvm::InvertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aefc772d1808d513abc142b59844cfe45">llvm::ScalarEvolution::isBasicBlockEntryGuardedByCond</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8b617baf7fc5914d8a245e702ea65a7d">llvm::ScalarEvolution::isLoopBackedgeGuardedByCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a23d78b7d4dbea0ecc84dc55313ad1f25">isLoopExitTestBasedOn</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality/#ade3ca81f3a303345f66492c713c0e4ec">anonymous{LoopInterchange.cpp}::LoopInterchangeLegality::isLoopStructureUnderstood</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a0334b7852f3d535571315a1c2a90a085">matchCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab57bfa30e7fbef3fb394f7bd5cfa6d0a">matchShiftULTCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad9d19d00519eec89a553d376d72c9520">mergeNestedCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a6a2f2b3d9153487f51dae119c07f8461">needsLFTR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a740a442f349b36821071c21e265e23e1">optimizeLoopExitWithUnknownExitCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness/#a9bcd938340c81deac2844875dfd6086e">anonymous{SafepointIRVerifier.cpp}::CFGDeadness::processFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/domconditioncache/#ac105333da6ce958e6a88367557e798ae">llvm::DomConditionCache::registerBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af04adca83664ebd947723470c4da58aa">removeUndefIntroducingPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a16b4faf9802df251058f89443ca35a6c">replaceExitCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad75372cc26ff6f641159aed90d5fc11e">reuseTableCompare</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevbackedgeconditionfolder/#a9692f2f6a4683b75235d1e2e90ecb8f8">anonymous{ScalarEvolution.cpp}::SCEVBackedgeConditionFolder::rewrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#ae78c54dce6798892e47ca90660f9a8f6">RunTermFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a63f2a772f8b7a673be8aa85f4ea406d7">llvm::setWidenableBranchCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a45bde60377059fca310bb78e5d3a3ccb">simplifyInstructionWithPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a070509ca4afed69062174feb05ef7022">anonymous{InlineCost.cpp}::CallAnalyzer::visitBranchInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aea9ba5a362fb88bd97349a302133dd03">llvm::InstCombinerImpl::visitBranchInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a27f63a779f3bcae1f300371e33227bed">llvm::widenWidenableBranch</a>.</p>

</div>
</div>

### getNumSuccessors() {#a96b8f11f6f21ca0321294669dab83b35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BranchInst::getNumSuccessors ()</td>
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



<p>Definition at line 3102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="#a7e4be8b16fbd68c9045a388904044e01">isConditional</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a74712012450beeec949c228fd21d10a6">getExpectedExitLoopLatchBranch</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#ade1da0b29f5e3cb310ac591da00699c3">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::getHashValue</a>, <a href="#aa05da2b94b366573d1651d5b163c521e">getSuccessor</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a3aaf79ae3bce520f7cb4d573292922e9">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a8e5c4577c64728c435eca5f4f7e163ab">replaceTargetsFromPHINode</a>, <a href="#adc5e7f9c460c68455e826783d77f9a99">setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7d391dbabb8fc073db875548184a768d">violatesLegacyMultiExitLoopCheck</a>.</p>

</div>
</div>

### getSuccessor() {#aa05da2b94b366573d1651d5b163c521e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::BranchInst::getSuccessor (unsigned i)</td>
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



<p>Definition at line 3104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="#a96b8f11f6f21ca0321294669dab83b35">getNumSuccessors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-hotcoldsplitting-cpp-/#aa5755510005963e0d33f000914c5489d">anonymous{HotColdSplitting.cpp}::analyzeProfMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a341358b4e9c3ffb463182ea3280b2016">BrPHIToSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/predicateinfobuilder/#aaaff3f60426ede3ce93de105f66cb581">llvm::PredicateInfoBuilder::buildPredicateInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#a20d58a0069048b80461676a4132ad1d4">canRotateDeoptimizingLatchExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#af10d0fccdcb58cbd2e3932e630d24dfa">checkBiasedBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#af4f43e9c3f0bc709f58c5c9a2d92eed5">checkOuterLoopInsts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-codemoverutils-cpp-/controlconditions/#a866163a9dbd27133c221fc2569333ddb">anonymous{CodeMoverUtils.cpp}::ControlConditions::collectControlConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#ade155905429b0a259a1030f418c04ad9">computeUnlikelySuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a0775987674a0fc922481db1966a5fdf5">llvm::VPRecipeBuilder::createEdgeMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af67eef9e8d101756a1a0164e63eb4556">dominatesMergePoint</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a715a08cb04246d426e200c8196ecf0ea">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::extractRangeChecksFromBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp/#ad459fdaea6898de5c02c8ed651ae50c9">FindWidenableTerminatorAboveLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds/#acfa250dd5ec97448681f9833e22d50cf">llvm::Loop::LoopBounds::getCanonicalPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a0d49831d7116d82b2d53c2bbb81cd12d">getEstimatedTripCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a74712012450beeec949c228fd21d10a6">getExpectedExitLoopLatchBranch</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#ade1da0b29f5e3cb310ac591da00699c3">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a5751a2dd7306ff9a59eae6c1de8925">llvm::GetIfCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#afb9fd1f991a7503fe4fd7dc16bda6f30">getKnownValueOnEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a580a6361a2bad87e6071ecc795bdae96">llvm::Loop::getLoopGuardBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/controlflowhoister/#ac2231bda91f0fdd79e476cb36e48d33b">anonymous{LICM.cpp}::ControlFlowHoister::getOrCreateHoistedBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#aea5dd05a61257355d99f96d8d6dc9f94">handlePhiDef</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a3aaf79ae3bce520f7cb4d573292922e9">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aefc772d1808d513abc142b59844cfe45">llvm::ScalarEvolution::isBasicBlockEntryGuardedByCond</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#afd0535a9a9691fbeaf8a97077837bff9">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::isEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8b617baf7fc5914d8a245e702ea65a7d">llvm::ScalarEvolution::isLoopBackedgeGuardedByCond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af65a1289341b6d2b3c37541e1cb55bdd">llvm::isProfitableToTransform</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a0334b7852f3d535571315a1c2a90a085">matchCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab57bfa30e7fbef3fb394f7bd5cfa6d0a">matchShiftULTCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a710878a88d68a9169313249bfd52862a">llvm::JumpThreadingPass::maybethreadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a6a58dfc629e1b208cdd7b2bd76203184">mergeConditionalStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad9d19d00519eec89a553d376d72c9520">mergeNestedCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a740a442f349b36821071c21e265e23e1">optimizeLoopExitWithUnknownExitCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness/#a9bcd938340c81deac2844875dfd6086e">anonymous{SafepointIRVerifier.cpp}::CFGDeadness::processFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#a7fdcbbf4a72726c120dc9d33b6ee13bb">profitableToRotateLoopExitingLatch</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/controlflowhoister/#a90cb1c8c28c96b3e0abcd1dc070a7d87">anonymous{LICM.cpp}::ControlFlowHoister::registerPossiblyHoistableBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af04adca83664ebd947723470c4da58aa">removeUndefIntroducingPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerconstantintrinsics-cpp/#aa39118ddf6c73ece724a5c5e93d0db1e">replaceConditionalBranchesOnConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a8e5c4577c64728c435eca5f4f7e163ab">replaceTargetsFromPHINode</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevbackedgeconditionfolder/#a9692f2f6a4683b75235d1e2e90ecb8f8">anonymous{ScalarEvolution.cpp}::SCEVBackedgeConditionFolder::rewrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#ae78c54dce6798892e47ca90660f9a8f6">RunTermFold</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ab30094b924bc7333b5bf134d7985ca18">llvm::FastISel::selectOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad7cd933f586fc0c66656a4751ac069f">llvm::setLoopEstimatedTripCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1c4994ac805321b7fa03617dff656ad8">shouldFoldCondBranchesToCommonDestination</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af08d593d99b84298decf28611dd32f50">shouldTryInjectBasingOnMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a45bde60377059fca310bb78e5d3a3ccb">simplifyInstructionWithPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#accef1dd983ed3831858fe41c90fcc214">llvm::JumpThreadingPass::threadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad98f06eded5a01ee8704f7d7d9ca4c5b">tryWidenCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#ae5a9dfd216e7560889e2366f34ddd9f1">updatePredecessorProfileMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7d391dbabb8fc073db875548184a768d">violatesLegacyMultiExitLoopCheck</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aea9ba5a362fb88bd97349a302133dd03">llvm::InstCombinerImpl::visitBranchInst</a>.</p>

</div>
</div>

### isConditional() {#a7e4be8b16fbd68c9045a388904044e01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchInst::isConditional ()</td>
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



<p>Definition at line 3090 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/predicateinfobuilder/#aaaff3f60426ede3ce93de105f66cb581">llvm::PredicateInfoBuilder::buildPredicateInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#a20d58a0069048b80461676a4132ad1d4">canRotateDeoptimizingLatchExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#af10d0fccdcb58cbd2e3932e630d24dfa">checkBiasedBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#ade155905429b0a259a1030f418c04ad9">computeUnlikelySuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a0775987674a0fc922481db1966a5fdf5">llvm::VPRecipeBuilder::createEdgeMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af67eef9e8d101756a1a0164e63eb4556">dominatesMergePoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a6ff25bdf0db077015fe35d4a82b4b6dc">FlattenLoopPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad600d9077d7e1eadff1334ee14f7f25a">llvm::foldBranchToCommonDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a98c59bcf49cb7343886e8f425d6d877b">foldICmpWithDominatingICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#af0e4d9315f1815020f42edec6a27ad1f">getBranchCondString</a>, <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds/#acfa250dd5ec97448681f9833e22d50cf">llvm::Loop::LoopBounds::getCanonicalPredicate</a>, <a href="#aebd4af5642453ce3169094f08dd3d7b8">getCondition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a5751a2dd7306ff9a59eae6c1de8925">llvm::GetIfCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#afb9fd1f991a7503fe4fd7dc16bda6f30">getKnownValueOnEdge</a>, <a href="#a96b8f11f6f21ca0321294669dab83b35">getNumSuccessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#a1324f8c4f6c399fbb6c4fae0404a47ca">getOuterLoopLatchCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#aea5dd05a61257355d99f96d8d6dc9f94">handlePhiDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp/#ad1d9e6fe4974ee0754beaf3d7756bf20">hasOnlyUniformBranches</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8b617baf7fc5914d8a245e702ea65a7d">llvm::ScalarEvolution::isLoopBackedgeGuardedByCond</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality/#ade3ca81f3a303345f66492c713c0e4ec">anonymous{LoopInterchange.cpp}::LoopInterchangeLegality::isLoopStructureUnderstood</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a0334b7852f3d535571315a1c2a90a085">matchCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab57bfa30e7fbef3fb394f7bd5cfa6d0a">matchShiftULTCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness/#a9bcd938340c81deac2844875dfd6086e">anonymous{SafepointIRVerifier.cpp}::CFGDeadness::processFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#a7fdcbbf4a72726c120dc9d33b6ee13bb">profitableToRotateLoopExitingLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/domconditioncache/#ac105333da6ce958e6a88367557e798ae">llvm::DomConditionCache::registerBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/controlflowhoister/#a90cb1c8c28c96b3e0abcd1dc070a7d87">anonymous{LICM.cpp}::ControlFlowHoister::registerPossiblyHoistableBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevbackedgeconditionfolder/#a9692f2f6a4683b75235d1e2e90ecb8f8">anonymous{ScalarEvolution.cpp}::SCEVBackedgeConditionFolder::rewrite</a>, <a href="#a3505dab06f59c36142a234321cdc3411">setCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/condbranchweights/#a6107a708fd27cbf780738c2491c8de4e">anonymous{StructurizeCFG.cpp}::CondBranchWeights::setMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1c4994ac805321b7fa03617dff656ad8">shouldFoldCondBranchesToCommonDestination</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a45bde60377059fca310bb78e5d3a3ccb">simplifyInstructionWithPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a>, <a href="#a254b2cfabe80269ee4f53f6698452db6">successors</a>, <a href="#af1b864f41057ebc4d889b1b31f71bc18">successors</a>, <a href="#a6550fe5bd437c1c3c6e237d726e36b90">swapSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/condbranchweights/#aba3ebc82320c756584510146c07e8139">anonymous{StructurizeCFG.cpp}::CondBranchWeights::tryParse</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ae4ca9bfe94c6cc3d952413c7907db47f">llvm::JumpThreadingPass::tryToUnfoldSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#ae5a9dfd216e7560889e2366f34ddd9f1">updatePredecessorProfileMetadata</a>.</p>

</div>
</div>

### isUnconditional() {#ad56f6a9b5cd05940017c4544df48bc30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchInst::isUnconditional ()</td>
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



<p>Definition at line 3089 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#af4f43e9c3f0bc709f58c5c9a2d92eed5">checkOuterLoopInsts</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a715a08cb04246d426e200c8196ecf0ea">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::extractRangeChecksFromBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad600d9077d7e1eadff1334ee14f7f25a">llvm::foldBranchToCommonDest</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#ade1da0b29f5e3cb310ac591da00699c3">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a580a6361a2bad87e6071ecc795bdae96">llvm::Loop::getLoopGuardBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#a390dfaf67ef6d58f12f5a19ee938c60f">handleBranchExpect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#aea5dd05a61257355d99f96d8d6dc9f94">handlePhiDef</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aefc772d1808d513abc142b59844cfe45">llvm::ScalarEvolution::isBasicBlockEntryGuardedByCond</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#afd0535a9a9691fbeaf8a97077837bff9">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::isEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a710878a88d68a9169313249bfd52862a">llvm::JumpThreadingPass::maybethreadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af04adca83664ebd947723470c4da58aa">removeUndefIntroducingPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerconstantintrinsics-cpp/#aa39118ddf6c73ece724a5c5e93d0db1e">replaceConditionalBranchesOnConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ab30094b924bc7333b5bf134d7985ca18">llvm::FastISel::selectOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ae4ca9bfe94c6cc3d952413c7907db47f">llvm::JumpThreadingPass::tryToUnfoldSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#aa0555f067de530264e995e433ebb7e42">llvm::JumpThreadingPass::tryToUnfoldSelect</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a070509ca4afed69062174feb05ef7022">anonymous{InlineCost.cpp}::CallAnalyzer::visitBranchInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aea9ba5a362fb88bd97349a302133dd03">llvm::InstCombinerImpl::visitBranchInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6ab9ce3ba2b714edf23aa74567ba4540">llvm::InstCombinerImpl::visitUnconditionalBranchInst</a>.</p>

</div>
</div>

### setCondition() {#a3505dab06f59c36142a234321cdc3411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BranchInst::setCondition (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 3097 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7e4be8b16fbd68c9045a388904044e01">isConditional</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a6ff25bdf0db077015fe35d4a82b4b6dc">FlattenLoopPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70cdc32fcfc8ba3feaf026f4959e2c2a">llvm::InvertBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad9d19d00519eec89a553d376d72c9520">mergeNestedCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a16b4faf9802df251058f89443ca35a6c">replaceExitCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#ae78c54dce6798892e47ca90660f9a8f6">RunTermFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a63f2a772f8b7a673be8aa85f4ea406d7">llvm::setWidenableBranchCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a27f63a779f3bcae1f300371e33227bed">llvm::widenWidenableBranch</a>.</p>

</div>
</div>

### setSuccessor() {#adc5e7f9c460c68455e826783d77f9a99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BranchInst::setSuccessor (unsigned idx, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * NewSucc)</td>
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



<p>Definition at line 3109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a> and <a href="#a96b8f11f6f21ca0321294669dab83b35">getNumSuccessors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpbranchonmaskrecipe/#aa11920a3a7cf966108b4137b9e1a4c8b">llvm::VPBranchOnMaskRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad9d19d00519eec89a553d376d72c9520">mergeNestedCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a8e5c4577c64728c435eca5f4f7e163ab">replaceTargetsFromPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad98f06eded5a01ee8704f7d7d9ca4c5b">tryWidenCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>.</p>

</div>
</div>

### successors() {#a254b2cfabe80269ee4f53f6698452db6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; succ_op_iterator &gt; llvm::BranchInst::successors ()</td>
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



<p>Definition at line 3121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a7e4be8b16fbd68c9045a388904044e01">isConditional</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#ad93396a26f6fd589ed400bb280319836">llvm::User::value_op_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a5d1730a173d0a69624b80e1e22e6d225">llvm::User::value_op_end</a>.</p>

</div>
</div>

### successors() {#af1b864f41057ebc4d889b1b31f71bc18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_succ_op_iterator &gt; llvm::BranchInst::successors ()</td>
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



<p>Definition at line 3127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a7e4be8b16fbd68c9045a388904044e01">isConditional</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#ad93396a26f6fd589ed400bb280319836">llvm::User::value_op_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a5d1730a173d0a69624b80e1e22e6d225">llvm::User::value_op_end</a>.</p>

</div>
</div>

### swapSuccessors() {#a6550fe5bd437c1c3c6e237d726e36b90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchInst::swapSuccessors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Swap the successors of this branch instruction.</p>


<p>Swaps the successors of the branch instruction. This also swaps any branch weight metadata associated with the instruction so that it continues to map correctly to each operand.</p>


<p>Declaration at line 3119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1168 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7e4be8b16fbd68c9045a388904044e01">isConditional</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6e324daba99cb1d67713a562f9a778d2">llvm::Instruction::swapProfMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a98c59bcf49cb7343886e8f425d6d877b">foldICmpWithDominatingICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af8c1d39848b445bea8e307b53f81c481">llvm::InstCombinerImpl::freelyInvertAllUsersOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70cdc32fcfc8ba3feaf026f4959e2c2a">llvm::InvertBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#ae78c54dce6798892e47ca90660f9a8f6">RunTermFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aea9ba5a362fb88bd97349a302133dd03">llvm::InstCombinerImpl::visitBranchInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### cloneImpl() {#a6caa25d916f318fa81a44bdbbf51fcd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchInst * BranchInst::cloneImpl ()</td>
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



<p>Declaration at line 3042 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 4421 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>.</p>


<p>Referenced by <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AssertOK() {#a96fa91c0c8bc1268c0f62d538b974428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BranchInst::AssertOK ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 3036 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1126 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a4ff84228c4e41f31dd35e8aac9654468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 3134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a9ec14a6005aa968e8e71c48c1936a2f9">classof</a>.</p>

</div>
</div>

### classof() {#a9ec14a6005aa968e8e71c48c1936a2f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BranchInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 3137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a4ff84228c4e41f31dd35e8aac9654468">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### Create() {#a9f40e42226cee617c16cb1c447b115c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchInst * llvm::BranchInst::Create (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * IfTrue, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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



<p>Definition at line 3072 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a4fcb90c9c38b3381765a891d0a61c1ea">alignOutputBlockWithAggFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aea49493e2ae224d30cda2b3235d180b0">buildClonedLoopBlocks</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b3fdb09b0789963c439d41fe91e44a1">llvm::changeToCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2ffeb0208ddb1c5cf8a4bfb2ef0c9008">llvm::VPBasicBlock::connectToPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abab736a0141f903dc32a6f48828ad908">llvm::IRBuilderBase::CreateBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a22e193e6a0495abb240bbb128af58cfc">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a972c30f044db799668bdcace5544edeb">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#af1d16783f6f4b4d20427e93da6dd606f">createMemMoveLoopUnknownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a5e53eb62d81882a5586764e2a9378a49">DoFlattenLoopPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a833a6084a93d5900e8bdd493b37bbbc7">llvm::ehAwareSplitEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5eeb42cfad58d947c605b1e21376e0b7">llvm::emitAMDGPUPrintfCall</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a72c491cdf8cf0283d87008831431f917">llvm::InnerLoopVectorizer::emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#af15e3fefdfa2f5ea86ef5b8eacfa3517">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::emitMemRuntimeChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#a04c0081718b0f5113134aa563e1a56ca">llvm::EpilogueVectorizerEpilogueLoop::emitMinimumVectorEpilogueIterCountCheck</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#aa55563b1c40f6c6c94622a87dd7b5dcb">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::emitSCEVChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbranchonmaskrecipe/#aa11920a3a7cf966108b4137b9e1a4c8b">llvm::VPBranchOnMaskRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a4e06ebf129ddfb3b33a64f1a456cfc24">fillOverallFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#af30ff2458bb283e423c1fc242a468579">findOrCreatePHIBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#aaffd2ef85a5bde3351bbc659c18c1ebe">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::forceSingleThreadPerWorkgroupHelper</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinefunction-cpp-/landingpadinlininginfo/#adcbc4d7e8bf9926797b48a2b3603e3a4">anonymous{InlineFunction.cpp}::LandingPadInliningInfo::forwardResume</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/controlflowhoister/#ac2231bda91f0fdd79e476cb36e48d33b">anonymous{LICM.cpp}::ControlFlowHoister::getOrCreateHoistedBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#af8ebafc2930bf25dfa6887c4b5bc2c33">getStrlenWithNull</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a045ddd9cf89c401caf98eb3acad6b1a7">insertBoundsCheck</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a9b79beccbeb33ff89c797f5ac7b3fce3">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0af4594038f5cb46e7a4c86713520c95">markAliveBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1f70470f7a7722fd55c58c81358107f2">mergeCleanupPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/insertcfgstrategy/#a4a797db667ae87ab16b62a35de4f4a01">llvm::InsertCFGStrategy::mutate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a77bc86cd5c15b83afe922fa7bbfe0f11">anonymous{LowerSwitch.cpp}::NewLeafBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#aec97a6e447a45c9027b71a487f5732ec">performBlockTailMerging</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#abbc2deb942b00a9d0d19a6613e374168">llvm::JumpThreadingPass::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac06e19670a4cb86b0c885cf67bdb1bc4">llvm::JumpThreadingPass::processImpliedCondition</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a96191c096e61f77ea0a6771263bdb5e1">llvm::JumpThreadingPass::processThreadableEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3057c2b7e1e25de160497b1ef3985c2a">redirectTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a73660474ea469de5320aec1e4f7c6e4c">redirectToHub</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ab1e7a17f7727ff9a32ffc2a1efdb7bcc">llvm::SCCPSolver::removeNonFeasibleEdges</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/virtualcallsite/#a06e083d4358f4e44f6d6319347a81cfb">anonymous{WholeProgramDevirt.cpp}::VirtualCallSite::replaceAndErase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerconstantintrinsics-cpp/#aa39118ddf6c73ece724a5c5e93d0db1e">replaceConditionalBranchesOnConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/indirectbrexpandpass-cpp/#a241c916e6342b5f14a7492f1b91cc715">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a0fafeb4f9eaccefdd578d45fa0fd1f9f">setupBranchForGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a9f3928b341e4412b8b66b794896014f0">simplifySuspendPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78e14f66d8a8405c6882b5ff6a3b7617">llvm::spliceBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac950ae90e1bea2697f515628f7704b2a">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a32b5360bb5f3831163d348fc96fc1198">llvm::fuzzerop::splitBlockDescriptor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#ab9fe9fd51104da9e7faa88a213b74b9b">anonymous{LowerSwitch.cpp}::SwitchConvert</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7f1482a3531f0a99f5481d84bae6127e">llvm::JumpThreadingPass::unfoldSelectInstr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-unifyfunctionexitnodes-cpp-/#a06b5d6856fd9067830ab0477c0b13f31">anonymous{UnifyFunctionExitNodes.cpp}::unifyReturnBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#adb133e739b469808feb3635786aeaa01">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::unifyReturnBlockSet</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-unifyfunctionexitnodes-cpp-/#af51c1104ae401b16bf1787ef769b356c">anonymous{UnifyFunctionExitNodes.cpp}::unifyUnreachableBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### Create() {#a33901f0ae7fea18fad9358970e01eeb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchInst * llvm::BranchInst::Create (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * IfTrue, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * IfFalse, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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



<p>Definition at line 3078 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
