---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/binaryoperator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BinaryOperator` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::BinaryOperator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/possiblydisjointinst">PossiblyDisjointInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An or instruction, which can be marked as "disjoint", indicating that the inputs don't have a 1 in the same bit position. <a href="/web-llvm/docs/api/classes/llvm/possiblydisjointinst/#details">More...</a></p>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a> (BinaryOps iType, Value *S1, Value *S2, Type *Ty, const Twine &amp;Name, InsertPosition InsertBefore)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36ae9959603396cfd5b8292112700bb2">operator new</a> (size_t S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ac9f7c9a3c261958690295ae994b656">operator delete</a> (void *Ptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a527bd9ac4fece095b5979a7d30ed93af">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a> (Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transparently provide more efficient getOperand methods. <a href="#a527bd9ac4fece095b5979a7d30ed93af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">BinaryOps</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31bf07f3f61525486633bc1d0bbaf029">getOpcode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80cc7c4bd4a37fc13e9765fd3a31dbfe">swapOperands</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Exchange the two operands to this instruction. <a href="#a80cc7c4bd4a37fc13e9765fd3a31dbfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae85f34cfedbd995195eb9ea0df517b92">cloneImpl</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb959feef2862685a00de40ac3522620">AssertOK</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f385eda0f71b4e8199b296fbc8e0da9">Create</a> (BinaryOps Op, Value *S1, Value *S2, const Twine &amp;Name=Twine(), InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a binary instruction, given the opcode and the two operands. <a href="#a8f385eda0f71b4e8199b296fbc8e0da9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac80f39cdc458ec63d7ff5f7490498230">CreateWithCopiedFlags</a> (BinaryOps Opc, Value *V1, Value *V2, Value *CopyO, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73ecec9fc9254930ac757b1e30a9a4e1">CreateWithFMF</a> (BinaryOps Opc, Value *V1, Value *V2, FastMathFlags FMF, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fdb430e8a6a952ae71e3a309919d79c">CreateFAddFMF</a> (Value *V1, Value *V2, FastMathFlags FMF, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac24b427d643de0a47151a909faaba408">CreateFSubFMF</a> (Value *V1, Value *V2, FastMathFlags FMF, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed325338b1b10d9eb5d0daa29474b4d">CreateFMulFMF</a> (Value *V1, Value *V2, FastMathFlags FMF, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2f94c836428e78d253e63f8b2d3e609">CreateFDivFMF</a> (Value *V1, Value *V2, FastMathFlags FMF, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9db96e4b900739b4047a803bdf895e82">CreateFAddFMF</a> (Value *V1, Value *V2, Instruction *FMFSource, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a885c3de943bddf8931a02e916c62bb5c">CreateFSubFMF</a> (Value *V1, Value *V2, Instruction *FMFSource, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78cf65739da4d78960d847fceea64bf8">CreateFMulFMF</a> (Value *V1, Value *V2, Instruction *FMFSource, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e219326bd3cb20a63ac8b8c8e49294">CreateFDivFMF</a> (Value *V1, Value *V2, Instruction *FMFSource, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70d7b5ed965c40fb10f25961540bc474">CreateFRemFMF</a> (Value *V1, Value *V2, Instruction *FMFSource, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3555c92374939e341c136f73c9354d86">CreateNSW</a> (BinaryOps Opc, Value *V1, Value *V2, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea4ea86573aa983a20bb9af1019fd0f5">CreateNSW</a> (BinaryOps Opc, Value *V1, Value *V2, const Twine &amp;Name, InsertPosition InsertBefore)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fbbce94455a0a2b51e1db3daf2faa2a">CreateNUW</a> (BinaryOps Opc, Value *V1, Value *V2, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb40063a5c7439f459f7f143e706b7ee">CreateNUW</a> (BinaryOps Opc, Value *V1, Value *V2, const Twine &amp;Name, InsertPosition InsertBefore)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75232ba08deca2d4237adb5780fe2198">CreateExact</a> (BinaryOps Opc, Value *V1, Value *V2, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83f8671569d1c9271896f8bb4b1be5e9">CreateExact</a> (BinaryOps Opc, Value *V1, Value *V2, const Twine &amp;Name, InsertPosition InsertBefore)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3620292d253c4ad2efdba8623f7ce5c">CreateDisjoint</a> (BinaryOps Opc, Value *V1, Value *V2, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cdc7abc417800f113d92c333ea29ddb">CreateDisjoint</a> (BinaryOps Opc, Value *V1, Value *V2, const Twine &amp;Name, InsertPosition InsertBefore)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17c16c797477788dba165b1d6e8e862d">CreateNeg</a> (Value *Op, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper functions to construct and inspect unary operations (NEG and NOT) via binary operators SUB and XOR: <a href="#a17c16c797477788dba165b1d6e8e862d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4c3a10c3f94bacfa216245cd4b84225">CreateNSWNeg</a> (Value *Op, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8578626ceb87974ed94fd56b56a37346">CreateNot</a> (Value *Op, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe189fd5af3809d6b750958bda727006">classof</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a549b2918a7a803c2e79122912b6aa642">classof</a> (const Value *V)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/user/intrusiveoperandsallocmarker">IntrusiveOperandsAllocMarker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6feb434c47a8bfecd45e2ef64c9f63c">AllocMarker</a> {2}</td>
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


<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


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


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="#afe189fd5af3809d6b750958bda727006">classof</a>, <a href="/web-llvm/docs/api/classes/llvm/possiblydisjointinst/#adbd4668d11944890c66c9ad293024b87">llvm::PossiblyDisjointInst::classof</a>, <a href="#a9db96e4b900739b4047a803bdf895e82">CreateFAddFMF</a>, <a href="#a18e219326bd3cb20a63ac8b8c8e49294">CreateFDivFMF</a>, <a href="#a78cf65739da4d78960d847fceea64bf8">CreateFMulFMF</a>, <a href="#a70d7b5ed965c40fb10f25961540bc474">CreateFRemFMF</a>, <a href="#a885c3de943bddf8931a02e916c62bb5c">CreateFSubFMF</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### BinaryOperator() {#acee1035fe1c77f85d4b80655e4df150a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator::BinaryOperator (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">BinaryOps</a> iType, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S2, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore)</td>
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



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 2562 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>.</p>


<p>Referenced by <a href="#ae85f34cfedbd995195eb9ea0df517b92">cloneImpl</a>, <a href="#a8f385eda0f71b4e8199b296fbc8e0da9">Create</a>, <a href="#a2cdc7abc417800f113d92c333ea29ddb">CreateDisjoint</a>, <a href="#ac3620292d253c4ad2efdba8623f7ce5c">CreateDisjoint</a>, <a href="#a83f8671569d1c9271896f8bb4b1be5e9">CreateExact</a>, <a href="#a75232ba08deca2d4237adb5780fe2198">CreateExact</a>, <a href="#a0fdb430e8a6a952ae71e3a309919d79c">CreateFAddFMF</a>, <a href="#a9db96e4b900739b4047a803bdf895e82">CreateFAddFMF</a>, <a href="#ab2f94c836428e78d253e63f8b2d3e609">CreateFDivFMF</a>, <a href="#a18e219326bd3cb20a63ac8b8c8e49294">CreateFDivFMF</a>, <a href="#a9ed325338b1b10d9eb5d0daa29474b4d">CreateFMulFMF</a>, <a href="#a78cf65739da4d78960d847fceea64bf8">CreateFMulFMF</a>, <a href="#a70d7b5ed965c40fb10f25961540bc474">CreateFRemFMF</a>, <a href="#ac24b427d643de0a47151a909faaba408">CreateFSubFMF</a>, <a href="#a885c3de943bddf8931a02e916c62bb5c">CreateFSubFMF</a>, <a href="#a17c16c797477788dba165b1d6e8e862d">CreateNeg</a>, <a href="#a8578626ceb87974ed94fd56b56a37346">CreateNot</a>, <a href="#aea4ea86573aa983a20bb9af1019fd0f5">CreateNSW</a>, <a href="#a3555c92374939e341c136f73c9354d86">CreateNSW</a>, <a href="#ad4c3a10c3f94bacfa216245cd4b84225">CreateNSWNeg</a>, <a href="#abb40063a5c7439f459f7f143e706b7ee">CreateNUW</a>, <a href="#a8fbbce94455a0a2b51e1db3daf2faa2a">CreateNUW</a>, <a href="#ac80f39cdc458ec63d7ff5f7490498230">CreateWithCopiedFlags</a>, <a href="#a73ecec9fc9254930ac757b1e30a9a4e1">CreateWithFMF</a>, <a href="#a527bd9ac4fece095b5979a7d30ed93af">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator delete() {#a1ac9f7c9a3c261958690295ae994b656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BinaryOperator::operator delete (void * Ptr)</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### operator new() {#a36ae9959603396cfd5b8292112700bb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::BinaryOperator::operator new (size_t S)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### DECLARE\_TRANSPARENT\_OPERAND\_ACCESSORS() {#a527bd9ac4fece095b5979a7d30ed93af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryOperator::DECLARE_TRANSPARENT_OPERAND_ACCESSORS (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transparently provide more efficient getOperand methods.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>.</p>

</div>
</div>

### getOpcode() {#a31bf07f3f61525486633bc1d0bbaf029}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOps llvm::BinaryOperator::getOpcode ()</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#af31783f53ca1f5cd62dc80d2729530b0">canShiftBinOpWithConstantRHS</a>, <a href="#ae85f34cfedbd995195eb9ea0df517b92">cloneImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a2088d6a1f9882689fbea2dff8f09494c">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computePolynomialBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a7467c1c3eff398cd97c3d8a2b2cebac0">constantFoldUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a48f061a53492f73dc9d82812f4350b44">detectPopcountIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a33e48dd73f38cb005f9a57fa3965879e">dropRedundantMaskingOfLeftShiftInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a23f5821d9ac264ae25dd087747e2c181">emitTransformedIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08d3e8ce57fb65481a42b256d26c264d">llvm::expandDivision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cfb58d48c02daaaa8ee7e924e9fb36">llvm::expandDivisionUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c6db1ba2b3654c01ec2363b2bc34ce4">llvm::expandDivisionUpTo64Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0154d60f04a5d8549b44635852557f0">llvm::expandRemainder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a090725add53936fcebc89f58fc9a7da1">llvm::expandRemainderUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27da54a97fcba955457048148b1fef99">llvm::expandRemainderUpTo64Bits</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a36b7410be1f86b52970bb1381904e282">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::foldBinOpIntoSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9317f2efaf85a4afc7cde58a2c0d734b">llvm::InstCombinerImpl::foldBinopWithPhiOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a6556e45ee27ad333bf33eda6b1f04b8a">foldBitCastBitwiseLogic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab60c98e34bf6a4b6b599ab93a3f12b06">llvm::InstCombinerImpl::foldICmpAndShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78aa741a7874614a21b66826ffe6e5ce">llvm::InstCombinerImpl::foldICmpBinOpEqualityWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a10cb0815e46ca2e42c7c40205f77277a">llvm::InstCombinerImpl::foldICmpBinOpWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a45705c727d8388c014471504b4ab0c4e">foldLogicCastConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a917f93b85c9b8cfe9ad68ba6d49966ba">foldSelectBinOpIdentity</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#aa231edc47a3993eaf9c7aa2bb324e2f5">foldSelectFunnelShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ac83b2f6d1a223c7b4ac9eb3783ee1465">foldSelectWithConstOpToBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a04e846746dd1839f88b9a39847f5d643">foldShiftedShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2511e442d198696042ad2a39cad89059">llvm::InstCombinerImpl::foldUsingDistributiveLaws</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa72b51b8f455c8a622bb6f8cc9c14860">llvm::InstCombinerImpl::foldVariableSignZeroExtensionOfVariableHighBitExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#af7e7c9415c23ae336af651877798a377">getAlternateBinop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ac7754c95309ff1784b1e47b0001deeee">getBinOpsForFactorization</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a55a8ce252bfbfa1af642af05f2c31e10">getSalvageOpsForBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#adb1a03152610d15e008c2fdcb93602ed">llvm::InductionDescriptor::isFPInductionPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a5423e9ec6ad1dea3f9a596429e72d463">isModifyingBinopOfNonZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aaa54a171521e00d29d7f61f33f3269d4">isNonZeroRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a50882a093546a573f3e879fc578f167d">isPowerOfTwoRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a2b0c71ae184c2340372a9b43dc675ff4">isReachableFromPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad984958be92d8e57544ae979a2a897e">processSDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a75f37a01df1919449e22c14ec860d8b1">processSRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a8208d3cd3c60073f5c9ceefec06ab2e3">reassociateFCmps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#ac80e92048884e85b87ddd733785e44d9">reassociateForUses</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4b2e9167fd714396a473ee5493c1350b">llvm::InstCombinerImpl::reassociateShiftAmtsOfTwoSameDirectionShifts</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonoptimizeszextends-cpp-/hexagonoptimizeszextends/#a4240fc0963676b19a8cbf8448a599700">anonymous{HexagonOptimizeSZextends.cpp}::HexagonOptimizeSZextends::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a5c0f04dd919f2fa52e52f277a68b1ac1">scalarize</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a34007246c68dde9443b1afc2a5b59318">setLimitsForBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a41c00c458f7416c93927bc2f332b3898">simplifyAssocCastAssoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a8863b1b71b53dbab1dd0bd7933ddb3cf">simplifyAssociativeBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a225d5b1dcc0015e743f1dbbf348a9c36">llvm::InstCombinerImpl::SimplifyAssociativeOrCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0327169186859791aafa580e4fb547e2">SinkShiftAndTruncate</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a8ff215a6e938a8df32c29c99bc126603">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::strengthenRightShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#aa6977569e4724e3cb0b65e13d0e2a8eb">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::VisitBinaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>.</p>

</div>
</div>

### swapOperands() {#a80cc7c4bd4a37fc13e9765fd3a31dbfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BinaryOperator::swapOperands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Exchange the two operands to this instruction.</p>


<p>This instruction is safe to use on any binary instruction and does not modify the semantics of the instruction. If the instruction cannot be reversed (ie, it's a Div), then return true.</p>


<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 2671 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a55743bd32282bf6f87aeb49237b1fb68">llvm::Instruction::isCommutative</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### cloneImpl() {#ae85f34cfedbd995195eb9ea0df517b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * BinaryOperator::cloneImpl ()</td>
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



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 4268 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="#a8f385eda0f71b4e8199b296fbc8e0da9">Create</a> and <a href="#a31bf07f3f61525486633bc1d0bbaf029">getOpcode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AssertOK() {#adb959feef2862685a00de40ac3522620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BinaryOperator::AssertOK ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 2571 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#afe189fd5af3809d6b750958bda727006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BinaryOperator::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a549b2918a7a803c2e79122912b6aa642">classof</a>.</p>

</div>
</div>

### classof() {#a549b2918a7a803c2e79122912b6aa642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BinaryOperator::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#afe189fd5af3809d6b750958bda727006">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### Create() {#a8f385eda0f71b4e8199b296fbc8e0da9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * BinaryOperator::Create (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">BinaryOps</a> Op, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name=<a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a>(), <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Construct a binary instruction, given the opcode and the two operands.</p>


<p>Optionally (if InstBefore is specified) insert the instruction into a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> right before the specified instruction. The specified <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> is allowed to be a dereferenced end iterator.</p>


<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 2639 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#aecee0c15c7ea2581b57ae1e0875f5df1">llvm::fuzzerop::binOpDescriptor</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#aee57a451f8dea6781fa17e7728ee78b5">anonymous{SimplifyIndVar.cpp}::WidenIV::cloneArithmeticIVUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#ae5441d4cfeb857eb3f3afad58fd88c08">anonymous{SimplifyIndVar.cpp}::WidenIV::cloneBitwiseIVUser</a>, <a href="#ae85f34cfedbd995195eb9ea0df517b92">cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d5176ac30d2d151700b01a9f3451131">llvm::InstCombinerImpl::commonIDivTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa831d259fa5719e16927b5f4877988db">llvm::InstCombinerImpl::commonShiftTransforms</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargettransforminfo-cpp/#a2efdcd5db2fb392d8ef38eca4bc0f570">convertNvvmIntrinsicToLlvm</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8f733600a2dd274a9d75d0aa03eea7b2">llvm::IRBuilderBase::CreateBinOpFMF</a>, <a href="#a2cdc7abc417800f113d92c333ea29ddb">CreateDisjoint</a>, <a href="#ac3620292d253c4ad2efdba8623f7ce5c">CreateDisjoint</a>, <a href="#a83f8671569d1c9271896f8bb4b1be5e9">CreateExact</a>, <a href="#a75232ba08deca2d4237adb5780fe2198">CreateExact</a>, <a href="#aea4ea86573aa983a20bb9af1019fd0f5">CreateNSW</a>, <a href="#a3555c92374939e341c136f73c9354d86">CreateNSW</a>, <a href="#abb40063a5c7439f459f7f143e706b7ee">CreateNUW</a>, <a href="#a8fbbce94455a0a2b51e1db3daf2faa2a">CreateNUW</a>, <a href="#ac80f39cdc458ec63d7ff5f7490498230">CreateWithCopiedFlags</a>, <a href="#a73ecec9fc9254930ac757b1e30a9a4e1">CreateWithFMF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a33e48dd73f38cb005f9a57fa3965879e">dropRedundantMaskingOfLeftShiftInput</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a5a706e35559bb3deb6e92a8ac4bfe1e8">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#ad8629a06eaa190b10f442dd35c1df09a">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateSaturatingIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a664aaf46532d6ebeed0dfeb704308d33">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a295de4cfe04f8cf0dee3bc16c78e5f13">llvm::InstCombinerImpl::foldBinOpShiftWithShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a6556e45ee27ad333bf33eda6b1f04b8a">foldBitCastBitwiseLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a5a46b94b8be40eba6d85169820f2a3a4">foldBitCeil</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a9bb2638252bcf281e82bfa7265d76c6e">foldBitOrderCrossLogicOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#ab01a210491dcbefc8db253f4dbaa6497">foldComplexAndOrPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78aa741a7874614a21b66826ffe6e5ce">llvm::InstCombinerImpl::foldICmpBinOpEqualityWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1140591a375ac3efde57977192880eb0">llvm::InstCombinerImpl::foldICmpOrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7c9fd9f2dba79c2289639f72457fcea1">llvm::InstCombinerImpl::foldICmpUsingBoolRange</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9eeb1caaa920e692849cb94d64b7d66f">llvm::InstCombinerImpl::foldSelectIntoOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a2c05df65ce7ce7ec1d78348be2452e8d">foldSelectShuffleWith1Binop</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a94c6c4745f22f8389f28f74c4e6db01f">foldShiftOfShiftedBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa72b51b8f455c8a622bb6f8cc9c14860">llvm::InstCombinerImpl::foldVariableSignZeroExtensionOfVariableHighBitExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af9fc0080b4accc0b19bfbbc624701e30">llvm::ConstantExpr::getAsInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#aebac730a26c607cea825366afca2d8b1">hoistBOAssociation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a697cde840957bbc0b2848a593c3e0d5a">hoistMulAddAssociation</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a2d3ce43f7795a8f4f6925bffbcc90279">matchDeMorgansLaws</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a48c169a79ae8cf4df76ce79bae91e926">processSaturatingInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a8208d3cd3c60073f5c9ceefec06ab2e3">reassociateFCmps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#ac80e92048884e85b87ddd733785e44d9">reassociateForUses</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4b2e9167fd714396a473ee5493c1350b">llvm::InstCombinerImpl::reassociateShiftAmtsOfTwoSameDirectionShifts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a8a96c9b1143670a73852464de9950e8e">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceSRemWithURem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a225d5b1dcc0015e743f1dbbf348a9c36">llvm::InstCombinerImpl::SimplifyAssociativeOrCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0049977ff1075a98e9f512bbf4d181a6">sinkAndCmp0Expression</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a612d91fe0858006abe73d7b62821da0c">llvm::InstCombinerImpl::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>.</p>

</div>
</div>

### CreateDisjoint() {#ac3620292d253c4ad2efdba8623f7ce5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateDisjoint (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">BinaryOps</a> Opc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a8f385eda0f71b4e8199b296fbc8e0da9">Create</a>.</p>

</div>
</div>

### CreateDisjoint() {#a2cdc7abc417800f113d92c333ea29ddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateDisjoint (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">BinaryOps</a> Opc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore)</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a8f385eda0f71b4e8199b296fbc8e0da9">Create</a>.</p>

</div>
</div>

### CreateExact() {#a75232ba08deca2d4237adb5780fe2198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateExact (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">BinaryOps</a> Opc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="#a8f385eda0f71b4e8199b296fbc8e0da9">Create</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#ac01940f561517355e394911c203bcedf">llvm::Instruction::setIsExact</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>.</p>

</div>
</div>

### CreateExact() {#a83f8671569d1c9271896f8bb4b1be5e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateExact (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">BinaryOps</a> Opc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore)</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="#a8f385eda0f71b4e8199b296fbc8e0da9">Create</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#ac01940f561517355e394911c203bcedf">llvm::Instruction::setIsExact</a>.</p>

</div>
</div>

### CreateFAddFMF() {#a0fdb430e8a6a952ae71e3a309919d79c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateFAddFMF (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a> and <a href="#a73ecec9fc9254930ac757b1e30a9a4e1">CreateWithFMF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a362318cf2eed59d9c8d159a8710ce91f">factorizeLerp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac633a4c4d399457c76640f7dea5ebcd7">llvm::InstCombinerImpl::foldFMulReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a92fdf04445f26ef88ea0e134408b30fe">llvm::InstCombinerImpl::visitFAdd</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa72f4f7fc2ee2bf6cd3b64bd07c37e8">llvm::InstCombinerImpl::visitFSub</a>.</p>

</div>
</div>

### CreateFAddFMF() {#a9db96e4b900739b4047a803bdf895e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateFAddFMF (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * FMFSource, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="#ac80f39cdc458ec63d7ff5f7490498230">CreateWithCopiedFlags</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

### CreateFDivFMF() {#ab2f94c836428e78d253e63f8b2d3e609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateFDivFMF (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a> and <a href="#a73ecec9fc9254930ac757b1e30a9a4e1">CreateWithFMF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a00e3a88ec91a20ce25260bfe2ff33bcc">factorizeFAddFSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#ada35ba039e94beae7918a289a5bcb417">foldFDivConstantDividend</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac633a4c4d399457c76640f7dea5ebcd7">llvm::InstCombinerImpl::foldFMulReassoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a27bba7d498620b1d330d2ef77362f04f">foldFNegIntoConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aed2c2c5e2a07649e02d6647d9a5c8852">llvm::InstCombinerImpl::foldPowiReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5457b45fe74cf2f411f5824d32fd389d">llvm::InstCombinerImpl::visitFDiv</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a>.</p>

</div>
</div>

### CreateFDivFMF() {#a18e219326bd3cb20a63ac8b8c8e49294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateFDivFMF (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * FMFSource, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="#ac80f39cdc458ec63d7ff5f7490498230">CreateWithCopiedFlags</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

### CreateFMulFMF() {#a9ed325338b1b10d9eb5d0daa29474b4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateFMulFMF (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a> and <a href="#a73ecec9fc9254930ac757b1e30a9a4e1">CreateWithFMF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a00e3a88ec91a20ce25260bfe2ff33bcc">factorizeFAddFSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a5331fd8c7fc139f6c95cda265ac15d97">foldFDivPowDivisor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#ad82d371a838bc44a8a9915f68870bfad">foldFDivSqrtDivisor</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac633a4c4d399457c76640f7dea5ebcd7">llvm::InstCombinerImpl::foldFMulReassoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a27bba7d498620b1d330d2ef77362f04f">foldFNegIntoConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4a128160ac46052a6accc9ba3e84ae08">llvm::InstCombinerImpl::foldSquareSumFP</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a92fdf04445f26ef88ea0e134408b30fe">llvm::InstCombinerImpl::visitFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5457b45fe74cf2f411f5824d32fd389d">llvm::InstCombinerImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abf257c2c6dadfee6ee83fabb6ea77c4f">llvm::InstCombinerImpl::visitFMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa72f4f7fc2ee2bf6cd3b64bd07c37e8">llvm::InstCombinerImpl::visitFSub</a>.</p>

</div>
</div>

### CreateFMulFMF() {#a78cf65739da4d78960d847fceea64bf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateFMulFMF (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * FMFSource, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="#ac80f39cdc458ec63d7ff5f7490498230">CreateWithCopiedFlags</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

### CreateFRemFMF() {#a70d7b5ed965c40fb10f25961540bc474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateFRemFMF (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * FMFSource, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="#ac80f39cdc458ec63d7ff5f7490498230">CreateWithCopiedFlags</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

### CreateFSubFMF() {#ac24b427d643de0a47151a909faaba408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateFSubFMF (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a> and <a href="#a73ecec9fc9254930ac757b1e30a9a4e1">CreateWithFMF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac633a4c4d399457c76640f7dea5ebcd7">llvm::InstCombinerImpl::foldFMulReassoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a27bba7d498620b1d330d2ef77362f04f">foldFNegIntoConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a92fdf04445f26ef88ea0e134408b30fe">llvm::InstCombinerImpl::visitFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abf257c2c6dadfee6ee83fabb6ea77c4f">llvm::InstCombinerImpl::visitFMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af616ac59efde7c61f6e8ff8bd80d2027">llvm::InstCombinerImpl::visitFNeg</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa72f4f7fc2ee2bf6cd3b64bd07c37e8">llvm::InstCombinerImpl::visitFSub</a>.</p>

</div>
</div>

### CreateFSubFMF() {#a885c3de943bddf8931a02e916c62bb5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateFSubFMF (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * FMFSource, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="#ac80f39cdc458ec63d7ff5f7490498230">CreateWithCopiedFlags</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

### CreateNeg() {#a17c16c797477788dba165b1d6e8e862d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * BinaryOperator::CreateNeg (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Helper functions to construct and inspect unary operations (NEG and NOT) via binary operators SUB and XOR:</p>


<p>Create the NEG and NOT instructions out of SUB and XOR instructions.</p>


<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 2647 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Reference <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#abaecf6dabc1e9495c8ba0c899ba1565c">CreateNeg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#ab2d3d519ed327a47cba69f5523785d2d">getShiftedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad984958be92d8e57544ae979a2a897e">processSDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a75f37a01df1919449e22c14ec860d8b1">processSRem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a612d91fe0858006abe73d7b62821da0c">llvm::InstCombinerImpl::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>.</p>

</div>
</div>

### CreateNot() {#a8578626ceb87974ed94fd56b56a37346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * BinaryOperator::CreateNot (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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



<p>Declaration at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 2660 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a458a807bd844c8d6ec4951c2fa00e61d">canonicalizeICmpBool</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#ac9ae2e49a0bf8f52cd2bac401c001b6c">canonicalizeLowbitMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a385c1da88456d434ee18caa8f48018c2">foldAndToXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#ab01a210491dcbefc8db253f4dbaa6497">foldComplexAndOrPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac457b78bde79027e427b9d2ca79bb2f1">llvm::InstCombinerImpl::foldICmpAndConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a26257c73e483eab4b0e15d53340de986">foldOrToXor</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aebb0348d8efce5fbf0d73f96cfb1212e">llvm::InstCombinerImpl::foldSelectOfBools</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a3b3df3036740dfcdeb37c3ad977b039a">foldXorToXor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fcd2292dd9e51480a2f43d41acfe2">llvm::invertCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a2d3ce43f7795a8f4f6925bffbcc90279">matchDeMorgansLaws</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a612d91fe0858006abe73d7b62821da0c">llvm::InstCombinerImpl::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>.</p>

</div>
</div>

### CreateNSW() {#a3555c92374939e341c136f73c9354d86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateNSW (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">BinaryOps</a> Opc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="#a8f385eda0f71b4e8199b296fbc8e0da9">Create</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4166b451a572b1e5d3fea7250af53653">llvm::Instruction::setHasNoSignedWrap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### CreateNSW() {#aea4ea86573aa983a20bb9af1019fd0f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateNSW (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">BinaryOps</a> Opc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore)</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="#a8f385eda0f71b4e8199b296fbc8e0da9">Create</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4166b451a572b1e5d3fea7250af53653">llvm::Instruction::setHasNoSignedWrap</a>.</p>

</div>
</div>

### CreateNSWNeg() {#ad4c3a10c3f94bacfa216245cd4b84225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * BinaryOperator::CreateNSWNeg (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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



<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 2654 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Reference <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a411aa95504f966614c8f5d5aeeef1f04">llvm::InstCombinerImpl::visitSRem</a>.</p>

</div>
</div>

### CreateNUW() {#a8fbbce94455a0a2b51e1db3daf2faa2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateNUW (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">BinaryOps</a> Opc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="#a8f385eda0f71b4e8199b296fbc8e0da9">Create</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0c03b71c79206ec41270dc3788183e0d">llvm::Instruction::setHasNoUnsignedWrap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a225d5b1dcc0015e743f1dbbf348a9c36">llvm::InstCombinerImpl::SimplifyAssociativeOrCommutative</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### CreateNUW() {#abb40063a5c7439f459f7f143e706b7ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateNUW (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">BinaryOps</a> Opc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="#a8f385eda0f71b4e8199b296fbc8e0da9">Create</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0c03b71c79206ec41270dc3788183e0d">llvm::Instruction::setHasNoUnsignedWrap</a>.</p>

</div>
</div>

### CreateWithCopiedFlags() {#ac80f39cdc458ec63d7ff5f7490498230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateWithCopiedFlags (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">BinaryOps</a> Opc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CopyO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3e6d2896c39a84cfa6c47f34cdc584ff">llvm::Instruction::copyIRFlags</a> and <a href="#a8f385eda0f71b4e8199b296fbc8e0da9">Create</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a7b8ca6f7206a11fd57d6e194b2523ffe">canonicalizeLogicFirst</a>, <a href="#a9db96e4b900739b4047a803bdf895e82">CreateFAddFMF</a>, <a href="#a18e219326bd3cb20a63ac8b8c8e49294">CreateFDivFMF</a>, <a href="#a78cf65739da4d78960d847fceea64bf8">CreateFMulFMF</a>, <a href="#a70d7b5ed965c40fb10f25961540bc474">CreateFRemFMF</a>, <a href="#a885c3de943bddf8931a02e916c62bb5c">CreateFSubFMF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ae2f9543c1954e97e2887aab7c33e18b4">instCombineSVELast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>.</p>

</div>
</div>

### CreateWithFMF() {#a73ecec9fc9254930ac757b1e30a9a4e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator * llvm::BinaryOperator::CreateWithFMF (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">BinaryOps</a> Opc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#acee1035fe1c77f85d4b80655e4df150a">BinaryOperator</a>, <a href="#a8f385eda0f71b4e8199b296fbc8e0da9">Create</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5ca8aa62fa8b3fe5bc0e8fbe5d8b8b7a">llvm::Instruction::setFastMathFlags</a>.</p>


<p>Referenced by <a href="#a0fdb430e8a6a952ae71e3a309919d79c">CreateFAddFMF</a>, <a href="#ab2f94c836428e78d253e63f8b2d3e609">CreateFDivFMF</a>, <a href="#a9ed325338b1b10d9eb5d0daa29474b4d">CreateFMulFMF</a> and <a href="#ac24b427d643de0a47151a909faaba408">CreateFSubFMF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### AllocMarker {#ad6feb434c47a8bfecd45e2ef64c9f63c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveOperandsAllocMarker llvm::BinaryOperator::AllocMarker {2}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
