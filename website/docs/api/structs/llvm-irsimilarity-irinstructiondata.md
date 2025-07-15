---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/irsimilarity/irinstructiondata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IRInstructionData` Struct Reference

<p>This provides the utilities for hashing an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to an unsigned integer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::IRSimilarity::IRInstructionData { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">llvm/Analysis/IRSimilarityIdentifier.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node&lt;T, Options&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3fdb189d1625b937b2aedcf1de64f09">hash_value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hashes <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> based on its opcode, types, and operand types. <a href="#ac3fdb189d1625b937b2aedcf1de64f09">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31d26022f657b77aa802a9190611e87b">IRInstructionData</a> (Instruction &amp;I, bool Legality, IRInstructionDataList &amp;IDL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather the information that is difficult to gather for an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>, or is changed. <a href="#a31d26022f657b77aa802a9190611e87b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e5e827e16f5593372018118eb77460d">IRInstructionData</a> (IRInstructionDataList &amp;IDL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11f86f876fc26e82aaa048a2215da380">initializeInstruction</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fills data stuctures for <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> when it is constructed from a. <a href="#a11f86f876fc26e82aaa048a2215da380">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec8cb8d34e83a9cfee265a5f8c9ca313">getPredicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the predicate that the compare instruction is using for hashing the instruction. <a href="#aec8cb8d34e83a9cfee265a5f8c9ca313">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bab19cf37f51e4f51c8b9118e0f41bf">getCalleeName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the callee name that the call instruction is using for hashing the instruction. <a href="#a0bab19cf37f51e4f51c8b9118e0f41bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac69ce6b6aa6400d488d250ce4998691b">setBranchSuccessors</a> (DenseMap&lt; BasicBlock *, unsigned &gt; &amp;BasicBlockToInteger)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For an <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> containing a branch, finds the relative distances from the source basic block to the target by taking the difference of the number assigned to the current basic block and the target basic block of the branch. <a href="#ac69ce6b6aa6400d488d250ce4998691b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0683ad49b9a0ccca8bd1c97987a8cf9">setCalleeName</a> (bool MatchByName=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For an <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> containing a <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a>, set the function name appropriately. <a href="#ae0683ad49b9a0ccca8bd1c97987a8cf9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab11b9d6834e7a409b18c71e0b19876f5">setPHIPredecessors</a> (DenseMap&lt; BasicBlock *, unsigned &gt; &amp;BasicBlockToInteger)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For an <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> containing a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>, finds the relative distances from the incoming basic block to the current block by taking the difference of the number assigned to the current basic block and the incoming basic block of the branch. <a href="#ab11b9d6834e7a409b18c71e0b19876f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39ea8bd6480d74c1dab6eb54eae61d27">getBlockOperVals</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> based operands for PHINodes and BranchInsts. <a href="#a39ea8bd6480d74c1dab6eb54eae61d27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f280453f9963266308cb61e428f5268">Inst</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The source <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> that is being wrapped. <a href="#a8f280453f9963266308cb61e428f5268">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab39a288c69393c860063b5d0348dc05a">OperVals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The values of the operands in the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="#ab39a288c69393c860063b5d0348dc05a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad05fd093f3eb994c056a4d353684aaf8">Legal</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The legality of the wrapped instruction. <a href="#ad05fd093f3eb994c056a4d353684aaf8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed3027a8796d2aa6a899077856e14da4">RevisedPredicate</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is only relevant if we are wrapping a <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> where we needed to change the predicate of a compare instruction from a greater than form to a less than form. <a href="#aed3027a8796d2aa6a899077856e14da4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a292aaa1e14576c8e38a2aad65d44f833">CalleeName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is only relevant if we are wrapping a <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a>. <a href="#a292aaa1e14576c8e38a2aad65d44f833">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2606c92d4c122037d9065123c3db3093">RelativeBlockLocations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This structure holds the distances of how far "ahead of" or "behind" the target blocks of a branch, or the incoming blocks of a phi nodes are. <a href="#a2606c92d4c122037d9065123c3db3093">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa685872100ad969dfd871803e3d7e0b9">IDL</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7aa1c92fb184b145e4841fc114e790b">predicateForConsistency</a> (CmpInst *CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A function that swaps the predicates to their less than form if they are in a greater than form. <a href="#aa7aa1c92fb184b145e4841fc114e790b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This provides the utilities for hashing an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to an unsigned integer.</p>


<p>Two IRInstructionDatas produce the same hash value when their underlying Instructions perform the same operation (even if they don't have the same input operands.) As a more concrete example, consider the following:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add1 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i32 %a, %<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea92eb5ffee6ae2fec3ad71c777531578f">b</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add2 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i32 %c, %d</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add3 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i64 %<a href="/web-llvm/docs/api/namespaces/llvm/numbers/#a92f4283d4e0e2ea1776894b3ae93640f">e</a>, %<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea8fa14cdd754f91cc6554c9e71929cce7">f</a></span></span></div>

</div>


<p>so:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">; These two adds have the same types and operand types, so they <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a6bd941efdf0dfa54d3abdb829ac86ae4">hash</a> to the</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">; same <a href="/web-llvm/docs/api/namespaces/llvm/xray/anonymous-blockverifier-cpp-/#a08f237df2d000ae6ee9be82263c9292d">number</a>.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add1 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i32 %a, %<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea92eb5ffee6ae2fec3ad71c777531578f">b</a> ; Hash: 1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add2 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i32 %c, %d ; Hash: 1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">; <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a7c84cffd04a037f3e087b309bf176929a77631ca4f0e08419b70726a447333ab6">This</a> <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> produces an i64. <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a7c84cffd04a037f3e087b309bf176929a77631ca4f0e08419b70726a447333ab6">This</a> differentiates it from %add1 and %add2. So,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">; it hashes to a different <a href="/web-llvm/docs/api/namespaces/llvm/xray/anonymous-blockverifier-cpp-/#a08f237df2d000ae6ee9be82263c9292d">number</a>.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add3 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i64 %<a href="/web-llvm/docs/api/namespaces/llvm/numbers/#a92f4283d4e0e2ea1776894b3ae93640f">e</a>, %<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea8fa14cdd754f91cc6554c9e71929cce7">f</a>; Hash: 2</span></span></div>

</div>


<p>This hashing scheme will be used to represent the program as a very long string. This string can then be placed in a data structure which can be used for similarity queries.</p>


<p>TODO: Handle types of Instructions which can be equal even with different operands. (E.g. comparisons with swapped predicates.) TODO: Handle CallInsts, which are only checked for function type by isSameOperationAs. TODO: Handle GetElementPtrInsts, as some of the operands have to be the exact same, and some do not.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<div class="doxySectionDef">

## Friends

### hash\_value {#ac3fdb189d1625b937b2aedcf1de64f09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> &amp; ID</td>
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

<p>Hashes <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> based on its opcode, types, and operand types.</p>


<p>Two <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> instances produce the same hash when they perform the same operation.</p>


<p>As a simple example, consider the following instructions.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add1 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i32 %x1, %y1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add2 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i32 %x2, %y2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%<a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a> = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a> i32 %x1, %y1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add_i64 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i64 %x2, %y2</span></span></div>

</div>


<p>Because the first two adds operate the same types, and are performing the same action, they will be hashed to the same value.</p>


<p>However, the subtraction instruction is not the same as an addition, and will be hashed to a different value.</p>


<p>Finally, the last add has a different type compared to the first two add instructions, so it will also be hashed to a different value that any of the previous instructions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed"&gt;ID&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> instance to be hashed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A hash_value of the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>.</p></dd>
</dl>


<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af80edfc5e42059e045aa7bf7fe42bee3">llvm::hash_combine_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e2e479cf4860dc8a00614e36ee3d5e9">llvm::hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a31d26022f657b77aa802a9190611e87b">IRInstructionData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IRInstructionData() {#a31d26022f657b77aa802a9190611e87b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRInstructionData::IRInstructionData (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, bool Legality, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> &amp; IDL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gather the information that is difficult to gather for an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>, or is changed.</p>


<p>i.e. the operands of an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> and the Types of those operands. This extra information allows for similarity matching to make assertions that allow for more flexibility when checking for whether an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> performs the same operation.</p>


<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aa685872100ad969dfd871803e3d7e0b9">IDL</a>, <a href="#a11f86f876fc26e82aaa048a2215da380">initializeInstruction</a>, <a href="#a8f280453f9963266308cb61e428f5268">Inst</a> and <a href="#ad05fd093f3eb994c056a4d353684aaf8">Legal</a>.</p>


<p>Referenced by <a href="#ac3fdb189d1625b937b2aedcf1de64f09">hash_value</a>.</p>

</div>
</div>

### IRInstructionData() {#a5e5e827e16f5593372018118eb77460d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRInstructionData::IRInstructionData (<a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> &amp; IDL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>Reference <a href="#aa685872100ad969dfd871803e3d7e0b9">IDL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBlockOperVals() {#a39ea8bd6480d74c1dab6eb54eae61d27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Value * &gt; IRInstructionData::getBlockOperVals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> based operands for PHINodes and BranchInsts.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A list of relevant BasicBlocks.</p></dd>
</dl>


<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a8f280453f9963266308cb61e428f5268">Inst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#ab39a288c69393c860063b5d0348dc05a">OperVals</a>.</p>


<p>Referenced by <a href="#ac69ce6b6aa6400d488d250ce4998691b">setBranchSuccessors</a>.</p>

</div>
</div>

### getCalleeName() {#a0bab19cf37f51e4f51c8b9118e0f41bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef IRInstructionData::getCalleeName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the callee name that the call instruction is using for hashing the instruction.</p>


<p>The <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> must be wrapping a <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a>.</p>


<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a292aaa1e14576c8e38a2aad65d44f833">CalleeName</a>, <a href="#a8f280453f9963266308cb61e428f5268">Inst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getPredicate() {#aec8cb8d34e83a9cfee265a5f8c9ca313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate IRInstructionData::getPredicate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the predicate that the compare instruction is using for hashing the instruction.</p>


<p>the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> must be wrapping a <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a>.</p>


<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a8f280453f9963266308cb61e428f5268">Inst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#aed3027a8796d2aa6a899077856e14da4">RevisedPredicate</a>.</p>

</div>
</div>

### initializeInstruction() {#a11f86f876fc26e82aaa048a2215da380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRInstructionData::initializeInstruction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fills data stuctures for <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> when it is constructed from a.</p>

<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a8f280453f9963266308cb61e428f5268">Inst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#ab39a288c69393c860063b5d0348dc05a">OperVals</a>, <a href="#aa7aa1c92fb184b145e4841fc114e790b">predicateForConsistency</a> and <a href="#aed3027a8796d2aa6a899077856e14da4">RevisedPredicate</a>.</p>


<p>Referenced by <a href="#a31d26022f657b77aa802a9190611e87b">IRInstructionData</a>.</p>

</div>
</div>

### setBranchSuccessors() {#ac69ce6b6aa6400d488d250ce4998691b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRInstructionData::setBranchSuccessors (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, unsigned &gt; &amp; BasicBlockToInteger)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For an <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> containing a branch, finds the relative distances from the source basic block to the target by taking the difference of the number assigned to the current basic block and the target basic block of the branch.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BasicBlockToInteger</td>
<td class="doxyParamItemDescription"><p>- The mapping of basic blocks to their location in the module.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="#a39ea8bd6480d74c1dab6eb54eae61d27">getBlockOperVals</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="#a8f280453f9963266308cb61e428f5268">Inst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a2606c92d4c122037d9065123c3db3093">RelativeBlockLocations</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06add2496ae8d635f9f169602771c88d376">llvm::Successor</a>.</p>

</div>
</div>

### setCalleeName() {#ae0683ad49b9a0ccca8bd1c97987a8cf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRInstructionData::setCalleeName (bool MatchByName=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For an <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> containing a <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a>, set the function name appropriately.</p>


<p>This will be an empty string if it is an indirect call, or we are not matching by name of the called function. It will be the name of the function if <span class="doxyComputerOutput">MatchByName</span> is true and it is not an indirect call. We may decide not to match by name in order to expand the size of the regions we can match. If a function name has the same type signature, but the different name, the region of code is still almost the same. Since function names can be treated as constants, the name itself could be extrapolated away. However, matching by name provides a specificity and more "identical" code than not matching by name.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MatchByName</td>
<td class="doxyParamItemDescription"><p>- A flag to mark whether we are using the called function name as a differentiating parameter.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a292aaa1e14576c8e38a2aad65d44f833">CalleeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a7157f9fa9dd11f234ec3c58517cb6d96">llvm::Intrinsic::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a8f280453f9963266308cb61e428f5268">Inst</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a574efc7d85ff014d5f15e077f3c82e6b">llvm::CallBase::isIndirectCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#ab2d91e185087b0ac1f22ef439a170c7f">llvm::Intrinsic::isOverloaded</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a8dc558dee9c54b788dd559fed3c0a39a">llvm::FunctionType::params</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>

</div>
</div>

### setPHIPredecessors() {#ab11b9d6834e7a409b18c71e0b19876f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRInstructionData::setPHIPredecessors (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, unsigned &gt; &amp; BasicBlockToInteger)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For an <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> containing a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>, finds the relative distances from the incoming basic block to the current block by taking the difference of the number assigned to the current basic block and the incoming basic block of the branch.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BasicBlockToInteger</td>
<td class="doxyParamItemDescription"><p>- The mapping of basic blocks to their location in the module.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ac53e1aabdf64e91b8b325bcac250d8a9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="#a8f280453f9963266308cb61e428f5268">Inst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a2606c92d4c122037d9065123c3db3093">RelativeBlockLocations</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CalleeName {#a292aaa1e14576c8e38a2aad65d44f833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::string&gt; llvm::IRSimilarity::IRInstructionData::CalleeName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is only relevant if we are wrapping a <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a>.</p>


<p>If we are requiring that the function calls have matching names as well as types, and the call is not an indirect call, this will hold the name of the function. If it is an indirect string, it will be the empty string. However, if this requirement is not in place it will be the empty string regardless of the function call type. The value held here is used to create the hash of the instruction, and check to make sure two instructions are close to one another.</p>


<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#a0bab19cf37f51e4f51c8b9118e0f41bf">getCalleeName</a> and <a href="#ae0683ad49b9a0ccca8bd1c97987a8cf9">setCalleeName</a>.</p>

</div>
</div>

### IDL {#aa685872100ad969dfd871803e3d7e0b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRInstructionDataList* llvm::IRSimilarity::IRInstructionData::IDL = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#a31d26022f657b77aa802a9190611e87b">IRInstructionData</a> and <a href="#a5e5e827e16f5593372018118eb77460d">IRInstructionData</a>.</p>

</div>
</div>

### Inst {#a8f280453f9963266308cb61e428f5268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* llvm::IRSimilarity::IRInstructionData::Inst = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The source <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> that is being wrapped.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#a39ea8bd6480d74c1dab6eb54eae61d27">getBlockOperVals</a>, <a href="#a0bab19cf37f51e4f51c8b9118e0f41bf">getCalleeName</a>, <a href="#aec8cb8d34e83a9cfee265a5f8c9ca313">getPredicate</a>, <a href="#a11f86f876fc26e82aaa048a2215da380">initializeInstruction</a>, <a href="#a31d26022f657b77aa802a9190611e87b">IRInstructionData</a>, <a href="#ac69ce6b6aa6400d488d250ce4998691b">setBranchSuccessors</a>, <a href="#ae0683ad49b9a0ccca8bd1c97987a8cf9">setCalleeName</a> and <a href="#ab11b9d6834e7a409b18c71e0b19876f5">setPHIPredecessors</a>.</p>

</div>
</div>

### Legal {#ad05fd093f3eb994c056a4d353684aaf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRSimilarity::IRInstructionData::Legal = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The legality of the wrapped instruction.</p>


<p>This is informed by <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bd">InstrType</a>, and is used when checking when two instructions are considered similar. If either instruction is not legal, the instructions are automatically not considered similar.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#a31d26022f657b77aa802a9190611e87b">IRInstructionData</a>.</p>

</div>
</div>

### OperVals {#ab39a288c69393c860063b5d0348dc05a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Value *, 4&gt; llvm::IRSimilarity::IRInstructionData::OperVals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The values of the operands in the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#a39ea8bd6480d74c1dab6eb54eae61d27">getBlockOperVals</a> and <a href="#a11f86f876fc26e82aaa048a2215da380">initializeInstruction</a>.</p>

</div>
</div>

### RelativeBlockLocations {#a2606c92d4c122037d9065123c3db3093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;int, 4&gt; llvm::IRSimilarity::IRInstructionData::RelativeBlockLocations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This structure holds the distances of how far "ahead of" or "behind" the target blocks of a branch, or the incoming blocks of a phi nodes are.</p>


<p>If the value is negative, it means that the block was registered before the block of this instruction in terms of blocks in the function. Code Example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">block_1:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br i1 %0, label %block_2, label %block_3</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">block_2:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br i1 %1, label %block_1, label %block_2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">block_3:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br i1 %2, label %block_2, label %block_1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">; Replacing the labels with relative <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a8fa743aa76b6902028f8a643dfb87171">values</a>, </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight"> becomes:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">block_1:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br i1 %0, distance 1, distance 2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">block_2:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br i1 %1, distance -1, distance 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">block_3:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br i1 %2, distance -1, distance -2</span></span></div>

</div>


<p>Taking block_2 as our example, block_1 is "behind" block_2, and block_2 is "ahead" of block_2.</p>


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#ac69ce6b6aa6400d488d250ce4998691b">setBranchSuccessors</a> and <a href="#ab11b9d6834e7a409b18c71e0b19876f5">setPHIPredecessors</a>.</p>

</div>
</div>

### RevisedPredicate {#aed3027a8796d2aa6a899077856e14da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;CmpInst::Predicate&gt; llvm::IRSimilarity::IRInstructionData::RevisedPredicate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is only relevant if we are wrapping a <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> where we needed to change the predicate of a compare instruction from a greater than form to a less than form.</p>


<p>It is std::nullopt otherwise.</p>


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#aec8cb8d34e83a9cfee265a5f8c9ca313">getPredicate</a> and <a href="#a11f86f876fc26e82aaa048a2215da380">initializeInstruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### predicateForConsistency() {#aa7aa1c92fb184b145e4841fc114e790b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate IRInstructionData::predicateForConsistency (<a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * CI)</td>
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

<p>A function that swaps the predicates to their less than form if they are in a greater than form.</p>


<p>Otherwise, the predicate is unchanged.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CI</td>
<td class="doxyParamItemDescription"><p>- The comparison operation to find a consistent preidcate for.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the consistent comparison predicate.</p></dd>
</dl>


<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">llvm::CmpInst::FCMP_OGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">llvm::CmpInst::FCMP_OGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">llvm::CmpInst::FCMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">llvm::CmpInst::FCMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a> and <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>.</p>


<p>Referenced by <a href="#a11f86f876fc26e82aaa048a2215da380">initializeInstruction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
