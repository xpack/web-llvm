---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpinstruction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VPInstruction` Class Reference

<p>This is a concrete Recipe that models a single VPlan-level instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPInstruction { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">Transforms/Vectorize/VPlan.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags">VPRecipeWithIRFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to record LLVM IR flag for a recipe along with it. <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpunrollpartaccessor">VPUnrollPartAccessor&lt;PartOpIdx&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to access the operand that contains the unroll part for this recipe after unrolling. <a href="/web-llvm/docs/api/classes/llvm/vpunrollpartaccessor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">unsigned char <a href="#a7ed904a57da127634068d146a8b6ef73">OpcodeTy</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a507f9482c01673384c0c203530dad6f2">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> opcodes, extending LLVM IR with idiomatics instructions. <a href="#a507f9482c01673384c0c203530dad6f2">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe83ec52998d9636245b5a6007936657">VPlanSlp</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a432b57e3924afb475fc91aafb56b5e0d">VPInstruction</a> (unsigned Opcode, ArrayRef&lt; VPValue * &gt; Operands, DebugLoc DL, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaab87e71e2ce50030cb513bc3151eef9">VPInstruction</a> (unsigned Opcode, std::initializer_list&lt; VPValue * &gt; Operands, DebugLoc DL={}, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48a72267f2f64714199a91155da60888">VPInstruction</a> (unsigned Opcode, CmpInst::Predicate Pred, VPValue *A, VPValue *B, DebugLoc DL={}, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa008922f90e2a3966fb4582c3abd4f1d">VPInstruction</a> (unsigned Opcode, std::initializer_list&lt; VPValue * &gt; Operands, WrapFlagsTy WrapFlags, DebugLoc DL={}, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ab6c89f88924902569eab504c112e8">VPInstruction</a> (unsigned Opcode, std::initializer_list&lt; VPValue * &gt; Operands, DisjointFlagsTy DisjointFlag, DebugLoc DL={}, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01acf999c0c5c61efca50df05ab76fe0">VPInstruction</a> (VPValue *Ptr, VPValue *Offset, GEPNoWrapFlags Flags, DebugLoc DL={}, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a256e4c0d88c74db616499748f0a224a1">VPInstruction</a> (unsigned Opcode, std::initializer_list&lt; VPValue * &gt; Operands, FastMathFlags FMFs, DebugLoc DL={}, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a5678fa8d469e9dd49b7e389c22d5c7">clone</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the current recipe. <a href="#a4a5678fa8d469e9dd49b7e389c22d5c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e93600f7fe97f0d774cda9179b1ff1">getOpcode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2ef259f4a63359fe35f05b8b67a911b">execute</a> (VPTransformState &amp;State) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the instruction. <a href="#af2ef259f4a63359fe35f05b8b67a911b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a004ecf8ed4165883d4dfa06716dd72c9">computeCost</a> (ElementCount VF, VPCostContext &amp;Ctx) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of this <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a>. <a href="#a004ecf8ed4165883d4dfa06716dd72c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca839409ad4f4fb66241f6b97da6674f">print</a> (raw_ostream &amp;O, const Twine &amp;Indent, VPSlotTracker &amp;SlotTracker) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> to <span class="doxyComputerOutput">O</span>. <a href="#aca839409ad4f4fb66241f6b97da6674f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a824509de893dd23a9dde948791384889">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> (for debugging). <a href="#a824509de893dd23a9dde948791384889">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f3fa71b92cd3ef9f488c5d4ede784c">hasResult</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f10a1f949eaa66f6daa0940c33ac26e">opcodeMayReadOrWriteFromMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the underlying opcode may read from or write to memory. <a href="#a7f10a1f949eaa66f6daa0940c33ac26e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accc830d2b6d4d03922cf5e6a238ae9c1">onlyFirstLaneUsed</a> (const VPValue *Op) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recipe only uses the first lane of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#accc830d2b6d4d03922cf5e6a238ae9c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0b84f190dbf600165d9b79f4cf51d6c">onlyFirstPartUsed</a> (const VPValue *Op) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recipe only uses the first part of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>. <a href="#aa0b84f190dbf600165d9b79f4cf51d6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0087d40306e4bdd882281c1f0ca82ca">isVectorToScalar</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> produces a scalar value from a vector, e.g. <a href="#ac0087d40306e4bdd882281c1f0ca82ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad11c8a9ccf3544709647a3c24cd4de0a">isSingleScalar</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a>'s operands are single scalars and the result is also a single scalar. <a href="#ad11c8a9ccf3544709647a3c24cd4de0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86455fc0e3398446a16243cf3aef28cd">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the symbolic name assigned to the <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a>. <a href="#a86455fc0e3398446a16243cf3aef28cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40451161c12289152dce77c548672a03">doesGeneratePerAllLanes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> generates scalar values for all lanes. <a href="#a40451161c12289152dce77c548672a03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b2a9f39e48767dec711796143ee6234">canGenerateScalarForFirstLane</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we can generate a scalar for the first lane only if needed. <a href="#a4b2a9f39e48767dec711796143ee6234">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dca33e36abd2e8a2a5c13319dea1edb">generate</a> (VPTransformState &amp;State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility methods serving <a href="#af2ef259f4a63359fe35f05b8b67a911b">execute()</a>: generates a single vector instance of the modeled instruction. <a href="#a9dca33e36abd2e8a2a5c13319dea1edb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84d6e98aea5dd44dbb407aa96ead9772">generatePerLane</a> (VPTransformState &amp;State, const VPLane &amp;Lane)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility methods serving <a href="#af2ef259f4a63359fe35f05b8b67a911b">execute()</a>: generates a scalar single instance of the modeled instruction for a given lane. <a href="#a84d6e98aea5dd44dbb407aa96ead9772">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d4d7dbadb6ac45570a53173fa2af669">isFPMathOp</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> is a floating point math operation, i.e. <a href="#a7d4d7dbadb6ac45570a53173fa2af669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">OpcodeTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a738983407d18f0eef1a7435a1a216f6b">Opcode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee3328b68143724f8e572a18009a400b">Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An optional name that can be used for the generated IR instruction. <a href="#aee3328b68143724f8e572a18009a400b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This is a concrete Recipe that models a single VPlan-level instruction.</p>


<p>While as any Recipe it may generate a sequence of IR instructions when executed, these instructions would always form a single-def expression as the <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> is also a single def-use vertex.</p>


<p>Definition at line 1189 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### OpcodeTy {#a7ed904a57da127634068d146a8b6ef73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef unsigned char llvm::VPInstruction::OpcodeTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1230 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a507f9482c01673384c0c203530dad6f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> opcodes, extending LLVM IR with idiomatics instructions.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FirstOrderRecurrenceSplice<a id="a507f9482c01673384c0c203530dad6f2a811727530f9a54b651d638943d34aa61"></a></td>
<td class="doxyEnumItemDescription">
 (=
        Instruction::OtherOpsEnd + 1)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Not<a id="a507f9482c01673384c0c203530dad6f2adc31f61474346e1f42ec58902ee8a48b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SLPLoad<a id="a507f9482c01673384c0c203530dad6f2ad637aaaf756031d33d399e2cdca38169"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SLPStore<a id="a507f9482c01673384c0c203530dad6f2a9de503016dbb7f9d0e96addb64752282"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ActiveLaneMask<a id="a507f9482c01673384c0c203530dad6f2a79a53c84dbac24c496a4c9a6cf70596c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExplicitVectorLength<a id="a507f9482c01673384c0c203530dad6f2a8c9deab6571a0b4db0c69c64c0d682eb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ResumePhi<a id="a507f9482c01673384c0c203530dad6f2a36144832b0ebcda13ce881d2b60eaf91"></a></td>
<td class="doxyEnumItemDescription">Creates a scalar phi in a leaf VPBB with a single predecessor in <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CalculateTripCountMinusVF<a id="a507f9482c01673384c0c203530dad6f2add61254acc7408bb3c3bb55765481418"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CanonicalIVIncrementForPart<a id="a507f9482c01673384c0c203530dad6f2ad271d9d05bf5644dfa1487b3fc42a131"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BranchOnCount<a id="a507f9482c01673384c0c203530dad6f2a49dcace93798ddd457a9d4e584bbc9a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BranchOnCond<a id="a507f9482c01673384c0c203530dad6f2a0062eccdb4956531f7b6a3cf71c3320c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ComputeReductionResult<a id="a507f9482c01673384c0c203530dad6f2ad9b4011dc2ac58da0fecd16d99f1f17d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExtractFromEnd<a id="a507f9482c01673384c0c203530dad6f2ad6b029191d02f4c7a7dda59e44c88ab6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LogicalAnd<a id="a507f9482c01673384c0c203530dad6f2abeeaaa123e853f501079c8214ebbe574"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PtrAdd<a id="a507f9482c01673384c0c203530dad6f2a055004cd2c472e5a3de6eb59c5f8d9f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AnyOf<a id="a507f9482c01673384c0c203530dad6f2aeb4304c45f6343ca9188dbe52456a969"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1195 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### VPlanSlp {#abe83ec52998d9636245b5a6007936657}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vplanslp">VPlanSlp</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1191 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#abe83ec52998d9636245b5a6007936657">VPlanSlp</a>.</p>


<p>Referenced by <a href="#abe83ec52998d9636245b5a6007936657">VPlanSlp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VPInstruction() {#a432b57e3924afb475fc91aafb56b5e0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPInstruction::VPInstruction (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 1265 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#afbcee996669bdac73eae32d28d2e4bd6">llvm::VPRecipeWithIRFlags::VPRecipeWithIRFlags</a>.</p>


<p>Referenced by <a href="#a4a5678fa8d469e9dd49b7e389c22d5c7">clone</a>.</p>

</div>
</div>

### VPInstruction() {#aaab87e71e2ce50030cb513bc3151eef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPInstruction::VPInstruction (unsigned Opcode, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 1270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### VPInstruction() {#a48a72267f2f64714199a91155da60888}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPInstruction::VPInstruction (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * A, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * B, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1274 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#afbcee996669bdac73eae32d28d2e4bd6">llvm::VPRecipeWithIRFlags::VPRecipeWithIRFlags</a>.</p>

</div>
</div>

### VPInstruction() {#aa008922f90e2a3966fb4582c3abd4f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPInstruction::VPInstruction (unsigned Opcode, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/structs/llvm/vprecipewithirflags/wrapflagsty">WrapFlagsTy</a> WrapFlags, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 1277 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#ab3a63ff3b45bc15bb37319586c23f61f">llvm::VPRecipeWithIRFlags::WrapFlags</a>.</p>

</div>
</div>

### VPInstruction() {#ab8ab6c89f88924902569eab504c112e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPInstruction::VPInstruction (unsigned Opcode, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/structs/llvm/vprecipewithirflags/disjointflagsty">DisjointFlagsTy</a> DisjointFlag, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 1282 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### VPInstruction() {#a01acf999c0c5c61efca50df05ab76fe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPInstruction::VPInstruction (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Offset, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 1290 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### VPInstruction() {#a256e4c0d88c74db616499748f0a224a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPInstruction::VPInstruction (unsigned Opcode, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMFs, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1296 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#a03dfa6aae22c9aaa0ce5808161d42c45">llvm::VPRecipeWithIRFlags::FMFs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#afbcee996669bdac73eae32d28d2e4bd6">llvm::VPRecipeWithIRFlags::VPRecipeWithIRFlags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#a4a5678fa8d469e9dd49b7e389c22d5c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPInstruction * llvm::VPInstruction::clone ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone the current recipe.</p>

<p>Definition at line 1301 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#a4a5678fa8d469e9dd49b7e389c22d5c7">clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a>, <a href="#a432b57e3924afb475fc91aafb56b5e0d">VPInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3feb4ab29b46ff2d493da56f4ee1e6e7">llvm::VPValue::VPInstruction</a>.</p>


<p>Referenced by <a href="#a4a5678fa8d469e9dd49b7e389c22d5c7">clone</a>.</p>

</div>
</div>

### computeCost() {#a004ecf8ed4165883d4dfa06716dd72c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost VPInstruction::computeCost (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext">VPCostContext</a> &amp; Ctx)</td>
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

<p>Return the cost of this <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a>.</p>

<p>Declaration at line 1316 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 706 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a92e93600f7fe97f0d774cda9179b1ff1">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a5fe7dd2466300bd8747d81384a7ced5d">llvm::VPValue::getUnderlyingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a5e3c306be8d629a994f3644765421d5f">llvm::vputils::onlyFirstLaneUsed</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae5262cc0e3a55bc74891cb8751d3b188">llvm::toVectorTy</a>.</p>

</div>
</div>

### dump() {#a824509de893dd23a9dde948791384889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPInstruction::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> (for debugging).</p>

<p>Declaration at line 1325 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a6c88376daf23b16ad26b7ac6c224d21e">llvm::VPRecipeBase::getParent</a> and <a href="#aca839409ad4f4fb66241f6b97da6674f">print</a>.</p>

</div>
</div>

### execute() {#af2ef259f4a63359fe35f05b8b67a911b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPInstruction::execute (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
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

<p>Generate the instruction.</p>


<p>TODO: We currently execute only per-part unless a specific instance is provided.</p>


<p>Declaration at line 1313 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#af44641b38a715b1326e5000ae611c9ea">llvm::VPRecipeWithIRFlags::getFastMathFlags</a>, <a href="#a92e93600f7fe97f0d774cda9179b1ff1">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#a648f12184c1f646e80420b0ab9817fa0">llvm::VPRecipeWithIRFlags::hasFastMathFlags</a>, <a href="#a53f3fa71b92cd3ef9f488c5d4ede784c">hasResult</a>, <a href="#ad11c8a9ccf3544709647a3c24cd4de0a">isSingleScalar</a>, <a href="#ac0087d40306e4bdd882281c1f0ca82ca">isVectorToScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a5e3c306be8d629a994f3644765421d5f">llvm::vputils::onlyFirstLaneUsed</a>.</p>

</div>
</div>

### getName() {#a86455fc0e3398446a16243cf3aef28cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::VPInstruction::getName ()</td>
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

<p>Returns the symbolic name assigned to the <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a>.</p>

<p>Definition at line 1368 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### getOpcode() {#a92e93600f7fe97f0d774cda9179b1ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VPInstruction::getOpcode ()</td>
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



<p>Definition at line 1308 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a004ecf8ed4165883d4dfa06716dd72c9">computeCost</a>, <a href="#af2ef259f4a63359fe35f05b8b67a911b">execute</a>, <a href="#a53f3fa71b92cd3ef9f488c5d4ede784c">hasResult</a>, <a href="#ad11c8a9ccf3544709647a3c24cd4de0a">isSingleScalar</a>, <a href="#ac0087d40306e4bdd882281c1f0ca82ca">isVectorToScalar</a>, <a href="#accc830d2b6d4d03922cf5e6a238ae9c1">onlyFirstLaneUsed</a>, <a href="#aa0b84f190dbf600165d9b79f4cf51d6c">onlyFirstPartUsed</a>, <a href="#a7f10a1f949eaa66f6daa0940c33ac26e">opcodeMayReadOrWriteFromMemory</a> and <a href="#aca839409ad4f4fb66241f6b97da6674f">print</a>.</p>

</div>
</div>

### hasResult() {#a53f3fa71b92cd3ef9f488c5d4ede784c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPInstruction::hasResult ()</td>
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



<p>Definition at line 1328 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#a507f9482c01673384c0c203530dad6f2a0062eccdb4956531f7b6a3cf71c3320c">BranchOnCond</a>, <a href="#a507f9482c01673384c0c203530dad6f2a49dcace93798ddd457a9d4e584bbc9a2">BranchOnCount</a> and <a href="#a92e93600f7fe97f0d774cda9179b1ff1">getOpcode</a>.</p>


<p>Referenced by <a href="#af2ef259f4a63359fe35f05b8b67a911b">execute</a> and <a href="#aca839409ad4f4fb66241f6b97da6674f">print</a>.</p>

</div>
</div>

### isSingleScalar() {#ad11c8a9ccf3544709647a3c24cd4de0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPInstruction::isSingleScalar ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a>'s operands are single scalars and the result is also a single scalar.</p>

<p>Declaration at line 1365 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="#a92e93600f7fe97f0d774cda9179b1ff1">getOpcode</a> and <a href="#a507f9482c01673384c0c203530dad6f2a36144832b0ebcda13ce881d2b60eaf91">ResumePhi</a>.</p>


<p>Referenced by <a href="#af2ef259f4a63359fe35f05b8b67a911b">execute</a>.</p>

</div>
</div>

### isVectorToScalar() {#ac0087d40306e4bdd882281c1f0ca82ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPInstruction::isVectorToScalar ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> produces a scalar value from a vector, e.g.</p>


<p>by performing a reduction or extracting a lane.</p>


<p>Declaration at line 1361 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="#a507f9482c01673384c0c203530dad6f2aeb4304c45f6343ca9188dbe52456a969">AnyOf</a>, <a href="#a507f9482c01673384c0c203530dad6f2ad9b4011dc2ac58da0fecd16d99f1f17d">ComputeReductionResult</a>, <a href="#a507f9482c01673384c0c203530dad6f2ad6b029191d02f4c7a7dda59e44c88ab6">ExtractFromEnd</a> and <a href="#a92e93600f7fe97f0d774cda9179b1ff1">getOpcode</a>.</p>


<p>Referenced by <a href="#af2ef259f4a63359fe35f05b8b67a911b">execute</a>.</p>

</div>
</div>

### onlyFirstLaneUsed() {#accc830d2b6d4d03922cf5e6a238ae9c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPInstruction::onlyFirstLaneUsed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Op)</td>
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

<p>Returns true if the recipe only uses the first lane of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>

<p>Declaration at line 1354 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="#a507f9482c01673384c0c203530dad6f2a79a53c84dbac24c496a4c9a6cf70596c">ActiveLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a507f9482c01673384c0c203530dad6f2a0062eccdb4956531f7b6a3cf71c3320c">BranchOnCond</a>, <a href="#a507f9482c01673384c0c203530dad6f2a49dcace93798ddd457a9d4e584bbc9a2">BranchOnCount</a>, <a href="#a507f9482c01673384c0c203530dad6f2add61254acc7408bb3c3bb55765481418">CalculateTripCountMinusVF</a>, <a href="#a507f9482c01673384c0c203530dad6f2ad271d9d05bf5644dfa1487b3fc42a131">CanonicalIVIncrementForPart</a>, <a href="#a507f9482c01673384c0c203530dad6f2a8c9deab6571a0b4db0c69c64c0d682eb">ExplicitVectorLength</a>, <a href="#a92e93600f7fe97f0d774cda9179b1ff1">getOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a5e3c306be8d629a994f3644765421d5f">llvm::vputils::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a>, <a href="#a507f9482c01673384c0c203530dad6f2a055004cd2c472e5a3de6eb59c5f8d9f5">PtrAdd</a> and <a href="#a507f9482c01673384c0c203530dad6f2a36144832b0ebcda13ce881d2b60eaf91">ResumePhi</a>.</p>

</div>
</div>

### onlyFirstPartUsed() {#aa0b84f190dbf600165d9b79f4cf51d6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPInstruction::onlyFirstPartUsed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Op)</td>
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

<p>Returns true if the recipe only uses the first part of operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p>

<p>Declaration at line 1357 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 832 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a507f9482c01673384c0c203530dad6f2a0062eccdb4956531f7b6a3cf71c3320c">BranchOnCond</a>, <a href="#a507f9482c01673384c0c203530dad6f2a49dcace93798ddd457a9d4e584bbc9a2">BranchOnCount</a>, <a href="#a507f9482c01673384c0c203530dad6f2ad271d9d05bf5644dfa1487b3fc42a131">CanonicalIVIncrementForPart</a>, <a href="#a92e93600f7fe97f0d774cda9179b1ff1">getOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a513233e0bcf9aaf36f9672eff75514ea">llvm::vputils::onlyFirstPartUsed</a> and <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a11d83265a9e4ff6c6ecd3cf222ad0208">llvm::VPUser::operands</a>.</p>

</div>
</div>

### opcodeMayReadOrWriteFromMemory() {#a7f10a1f949eaa66f6daa0940c33ac26e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPInstruction::opcodeMayReadOrWriteFromMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the underlying opcode may read from or write to memory.</p>

<p>Declaration at line 1351 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 786 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="#a507f9482c01673384c0c203530dad6f2aeb4304c45f6343ca9188dbe52456a969">AnyOf</a>, <a href="#a507f9482c01673384c0c203530dad6f2add61254acc7408bb3c3bb55765481418">CalculateTripCountMinusVF</a>, <a href="#a507f9482c01673384c0c203530dad6f2ad271d9d05bf5644dfa1487b3fc42a131">CanonicalIVIncrementForPart</a>, <a href="#a507f9482c01673384c0c203530dad6f2ad6b029191d02f4c7a7dda59e44c88ab6">ExtractFromEnd</a>, <a href="#a507f9482c01673384c0c203530dad6f2a811727530f9a54b651d638943d34aa61">FirstOrderRecurrenceSplice</a>, <a href="#a92e93600f7fe97f0d774cda9179b1ff1">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="#a507f9482c01673384c0c203530dad6f2abeeaaa123e853f501079c8214ebbe574">LogicalAnd</a>, <a href="#a507f9482c01673384c0c203530dad6f2adc31f61474346e1f42ec58902ee8a48b">Not</a> and <a href="#a507f9482c01673384c0c203530dad6f2a055004cd2c472e5a3de6eb59c5f8d9f5">PtrAdd</a>.</p>

</div>
</div>

### print() {#aca839409ad4f4fb66241f6b97da6674f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPInstruction::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Indent, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a> &amp; SlotTracker)</td>
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

<p>Print the <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> to <span class="doxyComputerOutput">O</span>.</p>

<p>Declaration at line 1321 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 857 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="#a507f9482c01673384c0c203530dad6f2a79a53c84dbac24c496a4c9a6cf70596c">ActiveLaneMask</a>, <a href="#a507f9482c01673384c0c203530dad6f2aeb4304c45f6343ca9188dbe52456a969">AnyOf</a>, <a href="#a507f9482c01673384c0c203530dad6f2a0062eccdb4956531f7b6a3cf71c3320c">BranchOnCond</a>, <a href="#a507f9482c01673384c0c203530dad6f2a49dcace93798ddd457a9d4e584bbc9a2">BranchOnCount</a>, <a href="#a507f9482c01673384c0c203530dad6f2add61254acc7408bb3c3bb55765481418">CalculateTripCountMinusVF</a>, <a href="#a507f9482c01673384c0c203530dad6f2ad271d9d05bf5644dfa1487b3fc42a131">CanonicalIVIncrementForPart</a>, <a href="#a507f9482c01673384c0c203530dad6f2ad9b4011dc2ac58da0fecd16d99f1f17d">ComputeReductionResult</a>, <a href="#a507f9482c01673384c0c203530dad6f2a8c9deab6571a0b4db0c69c64c0d682eb">ExplicitVectorLength</a>, <a href="#a507f9482c01673384c0c203530dad6f2ad6b029191d02f4c7a7dda59e44c88ab6">ExtractFromEnd</a>, <a href="#a507f9482c01673384c0c203530dad6f2a811727530f9a54b651d638943d34aa61">FirstOrderRecurrenceSplice</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a733c4c530159a8b86223376c0696430e">llvm::VPRecipeBase::getDebugLoc</a>, <a href="#a92e93600f7fe97f0d774cda9179b1ff1">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9affd129d19aae669647eb0d1c91f793">llvm::Instruction::getOpcodeName</a>, <a href="#a53f3fa71b92cd3ef9f488c5d4ede784c">hasResult</a>, <a href="#a507f9482c01673384c0c203530dad6f2abeeaaa123e853f501079c8214ebbe574">LogicalAnd</a>, <a href="#a507f9482c01673384c0c203530dad6f2adc31f61474346e1f42ec58902ee8a48b">Not</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3fc47e93505e87044e0861e4142eca20">llvm::VPValue::printAsOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#ae6a91bbf1cfed2d6ba572ca974c94161">llvm::VPRecipeWithIRFlags::printFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a0112474f9dc69912e4c067594692d15b">llvm::VPUser::printOperands</a>, <a href="#a507f9482c01673384c0c203530dad6f2a055004cd2c472e5a3de6eb59c5f8d9f5">PtrAdd</a>, <a href="#a507f9482c01673384c0c203530dad6f2a36144832b0ebcda13ce881d2b60eaf91">ResumePhi</a>, <a href="#a507f9482c01673384c0c203530dad6f2ad637aaaf756031d33d399e2cdca38169">SLPLoad</a> and <a href="#a507f9482c01673384c0c203530dad6f2a9de503016dbb7f9d0e96addb64752282">SLPStore</a>.</p>


<p>Referenced by <a href="#a824509de893dd23a9dde948791384889">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canGenerateScalarForFirstLane() {#a4b2a9f39e48767dec711796143ee6234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPInstruction::canGenerateScalarForFirstLane ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if we can generate a scalar for the first lane only if needed.</p>

<p>Declaration at line 1246 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>

</div>
</div>

### doesGeneratePerAllLanes() {#a40451161c12289152dce77c548672a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPInstruction::doesGeneratePerAllLanes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> generates scalar values for all lanes.</p>


<p>Most VPInstructions generate a single value per part, either vector or scalar. <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe">VPReplicateRecipe</a> takes care of generating multiple (scalar) values per all lanes, stemming from an original ingredient. This method identifies the (rare) cases of VPInstructions that do so as well, w/o an underlying ingredient.</p>


<p>Declaration at line 1242 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>

</div>
</div>

### generate() {#a9dca33e36abd2e8a2a5c13319dea1edb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * VPInstruction::generate (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Utility methods serving <a href="#af2ef259f4a63359fe35f05b8b67a911b">execute()</a>: generates a single vector instance of the modeled instruction.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the generated value. . In some cases an existing value is returned rather than a generated one.</p></dd>
</dl>


<p>Declaration at line 1251 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>

</div>
</div>

### generatePerLane() {#a84d6e98aea5dd44dbb407aa96ead9772}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * VPInstruction::generatePerLane (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vplane">VPLane</a> &amp; Lane)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Utility methods serving <a href="#af2ef259f4a63359fe35f05b8b67a911b">execute()</a>: generates a scalar single instance of the modeled instruction for a given lane.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the scalar generated value for lane <span class="doxyComputerOutput">Lane</span>.</p></dd>
</dl>


<p>Declaration at line 1256 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>

</div>
</div>

### isFPMathOp() {#a7d4d7dbadb6ac45570a53173fa2af669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPInstruction::isFPMathOp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> is a floating point math operation, i.e.</p>


<p>has fast-math flags.</p>


<p>Declaration at line 1261 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 741 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Name {#aee3328b68143724f8e572a18009a400b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::VPInstruction::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An optional name that can be used for the generated IR instruction.</p>

<p>Definition at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### Opcode {#a738983407d18f0eef1a7435a1a216f6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpcodeTy llvm::VPInstruction::Opcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
