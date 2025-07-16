---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ppctargetlowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PPCTargetLowering` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::PPCTargetLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">Target/PowerPC/PPCISelLowering.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class defines information used to lower LLVM code to legal <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> operators that the target instruction selector can accept natively. <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6cddb4c330de0e51a5977de243a3ded">PPCTargetLowering</a> (const PPCTargetMachine &amp;TM, const PPCSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22040a96a01d1504b931efe54483505b">getTargetNodeName</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a22040a96a01d1504b931efe54483505b">getTargetNodeName()</a> - This method returns the name of a target specific DAG node. <a href="#a22040a96a01d1504b931efe54483505b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e60bf8e76e27b02eaccac58a62993f4">isSelectSupported</a> (SelectSupportKind Kind) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681">TargetLoweringBase::LegalizeTypeAction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02131f91a9d9a10d8aa800bb662d681">getPreferredVectorAction</a> (MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPreferredVectorAction - The code we generate when vector types are legalized by promoting the integer element type is often much worse than code we generate if we widen the type for applicable vector types. <a href="#ab02131f91a9d9a10d8aa800bb662d681">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d752ab70921f29e5c50f5fb75b8c0c">useSoftFloat</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44135eb0a79dfbd49c8235956342fcf7">hasSPE</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a010fe1720a71b30574703fec238e5cab">getScalarShiftAmountTy</a> (const DataLayout &amp;, EVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type to use for a scalar shift opcode, given the shifted amount type. <a href="#a010fe1720a71b30574703fec238e5cab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44cdcb4d20bf8b1fdcaa0f856fd1b312">isCheapToSpeculateCttz</a> (Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is cheap to speculate a call to intrinsic cttz. <a href="#a44cdcb4d20bf8b1fdcaa0f856fd1b312">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f8412bb8c563691c11c966432f0d0b">isCheapToSpeculateCtlz</a> (Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is cheap to speculate a call to intrinsic ctlz. <a href="#a21f8412bb8c563691c11c966432f0d0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa20f41b6ac6a667d8b4c16973fc7196e">shallExtractConstSplatVectorElementToStore</a> (Type *VectorTy, unsigned ElemSizeInBits, unsigned &amp;Index) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target shall perform extract vector element and store given that the vector is known to be splat of constant. <a href="#aa20f41b6ac6a667d8b4c16973fc7196e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a0cf06e062ec0b758d186411b440d90">isCtlzFast</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if ctlz instruction is fast. <a href="#a3a0cf06e062ec0b758d186411b440d90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa3913c1ef2c5af7a66a953752888f67">isEqualityCmpFoldedWithSignedCmp</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if instruction generated for equality comparison is folded with instruction generated for signed comparison. <a href="#aaa3913c1ef2c5af7a66a953752888f67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a551288909ccbfb41e573e1f31222a605">hasAndNotCompare</a> (SDValue) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target should transform: (X &amp; Y) == Y ---&gt; (~X &amp; Y) == 0 (X &amp; Y) != Y ---&gt; (~X &amp; Y) != 0. <a href="#a551288909ccbfb41e573e1f31222a605">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79450c12a2b980587b2b71d175b15f11">preferIncOfAddToSubOfNot</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These two forms are equivalent: sub y, (xor x, -1) add (add x, 1), y The variant with two add's is IR-canonical. <a href="#a79450c12a2b980587b2b71d175b15f11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91d45f6f637b1db940277d23e6d471db">convertSetCCLogicToBitwiseLogic</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> bitwise logic to make pairs of compares more efficient. <a href="#a91d45f6f637b1db940277d23e6d471db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fd734bb5606f5c8bd7bd6ef49683e1e">getNegatedExpression</a> (SDValue Op, SelectionDAG &amp;DAG, bool LegalOps, bool OptForSize, NegatibleCost &amp;Cost, unsigned Depth=0) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the newly negated expression if the cost is not expensive and set the cost in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a></span> to indicate that if it is cheaper or neutral to do the negation. <a href="#a2fd734bb5606f5c8bd7bd6ef49683e1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea8d3912f4a0d003d32577f1098a8b44">getSetCCResultType</a> (const DataLayout &amp;DL, LLVMContext &amp;Context, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSetCCResultType - Return the <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">ISD::SETCC</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a> <a href="#aea8d3912f4a0d003d32577f1098a8b44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f3484a5a16158cba22281a95a187e38">enableAggressiveFMAFusion</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if target always benefits from combining into FMA for a given value type. <a href="#a6f3484a5a16158cba22281a95a187e38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e08a461c58c82e0564d2cd25c6d9990">getPreIndexedAddressParts</a> (SDNode *N, SDValue &amp;Base, SDValue &amp;Offset, ISD::MemIndexedMode &amp;AM, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPreIndexedAddressParts - returns true by value, base pointer and offset pointer and addressing mode by reference if the node's address can be legally represented as pre-indexed load / store address. <a href="#a7e08a461c58c82e0564d2cd25c6d9990">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec3b0201c5cd00acf45cc4eb33708687">SelectAddressEVXRegReg</a> (SDValue N, SDValue &amp;Base, SDValue &amp;Index, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectAddressEVXRegReg - Given the specified addressed, check to see if it can be more efficiently represented as [r+imm]. <a href="#aec3b0201c5cd00acf45cc4eb33708687">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a521dc9b8649af234d8bf514085b9a640">SelectAddressRegReg</a> (SDValue N, SDValue &amp;Base, SDValue &amp;Index, SelectionDAG &amp;DAG, MaybeAlign EncodingAlignment=std::nullopt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectAddressRegReg - Given the specified addressed, check to see if it can be more efficiently represented as [r+imm]. <a href="#a521dc9b8649af234d8bf514085b9a640">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a312de8232fec3e0e128f4a34b7ddc55d">SelectAddressRegImm</a> (SDValue N, SDValue &amp;Disp, SDValue &amp;Base, SelectionDAG &amp;DAG, MaybeAlign EncodingAlignment) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectAddressRegImm - Returns true if the address N can be represented by a base register plus a signed 16-bit displacement [r+imm], and if it is not better represented as reg+reg. <a href="#a312de8232fec3e0e128f4a34b7ddc55d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaf95509430b29d867f49362e176027d">SelectAddressRegImm34</a> (SDValue N, SDValue &amp;Disp, SDValue &amp;Base, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to the 16-bit case but for instructions that take a 34-bit displacement field (prefixed loads/stores). <a href="#adaf95509430b29d867f49362e176027d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dc501f0601464ff8459b49b60b29140">SelectAddressRegRegOnly</a> (SDValue N, SDValue &amp;Base, SDValue &amp;Index, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectAddressRegRegOnly - Given the specified addressed, force it to be represented as an indexed [r+r] operation. <a href="#a5dc501f0601464ff8459b49b60b29140">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae882b4864ba6e86e417710e0b990b6d6">SelectAddressPCRel</a> (SDValue N, SDValue &amp;Base) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectAddressPCRel - Represent the specified address as pc relative to be represented as [pc+imm]. <a href="#ae882b4864ba6e86e417710e0b990b6d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sched/#ab8d854a5ce2331586bcc6830cca52f0f">Sched::Preference</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdf7d53d8e2b25e7b5c7981da1f11bcf">getSchedulingPreference</a> (SDNode *N) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some scheduler, e.g. <a href="#afdf7d53d8e2b25e7b5c7981da1f11bcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae03fd553a0f5e640324a7cdddbffb6b8">LowerOperation</a> (SDValue Op, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerOperation - Provide custom lowering hooks for some operations. <a href="#ae03fd553a0f5e640324a7cdddbffb6b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49eedef79b249eb098470debb9601eb7">ReplaceNodeResults</a> (SDNode *N, SmallVectorImpl&lt; SDValue &gt; &amp;Results, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReplaceNodeResults - Replace the results of node with an illegal result type with new values built out of custom code. <a href="#a49eedef79b249eb098470debb9601eb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a414d9dfa6f85f8ad371a510821713e61">expandVSXLoadForLE</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf2cd323dcdc4b2b0a4741c62b30d0ba">expandVSXStoreForLE</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4ccdcee4c7a2e0892715d0a8094b86e">PerformDAGCombine</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be invoked for all target nodes and for any target-independent nodes that the target has registered with invoke it for. <a href="#ab4ccdcee4c7a2e0892715d0a8094b86e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5583b4d2c0c7813f44df3fe6d42d20e1">BuildSDIVPow2</a> (SDNode *N, const APInt &amp;Divisor, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDNode * &gt; &amp;Created) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets may override this function to provide custom SDIV lowering for power-of-2 denominators. <a href="#a5583b4d2c0c7813f44df3fe6d42d20e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fae73b0e495a895c3ce49f127bf8ef7">getRegisterByName</a> (const char *RegName, LLT VT, const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the name passed in. <a href="#a6fae73b0e495a895c3ce49f127bf8ef7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5be8668f644eaefda25f6905908bd9f3">computeKnownBitsForTargetNode</a> (const SDValue Op, KnownBits &amp;Known, const APInt &amp;DemandedElts, const SelectionDAG &amp;DAG, unsigned Depth=0) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine which of the bits specified in Mask are known to be either zero or one and return them in the KnownZero/KnownOne bitsets. <a href="#a5be8668f644eaefda25f6905908bd9f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af601ca614bf9dbae090272eddc645f50">getPrefLoopAlignment</a> (MachineLoop *ML) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the preferred loop alignment. <a href="#af601ca614bf9dbae090272eddc645f50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35b2d5bd709014ea612750859328b7f3">shouldInsertFencesForAtomic</a> (const Instruction *I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether <a href="/web-llvm/docs/api/classes/llvm/atomicexpandpass">AtomicExpandPass</a> should automatically insert fences and reduce ordering for this atomic. <a href="#a35b2d5bd709014ea612750859328b7f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff4c3b2eec63855bda40615dece5853f">emitLeadingFence</a> (IRBuilderBase &amp;Builder, Instruction *Inst, AtomicOrdering Ord) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts in the IR a target-specific intrinsic specifying a fence. <a href="#aff4c3b2eec63855bda40615dece5853f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c68a6f0cdbdeb8a431791ad286109a0">emitTrailingFence</a> (IRBuilderBase &amp;Builder, Instruction *Inst, AtomicOrdering Ord) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff42b7a0251319665ac35b24de49a9f3">shouldInlineQuadwordAtomics</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLowering::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5047a95accb91898b9135182491d547c">shouldExpandAtomicRMWInIR</a> (AtomicRMWInst *AI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the IR-level AtomicExpand pass should expand the given AtomicRMW, if at all. <a href="#a5047a95accb91898b9135182491d547c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLowering::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf15eefe45c9e2c4a90a40a7a9a779f3">shouldExpandAtomicCmpXchgInIR</a> (AtomicCmpXchgInst *AI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the given atomic cmpxchg should be expanded by the IR-level AtomicExpand pass. <a href="#acf15eefe45c9e2c4a90a40a7a9a779f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e0d3c023e19c20fbf01b40d36aced80">emitMaskedAtomicRMWIntrinsic</a> (IRBuilderBase &amp;Builder, AtomicRMWInst *AI, Value *AlignedAddr, Value *Incr, Value *Mask, Value *ShiftAmt, AtomicOrdering Ord) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a masked atomicrmw using a target-specific intrinsic. <a href="#a0e0d3c023e19c20fbf01b40d36aced80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a683761fbb11ed0969edf7eee08b08bf3">emitMaskedAtomicCmpXchgIntrinsic</a> (IRBuilderBase &amp;Builder, AtomicCmpXchgInst *CI, Value *AlignedAddr, Value *CmpVal, Value *NewVal, Value *Mask, AtomicOrdering Ord) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a masked cmpxchg using a target-specific intrinsic. <a href="#a683761fbb11ed0969edf7eee08b08bf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10d6f09e62a827099ec8b54efb4c035d">EmitInstrWithCustomInserter</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'usesCustomInserter' flag. <a href="#a10d6f09e62a827099ec8b54efb4c035d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a541b354a6386df6d03fcdc656d7d9db7">EmitAtomicBinary</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB, unsigned AtomicSize, unsigned BinOpcode, unsigned CmpOpcode=0, unsigned CmpPred=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e99e64e510ba34954d7fe85b1e30119">EmitPartwordAtomicBinary</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB, bool is8bit, unsigned Opcode, unsigned CmpOpcode=0, unsigned CmpPred=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a212384cdd746eaffedb7edc7a16a1cef">emitEHSjLjSetJmp</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056f22c11083630d8bcc82299cb783af">emitEHSjLjLongJmp</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cb46b1ded73af4c2924bd2d1d8db334">emitProbedAlloca</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20e0ba2c46bef474e31cf8c2f9322db0">hasInlineStackProbe</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4e23bdb97cbb1eebd9ddd6606a1006f">getStackProbeSize</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116">ConstraintType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97e1f4e021dcba5a7795f823781e04df">getConstraintType</a> (StringRef Constraint) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getConstraintType - Given a constraint, return the type of constraint it is for this target. <a href="#a97e1f4e021dcba5a7795f823781e04df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abc">ConstraintWeight</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a685bfe474ca920468f17fc82cf4664e6">getSingleConstraintMatchWeight</a> (AsmOperandInfo &amp;info, const char *constraint) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine constraint string and operand type and determine a weight value. <a href="#a685bfe474ca920468f17fc82cf4664e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add923d3128dce4cad95ce5ad642f6946">getRegForInlineAsmConstraint</a> (const TargetRegisterInfo *TRI, StringRef Constraint, MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a physical register constraint (e.g. <a href="#add923d3128dce4cad95ce5ad642f6946">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b3288a078ec78d279a486db1946b31">getByValTypeAlignment</a> (Type *Ty, const DataLayout &amp;DL) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getByValTypeAlignment - Return the desired alignment for ByVal aggregate function arguments in the caller parameter area. <a href="#a51b3288a078ec78d279a486db1946b31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46ae06ee635d7e06d852c36093a4d20e">LowerAsmOperandForConstraint</a> (SDValue Op, StringRef Constraint, std::vector&lt; SDValue &gt; &amp;Ops, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerAsmOperandForConstraint - Lower the specified operand into the Ops vector. <a href="#a46ae06ee635d7e06d852c36093a4d20e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a300242af50ce9daeda4a2e002df27">getInlineAsmMemConstraint</a> (StringRef ConstraintCode) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac05ba7b36777c445fb76f15011abf487">CollectTargetIntrinsicOperands</a> (const CallInst &amp;I, SmallVectorImpl&lt; SDValue &gt; &amp;Ops, SelectionDAG &amp;DAG) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7747bd26b2eea5f7c32012e5dcdbd61a">isLegalAddressingMode</a> (const DataLayout &amp;DL, const AddrMode &amp;AM, Type *Ty, unsigned AS, Instruction *I=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isLegalAddressingMode - Return true if the addressing mode represented by AM is legal for this target, for a load/store of the specified type. <a href="#a7747bd26b2eea5f7c32012e5dcdbd61a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeda0b757f19cd0c67deb589e0ce0cdb9">isLegalICmpImmediate</a> (int64_t Imm) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isLegalICmpImmediate - Return true if the specified immediate is legal icmp immediate, that is the target has icmp instructions which can compare a register against the immediate without having to materialize the immediate into a register. <a href="#aeda0b757f19cd0c67deb589e0ce0cdb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff5e1ccebed969088d63237834e19817">isLegalAddImmediate</a> (int64_t Imm) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isLegalAddImmediate - Return true if the specified immediate is legal add immediate, that is the target has add instructions which can add a register and the immediate without having to materialize the immediate into a register. <a href="#aff5e1ccebed969088d63237834e19817">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c9601934baa227ce802de96110b47bc">isTruncateFree</a> (Type *Ty1, Type *Ty2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isTruncateFree - Return true if it's free to truncate a value of type Ty1 to type Ty2. <a href="#a0c9601934baa227ce802de96110b47bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af075f198cd750d859857bb7b87544931">isTruncateFree</a> (EVT VT1, EVT VT2) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d0ce4ee513f57d110efb8247ea59afb">isZExtFree</a> (SDValue Val, EVT VT2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if zero-extending the specific node Val to type VT2 is free (either because it's implicitly zero-extended such as <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> ldrb / ldrh or because it's folded such as <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> zero-extending loads). <a href="#a2d0ce4ee513f57d110efb8247ea59afb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19198578d08502db0acb9cd75ccbcae0">isFPExtFree</a> (EVT DestVT, EVT SrcVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if an fpext operation is free (for instance, because single-precision floating-point numbers are implicitly extended to double-precision). <a href="#a19198578d08502db0acb9cd75ccbcae0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a61d6d5c09da51b4448488e38bd90b5">shouldConvertConstantLoadToIntImm</a> (const APInt &amp;Imm, Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it is beneficial to convert a load of a constant to just the constant itself. <a href="#a7a61d6d5c09da51b4448488e38bd90b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bce339379d3a541ec57b178e6deeca0">convertSelectOfConstantsToMath</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a select of constants (select Cond, C1, C2) should be transformed into simple math ops with the condition value. <a href="#a8bce339379d3a541ec57b178e6deeca0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a700728edd4a6a3ebe5797715cb535874">decomposeMulByConstant</a> (LLVMContext &amp;Context, EVT VT, SDValue C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to transform an integer multiplication-by-constant into simpler operations like shifts and adds. <a href="#a700728edd4a6a3ebe5797715cb535874">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6ccf4330a7bedc48475a8ec562fe5ed">isDesirableToTransformToIntegerOp</a> (unsigned Opc, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable for dag combiner to transform a floating point op of specified opcode to a equivalent op of an integer type. <a href="#aa6ccf4330a7bedc48475a8ec562fe5ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2168b4e8c9abe5efab1acc532d50feb">isAccessedAsGotIndirect</a> (SDValue N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26daafd86d9f5f03a8963dcc9e9b5804">isOffsetFoldingLegal</a> (const GlobalAddressSDNode *GA) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if folding a constant offset with the given GlobalAddress is legal. <a href="#a26daafd86d9f5f03a8963dcc9e9b5804">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f04233ae02eabefa03b17d72ff73601">getTgtMemIntrinsic</a> (IntrinsicInfo &amp;Info, const CallInst &amp;I, MachineFunction &amp;MF, unsigned Intrinsic) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an intrinsic, checks if on the target the intrinsic will need to map to a MemIntrinsicNode (touches memory). <a href="#a3f04233ae02eabefa03b17d72ff73601">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae7a66849fd8b672b9c9f6897d6326a1">getOptimalMemOpType</a> (const MemOp &amp;Op, const AttributeList &amp;FuncAttributes) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>It returns EVT::Other if the type should be determined using generic target-independent logic. <a href="#aae7a66849fd8b672b9c9f6897d6326a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5d9213c39b2fc64eaed3639539e8f65">allowsMisalignedMemoryAccesses</a> (EVT VT, unsigned AddrSpace, Align Alignment=Align(1), MachineMemOperand::Flags Flags=MachineMemOperand::MONone, unsigned *Fast=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is unaligned memory access allowed for the given type, and is it fast relative to software emulation. <a href="#ad5d9213c39b2fc64eaed3639539e8f65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad357707a4ab97832b2f9ad24490b4376">isFMAFasterThanFMulAndFAdd</a> (const MachineFunction &amp;MF, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isFMAFasterThanFMulAndFAdd - Return true if an FMA operation is faster than a pair of fmul and fadd instructions. <a href="#ad357707a4ab97832b2f9ad24490b4376">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ae7a06e074fcc6e88720bdaeeb1460">isFMAFasterThanFMulAndFAdd</a> (const Function &amp;F, Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IR version. <a href="#aa2ae7a06e074fcc6e88720bdaeeb1460">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a857dba88c2223d0a509b5d390f7144f0">isProfitableToHoist</a> (Instruction *I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isProfitableToHoist - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if it is profitable to hoist instruction <span class="doxyComputerOutput">I</span> to its dominator block. <a href="#a857dba88c2223d0a509b5d390f7144f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b947e723a15a56090d5a4d0f030f44f">getScratchRegisters</a> (CallingConv::ID CC) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a 0 terminated array of registers that can be safely used as scratch registers. <a href="#a7b947e723a15a56090d5a4d0f030f44f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6a695102bd6d1036b8c1e5f5dcdf815">shouldExpandBuildVectorWithShuffles</a> (EVT VT, unsigned DefinedValues) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad343d343b05ea16280e147de626fa46d">shouldKeepZExtForFP16Conv</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this target require the clearing of high-order bits in a register passed to the fp16 to fp conversion library function. <a href="#ad343d343b05ea16280e147de626fa46d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb9a1efd115f87d617c4bd692181df4c">createFastISel</a> (FunctionLoweringInfo &amp;FuncInfo, const TargetLibraryInfo *LibInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createFastISel - This method returns a target-specific <a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> object, or null if the target does not support "fast" instruction selection. <a href="#afb9a1efd115f87d617c4bd692181df4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf9bca8a4d7246c83bbfa566a51165e">functionArgumentNeedsConsecutiveRegisters</a> (Type *Ty, CallingConv::ID CallConv, bool isVarArg, const DataLayout &amp;DL) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if an argument of type Ty needs to be passed in a contiguous block of registers in calling convention CallConv. <a href="#a3bf9bca8a4d7246c83bbfa566a51165e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae00d7eb852ec09ae630c49f5b9454aff">getExceptionPointerRegister</a> (const Constant *PersonalityFn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register, this returns the register that receives the exception address on entry to an EH pad. <a href="#ae00d7eb852ec09ae630c49f5b9454aff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade9eaaa949a3aeb305931cbde5cae365">getExceptionSelectorRegister</a> (const Constant *PersonalityFn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register, this returns the register that receives the exception typeid on entry to a landing pad. <a href="#ade9eaaa949a3aeb305931cbde5cae365">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad022667ae203c4c91fca45e3c9f568d9">useLoadStackGuardNode</a> (const Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override to support customized stack guard loading. <a href="#ad022667ae203c4c91fca45e3c9f568d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6651f5dc988cb00064896052b5f7a42d">insertSSPDeclarations</a> (Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts necessary declarations for SSP (stack protection) purpose. <a href="#a6651f5dc988cb00064896052b5f7a42d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56627ff3e9d2a5c7fdde625fd55fb97">getSDagStackGuard</a> (const Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the variable that's previously inserted by insertSSPDeclarations, if any, otherwise return nullptr. <a href="#ae56627ff3e9d2a5c7fdde625fd55fb97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90186243528cfcd7b02837f130da5de2">isFPImmLegal</a> (const APFloat &amp;Imm, EVT VT, bool ForCodeSize) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target can instruction select the specified FP immediate natively. <a href="#a90186243528cfcd7b02837f130da5de2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76ee5e788bf1969bd98f670b3471a12b">getJumpTableEncoding</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the entry encoding for a jump table in the current function. <a href="#a76ee5e788bf1969bd98f670b3471a12b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf6c939e7121ecf6c9339ef40eb8bbde">isJumpTableRelative</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64ca42c56843a34b11476e34d5941628">getPICJumpTableRelocBase</a> (SDValue Table, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns relocation base for the given PIC jumptable. <a href="#a64ca42c56843a34b11476e34d5941628">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8d81b42a228a0a2e89454cf7a3d017">getPICJumpTableRelocBaseExpr</a> (const MachineFunction *MF, unsigned JTI, MCContext &amp;Ctx) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This returns the relocation base for the given PIC jumptable, the same as getPICJumpTableRelocBase, but as an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a>. <a href="#a9e8d81b42a228a0a2e89454cf7a3d017">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcd">PPC::AddrMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae058898e63ec72af7e4ed9b50ac8fbec">SelectOptimalAddrMode</a> (const SDNode *Parent, SDValue N, SDValue &amp;Disp, SDValue &amp;Base, SelectionDAG &amp;DAG, MaybeAlign Align) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectOptimalAddrMode - Based on a node N and it's Parent (a <a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a>), compute the address flags of the node, get the optimal address mode based on the flags, and set the Base and Disp based on the address mode. <a href="#ae058898e63ec72af7e4ed9b50ac8fbec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcd">PPC::AddrMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ee5344b14a547e1ede7370b62402ce">SelectForceXFormMode</a> (SDValue N, SDValue &amp;Disp, SDValue &amp;Base, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectForceXFormMode - Given the specified address, force it to be represented as an indexed [r+r] operation (an XForm instruction). <a href="#a19ee5344b14a547e1ede7370b62402ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a468544509fb441c63f6f75f53470cf30">splitValueIntoRegisterParts</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Val, SDValue *Parts, unsigned NumParts, MVT PartVT, std::optional&lt; CallingConv::ID &gt; CC) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-specific splitting of values into parts that fit a register storing a legal type. <a href="#a468544509fb441c63f6f75f53470cf30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0788f6af8ef22d48e3406bfd67a8d384">ccAssignFnForCall</a> (CallingConv::ID CC, bool Return, bool IsVarArg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a263f69437421410a39c26e0be576f028">supportsTailCallFor</a> (const CallBase *CB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f64e1a96749ea3286aec43bacda3117">initializeAddrModeMap</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the map that relates the different addressing modes of the load and store instructions to a set of flags. <a href="#a5f64e1a96749ea3286aec43bacda3117">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3860fc984ea7a7eb779e6c13368dceeb">canReuseLoadAddress</a> (SDValue Op, EVT MemVT, ReuseLoadInfo &amp;RLI, SelectionDAG &amp;DAG, ISD::LoadExtType ET=ISD::NON_EXTLOAD) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8036c6e2ca253282df2cf377c25b337c">spliceIntoChain</a> (SDValue ResChain, SDValue NewResChain, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e648440bd92514a5ac4384634c2adfd">LowerFP_TO_INTForReuse</a> (SDValue Op, ReuseLoadInfo &amp;RLI, SelectionDAG &amp;DAG, const SDLoc &amp;dl) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abefbc414fca41dcd74283d8490e69a25">LowerFP_TO_INTDirectMove</a> (SDValue Op, SelectionDAG &amp;DAG, const SDLoc &amp;dl) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Custom lowers floating point to integer conversions to use the direct move instructions available in ISA 2.07 to avoid the need for load/store combinations. <a href="#abefbc414fca41dcd74283d8490e69a25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a753e82c6e5748cadc5aef989ff3e9179">directMoveIsProfitable</a> (const SDValue &amp;Op) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze profitability of direct move prefer float load to int load plus direct move when there is no integer use of int load. <a href="#a753e82c6e5748cadc5aef989ff3e9179">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cfaeaf09ec86ab3d287cc15ba77a93c">LowerINT_TO_FPDirectMove</a> (SDValue Op, SelectionDAG &amp;DAG, const SDLoc &amp;dl) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Custom lowers integer to floating point conversions to use the direct move instructions available in ISA 2.07 to avoid the need for load/store combinations. <a href="#a3cfaeaf09ec86ab3d287cc15ba77a93c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7dd383d2eb5c031b779aea878a3d143">LowerINT_TO_FPVector</a> (SDValue Op, SelectionDAG &amp;DAG, const SDLoc &amp;dl) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f6bdc591f283e0a285d693314e08ee">LowerTRUNCATEVector</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d465c41010dd45b998f2439b5c5579">getFramePointerFrameIndex</a> (SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c8fe9d85e197c06d0551181e23899fd">getReturnAddrFrameIndex</a> (SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af14ac8041e5521a60193cd0c9e9a9cc9">IsEligibleForTailCallOptimization</a> (const GlobalValue *CalleeGV, CallingConv::ID CalleeCC, CallingConv::ID CallerCC, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsEligibleForTailCallOptimization - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the call is eligible for tail call optimization. <a href="#af14ac8041e5521a60193cd0c9e9a9cc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeedff75481dc6ea67cf6f1ec34ff342d">IsEligibleForTailCallOptimization_64SVR4</a> (const GlobalValue *CalleeGV, CallingConv::ID CalleeCC, CallingConv::ID CallerCC, const CallBase *CB, bool isVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const Function *CallerFunc, bool isCalleeExternalSymbol) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4fe7688b9dabb9b7bf17a03c7c28765">isEligibleForTCO</a> (const GlobalValue *CalleeGV, CallingConv::ID CalleeCC, CallingConv::ID CallerCC, const CallBase *CB, bool isVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const Function *CallerFunc, bool isCalleeExternalSymbol) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a569f1e97bf1305065e38ed8cc2e7e0d1">EmitTailCallLoadFPAndRetAddr</a> (SelectionDAG &amp;DAG, int SPDiff, SDValue Chain, SDValue &amp;LROpOut, SDValue &amp;FPOpOut, const SDLoc &amp;dl) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitTCFPAndRetAddrLoad - Emit load from frame pointer and return address stack slot. <a href="#a569f1e97bf1305065e38ed8cc2e7e0d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a67e2a6e6917feccba94dfc1698f8d">getTOCEntry</a> (SelectionDAG &amp;DAG, const SDLoc &amp;dl, SDValue GA) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e08926eca5d2933a60c74d1e243e24">LowerRETURNADDR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc62b841a88b15eaf6427d6a8688a494">LowerFRAMEADDR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88bb955bc687311870dd2b0f464a64ba">LowerConstantPool</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ebdd8b520a58b37999779befa1ec38f">LowerBlockAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae048923ceef9a1ce3cbbf20025c69f8">LowerGlobalTLSAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4acaca593f12a3166b84688c98c6a4de">LowerGlobalTLSAddressAIX</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab55608d59fdd6d56deab4a09b1cd2b07">LowerGlobalTLSAddressLinux</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac7c0116c861da06b3fb710642d280b3">LowerGlobalAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e3e75bfbcd67108c7b3a3782d3338b3">LowerJumpTable</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1dc4e6d14a38bf29c5ee48571780521">LowerUaddo</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef5cbd88afc22f441db0ce3aad6d597">LowerSETCC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1980328b3aff55b9af0ca30a9343864">LowerSSUBO</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab9dfb9ce0e97af376da9e65efad638e">LowerINIT_TRAMPOLINE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d110c1944430d51ea84db10039a8db7">LowerADJUST_TRAMPOLINE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192174630975b9c97101323257e3f2b9">LowerINLINEASM</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf516b68c8bb624b6000579e33957d0">LowerVASTART</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b574774c5d768e63533fc1296eefb97">LowerVAARG</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88438bd1ec337381ff86d3f32c701a47">LowerVACOPY</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84910fd0d9b7f0153a099711c9739c9e">LowerSTACKRESTORE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af544d38a73650dc0589656e39ff5e068">LowerGET_DYNAMIC_AREA_OFFSET</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a037a0ed3bc606a66a4eb9b6cade8c13b">LowerDYNAMIC_STACKALLOC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa418e55a51bb59f17e4a034ed03dde45">LowerEH_DWARF_CFA</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e1e1e1a04c5ee733f480aac631a07dc">LowerLOAD</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a7be9fbf4f1de22c2017e0cadeb4f55">LowerSTORE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a178df209b8c9568a179e308fa55321">LowerTRUNCATE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1816c47b4ddc3f4c467200ab9531b115">LowerSELECT_CC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerSELECT_CC - Lower floating point select_cc's into fsel instruction when possible. <a href="#a1816c47b4ddc3f4c467200ab9531b115">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f832eb5f10c0477b8e2c885b9c825ff">LowerFP_TO_INT</a> (SDValue Op, SelectionDAG &amp;DAG, const SDLoc &amp;dl) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5edeb98a4cb2737193389f8e746d8fa5">LowerINT_TO_FP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a037b03c0afc2af68af766204317122b8">LowerGET_ROUNDING</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11b9f143019b4034fa350f1eb30fbb1d">LowerSET_ROUNDING</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f1e0140983efb7b1656371533193c61">LowerSHL_PARTS</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fac7e4aa7c6abd6c3e5691bcaa5715e">LowerSRL_PARTS</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9e29594a62f5e0e9c878932ef9fb3d">LowerSRA_PARTS</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b9149f2f68926b2a5dd6a6afea44419">LowerFunnelShift</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fdd7a6b893778f85733222568a4992e">LowerBUILD_VECTOR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4b256bde82d233d1a18729d0be1edd5">LowerVECTOR_SHUFFLE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerVECTOR_SHUFFLE - Return the code we lower for VECTOR_SHUFFLE. <a href="#ac4b256bde82d233d1a18729d0be1edd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af74e485a4d4f42d7faa05ecaa3b0c3e8">LowerVPERM</a> (SDValue Op, SelectionDAG &amp;DAG, ArrayRef&lt; int &gt; PermMask, EVT VT, SDValue V1, SDValue V2) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b651ead7a2e58b325e3ab5e5745ee18">LowerINSERT_VECTOR_ELT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1c8de626be5ad29673ccd189469abd">LowerINTRINSIC_WO_CHAIN</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerINTRINSIC_WO_CHAIN - If this is an intrinsic that we want to custom lower, do it, otherwise return null. <a href="#a4a1c8de626be5ad29673ccd189469abd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a28469d8a96cb472e876bfc93725523">LowerINTRINSIC_VOID</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad348165aa5000ade156b95f4a800c92f">LowerBSWAP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b5524d63dae6e6e027826c9f649cf93">LowerATOMIC_CMP_SWAP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb4315b614e26656283753bbb1f05d8e">LowerIS_FPCLASS</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea6f9257cb75708f7c6bb48d11c685d6">lowerToLibCall</a> (const char *LibCallName, SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36df21ff3fcf300508a31598799c4428">lowerLibCallBasedOnType</a> (const char *LibCallFloatName, const char *LibCallDoubleName, SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30eceac5c1328b731fd5c34c99f76a08">isLowringToMASSFiniteSafe</a> (SDValue Op) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d2513e0b44ff4fdec30bf4f2b522fe1">isLowringToMASSSafe</a> (SDValue Op) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e817fa870a94affc7a96137caa4f83">isScalarMASSConversionEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a780987c4514625fbc5dd81221e7f1759">lowerLibCallBase</a> (const char *LibCallDoubleName, const char *LibCallFloatName, const char *LibCallDoubleNameFinite, const char *LibCallFloatNameFinite, SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2321e667b3b60da50d51b5a3938b861f">lowerPow</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab649c3363d8d0c6d9529b2002cb9f0b3">lowerSin</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a644000f1c44ef006422897513c65808a">lowerCos</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15e99965e35ab4ce7c54c4c39b42c96e">lowerLog</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9374f7ab647eb66051ec2cdb75446e9e">lowerLog10</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a63f13d27659d6cd192644cca16ab0e">lowerExp</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63f977669008ea781e098f5d9165d15f">LowerATOMIC_LOAD_STORE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe8e95da4d74f8d25e24fa4b40193f0b">LowerSCALAR_TO_VECTOR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea01ec63e5e633eb69ab0f1ed7bd8763">LowerMUL</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6fac18b3c7fd99170ad51b0f8f36f55">LowerFP_EXTEND</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36d24002edb234bc8e1815df30623a1b">LowerFP_ROUND</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a539208ae316f3faff5dcfe1e351abfb5">LowerROTL</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerROTL - Custom lowering for <a href="/web-llvm/docs/api/files/lib/lib/support/siphash-cpp/#addd42b95ef425979d1d0dca095dec800">ROTL(v1i128)</a> to vector_shuffle(v16i8). <a href="#a539208ae316f3faff5dcfe1e351abfb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c03e1007e384aefa7ad1055fe69cc1d">LowerVectorLoad</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04f4c9a7a840484c4272cab00d67a341">LowerVectorStore</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a890bd06b3a8f766f4ae0f9702753c09a">LowerCallResult</a> (SDValue Chain, SDValue InGlue, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb6bdcd0336f1d8f2c191803848cead4">FinishCall</a> (CallFlags CFlags, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVector&lt; std::pair&lt; unsigned, SDValue &gt;, 8 &gt; &amp;RegsToPass, SDValue InGlue, SDValue Chain, SDValue CallSeqStart, SDValue &amp;Callee, int SPDiff, unsigned NumBytes, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, SmallVectorImpl&lt; SDValue &gt; &amp;InVals, const CallBase *CB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53d663203ffeeaeca443ea37c8556aac">LowerFormalArguments</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower the incoming (formal) arguments, described by the Ins array, into the specified DAG. <a href="#a53d663203ffeeaeca443ea37c8556aac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdedec4cde0784077c92ef393adfbac2">LowerCall</a> (TargetLowering::CallLoweringInfo &amp;CLI, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower calls into the specified DAG. <a href="#afdedec4cde0784077c92ef393adfbac2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae89d61c3eda49c3dae51dc844aadf8fb">CanLowerReturn</a> (CallingConv::ID CallConv, MachineFunction &amp;MF, bool isVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, LLVMContext &amp;Context, const Type *RetTy) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook should be implemented to check whether the return values described by the Outs array can fit into the return registers. <a href="#ae89d61c3eda49c3dae51dc844aadf8fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2830601fd6e68cad81898be5ab97f196">LowerReturn</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; SDValue &gt; &amp;OutVals, const SDLoc &amp;dl, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower outgoing return values, described by the Outs array, into the specified DAG. <a href="#a2830601fd6e68cad81898be5ab97f196">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8175acc5d3a39b4738306fc7f9a6a25">extendArgForPPC64</a> (ISD::ArgFlagsTy Flags, EVT ObjectVT, SelectionDAG &amp;DAG, SDValue ArgVal, const SDLoc &amp;dl) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a915a0e13ef51c9859137ab9b1b3c88fe">LowerFormalArguments_AIX</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13703af0860a44f76b0a216890d2d8ed">LowerFormalArguments_64SVR4</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9337cd4048a4f818317e21e8ba5cf61">LowerFormalArguments_32SVR4</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0c63850ef1340ffded3e8c82513eabe">createMemcpyOutsideCallSeq</a> (SDValue Arg, SDValue PtrOff, SDValue CallSeqStart, ISD::ArgFlagsTy Flags, SelectionDAG &amp;DAG, const SDLoc &amp;dl) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76130c3e027890ec153a61bf81464546">LowerCall_64SVR4</a> (SDValue Chain, SDValue Callee, CallFlags CFlags, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; SDValue &gt; &amp;OutVals, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals, const CallBase *CB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e75d9362ba1c7f9d5cd048b587d4da8">LowerCall_32SVR4</a> (SDValue Chain, SDValue Callee, CallFlags CFlags, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; SDValue &gt; &amp;OutVals, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals, const CallBase *CB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5584ac92f647260591392f6e184733d7">LowerCall_AIX</a> (SDValue Chain, SDValue Callee, CallFlags CFlags, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; SDValue &gt; &amp;OutVals, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals, const CallBase *CB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae830ce15fa10f5c31dcd4c3092e69683">lowerEH_SJLJ_SETJMP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9cad51a503b553ae2e96458b3222c8">lowerEH_SJLJ_LONGJMP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac61461057c08b51c6cfaaec5a9b9e58">LowerBITCAST</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd0b756aa4efd040b574f090aaf219c4">DAGCombineExtBoolTrunc</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed869d56410d9b43eed9b16bc87b0fb4">DAGCombineBuildVector</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa00d8aff98a114fb5a053af40a1c1395">DAGCombineTruncBoolExt</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f9c5e379a2fdde72cc1b8d0072f82a">combineStoreFPToInt</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11f8b76cc3e0d5ddd423397a12a80fef">combineFPToIntToFP</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af26205c2c3487955cbe10bb9da639840">combineSHL</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d39a97103d96d16e49a27afc9da970a">combineSRA</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d92d6311cfe8b9c9e006f6b75f94a40">combineSRL</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55edac70ea7b252b1a2961862df5b9ce">combineMUL</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4484a2395677aedc94a5b65a720bb59e">combineADD</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f0901d5699d505cc3a3fdb15d73648e">combineFMALike</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad18f9407bcd34f0d9e0b0d6dd34a222a">combineTRUNCATE</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af680661800ce4554163f5de924d96692">combineSetCC</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f21596fd46355f492f9260cc97324d5">combineVectorShuffle</a> (ShuffleVectorSDNode *SVN, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58e0104c80dc81500a6206c84cac679f">combineVReverseMemOP</a> (ShuffleVectorSDNode *SVN, LSBaseSDNode *LSBase, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a8370967a56fb937bce19a06e41b62b">ConvertSETCCToSubtract</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ConvertSETCCToSubtract - looks at SETCC that compares ints. <a href="#a7a8370967a56fb937bce19a06e41b62b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbd0ca4c3f0a8a1a125b1eb14d917a6e">getSqrtEstimate</a> (SDValue Operand, SelectionDAG &amp;DAG, int Enabled, int &amp;RefinementSteps, bool &amp;UseOneConstNR, bool Reciprocal) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hooks for building estimates in place of slower divisions and square roots. <a href="#afbd0ca4c3f0a8a1a125b1eb14d917a6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af49324adfc981ac39b7de0b06ee7add0">getRecipEstimate</a> (SDValue Operand, SelectionDAG &amp;DAG, int Enabled, int &amp;RefinementSteps) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reciprocal estimate value for the input operand. <a href="#af49324adfc981ac39b7de0b06ee7add0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a774530d839b593968b499c96406ed88c">getSqrtInputTest</a> (SDValue Operand, SelectionDAG &amp;DAG, const DenormalMode &amp;Mode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a target-dependent comparison result if the input operand is suitable for use with a square root estimate calculation. <a href="#a774530d839b593968b499c96406ed88c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf5dcffda94b7c1a3c26d66ec38583c4">getSqrtResultForDenormInput</a> (SDValue Operand, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a target-dependent result if the input operand is not suitable for use with a square root estimate calculation. <a href="#adf5dcffda94b7c1a3c26d66ec38583c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26513e60cc41c9d2bc638a1eb9b64dcf">combineRepeatedFPDivisors</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate whether this target prefers to combine FDIVs with the same divisor. <a href="#a26513e60cc41c9d2bc638a1eb9b64dcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66527d30bb7389dd1319f0f13af9209d">combineElementTruncationToVectorTruncation</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reduces the number of fp-to-int conversion when building a vector. <a href="#a66527d30bb7389dd1319f0f13af9209d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35094c6016f824fe6c3a054404584d6f">lowerToVINSERTH</a> (ShuffleVectorSDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>lowerToVINSERTH - Return the <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if this VECTOR_SHUFFLE can be handled by the VINSERTH instruction introduced in ISA 3.0. <a href="#a35094c6016f824fe6c3a054404584d6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33c862e2cf268da4301451444f1e57a">lowerToVINSERTB</a> (ShuffleVectorSDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>lowerToVINSERTB - Return the <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if this VECTOR_SHUFFLE can be handled by the VINSERTB instruction introduced in ISA 3.0. <a href="#ab33c862e2cf268da4301451444f1e57a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a198c03e70cbea965e47222809c97f37a">lowerToXXSPLTI32DX</a> (ShuffleVectorSDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>lowerToXXSPLTI32DX - Return the <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if this VECTOR_SHUFFLE can be handled by the XXSPLTI32DX instruction introduced in ISA 3.1. <a href="#a198c03e70cbea965e47222809c97f37a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f665f37afe6472a71d5112f492387f2">mayBeEmittedAsTailCall</a> (const CallInst *CI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target may be able emit the call instruction as a tail call. <a href="#a5f665f37afe6472a71d5112f492387f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec92a6313081c12af66880a21d6c5a0f">isMaskAndCmp0FoldingBeneficial</a> (const Instruction &amp;AndI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if the target supports combining a chain like: <a href="#aec92a6313081c12af66880a21d6c5a0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcd">PPC::AddrMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18c60d8f49b0dc18b82458fa122e08ac">getAddrModeForFlags</a> (unsigned Flags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAddrModeForFlags - Based on the set of address flags, select the most optimal instruction format to match by. <a href="#a18c60d8f49b0dc18b82458fa122e08ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f8c71acf985e5bf1e2f519888f4f20a">computeMOFlags</a> (const SDNode *Parent, SDValue N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>computeMOFlags - Given a node N and it's Parent (a <a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a>), compute the address flags of the load/store instruction that is to be matched. <a href="#a9f8c71acf985e5bf1e2f519888f4f20a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5875f104559ccf841bd5ed72e85cd6af">Subtarget</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcd">PPC::AddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 16 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a013160d7e477c636f98070bd83b1e9">AddrModesMap</a></td>
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


<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCTargetLowering() {#ac6cddb4c330de0e51a5977de243a3ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCTargetLowering::PPCTargetLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine">PPCTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; STI)</td>
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



<p>Declaration at line 757 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af798622367e75c5536666dbfec5d5ea3">llvm::ISD::ABDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff129f5ab4fbc8279e7aaacb45f840b1">llvm::ISD::ABDU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a20084f62caecb0db80ad71bdabda73c2">llvm::ISD::ADDC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad116e32876f2275acf60ffb1651c9256">llvm::ISD::ADDE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab8c490e0623b6a0e2c12c12e0d924abe">llvm::TargetLoweringBase::AddPromotedToType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7c45a718f16057459d95d09d42ec6902">llvm::TargetLoweringBase::addRegisterClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af7bfad446dfd85837fe7ff904ebb1aff">llvm::ISD::ADJUST_TRAMPOLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a0afb938ef27c63f791a9e76d2c44e057">ANDIGlueBug</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9c91befeca2a25c8050d4c3dff8b6d67">llvm::ISD::ATOMIC_CMP_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c47226f266248f4b8c155b83601b109">llvm::ISD::ATOMIC_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1db943abc1bf78a911daeb7b03d81de8">llvm::ISD::ATOMIC_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeea401cc0b7fa5aa6f4d3a0612140e1d">llvm::ISD::BITREVERSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb">llvm::ISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716d19ebad1927a2e8dd5fe3f951f882">llvm::ISD::BR_JT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a41bd84b853e2c03fb1af1f4ca9ebdcaf">llvm::ISD::BUILD_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6df03220bbe2ea3cfb905f36fb26822c">llvm::TargetLoweringBase::computeRegisterProperties</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c">llvm::ISD::CTLZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a991d07d163bd4d9984cf1ef36e92c214">llvm::ISD::CTPOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6da41a113af0909470baea7486b3386b">llvm::ISD::CTTZ</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa3441acf8576e4bbf48e9bd73ca3c0d8c">llvm::TargetLoweringBase::Custom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a56adb1ba4082b00854c8401847ade1a9">llvm::PPC::DIR_970</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34ab81d0aba13bef5a963bb14709390283e">llvm::PPC::DIR_A2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34aa3892c789487c6e4d64043ae996717ee">llvm::PPC::DIR_E500</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a00d4f7d7f8d110db90749f417fceff3a">llvm::PPC::DIR_E500mc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34ac4e6bb06de05f2620850b3fc53a0433e">llvm::PPC::DIR_E5500</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a1a5dee2be7c154497739282b30ab123c">llvm::PPC::DIR_PWR10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34af6a785f2b13ce7870e8e4e6b9653f32f">llvm::PPC::DIR_PWR11</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a1a9618f9addb07ce52555fa524ccf39d">llvm::PPC::DIR_PWR4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a690b5c342106c270b005123adec2d7e6">llvm::PPC::DIR_PWR5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a40aa4eed5523516b6f4be5d29307b5cc">llvm::PPC::DIR_PWR5X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34aa2b626cb4809ee8a3b3da9d475eabe05">llvm::PPC::DIR_PWR6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a664d0abca2c75f8a6f8ce2dcc21cd676">llvm::PPC::DIR_PWR6X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a0c8a5dd168df904e8c29520a47502a61">llvm::PPC::DIR_PWR7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34aa3de856d909c5b0166919bf6e4bd1a3d">llvm::PPC::DIR_PWR8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a0a03bfd83c00f4d1edab975b7bfe7f36">llvm::PPC::DIR_PWR9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34ac1fc2f6d654da4e5a6a601e19d423846">llvm::PPC::DIR_PWR_FUTURE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af0201c87e6816e6372f163c9ee04a4ed">DisableP10StoreForward</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa71ac22470bf853868fe6b39a25bac72">llvm::ISD::DYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abad932e63381a4671b5db19a3404c82e">llvm::ISD::EH_DWARF_CFA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a122a450e069003dc86859ef47ab6e278">llvm::ISD::EH_SJLJ_LONGJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae5a57fe9fd413df909ab121ca1a813c7">llvm::ISD::EH_SJLJ_SETJMP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa4b85349547c5b6126817e10152007931">llvm::TargetLoweringBase::Expand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">llvm::ISD::EXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2b4d07600495a563319d6a3dda8dc44d">llvm::ISD::FABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad56e9199ae3993a09af36ff41d327a11">llvm::ISD::FCEIL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeffc3319657e213a530ce583603f7221">llvm::ISD::FCOPYSIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9133d7cfb6a66404ff7757b699bc3941">llvm::ISD::FCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abc6c09c7af98236460f0b020eb3be94e">llvm::ISD::FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad49a46d391f73aa96002adbdd0cf03f5">llvm::ISD::FEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af3542a99501ffb93cee4aae9d1ec2d05">llvm::ISD::FEXP2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4336c27826676e1ef61383cafa999219">llvm::ISD::FFLOOR</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a850652b63276e9d79e6c1e05146c84c0">llvm::MVT::fixedlen_vector_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a455f49e18d470b97cd293acd7fbdf169">llvm::ISD::FLDEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac82d37f93ae4420659acdd03f79b15e0">llvm::ISD::FLOG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0d05d4a5cd10a46f69f9e62d49d275bb">llvm::ISD::FLOG10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a558dc710055f9d60cc3c0893bc29a72d">llvm::ISD::FLOG2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a632dd4bb044d5cd11f671d176ef495f2">llvm::ISD::FMAXNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a25e670389809910f59726e8a11fa82e0">llvm::ISD::FMAXNUM_IEEE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9f59cc264907eb86e29564d5f6a5b213">llvm::ISD::FMINNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a907932b29f929b1827b1b93171dcaa3c">llvm::ISD::FMINNUM_IEEE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178">llvm::ISD::FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2dc876d6cc16ac04376483552292f9f4">llvm::ISD::FNEARBYINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d26c45c040d8f85d577a5f645261d1a">llvm::ISD::FNEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3e12fcc9960ef3bf0ae5876382d4c66f">llvm::ISD::FP16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a38f379e4fddf750c36f1323a04d12171">llvm::ISD::FP_TO_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#adfa86eda5d29b10227c46b4d8f071148">llvm::MVT::fp_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1a6952b1572a4ce241cc3cf45a9ab071">llvm::ISD::FPOW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a66b7368b776f6aff492cf970db3df548">llvm::ISD::FPOWI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdd7bbb76dac7962dda6e116e33699da">llvm::ISD::FREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a68014623710f7a44c808cd412236d6a1">llvm::ISD::FRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a87b7dd3d6a9b68d1558fc6b4706708b0">llvm::ISD::FROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a822b0d02b601898e2d6db5b39e12cc8a">llvm::ISD::FSHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a874350de5b4f6b8f4db13940e17ed81b">llvm::ISD::FSHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad46ae9fdfe20cd04f7fda7ccbb937543">llvm::ISD::FSIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6ba8fc92ee5081d3e533cb5322f74f29">llvm::ISD::FSINCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae1118ddac1ce0af8e9f7cc16c9e94fc0">llvm::ISD::FSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad">llvm::ISD::FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1e92ea554489509b0ad970901bcc715b">llvm::ISD::FTRUNC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad53cd7e7b02001174120015f80922e6f">llvm::TargetLoweringBase::GatherAllAliasesMaxDepth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af5caa395d199fab7e52a63feb73dcb10">llvm::ISD::GET_DYNAMIC_AREA_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89f3afc3fa907ff83759c6c76d97a973">llvm::ISD::GET_ROUNDING</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#aeefe52b8561be26c1281d79be439cd26">llvm::PPCSubtarget::getRegisterInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="#a44135eb0a79dfbd49c8235956342fcf7">hasSPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sched/#ab8d854a5ce2331586bcc6830cca52f0fa6530ebdb4e713581540e6ceb88897acb">llvm::Sched::Hybrid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4534a6db2862a28324932a8ea1cb54d6">llvm::ISD::INIT_TRAMPOLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae35d57f3c020672748fcc95607348986">llvm::ISD::INLINEASM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab969e7d43eb37a0398b5ded23bccc136">llvm::ISD::INLINEASM_BR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7b339f69bc3995d23399a85f81af6018">llvm::MVT::integer_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a76b6d3008e806ea613323ff316ef72c3">llvm::ISD::IS_FPCLASS</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#adfe2696265f6b0a7cd08bb6159fb9db4">llvm::TargetLoweringBase::IsStrictFPEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0c70100db6ddc0b37b56feb242145cf4">llvm::ISD::JumpTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aafb9a152dd1ee4089f5fc96a33c5c90d2">llvm::TargetLoweringBase::LibCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a25eed965b36ce43fc8b9daa2774dfad8">llvm::ISD::LLRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4e2fdf7d4dbc04469cf6a920262c82c8">llvm::ISD::LLROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a05f23e2cd900dc8f1dbf6702ab12423b">llvm::ISD::LRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adb1de74d602ef905e06785e0052b55bf">llvm::ISD::LROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3111deca0523de0afcc110cf020ebaaf">llvm::TargetLoweringBase::MaxLoadsPerMemcmp</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aae9cf790eaa990b803a93058582d78e8">llvm::TargetLoweringBase::MaxLoadsPerMemcmpOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aefbee33131c130f8f691c9a482f5fc40">llvm::TargetLoweringBase::MaxStoresPerMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1695feb44cd6dd30c64697360f1e76d3">llvm::TargetLoweringBase::MaxStoresPerMemcpyOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6d0f43699563375800a45f45bc11ff49">llvm::TargetLoweringBase::MaxStoresPerMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7800cede44a09d00fcc61b9087c20d85">llvm::TargetLoweringBase::MaxStoresPerMemmoveOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9830bda9bf50bfdab4c10954cc6fb1ac">llvm::TargetLoweringBase::MaxStoresPerMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a67f472063b7db365d0b5da597871e03d">llvm::TargetLoweringBase::MaxStoresPerMemsetOptSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa2a7c3eccf06b41e4275bbeadb46d22e">llvm::ISD::MULHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8a80d3b085af08f0dce1724207ef99b5">llvm::ISD::MULHU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a2eeb56ba19044c9c01c2c0606ada7083a5905b4b9443e62f9efe0c22aab6260d3">llvm::PPCSubtarget::POPCNTD_Fast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a507e89e4a7eefc0b875817f3f3362dc6">PPCGatherAllAliasesMaxDepth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#ac8a4451494d89396b365cb9a16b4543f">PPCMinimumJumpTableEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31ab5bb854fadd42503c849c4a48d7f3d90">llvm::ISD::PRE_INC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cc366cf4e0b825191ca9babcf290286">llvm::TargetLoweringBase::PredictableSelectIsExpensive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a691a4c9004e9bd04d1c0bebc5df57443">llvm::ISD::PREFETCH</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aaba91ac521e4f01f57413216273fd7b7f">llvm::TargetLoweringBase::Promote</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac43f9bea13e29622bbf18c861b52144d">llvm::ISD::READCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715">llvm::ISD::ROTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af1b946afff631cee7aa6de570bef7785">llvm::ISD::SADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a874f66e1efe5be79552bbe7ee3121a">llvm::ISD::SDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4fe6c878350458de2c3182392f830988">llvm::ISD::SET_ROUNDING</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6b928e5a6718acab4fa0030ce9198e8a">llvm::TargetLoweringBase::setBooleanContents</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0662d63e058816bf77a5b8f35331bd9d">llvm::TargetLoweringBase::setBooleanVectorContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#abbec47c0a3f39ed8fa200ccc9933318f">llvm::TargetLoweringBase::setCondCodeAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aeb09b1add015714789734df22b143112">llvm::TargetLoweringBase::setHasMultipleConditionRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4978da84fa67e0aa3a513c27e6367e91">llvm::TargetLoweringBase::setIndexedLoadAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8257b6c2db03e8af1a87bb4d7cb8c878">llvm::TargetLoweringBase::setIndexedStoreAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af7666cad940e6ca0f5c37b9e7b23157d">llvm::TargetLoweringBase::setJumpIsExpensive</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8b36797b46a42e7b489e47c2d009bc1d">llvm::TargetLoweringBase::setLibcallName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad1d4d71bf37fea6a3170f27438d41e6d">llvm::TargetLoweringBase::setLoadExtAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4df001a3c611cc8b423ca0e54560210f">llvm::TargetLoweringBase::setMaxAtomicSizeInBitsSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6566d8c65c03ad2f7b18ed08f0e7f208">llvm::TargetLoweringBase::setMinFunctionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9cc71effed4a85d71b1e556d266f0d3b">llvm::TargetLoweringBase::setMinimumJumpTableEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a2544bef91bdf3e85c561e59a0e662292">llvm::TargetLoweringBase::setMinStackArgumentAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a71f916390487bb109d9968c72553eaf4">llvm::ISD::SETO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ac7bb30d4918c1ee9dd208083154e109f">llvm::ISD::SETOGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a1febf3bac2f3d7d98ec19f1ff5c385ea">llvm::ISD::SETOLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a57c68bf7ef20bd558854a24d5b0c1e72">llvm::ISD::SETONE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a07c0c67913bb543fc45ce9ef65ef260a">llvm::TargetLoweringBase::setOperationAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8bb50938977c871d4dfa617d1b759a9a">llvm::TargetLoweringBase::setPrefFunctionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4aebe88e5c44bdb37513651bc72c2889">llvm::TargetLoweringBase::setPrefLoopAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af2a24aed2ba5d4f9c8db9904df6fa635">llvm::TargetLoweringBase::setSchedulingPreference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab8a44fb1f49bcfbed806fef69301a67a">llvm::TargetLoweringBase::setStackPointerRegisterToSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac87dc82fa9f824a797198e7b0e16141d">llvm::TargetLoweringBase::setTargetDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa243085e56636cc454143f916686c190">llvm::TargetLoweringBase::setTruncStoreAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a0deb50cd2f3f8e4a94eef4cdf769b848">llvm::ISD::SETUEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a292be4a9782030bfad637581d25a5897">llvm::ISD::SETUGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a473200f06bdd611fdbed43d908b84305">llvm::ISD::SETULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a48a334bbe606d5e82c9cd84eaa127b50">llvm::ISD::SETUO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="#aff42b7a0251319665ac35b24de49a9f3">shouldInlineQuadwordAtomics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af3b59179b6fcbc89463181015ace8e9b">llvm::ISD::SMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaac895215ecbb3c411c957c8beb39b70">llvm::ISD::SMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1354c6f8508d6cd697dc89a5d9a52dfd">llvm::ISD::SMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sched/#ab8d854a5ce2331586bcc6830cca52f0fac13545a6345c7d5b3c9cc8932ad3b0e9">llvm::Sched::Source</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6efe16ea597cfd8eeac26516fc992ee7">llvm::ISD::SSUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a77984d86d70df1f3229da7a5119652a9">llvm::ISD::SSUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a023a9de787026fe61b024476bf9c32cb">llvm::ISD::STACKRESTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a031ce694e40832d40a163d7254a8df14">llvm::ISD::STACKSAVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad11fa7fd2a91d210ecbdf09d56cd9f42">llvm::ISD::STRICT_FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1fb1e48394636004fd75f5916f0d730f">llvm::ISD::STRICT_FCEIL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4151e13f7626f6d790d58c0fa444f32e">llvm::ISD::STRICT_FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab74cbb3933c5f5d2cc90d299836c05cc">llvm::ISD::STRICT_FFLOOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a26ff7f7547f66e1a4f6d5e7efe4b2f59">llvm::ISD::STRICT_FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92f7a0e4dfe860ff938d463d84270ba3">llvm::ISD::STRICT_FMAXNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98f18e85e4e6421f5c859680602a4c1f">llvm::ISD::STRICT_FMINNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4b912b6be299d30d75b876e939d16fd6">llvm::ISD::STRICT_FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae463c3e40819d6e9de30d7d858867ef4">llvm::ISD::STRICT_FNEARBYINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac47e026e409ff39f319cbb3b096863e6">llvm::ISD::STRICT_FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2273d9cd04ba6e4a7c1a4b28ab1aaba">llvm::ISD::STRICT_FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed">llvm::ISD::STRICT_FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf955b4b70f63865e022c329d1775579">llvm::ISD::STRICT_FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af57a22f2843a1c3a79d17350945ede58">llvm::ISD::STRICT_FRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0953e80e4e94f6ded9680e64c5df5cc">llvm::ISD::STRICT_FROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0466b21bfb4f3596e41380d8e2d1956f">llvm::ISD::STRICT_FSETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c8d07d668872f2176fb34724cd799c4">llvm::ISD::STRICT_FSETCCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a476844aad24870fab3d132b5fe6b1f37">llvm::ISD::STRICT_FSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad6192a54cb1dfeca8173749cc735269a">llvm::ISD::STRICT_FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a883c1084962f12018ca0fe3e1222fa7d">llvm::ISD::STRICT_FTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab38d2af541b99492acf69c041c98bcb6">llvm::ISD::STRICT_SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a56735332b7dc26b4e164035831fb40ab">llvm::ISD::STRICT_UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2ab6db512a611d1ef4ff8069e2bbfd0d">llvm::ISD::SUBC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac9246c101c0cc9232e37b3941194bb13">llvm::ISD::SUBE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aaa96f111a59a7a2e7f9c689b344543df">llvm::TargetLowering::TargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac5fb8808f3dcb9f0a83f1fc2e7747485">llvm::ISD::TRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1ddf36330110b4abea43fe390bea9ef9">llvm::ISD::UADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5e433873c201ad85c30e42da1ae05977">llvm::ISD::UADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a257ffa49107e2db978e8a6e2688ada">llvm::ISD::UDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af675e759c0ffff8d48ea14a60fe3517b">llvm::ISD::UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a17126302da6199930e55e841ca1b082d">llvm::ISD::UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a79c959df09509d7ff66d9b04bc40d18d">llvm::ISD::UMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28">llvm::ISD::UREM</a>, <a href="#a61d752ab70921f29e5c50f5fb75b8c0c">useSoftFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89166b38f12c0bd3e8a61d8f1a5a8bc8">llvm::ISD::USUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae77d03846b31c41c4860bcd96d780a78">llvm::ISD::VAARG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a804c1960ac64628cdd1f74d7de885284">llvm::ISD::VACOPY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1aadbb14ab26b74d841ac003363e3a5d">llvm::ISD::VAEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adfe32beaa596a1512b17e66b46e773ed">llvm::ISD::VASTART</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0b7d2c769fd0fbaab3c4a2fc8e7ea0c">llvm::ISD::VSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a695a19c9c3ae14638be151add82755cb">llvm::TargetLoweringBase::ZeroOrNegativeOneBooleanContent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a0e2d72cfdcc49d2d189f440b3cc31dff">llvm::TargetLoweringBase::ZeroOrOneBooleanContent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allowsMisalignedMemoryAccesses() {#ad5d9213c39b2fc64eaed3639539e8f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::allowsMisalignedMemoryAccesses (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, unsigned AddrSpace, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(1), <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dd">MachineMemOperand::Flags</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">MachineMemOperand::MONone</a>, unsigned * Fast=nullptr)</td>
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

<p>Is unaligned memory access allowed for the given type, and is it fast relative to software emulation.</p>

<p>Declaration at line 1084 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17803 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1c09895eaf1069239b0494b5e5c10187">DisablePPCUnaligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3cb888a2ce8e95e0d9769687a5e2f7d8">llvm::EVT::isFloatingPoint</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>.</p>

</div>
</div>

### BuildSDIVPow2() {#a5583b4d2c0c7813f44df3fe6d42d20e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::BuildSDIVPow2 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Divisor, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; Created)</td>
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

<p>Targets may override this function to provide custom SDIV lowering for power-of-2 denominators.</p>


<p>If the target returns an empty <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, LLVM assumes SDIV is expensive and replaces it with a series of other integer operations.</p>


<p>Declaration at line 906 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 16928 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1b6b4785fa27be394cf040e543d9fe7c">llvm::APInt::isNegatedPowerOf2</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad1b0513de876d1c85cf6268ca21b2c86">llvm::APInt::isPowerOf2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ad78bb5b4a8218f88e112b72fab5d508c">llvm::PPCISD::SRA_ADDZE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>.</p>

</div>
</div>

### ccAssignFnForCall() {#a0788f6af8ef22d48e3406bfd67a8d384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCAssignFn * PPCTargetLowering::ccAssignFnForCall (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, bool Return, bool IsVarArg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 19114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f6b893bc99ce3ce20fdc74a21b37e61">llvm::CC_PPC64_ELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca94ec9273479164e4aec1d5d91b71dc85">llvm::CallingConv::Cold</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6ad6b0d0babae82bf8b5ef6cac807c7b">llvm::RetCC_PPC_Cold</a>.</p>

</div>
</div>

### CollectTargetIntrinsicOperands() {#ac05ba7b36777c445fb76f15011abf487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCTargetLowering::CollectTargetIntrinsicOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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



<p>Declaration at line 1011 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a82e2e151e4db313b8832505c9955b689">llvm::SelectionDAG::getMDNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp/#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### computeKnownBitsForTargetNode() {#a5be8668f644eaefda25f6905908bd9f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCTargetLowering::computeKnownBitsForTargetNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth=0)</td>
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

<p>Determine which of the bits specified in Mask are known to be either zero or one and return them in the KnownZero/KnownOne bitsets.</p>


<p>The DemandedElts argument allows us to only collect the known bits that are shared by the requested vector elements.</p>


<p>Declaration at line 912 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 16961 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a8032251e5c6dfb52579250ef6373d599">llvm::PPCISD::LBRX</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a538f22b4ea2ff04a0b41403f26eaeb67">llvm::KnownBits::resetAll</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>

</div>
</div>

### convertSelectOfConstantsToMath() {#a8bce339379d3a541ec57b178e6deeca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCTargetLowering::convertSelectOfConstantsToMath (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if a select of constants (select Cond, C1, C2) should be transformed into simple math ops with the condition value.</p>


<p>For example: select Cond, C1, C1-1 --&gt; add (zext Cond), C1-1</p>


<p>Definition at line 1048 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>

</div>
</div>

### convertSetCCLogicToBitwiseLogic() {#a91d45f6f637b1db940277d23e6d471db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCTargetLowering::convertSetCCLogicToBitwiseLogic (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> bitwise logic to make pairs of compares more efficient.</p>


<p>For example: and (seteq A, B), (seteq C, D) --&gt; seteq (or (xor A, B), (xor C, D)), 0 This should be true when it takes more than one instruction to lower setcc (cmp+set on x86 scalar), when bitwise ops are faster than logic on condition bits (crand on PowerPC), and/or when reducing cmp+br is a win.</p>


<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#ad958859a7af278dd5ea2b593c2b25050">llvm::EVT::isScalarInteger</a>.</p>

</div>
</div>

### createFastISel() {#afb9a1efd115f87d617c4bd692181df4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastISel * PPCTargetLowering::createFastISel (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FuncInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * LibInfo)</td>
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

<p>createFastISel - This method returns a target-specific <a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> object, or null if the target does not support "fast" instruction selection.</p>

<p>Declaration at line 1116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17985 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a2cd7fb94f62f409bc4faf2a20e0904eb">llvm::PPC::createFastISel</a>.</p>

</div>
</div>

### decomposeMulByConstant() {#a700728edd4a6a3ebe5797715cb535874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::decomposeMulByConstant (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> C)</td>
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

<p>Return true if it is profitable to transform an integer multiplication-by-constant into simpler operations like shifts and adds.</p>


<p>This may be true if the target does not directly support the multiplication operation for the specified type or the sequence of simpler ops is faster than the multiply.</p>


<p>Declaration at line 1052 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17841 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#ad958859a7af278dd5ea2b593c2b25050">llvm::EVT::isScalarInteger</a>.</p>

</div>
</div>

### EmitAtomicBinary() {#a541b354a6386df6d03fcdc656d7d9db7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * PPCTargetLowering::EmitAtomicBinary (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, unsigned AtomicSize, unsigned BinOpcode, unsigned CmpOpcode=0, unsigned CmpPred=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 951 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 12349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4874816314c3308be0bf1e71de2078d8">llvm::MachineBasicBlock::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355ad9add708b3d9680d64242cf06f448462">llvm::PPC::PRED_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a>.</p>


<p>Referenced by <a href="#a10d6f09e62a827099ec8b54efb4c035d">EmitInstrWithCustomInserter</a> and <a href="#a2e99e64e510ba34954d7fe85b1e30119">EmitPartwordAtomicBinary</a>.</p>

</div>
</div>

### emitEHSjLjLongJmp() {#a056f22c11083630d8bcc82299cb783af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * PPCTargetLowering::emitEHSjLjLongJmp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 12881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad84ebe08bb098cd283e922fd186f77e9">llvm::MachineInstrBuilder::cloneMemRefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ab8e1af73424a59a00656c9ffd505c03f">llvm::MVT::getStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aa8ab0804ddb40450da6549e1943817a2">llvm::TargetLowering::isPositionIndependent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a65426f2f59cffd6edeb85831b24dbc48">setUsesTOCBasePtr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#a10d6f09e62a827099ec8b54efb4c035d">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### emitEHSjLjSetJmp() {#a212384cdd746eaffedb7edc7a16a1cef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineBasicBlock * PPCTargetLowering::emitEHSjLjSetJmp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 964 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 12739 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a8880ccaea51a4ee9b48c3c8d7fbfebf4">llvm::MachineInstrBuilder::addRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad84ebe08bb098cd283e922fd186f77e9">llvm::MachineInstrBuilder::cloneMemRefs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a56e1b2d1999aadf4c513caee1ce5275b">llvm::BranchProbability::getOne</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1a78b9f867cb5be3a052d6ad972484ca">llvm::TargetLoweringBase::getRegClassFor</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ab8e1af73424a59a00656c9ffd505c03f">llvm::MVT::getStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#afd00958cba7080048a84cccfcef55d71">llvm::BranchProbability::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a65426f2f59cffd6edeb85831b24dbc48">setUsesTOCBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a10d6f09e62a827099ec8b54efb4c035d">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### EmitInstrWithCustomInserter() {#a10d6f09e62a827099ec8b54efb4c035d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * PPCTargetLowering::EmitInstrWithCustomInserter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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

<p>This method should be implemented by targets that mark instructions with the 'usesCustomInserter' flag.</p>


<p>These instructions are special in various ways, which require special support to insert. The specified <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> is created but not inserted into any basic blocks, and this method is called to expand it into a sequence of instructions, potentially also creating new basic blocks and control flow. As long as the returned basic block is different (i.e., we created a new one), the custom inserter is free to modify the rest of <span class="doxyComputerOutput">MBB</span>.</p>


<p>Declaration at line 949 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 13212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a86a93dd8ddbce120d8c3101c16bc3cc6">llvm::MachineInstrBuilder::addFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae565d45627e1678a3e37bd6a016c561c">llvm::MachineInstrBuilder::addMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1ae307f415a8989475e3f7ddd6eefc8b">llvm::MachineFrameInfo::CreateStackObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a541b354a6386df6d03fcdc656d7d9db7">EmitAtomicBinary</a>, <a href="#a056f22c11083630d8bcc82299cb783af">emitEHSjLjLongJmp</a>, <a href="#a212384cdd746eaffedb7edc7a16a1cef">emitEHSjLjSetJmp</a>, <a href="#a2e99e64e510ba34954d7fe85b1e30119">EmitPartwordAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="#a2cb46b1ded73af4c2924bd2d1d8db334">emitProbedAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4874816314c3308be0bf1e71de2078d8">llvm::MachineBasicBlock::getBasicBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a8320a54de0a273478de910ac3795058b">llvm::MachineFrameInfo::getObjectAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a5e8a1ef711294cc52d6e2c41279f4c0f">IsSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a04c194c51d42f6cb99a5495af70cfb65">IsSelectCC</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a1cf224b3316c689f4735877ef0bbd893">llvm::MachineInstr::NoFPExcept</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355a3382a0bee0f471ebce5e57f6cbdc91d6">llvm::PPC::PRED_BIT_SET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355a8cd4d49277068c1eab8d4d7c4835b817">llvm::PPC::PRED_GT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355a46cd6e935d7b9cc679d9cb0cf025ae91">llvm::PPC::PRED_LT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355ad9add708b3d9680d64242cf06f448462">llvm::PPC::PRED_NE</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4472755d36621c5e2d056eec5056202e">llvm::MachineBasicBlock::setCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a>.</p>

</div>
</div>

### emitLeadingFence() {#aff4c3b2eec63855bda40615dece5853f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * PPCTargetLowering::emitLeadingFence (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ord)</td>
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

<p>Inserts in the IR a target-specific intrinsic specifying a fence.</p>


<p>It is called by <a href="/web-llvm/docs/api/classes/llvm/atomicexpandpass">AtomicExpandPass</a> before expanding an AtomicRMW/AtomicCmpXchg/AtomicStore/AtomicLoad if shouldInsertFencesForAtomic returns true.</p>


<p>Inst is the original atomic instruction, prior to other expansions that may be performed.</p>


<p>This function should either return a nullptr, or a pointer to an IR-level Instruction*. Even complex fence sequences can be represented by a single Instruction* through an intrinsic to be lowered later.</p>


<p>The default implementation emits an IR fence before any release (or stronger) operation that stores, and after any acquire (or stronger) operation. This is generally a correct implementation, but backends may override if they wish to use alternative schemes (e.g. the PowerPC standard ABI uses a fence before a seq_cst load instead of after a seq_cst store).</p>


<p>Declaration at line 924 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 12322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aaf3ff3fef7a854e7b213f166670c2aca">callIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a586359566c841c85abfd8922e220213e">llvm::isReleaseOrStronger</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a>.</p>


<p>Referenced by <a href="#a683761fbb11ed0969edf7eee08b08bf3">emitMaskedAtomicCmpXchgIntrinsic</a>.</p>

</div>
</div>

### emitMaskedAtomicCmpXchgIntrinsic() {#a683761fbb11ed0969edf7eee08b08bf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * PPCTargetLowering::emitMaskedAtomicCmpXchgIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst">AtomicCmpXchgInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * AlignedAddr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CmpVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Mask, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ord)</td>
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

<p>Perform a masked cmpxchg using a target-specific intrinsic.</p>


<p>This represents the core LL/SC loop which will be lowered at a late stage by the backend. The target-specific intrinsic returns the loaded value and is not responsible for masking and shifting the result.</p>


<p>Declaration at line 942 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 19200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="#aff4c3b2eec63855bda40615dece5853f">emitLeadingFence</a>, <a href="#a1c68a6f0cdbdeb8a431791ad286109a0">emitTrailingFence</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="#aff42b7a0251319665ac35b24de49a9f3">shouldInlineQuadwordAtomics</a>.</p>

</div>
</div>

### emitMaskedAtomicRMWIntrinsic() {#a0e0d3c023e19c20fbf01b40d36aced80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * PPCTargetLowering::emitMaskedAtomicRMWIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * AI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * AlignedAddr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Incr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Mask, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ShiftAmt, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ord)</td>
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

<p>Perform a masked atomicrmw using a target-specific intrinsic.</p>


<p>This represents the core LL/SC loop which will be lowered at a late stage by the backend. The target-specific intrinsic returns the loaded value and is not responsible for masking and shifting the result.</p>


<p>Declaration at line 937 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 19178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aa7f6e181466687153766e195e20fea37">getIntrinsicForAtomicRMWBinOp128</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a99fd4ef84981d6a2774c14c741b5ed65">llvm::AtomicRMWInst::getOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="#aff42b7a0251319665ac35b24de49a9f3">shouldInlineQuadwordAtomics</a>.</p>

</div>
</div>

### EmitPartwordAtomicBinary() {#a2e99e64e510ba34954d7fe85b1e30119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * PPCTargetLowering::EmitPartwordAtomicBinary (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, bool is8bit, unsigned Opcode, unsigned CmpOpcode=0, unsigned CmpPred=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 957 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 12524 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#a541b354a6386df6d03fcdc656d7d9db7">EmitAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4874816314c3308be0bf1e71de2078d8">llvm::MachineBasicBlock::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aae89411ebc82571d39a33d35726f9604">isSignExtended</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355ad9add708b3d9680d64242cf06f448462">llvm::PPC::PRED_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a>.</p>


<p>Referenced by <a href="#a10d6f09e62a827099ec8b54efb4c035d">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### emitProbedAlloca() {#a2cb46b1ded73af4c2924bd2d1d8db334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * PPCTargetLowering::emitProbedAlloca (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 970 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 13012 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="#ac4e23bdb97cbb1eebd9ddd6606a1006f">getStackProbeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355a34be5288a1bb24e5120358395f7f0dc3">llvm::PPC::PRED_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a>.</p>


<p>Referenced by <a href="#a10d6f09e62a827099ec8b54efb4c035d">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### emitTrailingFence() {#a1c68a6f0cdbdeb8a431791ad286109a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * PPCTargetLowering::emitTrailingFence (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ord)</td>
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



<p>Declaration at line 926 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 12332 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aaf3ff3fef7a854e7b213f166670c2aca">callIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab7e43783656ce7aae69f3da31509ff88">llvm::Instruction::hasAtomicLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abbc497e16b1809ff526b1c755483d35c">llvm::isAcquireOrStronger</a>.</p>


<p>Referenced by <a href="#a683761fbb11ed0969edf7eee08b08bf3">emitMaskedAtomicCmpXchgIntrinsic</a>.</p>

</div>
</div>

### enableAggressiveFMAFusion() {#a6f3484a5a16158cba22281a95a187e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::enableAggressiveFMAFusion (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if target always benefits from combining into FMA for a given value type.</p>


<p>This must typically return false on targets where FMA takes more cycles to execute than FADD.</p>


<p>Declaration at line 846 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 1875 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#a3cb888a2ce8e95e0d9769687a5e2f7d8">llvm::EVT::isFloatingPoint</a>.</p>

</div>
</div>

### expandVSXLoadForLE() {#a414d9dfa6f85f8ad371a510821713e61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::expandVSXLoadForLE (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 15541 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#a9e3e1453357b1b1cd870a4ac3528f918">llvm::TargetLowering::DAGCombinerInfo::AddToWorklist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#acf37bd7e831bdb2a5c9da8d63f843101">llvm::TargetLowering::DAGCombinerInfo::DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ab858661e16a61c4fc6b27b6b26aac17b">llvm::MemSDNode::getChain</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6cc63109335eefe2c5727d1e12fc820">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aa078a60d1127b9daad580b6d2ba7ef91">llvm::MemSDNode::getMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a0ffa31699dee0349f9b9ae1d3ccb21f1">llvm::MachineMemOperand::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a0b0401973fc9567440717a5d32a8eb8d">llvm::LocationSize::hasValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#a06663f3ab188bef45b0f669c9f109df5">llvm::TargetLowering::DAGCombinerInfo::isBeforeLegalizeOps</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a9f74f2eb04440389d18aabcff035a19f">llvm::PPCISD::LXVD2X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a01c94937492f3ac3fb1e0be8eb0b9ef1">llvm::ISD::MERGE_VALUES</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a4156aa36da735bf4f407406f04aa9a49">llvm::PPCISD::XXSWAPD</a>.</p>


<p>Referenced by <a href="#ab4ccdcee4c7a2e0892715d0a8094b86e">PerformDAGCombine</a>.</p>

</div>
</div>

### expandVSXStoreForLE() {#abf2cd323dcdc4b2b0a4741c62b30d0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::expandVSXStoreForLE (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 902 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 15607 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#a9e3e1453357b1b1cd870a4ac3528f918">llvm::TargetLowering::DAGCombinerInfo::AddToWorklist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#acf37bd7e831bdb2a5c9da8d63f843101">llvm::TargetLowering::DAGCombinerInfo::DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ab858661e16a61c4fc6b27b6b26aac17b">llvm::MemSDNode::getChain</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6cc63109335eefe2c5727d1e12fc820">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aa078a60d1127b9daad580b6d2ba7ef91">llvm::MemSDNode::getMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a0ffa31699dee0349f9b9ae1d3ccb21f1">llvm::MachineMemOperand::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a0b0401973fc9567440717a5d32a8eb8d">llvm::LocationSize::hasValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#a06663f3ab188bef45b0f669c9f109df5">llvm::TargetLowering::DAGCombinerInfo::isBeforeLegalizeOps</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ad7ff3b99ede678baebc8e3cd79b1090a">llvm::PPCISD::STXVD2X</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a4156aa36da735bf4f407406f04aa9a49">llvm::PPCISD::XXSWAPD</a>.</p>


<p>Referenced by <a href="#ab4ccdcee4c7a2e0892715d0a8094b86e">PerformDAGCombine</a>.</p>

</div>
</div>

### functionArgumentNeedsConsecutiveRegisters() {#a3bf9bca8a4d7246c83bbfa566a51165e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCTargetLowering::functionArgumentNeedsConsecutiveRegisters (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Returns true if an argument of type Ty needs to be passed in a contiguous block of registers in calling convention CallConv.</p>

<p>Definition at line 1121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### getByValTypeAlignment() {#a51b3288a078ec78d279a486db1946b31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align PPCTargetLowering::getByValTypeAlignment (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>getByValTypeAlignment - Return the desired alignment for ByVal aggregate function arguments in the caller parameter area.</p>

<p>Declaration at line 990 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 1647 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a8baa555a40ec02c58a1e0455237f65f9">getMaxByValAlign</a>.</p>

</div>
</div>

### getConstraintType() {#a97e1f4e021dcba5a7795f823781e04df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCTargetLowering::ConstraintType PPCTargetLowering::getConstraintType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint)</td>
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

<p>getConstraintType - Given a constraint, return the type of constraint it is for this target.</p>

<p>Declaration at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17068 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a420d729d2e7d056ec884c094ccdc4467">llvm::TargetLowering::C_Memory</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a1d7718fd43ac0a5c715686a76f9cfd89">llvm::TargetLowering::C_RegisterClass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a45b2deb637d370d68d3bd3786c21e415">llvm::TargetLowering::getConstraintType</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### getExceptionPointerRegister() {#ae00d7eb852ec09ae630c49f5b9454aff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register PPCTargetLowering::getExceptionPointerRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PersonalityFn)</td>
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

<p>If a physical register, this returns the register that receives the exception address on entry to an EH pad.</p>

<p>Declaration at line 1137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17954 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### getExceptionSelectorRegister() {#ade9eaaa949a3aeb305931cbde5cae365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register PPCTargetLowering::getExceptionSelectorRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PersonalityFn)</td>
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

<p>If a physical register, this returns the register that receives the exception typeid on entry to a landing pad.</p>

<p>Declaration at line 1142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17959 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### getInlineAsmMemConstraint() {#a73a300242af50ce9daeda4a2e002df27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAsm::ConstraintCode llvm::PPCTargetLowering::getInlineAsmMemConstraint (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ConstraintCode)</td>
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



<p>Definition at line 999 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a12470fe406d44017d96eab37dd65fc14">llvm::InlineAsm::es</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a3acbc2d34d9a6d35b63a04f0ae20136c">llvm::TargetLowering::getInlineAsmMemConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0af09564c9ca56850d4cd6b3319e541aee">llvm::InlineAsm::Q</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a21c2e59531c8710156d34a3c30ac81d5">llvm::InlineAsm::Z</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0ad94eb39b7c5996a928c1d97e2d336207">llvm::InlineAsm::Zy</a>.</p>

</div>
</div>

### getJumpTableEncoding() {#a76ee5e788bf1969bd98f670b3471a12b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PPCTargetLowering::getJumpTableEncoding ()</td>
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

<p>Return the entry encoding for a jump table in the current function.</p>


<p>The returned value is a member of the <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#aaa21facdbb167f7c33d21907b8e5b9d3">MachineJumpTableInfo::JTEntryKind</a> enum.</p>


<p>Declaration at line 1152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#aaa21facdbb167f7c33d21907b8e5b9d3a6e05991949952d4e85600b0868dcd803">llvm::MachineJumpTableInfo::EK_LabelDifference32</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aded686370215fda472fa7b38ccbba458">llvm::TargetLowering::getJumpTableEncoding</a> and <a href="#adf6c939e7121ecf6c9339ef40eb8bbde">isJumpTableRelative</a>.</p>

</div>
</div>

### getNegatedExpression() {#a2fd734bb5606f5c8bd7bd6ef49683e1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::getNegatedExpression (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool LegalOps, bool OptForSize, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad717707a2df4226d0388460e87c8cd84">NegatibleCost</a> &amp; Cost, unsigned Depth=0)</td>
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

<p>Return the newly negated expression if the cost is not expensive and set the cost in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a></span> to indicate that if it is cheaper or neutral to do the negation.</p>

<p>Declaration at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18003 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad717707a2df4226d0388460e87c8cd84a920c5f62b372ce8ed1056422a02c356a">llvm::TargetLoweringBase::Expensive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a24c65ae2b770c0b178a4c2458586b058">llvm::PPCISD::FNMSUB</a>, <a href="#a2fd734bb5606f5c8bd7bd6ef49683e1e">getNegatedExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aea3e575b3cff4eb444567d50959b929c">llvm::TargetLowering::getNegatedExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9245ed740fe76aaad3e5b0650da21c98">llvm::TargetLoweringBase::isOperationLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4d5e16cbde22f5e6f007940d57a428fd">llvm::SelectionDAG::MaxRecursionDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="#a2fd734bb5606f5c8bd7bd6ef49683e1e">getNegatedExpression</a>.</p>

</div>
</div>

### getOptimalMemOpType() {#aae7a66849fd8b672b9c9f6897d6326a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT PPCTargetLowering::getOptimalMemOpType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memop">MemOp</a> &amp; Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &amp; FuncAttributes)</td>
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

<p>It returns EVT::Other if the type should be determined using generic target-independent logic.</p>

<p>Declaration at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17712 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### getPICJumpTableRelocBase() {#a64ca42c56843a34b11476e34d5941628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::getPICJumpTableRelocBase (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Table, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Returns relocation base for the given PIC jumptable.</p>

<p>Declaration at line 1154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#aa85a26f5f6b24110a2388e4726cdd282">getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ab4681990679f127bf757790e59678f80">llvm::TargetLowering::getPICJumpTableRelocBase</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a9e4500d93af7f70fdff992d9d748559d">llvm::PPCISD::GlobalBaseReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a>.</p>

</div>
</div>

### getPICJumpTableRelocBaseExpr() {#a9e8d81b42a228a0a2e89454cf7a3d017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * PPCTargetLowering::getPICJumpTableRelocBaseExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, unsigned JTI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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

<p>This returns the relocation base for the given PIC jumptable, the same as getPICJumpTableRelocBase, but as an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a>.</p>

<p>Declaration at line 1156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#aa85a26f5f6b24110a2388e4726cdd282">getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a28b6761f167a2c40e54f5291ac35051d">llvm::MachineFunction::getPICBaseSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a993d38cd5b37a6ee0c9c3cb24ada5392">llvm::TargetLowering::getPICJumpTableRelocBaseExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a>.</p>

</div>
</div>

### getPreferredVectorAction() {#ab02131f91a9d9a10d8aa800bb662d681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLoweringBase::LegalizeTypeAction llvm::PPCTargetLowering::getPreferredVectorAction (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
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

<p>getPreferredVectorAction - The code we generate when vector types are legalized by promoting the integer element type is often much worse than code we generate if we widen the type for applicable vector types.</p>


<p>The issue with promoting is that the vector is scalaraized, individual elements promoted and then the vector is rebuilt. So say we load a pair of v4i8's and shuffle them. This will turn into a mess of 8 extending loads, moves back into VSR's (or memory ops if we don't have moves) and then the VPERM for the shuffle. All in all a very slow sequence.</p>


<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a59ae7f93fccb0ae431e82f8d74ba443c">llvm::TargetLoweringBase::getPreferredVectorAction</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a447ebcc5de7a1d9bc163862bf2c78e41">llvm::MVT::isScalableVector</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681a26f35604723482a1aee6514940c2987d">llvm::TargetLoweringBase::TypePromoteInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681a40cd81ebfaf97cef327ad65d37b816da">llvm::TargetLoweringBase::TypeSplitVector</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681a5290057031a9bc71850f61e757cb940e">llvm::TargetLoweringBase::TypeWidenVector</a>.</p>

</div>
</div>

### getPrefLoopAlignment() {#af601ca614bf9dbae090272eddc645f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align PPCTargetLowering::getPrefLoopAlignment (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * ML)</td>
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

<p>Return the preferred loop alignment.</p>

<p>Declaration at line 918 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17016 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a56adb1ba4082b00854c8401847ade1a9">llvm::PPC::DIR_970</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a1a5dee2be7c154497739282b30ab123c">llvm::PPC::DIR_PWR10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34af6a785f2b13ce7870e8e4e6b9653f32f">llvm::PPC::DIR_PWR11</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a1a9618f9addb07ce52555fa524ccf39d">llvm::PPC::DIR_PWR4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a690b5c342106c270b005123adec2d7e6">llvm::PPC::DIR_PWR5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a40aa4eed5523516b6f4be5d29307b5cc">llvm::PPC::DIR_PWR5X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34aa2b626cb4809ee8a3b3da9d475eabe05">llvm::PPC::DIR_PWR6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a664d0abca2c75f8a6f8ce2dcc21cd676">llvm::PPC::DIR_PWR6X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a0c8a5dd168df904e8c29520a47502a61">llvm::PPC::DIR_PWR7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34aa3de856d909c5b0166919bf6e4bd1a3d">llvm::PPC::DIR_PWR8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a0a03bfd83c00f4d1edab975b7bfe7f36">llvm::PPC::DIR_PWR9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34ac1fc2f6d654da4e5a6a601e19d423846">llvm::PPC::DIR_PWR_FUTURE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a9a81754664d4a526243dfdb8d26fec3b">DisableInnermostLoopAlign32</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6d826603b43f8d54445e71d004a79f36">llvm::TargetLoweringBase::getPrefLoopAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3ad01fd9b01e9dde8bd3dc247afbfb7218">ML</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getPreIndexedAddressParts() {#a7e08a461c58c82e0564d2cd25c6d9990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::getPreIndexedAddressParts (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31">ISD::MemIndexedMode</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>getPreIndexedAddressParts - returns true by value, base pointer and offset pointer and addressing mode by reference if the node's address can be legally represented as pre-indexed load / store address.</p>

<p>Declaration at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3070 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aa4abb7e9879643e764ba92b14f2802d0">DisablePPCPreinc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#a6b0daf17b9f0011e9a4c4c8f00644c12">isLoad</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31ab5bb854fadd42503c849c4a48d7f3d90">llvm::ISD::PRE_INC</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="#a312de8232fec3e0e128f4a34b7ddc55d">SelectAddressRegImm</a>, <a href="#a521dc9b8649af234d8bf514085b9a640">SelectAddressRegReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a9b97177f4c89df3fd0a2f05deec3378f">usePartialVectorLoads</a>.</p>

</div>
</div>

### getRegForInlineAsmConstraint() {#add923d3128dce4cad95ce5ad642f6946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, const TargetRegisterClass * &gt; PPCTargetLowering::getRegForInlineAsmConstraint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
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

<p>Given a physical register constraint (e.g.</p>


<p>{edx}), return the register number and the register class for the register.</p>


<p>Given a register class constraint, like 'r', if this corresponds directly to an LLVM register class, return a register of 0 and the register class pointer.</p>


<p>This should only be used for C_Register constraints. On error, this returns a register number of 0 and a null register class pointer.</p>


<p>Declaration at line 985 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#af09507c47dcb4cdb2a13064aaa6d5243">llvm::TargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getRegisterByName() {#a6fae73b0e495a895c3ce49f127bf8ef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register PPCTargetLowering::getRegisterByName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RegName, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Return the register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the name passed in.</p>


<p>Used by named register global variables extension. There is no target-independent behaviour so the default action is to bail.</p>


<p>Declaration at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17497 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a4ff6b3fd769bb0563feaa4fd3e58e23f">MatchRegisterName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>

</div>
</div>

### getScalarShiftAmountTy() {#a010fe1720a71b30574703fec238e5cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::PPCTargetLowering::getScalarShiftAmountTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
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

<p>Return the type to use for a scalar shift opcode, given the shifted amount type.</p>


<p>Targets should return a legal type if the input type is legal. Targets can return a type that is too small if the input type is illegal.</p>


<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>

</div>
</div>

### getSchedulingPreference() {#afdf7d53d8e2b25e7b5c7981da1f11bcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Sched::Preference PPCTargetLowering::getSchedulingPreference (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *)</td>
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

<p>Some scheduler, e.g.</p>


<p>hybrid, can switch to different scheduling heuristics for different nodes. This function returns the preference (or none) for the given node.</p>


<p>Declaration at line 889 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17976 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af35d4876c650d69c3ae5fa79c5e32672">DisableILPPref</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a62d8f9b1392945a99d900e55b9a2727f">llvm::TargetLoweringBase::getSchedulingPreference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sched/#ab8d854a5ce2331586bcc6830cca52f0fac4801b47c85ae3044251c5ca7443b1df">llvm::Sched::ILP</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getScratchRegisters() {#a7b947e723a15a56090d5a4d0f030f44f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg * PPCTargetLowering::getScratchRegisters (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
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

<p>Returns a 0 terminated array of registers that can be safely used as scratch registers.</p>

<p>Declaration at line 1104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17942 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### getSDagStackGuard() {#ae56627ff3e9d2a5c7fdde625fd55fb97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * PPCTargetLowering::getSDagStackGuard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Return the variable that's previously inserted by insertSSPDeclarations, if any, otherwise return nullptr.</p>


<p>Should be used only when getIRStackGuard returns nullptr.</p>


<p>Declaration at line 1147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18087 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a80083daf41bf6d643ef8e00f171955f5">AIXSSPCanaryWordName</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a40e9675119de3bcd2fd05b549994a17d">llvm::TargetLoweringBase::getSDagStackGuard</a>.</p>

</div>
</div>

### getSetCCResultType() {#aea8d3912f4a0d003d32577f1098a8b44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT PPCTargetLowering::getSetCCResultType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>getSetCCResultType - Return the <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">ISD::SETCC</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a></p>

<p>Declaration at line 840 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 1867 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a0351571482fea42a3b326147fb2ce9e2">llvm::EVT::changeVectorElementTypeToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>


<p>Referenced by <a href="#a49eedef79b249eb098470debb9601eb7">ReplaceNodeResults</a>.</p>

</div>
</div>

### getSingleConstraintMatchWeight() {#a685bfe474ca920468f17fc82cf4664e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::ConstraintWeight PPCTargetLowering::getSingleConstraintMatchWeight (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a> &amp; info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * constraint)</td>
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

<p>Examine constraint string and operand type and determine a weight value.</p>


<p>Examine constraint type and operand type and determine a weight value.</p>


<p>The operand object must already have been set up with the operand type.</p>


<p>This object must already have been set up with the operand type and the current alternative constraint selected.</p>


<p>Declaration at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abcad4df0dd48c58dea43776a5a77e74ba76">llvm::TargetLowering::CW_Default</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abca2a03cc05a305d0cd861ff2d070da40ca">llvm::TargetLowering::CW_Invalid</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abca5b8290e7824d2be12d9886e17c7aedd6">llvm::TargetLowering::CW_Memory</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abcaa36ab38b266c612487d9ff61df7475af">llvm::TargetLowering::CW_Register</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#afaa66a325b7b8c5c79eb2c8e9822ffd2">llvm::TargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa0fd6bf3d33236279db7b707bba755f4">llvm::Type::isDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3ffc75c3a4cb82ba307a3334483eb4ac">llvm::Type::isFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>.</p>

</div>
</div>

### getStackProbeSize() {#ac4e23bdb97cbb1eebd9ddd6606a1006f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PPCTargetLowering::getStackProbeSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 975 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 12990 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4c866d3504a1e0717c8152a590bd6203">llvm::Function::getFnAttributeAsParsedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a07ed686a79bd6b4e4702981c4f85ec19">llvm::TargetFrameLowering::getStackAlignment</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>.</p>


<p>Referenced by <a href="#a2cb46b1ded73af4c2924bd2d1d8db334">emitProbedAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>.</p>

</div>
</div>

### getTargetNodeName() {#a22040a96a01d1504b931efe54483505b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * PPCTargetLowering::getTargetNodeName (unsigned Opcode)</td>
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

<p><a href="#a22040a96a01d1504b931efe54483505b">getTargetNodeName()</a> - This method returns the name of a target specific DAG node.</p>

<p>Declaration at line 762 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 1690 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a9d22d6055af16a92989e3413db5c61e4">llvm::PPCISD::ACC_BUILD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a606fcb46940146f9bb7ee312d6a4835f">llvm::PPCISD::ADD_TLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a6f48c93bc2c3495090cdad2d375290dc">llvm::PPCISD::ADDI_DTPREL_L</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ac3043814fcbe457dc6a768c714864692">llvm::PPCISD::ADDI_TLSGD_L</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a046e97f3becfbef4e0b3e1760a809dca">llvm::PPCISD::ADDI_TLSGD_L_ADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ad1e4cb7a1fc0c9ea50baef6974f21431">llvm::PPCISD::ADDI_TLSLD_L</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a41664c9403b22dedab5a78fc8ef07b42">llvm::PPCISD::ADDI_TLSLD_L_ADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a5fdb4eb697cc8fb8a8aa8fa53effac34">llvm::PPCISD::ADDIS_DTPREL_HA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a390f7ff6ebc81e2540d946d8d1061f29">llvm::PPCISD::ADDIS_GOT_TPREL_HA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a968bba2363b57ced282bda51b19c8162">llvm::PPCISD::ADDIS_TLSGD_HA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19abdad0d05f0b11932ef877b95832e31ea">llvm::PPCISD::ADDIS_TLSLD_HA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a320d58aba8e7aee5461dbb44378a83ba">llvm::PPCISD::ANDI_rec_1_EQ_BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a2f5e9e30846196a91f11a3e45e802eb7">llvm::PPCISD::ANDI_rec_1_GT_BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a05c872ee0bd45120100d36acd763c832">llvm::PPCISD::ATOMIC_CMP_SWAP_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a427c8d80e0d4ec009de59a94847ce3c2">llvm::PPCISD::ATOMIC_CMP_SWAP_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a453b3ee2482b8a61bbcf5ce1cd6e395e">llvm::PPCISD::BCTRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a7382bd1ceab96ffedb276ad49b4308ca">llvm::PPCISD::BCTRL_LOAD_TOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a8733bcf440af126f3cd4df36ec026da6">llvm::PPCISD::BCTRL_LOAD_TOC_RM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa82b0f1a7296f1ae77fe7a79dcd8631c">llvm::PPCISD::BCTRL_RM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a160ec67350dc5e964fc0a12a9cde1df8">llvm::PPCISD::BDNZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19addb9d78754c1f2e6d765a0da913f0800">llvm::PPCISD::BDZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ab0e0c5eda3a0cf78f4c93f32e37b9439">llvm::PPCISD::BUILD_FP128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a4726c939556eac0d044c4ba355e51e16">llvm::PPCISD::BUILD_SPE64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa09dfd0e28e0ffea73ccfc88fb2fd95c">llvm::PPCISD::CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ada865a374b524adeca1892f0eed6eb0e">llvm::PPCISD::CALL_NOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a0a587e32cccf298ed32dfcefa59d08d9">llvm::PPCISD::CALL_NOP_RM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ab9d1ecf80764a45e6761396dfb71efdb">llvm::PPCISD::CALL_NOTOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a01495b70fc5bd028897c0b297fa2438f">llvm::PPCISD::CALL_NOTOC_RM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a0ca86fac87a16ac9aa26f6ab3625a5aa">llvm::PPCISD::CALL_RM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a39b31c544933df302c4b6b049a0185e0">llvm::PPCISD::CLRBHRB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19acbf3c8dc964f8156f3bc2749ba63869d">llvm::PPCISD::CMPB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a0992940624286ed6bc85cd7163501613">llvm::PPCISD::COND_BRANCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a7fa84f3807a868c9e48e0928e3ac7f81">llvm::PPCISD::CR6SET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a0a616f27a6f2de704ab3ed849b50b181">llvm::PPCISD::CR6UNSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a098fa0d2b0ca58b9d504edb6a164ee54">llvm::PPCISD::DYNALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ac4a20bcfe32da6eeed7334e31f358682">llvm::PPCISD::DYNAREAOFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ae1846075ba0055d16c23e95fb9069efd">llvm::PPCISD::EH_SJLJ_LONGJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a819ce93b1bf9e907128d4a48ce356a21">llvm::PPCISD::EH_SJLJ_SETJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a3f9ba00aac004b0e0ab81e7bb6e6a82f">llvm::PPCISD::EXTRACT_SPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a4d78018aab544301aaa95d949c194cb3">llvm::PPCISD::EXTRACT_VSX_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ad7cc7f9bc57ea2f3d5deb4e305c50cc3">llvm::PPCISD::EXTSWSLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ad2b0da006c4560646ac3eb561a8b73b2">llvm::PPCISD::FADDRTZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a7d46bc38a9f3de58adde307de9c5e892">llvm::PPCISD::FCFID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a7e06dc9bf94c1b690b4379bec9d64962">llvm::PPCISD::FCFIDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aea46f7cc94ac666cf413d686484ce45d">llvm::PPCISD::FCFIDU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa52f8d0b1001830d27a193285d4a7090">llvm::PPCISD::FCFIDUS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a043df81d8fc961c94e42fc8fa2c71331">llvm::PPCISD::FCTIDUZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a2a79156c141fbb0faadd358c767b906b">llvm::PPCISD::FCTIDZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a88c7793fdfe5003a35e5cac9a3527eb9">llvm::PPCISD::FCTIWUZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a2a6e33357fd46c15294432ab65adecec">llvm::PPCISD::FCTIWZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19abc3b4bb39053cdc6356a2b4cdd9fca36">llvm::PPCISD::FIRST_NUMBER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a24c65ae2b770c0b178a4c2458586b058">llvm::PPCISD::FNMSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ac9eb1f199dbf096dc303ec84b69537f0">llvm::PPCISD::FP_EXTEND_HALF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a3475aac39d7d3909ef94c56fbdfbe7a9">llvm::PPCISD::FRE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19abe7e3f85845897ad4b6270b32f8c7030">llvm::PPCISD::FRSQRTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aed93fe593cbca270b48f14bc00c5d73a">llvm::PPCISD::FSEL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a0742f4312740e5a3d92ed2dfbadc3572">llvm::PPCISD::FSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ac92e8ccc748c33e78a958b4a590abf42">llvm::PPCISD::FTSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a2c181ed9e9ec3fb57f7e8542df22f422">llvm::PPCISD::GET_TLS_ADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a8862af7d0d03a2e2689a8ea634913d96">llvm::PPCISD::GET_TLS_MOD_AIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ac0753db07d6a64f1ee53f3d31dbac379">llvm::PPCISD::GET_TLSLD_ADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ae427b9b3788c953b56cebb1dfc0e61fc">llvm::PPCISD::GET_TPOINTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a9e4500d93af7f70fdff992d9d748559d">llvm::PPCISD::GlobalBaseReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19afaa3b6d013f5589d52186fb31c1507de">llvm::PPCISD::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a8032251e5c6dfb52579250ef6373d599">llvm::PPCISD::LBRX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19af54af574e0a93231dd275e38ed4cf026">llvm::PPCISD::LD_GOT_TPREL_L</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa95297a81ed350b1df6d0e322be12e23">llvm::PPCISD::LD_SPLAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a901207ea8da185757fdf6b2f36a1a395">llvm::PPCISD::LD_VSX_LH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19af19177e57893484cb79f34527b5cd7f8">llvm::PPCISD::LFIWAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a480a6977d64df14b9af6821de3f520b9">llvm::PPCISD::LFIWZX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19abcb9c462158b362a5edc6a1d754c9edb">llvm::PPCISD::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aeff91ba7f74fec449108bf0c7bcac818">llvm::PPCISD::LOAD_VEC_BE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a21e2465b6dea8fe886e3261185e13c8d">llvm::PPCISD::LXSIZX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a9f74f2eb04440389d18aabcff035a19f">llvm::PPCISD::LXVD2X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ae507654c72e23edbb1c74349cb5cfe33">llvm::PPCISD::LXVRZX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a57dec08b9c245de78b203b5ce73a85a3">llvm::PPCISD::MAT_PCREL_ADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aea2dbb65ca28f544afc80f4665a6f82c">llvm::PPCISD::MFBHRBE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aab6a046c536c71121190fefd548d6b25">llvm::PPCISD::MFFS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a58202903ffe35789bd984f290d83e11f">llvm::PPCISD::MFOCRF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19af5896749994dc6b774ce5c9c4a64966a">llvm::PPCISD::MFVSR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa48a0d892596a0da3cf4a82c6ff5a91f">llvm::PPCISD::MTCTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a63a76994e79df471be43c2773b1d9003">llvm::PPCISD::MTVSRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a19c6996c521458ff9fa40429470e5a45">llvm::PPCISD::MTVSRZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ab0724ba8c987cd526c269d09bb5b2bf7">llvm::PPCISD::PADDI_DTPREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ac677b8b728cb9be271ba1e5c69c4a323">llvm::PPCISD::PAIR_BUILD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a6e3a9527c997e95ea74a9c377ba14add">llvm::PPCISD::PPC32_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a75da00c638a1f554457f78c4e2ef7a5c">llvm::PPCISD::PPC32_PICGOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a93beacf6ed2253988c2898d81ff02a48">llvm::PPCISD::PROBED_ALLOCA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a4fed17be029140e1e4721aedfa68fa4a">llvm::PPCISD::READ_TIME_BASE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a48f471d5b31fefcebe7a7be442b7e27e">llvm::PPCISD::RET_GLUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a25c6863bf54d5a65a55506cce743e333">llvm::PPCISD::RFEBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a2ae057e4de45c51c89b7e5dc5053df62">llvm::PPCISD::SC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a4b53fee9c411b207317f688e141e9128">llvm::PPCISD::SCALAR_TO_VECTOR_PERMUTED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a8979933cc5b3ebf6a3f6a322dfe1330c">llvm::PPCISD::SETBC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a9855b472ab773e21bafb60ffca9d4cec">llvm::PPCISD::SETBCR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a01e7f48b2ccc0aed9c6f66314b23af32">llvm::PPCISD::SEXT_LD_SPLAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a56a6aa00c6f25ef2c1f51277099a78a4">llvm::PPCISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a3cafc18814a975a06f6e8a39926700b4">llvm::PPCISD::SINT_VEC_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aad0d80bf5cf5a07b271e4357ed436f62">llvm::PPCISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ad78bb5b4a8218f88e112b72fab5d508c">llvm::PPCISD::SRA_ADDZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a1b0abca17bd696928f9399acfd3d1522">llvm::PPCISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a42f12c79832e19ec572ddd606b803756">llvm::PPCISD::ST_VSR_SCAL_INT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19af2142b68a3cab0d2f680eecbb31c76e0">llvm::PPCISD::STBRX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa71de12afd261e0b3f2e040ce1c10315">llvm::PPCISD::STFIWX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a3b16216732bca028b1c75cf3d662966a">llvm::PPCISD::STORE_COND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a1587d1d239eb39b23bdc1d173ccef453">llvm::PPCISD::STORE_VEC_BE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ac81afec4bdfa40303000449f212d7ac3">llvm::PPCISD::STRICT_FADDRTZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a07c87149008709f85754a38b4f22adaf">llvm::PPCISD::STRICT_FCFID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a746850a5fa94a4ce3e8071b6219121f6">llvm::PPCISD::STRICT_FCFIDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a72a662f3bbd13bf94bf0262ac1d4e868">llvm::PPCISD::STRICT_FCFIDU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ab58ea28e66ebad19b7718055fc998f08">llvm::PPCISD::STRICT_FCFIDUS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a8a5acab2f34e1b806efaa3ee64c5a3aa">llvm::PPCISD::STRICT_FCTIDUZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ad00a593b7d71618f307d171781f5558d">llvm::PPCISD::STRICT_FCTIDZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a553b2f3eaf318b2455673f16cb396baf">llvm::PPCISD::STRICT_FCTIWUZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a8a852db39a510adbbbadbbdede7aa648">llvm::PPCISD::STRICT_FCTIWZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a5043cfa31ad158389477a46bd7c366b4">llvm::PPCISD::STXSIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ad7ff3b99ede678baebc8e3cd79b1090a">llvm::PPCISD::STXVD2X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aeec65142befe62f016e921ebf1ab2976">llvm::PPCISD::SWAP_NO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa4dc9f480c199614ca9475c7969ead06">llvm::PPCISD::TC_RETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19af5d482f504e4591346e162e5cf33faaa">llvm::PPCISD::TLS_DYNAMIC_MAT_PCREL_ADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ab46d5355de307e34ab21c677c7c7c7db">llvm::PPCISD::TLS_LOCAL_EXEC_MAT_ADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19addcc7a7066b3355e80163ae36bdac00e">llvm::PPCISD::TLSGD_AIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a09ab315581c1b578f529f618351ee400">llvm::PPCISD::TLSLD_AIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a5ac8e8dafc2dd10379a59ceff7b237d6">llvm::PPCISD::TOC_ENTRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ae29580d04452d6ce523cc25ba9f833a2">llvm::PPCISD::UINT_VEC_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a63d10572d28760b1a149732cc760628a">llvm::PPCISD::VADD_SPLAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a43a3ad5a512466965973ac46c8239c60">llvm::PPCISD::VCMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aaa7a0554c16e55d6c686d04418d15108">llvm::PPCISD::VCMP_rec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a1ee1a9a5178726a6542ef8ab6d50fc03">llvm::PPCISD::VECINSERT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ad193a3cd768e4fb4bb4239e8bbaf6c7f">llvm::PPCISD::VECSHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ab1825d0c725f95300cef6d29474457c3">llvm::PPCISD::VEXTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19abd37e9e242507f9bcda602075a67c9dd">llvm::PPCISD::VPERM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a9ff59d0440e169de36176333f9905ec7">llvm::PPCISD::XSMAXC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa92d1e6695bd2774d420cfbf25f381b5">llvm::PPCISD::XSMINC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a93f8e78c9b32393c5190960b84dc3a57">llvm::PPCISD::XXMFACC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ab8bc34e0a04f9698bc188b3d75488d38">llvm::PPCISD::XXPERM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a5c9fa769fde0b5d1e1068e564fa14c93">llvm::PPCISD::XXPERMDI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a58495c4d013cd9851f4ab527c3548b22">llvm::PPCISD::XXSPLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a31d181189194ec87162affcc5e92b150">llvm::PPCISD::XXSPLTI32DX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ac0436a181d9ba4cb7067186d26e52f56">llvm::PPCISD::XXSPLTI_SP_TO_DP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a4156aa36da735bf4f407406f04aa9a49">llvm::PPCISD::XXSWAPD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ad423fc6dce425d3b017dea23db96a20b">llvm::PPCISD::ZEXT_LD_SPLAT</a>.</p>

</div>
</div>

### getTgtMemIntrinsic() {#a3f04233ae02eabefa03b17d72ff73601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::getTgtMemIntrinsic (<a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/intrinsicinfo">IntrinsicInfo</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;, unsigned)</td>
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

<p>Given an intrinsic, checks if on the target the intrinsic will need to map to a MemIntrinsicNode (touches memory).</p>


<p>If this is the case, it returns true and store the intrinsic information into the <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/intrinsicinfo">IntrinsicInfo</a> that was passed to the function.</p>


<p>Declaration at line 1072 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17555 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a1572b31fadbd0d758314b8d35a050410">llvm::EVT::getStoreSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda796891d6ca349b671fce24b6d01d77a8">llvm::MachineMemOperand::MOVolatile</a>.</p>

</div>
</div>

### hasAndNotCompare() {#a551288909ccbfb41e573e1f31222a605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCTargetLowering::hasAndNotCompare (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Y)</td>
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

<p>Return true if the target should transform: (X &amp; Y) == Y ---&gt; (~X &amp; Y) == 0 (X &amp; Y) != Y ---&gt; (~X &amp; Y) != 0.</p>


<p>This may be profitable if the target has a bitwise and-not operation that sets comparison flags. A target may want to limit the transformation based on the type of Y or if Y is a constant.</p>


<p>Note that the transform will not occur if Y is known to be a power-of-2 because a mask and compare of a single bit can be handled by inverting the predicate, for example: (X &amp; 8) == 8 ---&gt; (X &amp; 8) != 0</p>


<p>Definition at line 825 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>

</div>
</div>

### hasInlineStackProbe() {#a20e0ba2c46bef474e31cf8c2f9322db0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::hasInlineStackProbe (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 973 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 12982 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a4c319db4fe05c27cfe55bd133a87414d">llvm::Function::getFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a968930aea9d9efa8d46dd890fce75643">llvm::Attribute::getValueAsString</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>.</p>

</div>
</div>

### hasSPE() {#a44135eb0a79dfbd49c8235956342fcf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::hasSPE ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 798 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 1661 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#ac6cddb4c330de0e51a5977de243a3ded">PPCTargetLowering</a> and <a href="#a521dc9b8649af234d8bf514085b9a640">SelectAddressRegReg</a>.</p>

</div>
</div>

### insertSSPDeclarations() {#a6651f5dc988cb00064896052b5f7a42d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCTargetLowering::insertSSPDeclarations (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Inserts necessary declarations for SSP (stack protection) purpose.</p>


<p>Should be used only when getIRStackGuard returns nullptr.</p>


<p>Declaration at line 1146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18077 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a80083daf41bf6d643ef8e00f171955f5">AIXSSPCanaryWordName</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af3e31a71f6d0e55d41956d5b20ed7989">llvm::TargetLoweringBase::insertSSPDeclarations</a>.</p>

</div>
</div>

### isAccessedAsGotIndirect() {#af2168b4e8c9abe5efab1acc532d50feb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isAccessedAsGotIndirect (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1068 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17523 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ae106f6c6362377b3016f0d174227e193">llvm::TargetMachine::getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a>.</p>

</div>
</div>

### isCheapToSpeculateCtlz() {#a21f8412bb8c563691c11c966432f0d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCTargetLowering::isCheapToSpeculateCtlz (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Return true if it is cheap to speculate a call to intrinsic ctlz.</p>

<p>Definition at line 808 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>

</div>
</div>

### isCheapToSpeculateCttz() {#a44cdcb4d20bf8b1fdcaa0f856fd1b312}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCTargetLowering::isCheapToSpeculateCttz (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Return true if it is cheap to speculate a call to intrinsic cttz.</p>

<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>

</div>
</div>

### isCtlzFast() {#a3a0cf06e062ec0b758d186411b440d90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCTargetLowering::isCtlzFast ()</td>
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

<p>Return true if ctlz instruction is fast.</p>

<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>

</div>
</div>

### isDesirableToTransformToIntegerOp() {#aa6ccf4330a7bedc48475a8ec562fe5ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCTargetLowering::isDesirableToTransformToIntegerOp (unsigned, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
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

<p>Return true if it is profitable for dag combiner to transform a floating point op of specified opcode to a equivalent op of an integer type.</p>


<p>e.g. f32 load -&gt; i32 load can be profitable on <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a>.</p>


<p>Definition at line 1055 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>.</p>

</div>
</div>

### isEqualityCmpFoldedWithSignedCmp() {#aaa3913c1ef2c5af7a66a953752888f67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCTargetLowering::isEqualityCmpFoldedWithSignedCmp ()</td>
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

<p>Return true if instruction generated for equality comparison is folded with instruction generated for signed comparison.</p>

<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>

</div>
</div>

### isFMAFasterThanFMulAndFAdd() {#ad357707a4ab97832b2f9ad24490b4376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isFMAFasterThanFMulAndFAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>isFMAFasterThanFMulAndFAdd - Return true if an FMA operation is faster than a pair of fmul and fadd instructions.</p>


<p>fmuladd intrinsics will be expanded to FMAs when this method returns true, otherwise fmuladd is expanded to fmul + fadd.</p>


<p>Declaration at line 1093 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17868 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab0cfceeb37508e56f9c127e59766a668">llvm::EVT::getTypeForEVT</a> and <a href="#ad357707a4ab97832b2f9ad24490b4376">isFMAFasterThanFMulAndFAdd</a>.</p>


<p>Referenced by <a href="#ad357707a4ab97832b2f9ad24490b4376">isFMAFasterThanFMulAndFAdd</a> and <a href="#a857dba88c2223d0a509b5d390f7144f0">isProfitableToHoist</a>.</p>

</div>
</div>

### isFMAFasterThanFMulAndFAdd() {#aa2ae7a06e074fcc6e88720bdaeeb1460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isFMAFasterThanFMulAndFAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *)</td>
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

<p>IR version.</p>

<p>Declaration at line 1096 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17874 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaaf645dbe1647a41fce26595aa8cd8bdfc">llvm::Type::FP128TyID</a>.</p>

</div>
</div>

### isFPExtFree() {#a19198578d08502db0acb9cd75ccbcae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isFPExtFree (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> DestVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SrcVT)</td>
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

<p>Return true if an fpext operation is free (for instance, because single-precision floating-point numbers are implicitly extended to double-precision).</p>

<p>Declaration at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17786 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#a3cb888a2ce8e95e0d9769687a5e2f7d8">llvm::EVT::isFloatingPoint</a>.</p>

</div>
</div>

### isFPImmLegal() {#a90186243528cfcd7b02837f130da5de2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isFPImmLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>, bool ForCodeSize)</td>
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

<p>Returns true if the target can instruction select the specified FP immediate natively.</p>


<p>If false, the legalizer will materialize the FP immediate as a load from a constant pool.</p>


<p>Declaration at line 1149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18093 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a482d9cf95b588eb05cefeaa5c05be9a3">llvm::APFloatBase::rmTowardZero</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>

</div>
</div>

### isJumpTableRelative() {#adf6c939e7121ecf6c9339ef40eb8bbde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isJumpTableRelative ()</td>
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



<p>Declaration at line 1153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a88a3d24891c523c6a8646c4a4ea87502">llvm::TargetLoweringBase::isJumpTableRelative</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a8486eb6b484e597fa39976e4b191daa5">UseAbsoluteJumpTables</a>.</p>


<p>Referenced by <a href="#a76ee5e788bf1969bd98f670b3471a12b">getJumpTableEncoding</a>.</p>

</div>
</div>

### isLegalAddImmediate() {#aff5e1ccebed969088d63237834e19817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isLegalAddImmediate (int64_t Imm)</td>
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

<p>isLegalAddImmediate - Return true if the specified immediate is legal add immediate, that is the target has add instructions which can add a register and the immediate without having to materialize the immediate into a register.</p>

<p>Declaration at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17799 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### isLegalAddressingMode() {#a7747bd26b2eea5f7c32012e5dcdbd61a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isLegalAddressingMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode">AddrMode</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned AS, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
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

<p>isLegalAddressingMode - Return true if the addressing mode represented by AM is legal for this target, for a load/store of the specified type.</p>

<p>Declaration at line 1017 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17384 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a2d775e3fd8ebcd0941d1e12cbfccda3d">llvm::TargetLoweringBase::AddrMode::BaseGV</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a115ffe6d615735fbe8b1bf31877565ba">llvm::TargetLoweringBase::AddrMode::BaseOffs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8868c35de6c36dc0d57e84f256c4ffde">llvm::TargetLoweringBase::AddrMode::HasBaseReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8ea7d02f0e4b0c1d37d6986ec9f7f5c0">llvm::TargetLoweringBase::AddrMode::Scale</a>.</p>

</div>
</div>

### isLegalICmpImmediate() {#aeda0b757f19cd0c67deb589e0ce0cdb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isLegalICmpImmediate (int64_t Imm)</td>
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

<p>isLegalICmpImmediate - Return true if the specified immediate is legal icmp immediate, that is the target has icmp instructions which can compare a register against the immediate without having to materialize the immediate into a register.</p>

<p>Declaration at line 1025 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17795 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### isOffsetFoldingLegal() {#a26daafd86d9f5f03a8963dcc9e9b5804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isOffsetFoldingLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * GA)</td>
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

<p>Return true if folding a constant offset with the given GlobalAddress is legal.</p>


<p>It is frequently not legal in PIC relocation models.</p>


<p>Declaration at line 1070 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17550 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### isProfitableToHoist() {#a857dba88c2223d0a509b5d390f7144f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isProfitableToHoist (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>isProfitableToHoist - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if it is profitable to hoist instruction <span class="doxyComputerOutput">I</span> to its dominator block.</p>


<p>For example, it is not profitable if <span class="doxyComputerOutput">I</span> and it's only user can form a FMA instruction, because Powerpc prefers FMADD.</p>


<p>Declaration at line 1102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17890 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fpopfusion/#a9c71bae9f02af273833fde586d529fc5aa9dfaae1f5b7d4ebb31ccf9aee1aacce">llvm::FPOpFusion::Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a126c61d55fb4d2e509537ce68e8b6400">llvm::TargetLoweringBase::getValueType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad357707a4ab97832b2f9ad24490b4376">isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa93fbbc66d52a51d178af8ac4398ec05">llvm::TargetLoweringBase::isOperationLegalOrCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#ac072f8698be17d52f20bb63d59e6ce41">llvm::LoadInst::isUnordered</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

### isSelectSupported() {#a3e60bf8e76e27b02eaccac58a62993f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCTargetLowering::isSelectSupported (<a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a575e134a5e8414029a5c4a284858e6cd">SelectSupportKind</a> Kind)</td>
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



<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a575e134a5e8414029a5c4a284858e6cda14714058f9e9eb27b0a4ec62d23bddd5">llvm::TargetLoweringBase::ScalarCondVectorVal</a>.</p>

</div>
</div>

### isTruncateFree() {#a0c9601934baa227ce802de96110b47bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isTruncateFree (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty1, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty2)</td>
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

<p>isTruncateFree - Return true if it's free to truncate a value of type Ty1 to type Ty2.</p>


<p>e.g. On <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> it's free to truncate a i64 value in register X1 to i32 by referencing its sub-register R1.</p>


<p>Declaration at line 1036 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17750 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>.</p>

</div>
</div>

### isTruncateFree() {#af075f198cd750d859857bb7b87544931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isTruncateFree (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT1, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT2)</td>
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



<p>Declaration at line 1037 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17758 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a>.</p>

</div>
</div>

### isZExtFree() {#a2d0ce4ee513f57d110efb8247ea59afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isZExtFree (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT2)</td>
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

<p>Return true if zero-extending the specific node Val to type VT2 is free (either because it's implicitly zero-extended such as <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> ldrb / ldrh or because it's folded such as <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> zero-extending loads).</p>

<p>Declaration at line 1039 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17766 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a342be90695496b88a8854a775dfd030f">llvm::TargetLoweringBase::isZExtFree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6aacde2c67988b43a261a7f7ceac4be3">llvm::ISD::NON_EXTLOAD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>

</div>
</div>

### LowerAsmOperandForConstraint() {#a46ae06ee635d7e06d852c36093a4d20e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCTargetLowering::LowerAsmOperandForConstraint (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>LowerAsmOperandForConstraint - Lower the specified operand into the Ops vector.</p>


<p>If it is invalid, don't add anything to Ops.</p>


<p>Declaration at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a75d113cb1b8cc3c14b601d928dccee40">llvm::ConstantSDNode::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ad3f2eb78e627fd0d785fd4119d299558">llvm::TargetLowering::LowerAsmOperandForConstraint</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### LowerOperation() {#ae03fd553a0f5e640324a7cdddbffb6b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerOperation (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>LowerOperation - Provide custom lowering hooks for some operations.</p>

<p>Declaration at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 12103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af7bfad446dfd85837fe7ff904ebb1aff">llvm::ISD::ADJUST_TRAMPOLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9c91befeca2a25c8050d4c3dff8b6d67">llvm::ISD::ATOMIC_CMP_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1db943abc1bf78a911daeb7b03d81de8">llvm::ISD::ATOMIC_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa71ac22470bf853868fe6b39a25bac72">llvm::ISD::DYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abad932e63381a4671b5db19a3404c82e">llvm::ISD::EH_DWARF_CFA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a122a450e069003dc86859ef47ab6e278">llvm::ISD::EH_SJLJ_LONGJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae5a57fe9fd413df909ab121ca1a813c7">llvm::ISD::EH_SJLJ_SETJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9133d7cfb6a66404ff7757b699bc3941">llvm::ISD::FCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad49a46d391f73aa96002adbdd0cf03f5">llvm::ISD::FEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac82d37f93ae4420659acdd03f79b15e0">llvm::ISD::FLOG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0d05d4a5cd10a46f69f9e62d49d275bb">llvm::ISD::FLOG10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1a6952b1572a4ce241cc3cf45a9ab071">llvm::ISD::FPOW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdb38c8daa8c1ab881007062d113cef3">llvm::ISD::FRAMEADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a822b0d02b601898e2d6db5b39e12cc8a">llvm::ISD::FSHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a874350de5b4f6b8f4db13940e17ed81b">llvm::ISD::FSHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad46ae9fdfe20cd04f7fda7ccbb937543">llvm::ISD::FSIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af5caa395d199fab7e52a63feb73dcb10">llvm::ISD::GET_DYNAMIC_AREA_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89f3afc3fa907ff83759c6c76d97a973">llvm::ISD::GET_ROUNDING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4534a6db2862a28324932a8ea1cb54d6">llvm::ISD::INIT_TRAMPOLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae35d57f3c020672748fcc95607348986">llvm::ISD::INLINEASM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab969e7d43eb37a0398b5ded23bccc136">llvm::ISD::INLINEASM_BR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a76b6d3008e806ea613323ff316ef72c3">llvm::ISD::IS_FPCLASS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0c70100db6ddc0b37b56feb242145cf4">llvm::ISD::JumpTable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2dfacb29792dd59f2cfbe529206265bc">llvm::ISD::RETURNADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4fe6c878350458de2c3182392f830988">llvm::ISD::SET_ROUNDING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6efe16ea597cfd8eeac26516fc992ee7">llvm::ISD::SSUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a023a9de787026fe61b024476bf9c32cb">llvm::ISD::STACKRESTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2273d9cd04ba6e4a7c1a4b28ab1aaba">llvm::ISD::STRICT_FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed">llvm::ISD::STRICT_FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf955b4b70f63865e022c329d1775579">llvm::ISD::STRICT_FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0466b21bfb4f3596e41380d8e2d1956f">llvm::ISD::STRICT_FSETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c8d07d668872f2176fb34724cd799c4">llvm::ISD::STRICT_FSETCCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab38d2af541b99492acf69c041c98bcb6">llvm::ISD::STRICT_SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a56735332b7dc26b4e164035831fb40ab">llvm::ISD::STRICT_UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1ddf36330110b4abea43fe390bea9ef9">llvm::ISD::UADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae77d03846b31c41c4860bcd96d780a78">llvm::ISD::VAARG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a804c1960ac64628cdd1f74d7de885284">llvm::ISD::VACOPY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adfe32beaa596a1512b17e66b46e773ed">llvm::ISD::VASTART</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a>.</p>

</div>
</div>

### PerformDAGCombine() {#ab4ccdcee4c7a2e0892715d0a8094b86e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::PerformDAGCombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
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

<p>This method will be invoked for all target nodes and for any target-independent nodes that the target has registered with invoke it for.</p>


<p>The semantics are as follows: Return <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>: SDValue.Val == 0 - No change was made SDValue.Val == N - N was replaced, is dead, and is already handled. otherwise - N should be replaced by the returned Operand.</p>


<p>In addition, methods provided by <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> may be used to perform more complex transformations.</p>


<p>Declaration at line 904 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 16134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a35c1cf0dd553444732dba8e8b9be0f6b">llvm::ISD::ABS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3ad406477784397709a339d5a2957b43">llvm::EVT::bitsGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5be7fb35e0f523af6c939fba303403df">llvm::ISD::BR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb">llvm::ISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a41bd84b853e2c03fb1af1f4ca9ebdcaf">llvm::ISD::BUILD_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a7b41ee83365bacbeb6829da71fd2331d">BuildIntrinsicOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#adff1fcbcf8e82995a72f1efd2d62ec11">llvm::TargetLowering::DAGCombinerInfo::CombineTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd6aa057934751aaac54e5c18bcc18eb">llvm::commonAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a0992940624286ed6bc85cd7163501613">llvm::PPCISD::COND_BRANCH</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#acf37bd7e831bdb2a5c9da8d63f843101">llvm::TargetLowering::DAGCombinerInfo::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a414d9dfa6f85f8ad371a510821713e61">expandVSXLoadForLE</a>, <a href="#abf2cd323dcdc4b2b0a4741c62b30d0ba">expandVSXStoreForLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1e2f76e32afeff50a4cae3055b365099">findConsecutiveLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a24c65ae2b770c0b178a4c2458586b058">llvm::PPCISD::FNMSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a800e74bec9b78d6739665027c3616a55">llvm::DataLayout::getABITypeAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6e64fef2ad2ba4052cd8365e97e8d2">llvm::SDNode::getAsZExtVal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab85f5fcb2f3bb0aaf83041a41182a2d4">llvm::SelectionDAG::getIntPtrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6cc63109335eefe2c5727d1e12fc820">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#af6fe41bd1c6914242c20b4917de0d3f4">llvm::SDValue::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#acbcc973a299b6f8733774668210b5227">llvm::SDValue::getSimpleValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a1572b31fadbd0d758314b8d35a050410">llvm::EVT::getStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab0cfceeb37508e56f9c127e59766a668">llvm::EVT::getTypeForEVT</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac0a534d63ac5c5b87f36acdade953fbe">llvm::SDNode::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#ac06076876542c9f3f22c47f36c2edb9d">getVectorCompareInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad0c6f059b29535f2c790d1c4f92b7a93">llvm::SelectionDAG::getZExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ad82ad170343d0b4fe88a5551ec43659d">llvm::SDNode::hasNUsesOfValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a295d0b84f4e63438c0edb0021c41d47a">llvm::SDNode::hasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#a2030eb1014aca2732ca4ecfb9ae4b5a0">llvm::TargetLowering::DAGCombinerInfo::isAfterLegalizeDAG</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#ac79f060cd8d4b63fc6d682c076cbeec0">llvm::TargetLowering::DAGCombinerInfo::isBeforeLegalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#aaac3e239cbdfe15a8e9bad4f8e1e3a95">llvm::ISD::isBuildVectorAllZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a6f89a07c015a54253416b726e352bdc4">llvm::BuildVectorSDNode::isConstantSplat</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abda309a31acb43c06215c1772727bf1c">llvm::EVT::isExtended</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a15623094a1ed0cd7163dc786e44c87c9">llvm::ISD::isNON_EXTLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#afaaeadcd82b42fc0d385a6247bf7bb52">llvm::ISD::isNormalLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a308088c2d65f8f3955f5fb0f6aca7ccc">llvm::ISD::isNormalStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a86775f3d85d98a31b2751e1eb348ea">llvm::isNullConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a72e897dd9e9942885e377bfdc0fb746c">isStoreConditional</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a8032251e5c6dfb52579250ef6373d599">llvm::PPCISD::LBRX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad5386f4196a9eab5701c451469f2e20e">llvm::SelectionDAG::MaskedValueIsZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a58202903ffe35789bd984f290d83e11f">llvm::PPCISD::MFOCRF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6aacde2c67988b43a261a7f7ceac4be3">llvm::ISD::NON_EXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31ab5bb854fadd42503c849c4a48d7f3d90">llvm::ISD::PRE_INC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355a34be5288a1bb24e5120358395f7f0dc3">llvm::PPC::PRED_EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355a44abec85091b571da2189ac4bd139095">llvm::PPC::PRED_GE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355a46cd6e935d7b9cc679d9cb0cf025ae91">llvm::PPC::PRED_LT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355ad9add708b3d9680d64242cf06f448462">llvm::PPC::PRED_NE</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac630ccda26fea2f45afa3fb89bc1a8f4">llvm::SelectionDAG::ReplaceAllUsesOfValueWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715">llvm::ISD::ROTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a56a6aa00c6f25ef2c1f51277099a78a4">llvm::PPCISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aad0d80bf5cf5a07b271e4357ed436f62">llvm::PPCISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a1b0abca17bd696928f9399acfd3d1522">llvm::PPCISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19af2142b68a3cab0d2f680eecbb31c76e0">llvm::PPCISD::STBRX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a3b16216732bca028b1c75cf3d662966a">llvm::PPCISD::STORE_COND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed">llvm::ISD::STRICT_FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf955b4b70f63865e022c329d1775579">llvm::ISD::STRICT_FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae8c041f67463ea67d6c43867729b82cb">llvm::SelectionDAG::UpdateNodeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a9450817c42562fe06198b67be72a24ac">llvm::SDNode::use_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#aef02f2c1bd12936a80611b134b24a47d">llvm::SDNode::use_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ae04dc684fcd3d20b890bbf44e4a28395">llvm::SDNode::user_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ad5596cf1822f4cc9e37fb75b6dff630f">llvm::SDNode::users</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a43a3ad5a512466965973ac46c8239c60">llvm::PPCISD::VCMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aaa7a0554c16e55d6c686d04418d15108">llvm::PPCISD::VCMP_rec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### preferIncOfAddToSubOfNot() {#a79450c12a2b980587b2b71d175b15f11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::preferIncOfAddToSubOfNot (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>These two forms are equivalent: sub y, (xor x, -1) add (add x, 1), y The variant with two add's is IR-canonical.</p>


<p>Some targets may prefer one to the other.</p>


<p>Declaration at line 829 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 1665 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#ad958859a7af278dd5ea2b593c2b25050">llvm::EVT::isScalarInteger</a>.</p>

</div>
</div>

### ReplaceNodeResults() {#a49eedef79b249eb098470debb9601eb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCTargetLowering::ReplaceNodeResults (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>ReplaceNodeResults - Replace the results of node with an illegal result type with new values built out of custom code.</p>

<p>Declaration at line 898 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 12202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c47226f266248f4b8c155b83601b109">llvm::ISD::ATOMIC_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a41bd84b853e2c03fb1af1f4ca9ebdcaf">llvm::ISD::BUILD_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a822b0d02b601898e2d6db5b39e12cc8a">llvm::ISD::FSHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a874350de5b4f6b8f4db13940e17ed81b">llvm::ISD::FSHR</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="#aea8d3912f4a0d003d32577f1098a8b44">getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a4fed17be029140e1e4721aedfa68fa4a">llvm::PPCISD::READ_TIME_BASE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac43f9bea13e29622bbf18c861b52144d">llvm::ISD::READCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed">llvm::ISD::STRICT_FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf955b4b70f63865e022c329d1775579">llvm::ISD::STRICT_FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae77d03846b31c41c4860bcd96d780a78">llvm::ISD::VAARG</a>.</p>

</div>
</div>

### SelectAddressEVXRegReg() {#aec3b0201c5cd00acf45cc4eb33708687}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::SelectAddressEVXRegReg (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SelectAddressEVXRegReg - Given the specified addressed, check to see if it can be more efficiently represented as [r+imm].</p>


<p>SelectAddressEVXRegReg - Given the specified address, check to see if it can be represented as an indexed [r+r] operation.</p>


<p>Declaration at line 858 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2693 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a521dc9b8649af234d8bf514085b9a640">SelectAddressRegReg</a>.</p>

</div>
</div>

### SelectAddressPCRel() {#ae882b4864ba6e86e417710e0b990b6d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::SelectAddressPCRel (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SelectAddressPCRel - Represent the specified address as pc relative to be represented as [pc+imm].</p>


<p>Returns true if this address is a PC Relative address.</p>


<p>PC Relative addresses are marked with the flag <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffa777b254f8a19bf466553840f89ecaf31">PPCII::MO_PCREL_FLAG</a> or if the node opcode is <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a57dec08b9c245de78b203b5ce73a85a3">PPCISD::MAT_PCREL_ADDR</a>.</p>


<p>Declaration at line 887 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3011 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#afa8da6f68560141aad9b3bb3e333a2c3">isValidPCRelNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a57dec08b9c245de78b203b5ce73a85a3">llvm::PPCISD::MAT_PCREL_ADDR</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a312de8232fec3e0e128f4a34b7ddc55d">SelectAddressRegImm</a> and <a href="#a521dc9b8649af234d8bf514085b9a640">SelectAddressRegReg</a>.</p>

</div>
</div>

### SelectAddressRegImm() {#a312de8232fec3e0e128f4a34b7ddc55d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::SelectAddressRegImm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> EncodingAlignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SelectAddressRegImm - Returns true if the address N can be represented by a base register plus a signed 16-bit displacement [r+imm], and if it is not better represented as reg+reg.</p>


<p>Returns true if the address N can be represented by a base register plus a signed 16-bit displacement [r+imm], and if it is not better represented as reg+reg.</p>


<p>If <span class="doxyComputerOutput">EncodingAlignment</span> is non-zero, only accept displacements suitable for instruction encoding requirement, i.e. multiples of 4 for DS form.</p>


<p>If <span class="doxyComputerOutput">EncodingAlignment</span> is non-zero, only accept displacements that are multiples of that value.</p>


<p>Declaration at line 874 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2819 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aa45779e6cfae9dac4c65a6aa4bbdab74">fixupFuncForFI</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c04c72abd24de2572a03ef686a36dd6">llvm::SelectionDAG::getMachineNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7fc96403de39ca28a30bf2a4a38b113f">llvm::SelectionDAG::getSignedTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6ececde40ed933c2dfb5af16cb002529">llvm::SelectionDAG::getTargetFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac0a534d63ac5c5b87f36acdade953fbe">llvm::SDNode::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25f1d7ccf87af8d87fcb950f7ed758b5">llvm::isAligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a267dbd8fce711ee4a1adc8ee2b42fa0a">llvm::isIntS16Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19abcb9c462158b362a5edc6a1d754c9edb">llvm::PPCISD::Lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="#ae882b4864ba6e86e417710e0b990b6d6">SelectAddressPCRel</a>, <a href="#a521dc9b8649af234d8bf514085b9a640">SelectAddressRegReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a038a7f124b4118456a27a739c03650bf">llvm::ISD::TargetConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a87b8176af163ee944af127081d24f4a2">llvm::ISD::TargetGlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc9ad7857b7faf49dcde3dcf434e22a6">llvm::ISD::TargetGlobalTLSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a603c0651ff8c3a929c5e1d8b9a8f14cb">llvm::ISD::TargetJumpTable</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>


<p>Referenced by <a href="#a7e08a461c58c82e0564d2cd25c6d9990">getPreIndexedAddressParts</a>.</p>

</div>
</div>

### SelectAddressRegImm34() {#adaf95509430b29d867f49362e176027d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::SelectAddressRegImm34 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to the 16-bit case but for instructions that take a 34-bit displacement field (prefixed loads/stores).</p>

<p>Declaration at line 877 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2924 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7fc96403de39ca28a30bf2a4a38b113f">llvm::SelectionDAG::getSignedTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6ececde40ed933c2dfb5af16cb002529">llvm::SelectionDAG::getTargetFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ee9da8b28b365034ec4d2be17184ba7">llvm::isIntS34Immediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>

</div>
</div>

### SelectAddressRegReg() {#a521dc9b8649af234d8bf514085b9a640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::SelectAddressRegReg (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> EncodingAlignment=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SelectAddressRegReg - Given the specified addressed, check to see if it can be more efficiently represented as [r+imm].</p>


<p>SelectAddressRegReg - Given the specified addressed, check to see if it can be represented as an indexed [r+r] operation.</p>


<p>If <span class="doxyComputerOutput">EncodingAlignment</span> is non-zero, only accept displacement which is not suitable for [r+imm]. Returns false if it can be represented by [r+imm], which are preferred.</p>


<p>Returns false if it can be more efficiently represented as [r+imm]. If <span class="doxyComputerOutput">EncodingAlignment</span> is non-zero and N can be represented by a base register plus a signed 16-bit displacement, make a more precise judgement by checking (displacement % <span class="doxyComputerOutput">EncodingAlignment</span>).</p>


<p>Declaration at line 865 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2728 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac0e942dde4b113c4c0b1fd76333db93a">llvm::APInt::getBoolValue</a>, <a href="#a44135eb0a79dfbd49c8235956342fcf7">hasSPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25f1d7ccf87af8d87fcb950f7ed758b5">llvm::isAligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a267dbd8fce711ee4a1adc8ee2b42fa0a">llvm::isIntS16Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19abcb9c462158b362a5edc6a1d754c9edb">llvm::PPCISD::Lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="#aec3b0201c5cd00acf45cc4eb33708687">SelectAddressEVXRegReg</a>, <a href="#ae882b4864ba6e86e417710e0b990b6d6">SelectAddressPCRel</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>


<p>Referenced by <a href="#a7e08a461c58c82e0564d2cd25c6d9990">getPreIndexedAddressParts</a>, <a href="#a312de8232fec3e0e128f4a34b7ddc55d">SelectAddressRegImm</a> and <a href="#a5dc501f0601464ff8459b49b60b29140">SelectAddressRegRegOnly</a>.</p>

</div>
</div>

### SelectAddressRegRegOnly() {#a5dc501f0601464ff8459b49b60b29140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::SelectAddressRegRegOnly (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SelectAddressRegRegOnly - Given the specified addressed, force it to be represented as an indexed [r+r] operation.</p>

<p>Declaration at line 882 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 2973 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a267dbd8fce711ee4a1adc8ee2b42fa0a">llvm::isIntS16Immediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a521dc9b8649af234d8bf514085b9a640">SelectAddressRegReg</a>.</p>

</div>
</div>

### SelectForceXFormMode() {#a19ee5344b14a547e1ede7370b62402ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPC::AddrMode PPCTargetLowering::SelectForceXFormMode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SelectForceXFormMode - Given the specified address, force it to be represented as an indexed [r+r] operation (an XForm instruction).</p>

<p>Declaration at line 1169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18801 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcdaaac3056a5c906602555ed94a3636077c">llvm::PPC::AM_XForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a267dbd8fce711ee4a1adc8ee2b42fa0a">llvm::isIntS16Immediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a3c48cdb4fcbd71e51a4ec4c1d5c6a99a">provablyDisjointOr</a>.</p>

</div>
</div>

### SelectOptimalAddrMode() {#ae058898e63ec72af7e4ed9b50ac8fbec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPC::AddrMode PPCTargetLowering::SelectOptimalAddrMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Align)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SelectOptimalAddrMode - Based on a node N and it's Parent (a <a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a>), compute the address flags of the node, get the optimal address mode based on the flags, and set the Base and Disp based on the address mode.</p>

<p>Declaration at line 1163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18979 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcda14463e6ffd7cc9fd0b93c79fe4856931">llvm::PPC::AM_DForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcda40a73e5d0d8196bfe33b2866c06d870d">llvm::PPC::AM_DQForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcdafbe45acde65a4870e22102ab63f4643c">llvm::PPC::AM_DSForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcda319ec6c4a7dda0fbaf3b177aa1dd57a5">llvm::PPC::AM_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcdab748f1b6c866a08f2b1e5a2216e8e73d">llvm::PPC::AM_PCRel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcda5615f105433d37ceb5557243c2ff09cb">llvm::PPC::AM_PrefixDForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcdaaac3056a5c906602555ed94a3636077c">llvm::PPC::AM_XForm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aa45779e6cfae9dac4c65a6aa4bbdab74">fixupFuncForFI</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6e64fef2ad2ba4052cd8365e97e8d2">llvm::SDNode::getAsZExtVal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c04c72abd24de2572a03ef686a36dd6">llvm::SelectionDAG::getMachineNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7fc96403de39ca28a30bf2a4a38b113f">llvm::SelectionDAG::getSignedTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6ececde40ed933c2dfb5af16cb002529">llvm::SelectionDAG::getTargetFrameIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25f1d7ccf87af8d87fcb950f7ed758b5">llvm::isAligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a267dbd8fce711ee4a1adc8ee2b42fa0a">llvm::isIntS16Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ee9da8b28b365034ec4d2be17184ba7">llvm::isIntS34Immediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a4bbe57bdaf29b707d8015c6268016aaa">isPCRelNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80ad344a01b52e5179abac75ab1b8dd1206">llvm::PPC::MOF_AddrIsSImm32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80ad559259939478cfc1e6b96bffd48e984">llvm::PPC::MOF_RPlusLo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80a3d549266ccdcd583d15c88dfaa9e7e4a">llvm::PPC::MOF_RPlusSImm16</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a853a1693caf74a6f250655800e136595">setXFormForUnalignedFI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a038a7f124b4118456a27a739c03650bf">llvm::ISD::TargetConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a87b8176af163ee944af127081d24f4a2">llvm::ISD::TargetGlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc9ad7857b7faf49dcde3dcf434e22a6">llvm::ISD::TargetGlobalTLSAddress</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a603c0651ff8c3a929c5e1d8b9a8f14cb">llvm::ISD::TargetJumpTable</a>.</p>

</div>
</div>

### shallExtractConstSplatVectorElementToStore() {#aa20f41b6ac6a667d8b4c16973fc7196e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::shallExtractConstSplatVectorElementToStore (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * VectorTy, unsigned ElemSizeInBits, unsigned &amp; Index)</td>
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

<p>Return true if the target shall perform extract vector element and store given that the vector is known to be splat of constant.</p>


<p><span class="doxyComputerOutput">Index</span>[out] gives the index of the vector element to be extracted when this is true.</p>


<p>Declaration at line 813 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 1669 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### shouldConvertConstantLoadToIntImm() {#a7a61d6d5c09da51b4448488e38bd90b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::shouldConvertConstantLoadToIntImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Returns true if it is beneficial to convert a load of a constant to just the constant itself.</p>

<p>Declaration at line 1045 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17742 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### shouldExpandAtomicCmpXchgInIR() {#acf15eefe45c9e2c4a90a40a7a9a779f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AtomicExpansionKind PPCTargetLowering::shouldExpandAtomicCmpXchgInIR (<a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst">AtomicCmpXchgInst</a> * AI)</td>
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

<p>Returns how the given atomic cmpxchg should be expanded by the IR-level AtomicExpand pass.</p>

<p>Declaration at line 935 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 19149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a13c9a4cc2733456213b8eab8511cd568">llvm::AtomicCmpXchgInst::getNewValOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84ae8e80c2bf991369add363ad75aa12137">llvm::TargetLoweringBase::MaskedIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9638f2649a117b559c3a3ebbe4e07cdf">llvm::TargetLoweringBase::shouldExpandAtomicCmpXchgInIR</a>, <a href="#aff42b7a0251319665ac35b24de49a9f3">shouldInlineQuadwordAtomics</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### shouldExpandAtomicRMWInIR() {#a5047a95accb91898b9135182491d547c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AtomicExpansionKind PPCTargetLowering::shouldExpandAtomicRMWInIR (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * RMW)</td>
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

<p>Returns how the IR-level AtomicExpand pass should expand the given AtomicRMW, if at all.</p>


<p>Default is to never expand.</p>


<p>Declaration at line 932 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 19130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a369f472273bc816735055f13a6e6fd6c">llvm::TargetLoweringBase::CmpXChg</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a99fd4ef84981d6a2774c14c741b5ed65">llvm::AtomicRMWInst::getOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84ae8e80c2bf991369add363ad75aa12137">llvm::TargetLoweringBase::MaskedIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acbe42d1632a205dcd01568e46caee587">llvm::TargetLoweringBase::shouldExpandAtomicRMWInIR</a>, <a href="#aff42b7a0251319665ac35b24de49a9f3">shouldInlineQuadwordAtomics</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615ad3ed1a8c334bc3a50d59aaa57ee9e9f3">llvm::AtomicRMWInst::UDecWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a9334c9815ddc2b25804c6c03b68cc39b">llvm::AtomicRMWInst::UIncWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a0f94e2ef083268e45d22a220f92567a4">llvm::AtomicRMWInst::USubCond</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a7bf1abb23eccced685c706917aff605c">llvm::AtomicRMWInst::USubSat</a>.</p>

</div>
</div>

### shouldExpandBuildVectorWithShuffles() {#ad6a695102bd6d1036b8c1e5f5dcdf815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::shouldExpandBuildVectorWithShuffles (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, unsigned DefinedValues)</td>
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



<p>Declaration at line 1108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a130f9b8849c55cb78a279fc3b05e55e9">llvm::TargetLoweringBase::shouldExpandBuildVectorWithShuffles</a>.</p>

</div>
</div>

### shouldInlineQuadwordAtomics() {#aff42b7a0251319665ac35b24de49a9f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::shouldInlineQuadwordAtomics ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 929 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 19125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#a683761fbb11ed0969edf7eee08b08bf3">emitMaskedAtomicCmpXchgIntrinsic</a>, <a href="#a0e0d3c023e19c20fbf01b40d36aced80">emitMaskedAtomicRMWIntrinsic</a>, <a href="#ac6cddb4c330de0e51a5977de243a3ded">PPCTargetLowering</a>, <a href="#acf15eefe45c9e2c4a90a40a7a9a779f3">shouldExpandAtomicCmpXchgInIR</a> and <a href="#a5047a95accb91898b9135182491d547c">shouldExpandAtomicRMWInIR</a>.</p>

</div>
</div>

### shouldInsertFencesForAtomic() {#a35b2d5bd709014ea612750859328b7f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCTargetLowering::shouldInsertFencesForAtomic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Whether <a href="/web-llvm/docs/api/classes/llvm/atomicexpandpass">AtomicExpandPass</a> should automatically insert fences and reduce ordering for this atomic.</p>


<p>This should be true for most architectures with weak memory ordering. Defaults to false.</p>


<p>Definition at line 920 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### shouldKeepZExtForFP16Conv() {#ad343d343b05ea16280e147de626fa46d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCTargetLowering::shouldKeepZExtForFP16Conv ()</td>
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

<p>Does this target require the clearing of high-order bits in a register passed to the fp16 to fp conversion library function.</p>

<p>Definition at line 1112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>

</div>
</div>

### splitValueIntoRegisterParts() {#a468544509fb441c63f6f75f53470cf30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::splitValueIntoRegisterParts (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> * Parts, unsigned NumParts, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> PartVT, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> &gt; CC)</td>
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

<p>Target-specific splitting of values into parts that fit a register storing a legal type.</p>

<p>Declaration at line 1172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18835 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### supportsTailCallFor() {#a263f69437421410a39c26e0be576f028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::supportsTailCallFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 5876 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a7477aafbbe989ad35b96fac186d8e9fd">llvm::Function::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#afac5b39bcbb90d660f83d9b4bd8c6d95">llvm::CallBase::getCaller</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a3ff92cec76009e859cb0c419d6e8ba5f">llvm::CallBase::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a3275c50993afaf4fdd723640c2c3ca0f">llvm::Function::getDataLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a175f10e8ec1c2ec4fa24431ac5429a36">llvm::GetReturnInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#acdd05db170cbfee8a0fcbc047b8504e5">llvm::Function::getReturnType</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#af457a58a84b500d44feb7b699aa43ec1">llvm::Function::isVarArg</a>.</p>

</div>
</div>

### useLoadStackGuardNode() {#ad022667ae203c4c91fca45e3c9f568d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::useLoadStackGuardNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Override to support customized stack guard loading.</p>

<p>Declaration at line 1145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18069 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ad2b27b633b21a362571660ad09273d52">llvm::TargetLowering::useLoadStackGuardNode</a>.</p>

</div>
</div>

### useSoftFloat() {#a61d752ab70921f29e5c50f5fb75b8c0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::useSoftFloat ()</td>
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



<p>Declaration at line 796 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 1657 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#ac6cddb4c330de0e51a5977de243a3ded">PPCTargetLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### CanLowerReturn() {#ae89d61c3eda49c3dae51dc844aadf8fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::CanLowerReturn (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy)</td>
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

<p>This hook should be implemented to check whether the return values described by the Outs array can fit into the return registers.</p>


<p>If false is returned, an sret-demotion is performed.</p>


<p>Declaration at line 1373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 7874 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### canReuseLoadAddress() {#a3860fc984ea7a7eb779e6c13368dceeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::canReuseLoadAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> MemVT, ReuseLoadInfo &amp; RLI, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7">ISD::LoadExtType</a> ET=<a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6aacde2c67988b43a261a7f7ceac4be3">ISD::NON_EXTLOAD</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### combineADD() {#a4484a2395677aedc94a5b65a720bb59e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::combineADD (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1440 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### combineElementTruncationToVectorTruncation() {#a66527d30bb7389dd1319f0f13af9209d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::combineElementTruncationToVectorTruncation (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reduces the number of fp-to-int conversion when building a vector.</p>


<p>If this vector is built out of floating to integer conversions, transform it to a vector built out of floating point values followed by a single floating to integer conversion of the vector. Namely (build_vector (fptosi $A), (fptosi $B), ...) becomes (fptosi (build_vector ($A, $B, ...)))</p>


<p>Declaration at line 1466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 14984 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### combineFMALike() {#a8f0901d5699d505cc3a3fdb15d73648e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::combineFMALike (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18483 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### combineFPToIntToFP() {#a11f8b76cc3e0d5ddd423397a12a80fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::combineFPToIntToFP (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 15432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### combineMUL() {#a55edac70ea7b252b1a2961862df5b9ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::combineMUL (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### combineRepeatedFPDivisors() {#a26513e60cc41c9d2bc638a1eb9b64dcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PPCTargetLowering::combineRepeatedFPDivisors ()</td>
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

<p>Indicate whether this target prefers to combine FDIVs with the same divisor.</p>


<p>If the transform should never be done, return zero. If the transform should be done, return the minimum number of divisor uses that must exist.</p>


<p>Declaration at line 1463 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 14094 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### combineSetCC() {#af680661800ce4554163f5de924d96692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::combineSetCC (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1443 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 14937 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### combineSHL() {#af26205c2c3487955cbe10bb9da639840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::combineSHL (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1436 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### combineSRA() {#a2d39a97103d96d16e49a27afc9da970a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::combineSRA (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### combineSRL() {#a6d92d6311cfe8b9c9e006f6b75f94a40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::combineSRL (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### combineStoreFPToInt() {#a49f9c5e379a2fdde72cc1b8d0072f82a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::combineStoreFPToInt (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 15670 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### combineTRUNCATE() {#ad18f9407bcd34f0d9e0b0d6dd34a222a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::combineTRUNCATE (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1442 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### combineVectorShuffle() {#a8f21596fd46355f492f9260cc97324d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::combineVectorShuffle (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * SVN, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1444 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 15879 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### combineVReverseMemOP() {#a58e0104c80dc81500a6206c84cac679f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::combineVReverseMemOP (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * SVN, <a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode">LSBaseSDNode</a> * LSBase, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1446 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 16050 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### computeMOFlags() {#a9f8c71acf985e5bf1e2f519888f4f20a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PPCTargetLowering::computeMOFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>computeMOFlags - Given a node N and it's Parent (a <a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a>), compute the address flags of the load/store instruction that is to be matched.</p>


<p>The address flags are stored in a map, which is then searched through to determine the optimal load/store instruction format.</p>


<p>Declaration at line 1498 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18683 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### ConvertSETCCToSubtract() {#a7a8370967a56fb937bce19a06e41b62b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::ConvertSETCCToSubtract (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ConvertSETCCToSubtract - looks at SETCC that compares ints.</p>


<p>It replaces SETCC with integer subtraction when (1) there is a legal way of doing it (2) keeping the result of comparison in GPR has performance benefit.</p>


<p>Declaration at line 1452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 14346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### createMemcpyOutsideCallSeq() {#aa0c63850ef1340ffded3e8c82513eabe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::createMemcpyOutsideCallSeq (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Arg, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> PtrOff, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> CallSeqStart, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 6232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### DAGCombineBuildVector() {#aed869d56410d9b43eed9b16bc87b0fb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::DAGCombineBuildVector (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 15341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### DAGCombineExtBoolTrunc() {#acd0b756aa4efd040b574f090aaf219c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::DAGCombineExtBoolTrunc (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1431 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 14661 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### DAGCombineTruncBoolExt() {#aa00d8aff98a114fb5a053af40a1c1395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::DAGCombineTruncBoolExt (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 14386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### directMoveIsProfitable() {#a753e82c6e5748cadc5aef989ff3e9179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::directMoveIsProfitable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze profitability of direct move prefer float load to int load plus direct move when there is no integer use of int load.</p>

<p>Declaration at line 1237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8681 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### EmitTailCallLoadFPAndRetAddr() {#a569f1e97bf1305065e38ed8cc2e7e0d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::EmitTailCallLoadFPAndRetAddr (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, int SPDiff, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; LROpOut, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; FPOpOut, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmitTCFPAndRetAddrLoad - Emit load from frame pointer and return address stack slot.</p>


<p>Returns the chain as result and the loaded frame pointers in LROpOut/FPOpout. Used when tail calling.</p>


<p>Declaration at line 1269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 5278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### extendArgForPPC64() {#ae8175acc5d3a39b4738306fc7f9a6a25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::extendArgForPPC64 (<a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ObjectVT, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ArgVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 4502 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### FinishCall() {#aeb6bdcd0336f1d8f2c191803848cead4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::FinishCall (<a href="/web-llvm/docs/api/structs/llvm/ppctargetlowering/callflags">CallFlags</a> CFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;, 8 &gt; &amp; RegsToPass, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> InGlue, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> CallSeqStart, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Callee, int SPDiff, unsigned NumBytes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 5806 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### getAddrModeForFlags() {#a18c60d8f49b0dc18b82458fa122e08ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPC::AddrMode PPCTargetLowering::getAddrModeForFlags (unsigned Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getAddrModeForFlags - Based on the set of address flags, select the most optimal instruction format to match by.</p>

<p>Declaration at line 1492 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18567 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### getFramePointerFrameIndex() {#a30d465c41010dd45b998f2439b5c5579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::getFramePointerFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8020 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### getRecipEstimate() {#af49324adfc981ac39b7de0b06ee7add0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::getRecipEstimate (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Operand, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, int Enabled, int &amp; RefinementSteps)</td>
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

<p>Return a reciprocal estimate value for the input operand.</p>


<p><span class="doxyComputerOutput">Enabled</span> is a <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cbb26a6b04c9a328e0e0966881da33f">ReciprocalEstimate</a> enum with value either 'Unspecified' or 'Enabled' as set by a potential default override attribute. If <span class="doxyComputerOutput">RefinementSteps</span> is 'Unspecified', the number of Newton-Raphson refinement iterations required to generate a sufficient (though not necessarily IEEE-754 compliant) estimate is returned in that parameter. A target may choose to implement its own refinement within this function. If that's true, then return '0' as the number of RefinementSteps to avoid any further refinement of the estimate. An empty <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> return means no estimate sequence can be created.</p>


<p>Declaration at line 1457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 14079 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### getReturnAddrFrameIndex() {#a8c8fe9d85e197c06d0551181e23899fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::getReturnAddrFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 7997 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### getSqrtEstimate() {#afbd0ca4c3f0a8a1a125b1eb14d917a6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::getSqrtEstimate (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Operand, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, int Enabled, int &amp; RefinementSteps, bool &amp; UseOneConstNR, bool Reciprocal)</td>
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

<p>Hooks for building estimates in place of slower divisions and square roots.</p>


<p>Return either a square root or its reciprocal estimate value for the input operand. <span class="doxyComputerOutput">Enabled</span> is a <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cbb26a6b04c9a328e0e0966881da33f">ReciprocalEstimate</a> enum with value either 'Unspecified' or 'Enabled' as set by a potential default override attribute. If <span class="doxyComputerOutput">RefinementSteps</span> is 'Unspecified', the number of Newton-Raphson refinement iterations required to generate a sufficient (though not necessarily IEEE-754 compliant) estimate is returned in that parameter. The boolean UseOneConstNR output is used to select a Newton-Raphson algorithm implementation that uses either one or two constants. The boolean Reciprocal is used to select whether the estimate is for the square root of the input operand or the reciprocal of its square root. A target may choose to implement its own refinement within this function. If that's true, then return '0' as the number of RefinementSteps to avoid any further refinement of the estimate. An empty <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> return means no estimate sequence can be created.</p>


<p>Declaration at line 1454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 14059 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### getSqrtInputTest() {#a774530d839b593968b499c96406ed88c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::getSqrtInputTest (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Operand, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a> &amp; Mode)</td>
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

<p>Return a target-dependent comparison result if the input operand is suitable for use with a square root estimate calculation.</p>


<p>For example, the comparison may check if the operand is NAN, INF, zero, normal, etc. The result should be used as the condition operand for a select or branch.</p>


<p>Declaration at line 1459 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 14018 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### getSqrtResultForDenormInput() {#adf5dcffda94b7c1a3c26d66ec38583c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::getSqrtResultForDenormInput (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Operand, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Return a target-dependent result if the input operand is not suitable for use with a square root estimate calculation.</p>

<p>Declaration at line 1461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 14048 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### getTOCEntry() {#a31a67e2a6e6917feccba94dfc1698f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::getTOCEntry (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> GA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### initializeAddrModeMap() {#a5f64e1a96749ea3286aec43bacda3117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCTargetLowering::initializeAddrModeMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize the map that relates the different addressing modes of the load and store instructions to a set of flags.</p>


<p>This ensures the load/store instruction is correctly matched during instruction selection.</p>


<p>Declaration at line 1224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 1568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### IsEligibleForTailCallOptimization() {#af14ac8041e5521a60193cd0c9e9a9cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::IsEligibleForTailCallOptimization (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * CalleeGV, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CalleeCC, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallerCC, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsEligibleForTailCallOptimization - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the call is eligible for tail call optimization.</p>


<p>Targets which want to do tail call optimization should implement this function.</p>


<p>Declaration at line 1249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 5159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### IsEligibleForTailCallOptimization\_64SVR4() {#aeedff75481dc6ea67cf6f1ec34ff342d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::IsEligibleForTailCallOptimization_64SVR4 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * CalleeGV, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CalleeCC, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallerCC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * CallerFunc, bool isCalleeExternalSymbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 5072 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### isEligibleForTCO() {#aa4fe7688b9dabb9b7bf17a03c7c28765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isEligibleForTCO (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * CalleeGV, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CalleeCC, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallerCC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * CallerFunc, bool isCalleeExternalSymbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 5897 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### isLowringToMASSFiniteSafe() {#a30eceac5c1328b731fd5c34c99f76a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isLowringToMASSFiniteSafe (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18904 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### isLowringToMASSSafe() {#a8d2513e0b44ff4fdec30bf4f2b522fe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isLowringToMASSSafe (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18910 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### isMaskAndCmp0FoldingBeneficial() {#aec92a6313081c12af66880a21d6c5a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isMaskAndCmp0FoldingBeneficial (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; AndI)</td>
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

<p>Return if the target supports combining a chain like:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%andResult = and %val1, #<a href="/web-llvm/docs/api/namespaces/shuffles/#a6abf8a645bd24dfb42085db9672ac39a">mask</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%icmpResult = icmp %andResult, 0</span></span></div>

</div>


<p>into a single machine instruction of a form like:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">cc = <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">test</a> %</span><span class="doxyHighlightKeyword">register</span><span class="doxyHighlight">, #<a href="/web-llvm/docs/api/namespaces/shuffles/#a6abf8a645bd24dfb42085db9672ac39a">mask</a></span></span></div>

</div>


<p>Declaration at line 1488 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### isScalarMASSConversionEnabled() {#a75e817fa870a94affc7a96137caa4f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::isScalarMASSConversionEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18914 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerADJUST\_TRAMPOLINE() {#a0d110c1944430d51ea84db10039a8db7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerADJUST_TRAMPOLINE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3935 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerATOMIC\_CMP\_SWAP() {#a5b5524d63dae6e6e027826c9f649cf93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerATOMIC_CMP_SWAP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 11410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerATOMIC\_LOAD\_STORE() {#a63f977669008ea781e098f5d9165d15f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerATOMIC_LOAD_STORE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 11444 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBITCAST() {#aac61461057c08b51c6cfaaec5a9b9e58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerBITCAST (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 9504 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBlockAddress() {#a1ebdd8b520a58b37999779befa1ec38f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerBlockAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBSWAP() {#ad348165aa5000ade156b95f4a800c92f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerBSWAP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 11390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBUILD\_VECTOR() {#a1fdd7a6b893778f85733222568a4992e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerBUILD_VECTOR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 9620 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCall() {#afdedec4cde0784077c92ef393adfbac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerCall (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">TargetLowering::CallLoweringInfo</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;)</td>
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

<p>This hook must be implemented to lower calls into the specified DAG.</p>


<p>The outgoing arguments to the call are described by the Outs array, and the values to be returned by the call are described by the Ins array. The implementation should fill in the InVals array with legal-type return values from the call, and return the resulting token chain value.</p>


<p>Declaration at line 1370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 5916 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCall\_32SVR4() {#a0e75d9362ba1c7f9d5cd048b587d4da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerCall_32SVR4 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Callee, <a href="/web-llvm/docs/api/structs/llvm/ppctargetlowering/callflags">CallFlags</a> CFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutVals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 5993 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCall\_64SVR4() {#a76130c3e027890ec153a61bf81464546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerCall_64SVR4 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Callee, <a href="/web-llvm/docs/api/structs/llvm/ppctargetlowering/callflags">CallFlags</a> CFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutVals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 6247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCall\_AIX() {#a5584ac92f647260591392f6e184733d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerCall_AIX (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Callee, <a href="/web-llvm/docs/api/structs/llvm/ppctargetlowering/callflags">CallFlags</a> CFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutVals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1419 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 7552 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCallResult() {#a890bd06b3a8f766f4ae0f9702753c09a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerCallResult (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> InGlue, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 5368 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerConstantPool() {#a88bb955bc687311870dd2b0f464a64ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerConstantPool (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### lowerCos() {#a644000f1c44ef006422897513c65808a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::lowerCos (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18945 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerDYNAMIC\_STACKALLOC() {#a037a0ed3bc606a66a4eb9b6cade8c13b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerDYNAMIC_STACKALLOC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8042 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerEH\_DWARF\_CFA() {#aa418e55a51bb59f17e4a034ed03dde45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerEH_DWARF_CFA (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8064 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### lowerEH\_SJLJ\_LONGJMP() {#abb9cad51a503b553ae2e96458b3222c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::lowerEH_SJLJ_LONGJMP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8083 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### lowerEH\_SJLJ\_SETJMP() {#ae830ce15fa10f5c31dcd4c3092e69683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::lowerEH_SJLJ_SETJMP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8075 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### lowerExp() {#a1a63f13d27659d6cd192644cca16ab0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::lowerExp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18960 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFormalArguments() {#a53d663203ffeeaeca443ea37c8556aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerFormalArguments (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;)</td>
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

<p>This hook must be implemented to lower the incoming (formal) arguments, described by the Ins array, into the specified DAG.</p>


<p>The implementation should fill in the InVals array with legal-type argument values, and return the resulting token chain value.</p>


<p>Declaration at line 1365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 4236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFormalArguments\_32SVR4() {#aa9337cd4048a4f818317e21e8ba5cf61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerFormalArguments_32SVR4 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 4251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFormalArguments\_64SVR4() {#a13703af0860a44f76b0a216890d2d8ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerFormalArguments_64SVR4 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 4516 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFormalArguments\_AIX() {#a915a0e13ef51c9859137ab9b1b3c88fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerFormalArguments_AIX (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 7210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_EXTEND() {#ad6fac18b3c7fd99170ad51b0f8f36f55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerFP_EXTEND (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 11962 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_ROUND() {#a36d24002edb234bc8e1815df30623a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerFP_ROUND (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 11952 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_TO\_INT() {#a9f832eb5f10c0477b8e2c885b9c825ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerFP_TO_INT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8495 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_TO\_INTDirectMove() {#abefbc414fca41dcd74283d8490e69a25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerFP_TO_INTDirectMove (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Custom lowers floating point to integer conversions to use the direct move instructions available in ISA 2.07 to avoid the need for load/store combinations.</p>

<p>Declaration at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8484 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_TO\_INTForReuse() {#a9e648440bd92514a5ac4384634c2adfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCTargetLowering::LowerFP_TO_INTForReuse (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, ReuseLoadInfo &amp; RLI, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFRAMEADDR() {#adc62b841a88b15eaf6427d6a8688a494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerFRAMEADDR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFunnelShift() {#a7b9149f2f68926b2a5dd6a6afea44419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerFunnelShift (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 9351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGET\_DYNAMIC\_AREA\_OFFSET() {#af544d38a73650dc0589656e39ff5e068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerGET_DYNAMIC_AREA_OFFSET (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 7953 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGET\_ROUNDING() {#a037b03c0afc2af68af766204317122b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerGET_ROUNDING (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 9192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalAddress() {#aac7c0116c861da06b3fb710642d280b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerGlobalAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3700 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalTLSAddress() {#aae048923ceef9a1ce3cbbf20025c69f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerGlobalTLSAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3374 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalTLSAddressAIX() {#a4acaca593f12a3166b84688c98c6a4de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerGlobalTLSAddressAIX (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalTLSAddressLinux() {#ab55608d59fdd6d56deab4a09b1cd2b07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerGlobalTLSAddressLinux (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3572 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINIT\_TRAMPOLINE() {#aab9dfb9ce0e97af376da9e65efad638e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerINIT_TRAMPOLINE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3994 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINLINEASM() {#a192174630975b9c97101323257e3f2b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerINLINEASM (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3943 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINSERT\_VECTOR\_ELT() {#a9b651ead7a2e58b325e3ab5e5745ee18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerINSERT_VECTOR_ELT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 11718 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINT\_TO\_FP() {#a5edeb98a4cb2737193389f8e746d8fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerINT_TO_FP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8836 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINT\_TO\_FPDirectMove() {#a3cfaeaf09ec86ab3d287cc15ba77a93c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerINT_TO_FPDirectMove (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Custom lowers integer to floating point conversions to use the direct move instructions available in ISA 2.07 to avoid the need for load/store combinations.</p>

<p>Declaration at line 1238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8739 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINT\_TO\_FPVector() {#aa7dd383d2eb5c031b779aea878a3d143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerINT_TO_FPVector (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8776 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINTRINSIC\_VOID() {#a8a28469d8a96cb472e876bfc93725523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerINTRINSIC_VOID (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 11359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINTRINSIC\_WO\_CHAIN() {#a4a1c8de626be5ad29673ccd189469abd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerINTRINSIC_WO_CHAIN (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LowerINTRINSIC_WO_CHAIN - If this is an intrinsic that we want to custom lower, do it, otherwise return null.</p>

<p>Declaration at line 1316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 11025 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerIS\_FPCLASS() {#afb4315b614e26656283753bbb1f05d8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerIS_FPCLASS (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 11634 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerJumpTable() {#a2e3e75bfbcd67108c7b3a3782d3338b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerJumpTable (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### lowerLibCallBase() {#a780987c4514625fbc5dd81221e7f1759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::lowerLibCallBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * LibCallDoubleName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * LibCallFloatName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * LibCallDoubleNameFinite, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * LibCallFloatNameFinite, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18918 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### lowerLibCallBasedOnType() {#a36df21ff3fcf300508a31598799c4428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::lowerLibCallBasedOnType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * LibCallFloatName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * LibCallDoubleName, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18892 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerLOAD() {#a7e1e1e1a04c5ee733f480aac631a07dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerLOAD (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8090 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### lowerLog() {#a15e99965e35ab4ce7c54c4c39b42c96e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::lowerLog (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18950 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### lowerLog10() {#a9374f7ab647eb66051ec2cdb75446e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::lowerLog10 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18955 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerMUL() {#aea01ec63e5e633eb69ab0f1ed7bd8763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerMUL (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 11888 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### lowerPow() {#a2321e667b3b60da50d51b5a3938b861f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::lowerPow (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18935 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerReturn() {#a2830601fd6e68cad81898be5ab97f196}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerReturn (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
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

<p>This hook must be implemented to lower outgoing return values, described by the Outs array, into the specified DAG.</p>


<p>The implementation should return the resulting token chain value.</p>


<p>Declaration at line 1378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 7888 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerRETURNADDR() {#a72e08926eca5d2933a60c74d1e243e24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerRETURNADDR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 17427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerROTL() {#a539208ae316f3faff5dcfe1e351abfb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerROTL (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LowerROTL - Custom lowering for <a href="/web-llvm/docs/api/files/lib/lib/support/siphash-cpp/#addd42b95ef425979d1d0dca095dec800">ROTL(v1i128)</a> to vector_shuffle(v16i8).</p>


<p>We lower <a href="/web-llvm/docs/api/files/lib/lib/support/siphash-cpp/#addd42b95ef425979d1d0dca095dec800">ROTL(v1i128)</a> to vector_shuffle(v16i8) only if shift amount is a multiple of 8. Otherwise convert it to a scalar rotation(i128) i.e (or (shl x, C1), (srl x, 128-C1)).</p>


<p>Declaration at line 1345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 10281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSCALAR\_TO\_VECTOR() {#abe8e95da4d74f8d25e24fa4b40193f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerSCALAR_TO_VECTOR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 11650 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSELECT\_CC() {#a1816c47b4ddc3f4c467200ab9531b115}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerSELECT_CC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LowerSELECT_CC - Lower floating point select_cc's into fsel instruction when possible.</p>

<p>Declaration at line 1301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSET\_ROUNDING() {#a11b9f143019b4034fa350f1eb30fbb1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerSET_ROUNDING (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 9095 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSETCC() {#a1ef5cbd88afc22f441db0ce3aad6d597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerSETCC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3749 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSHL\_PARTS() {#a5f1e0140983efb7b1656371533193c61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerSHL_PARTS (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 9264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### lowerSin() {#ab649c3363d8d0c6d9529b2002cb9f0b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::lowerSin (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18940 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSRA\_PARTS() {#abb9e29594a62f5e0e9c878932ef9fb3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerSRA_PARTS (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 9322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSRL\_PARTS() {#a3fac7e4aa7c6abd6c3e5691bcaa5715e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerSRL_PARTS (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 9293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSSUBO() {#aa1980328b3aff55b9af0ca30a9343864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerSSUBO (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 12077 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSTACKRESTORE() {#a84910fd0d9b7f0153a099711c9739c9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerSTACKRESTORE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 7969 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSTORE() {#a8a7be9fbf4f1de22c2017e0cadeb4f55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerSTORE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### lowerToLibCall() {#aea6f9257cb75708f7c6bb48d11c685d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::lowerToLibCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * LibCallName, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18853 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### lowerToVINSERTB() {#ab33c862e2cf268da4301451444f1e57a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::lowerToVINSERTB (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>lowerToVINSERTB - Return the <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if this VECTOR_SHUFFLE can be handled by the VINSERTB instruction introduced in ISA 3.0.</p>


<p>lowerToVINSERTB - Return the <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if this VECTOR_SHUFFLE can be handled by the VINSERTB instruction introduced in ISA 3.0, else just return default <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>.</p>


<p>This is essentially v16i8 vector version of VINSERTH.</p>


<p>Declaration at line 1478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 9993 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### lowerToVINSERTH() {#a35094c6016f824fe6c3a054404584d6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::lowerToVINSERTH (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>lowerToVINSERTH - Return the <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if this VECTOR_SHUFFLE can be handled by the VINSERTH instruction introduced in ISA 3.0.</p>


<p>lowerToVINSERTH - Return the <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if this VECTOR_SHUFFLE can be handled by the VINSERTH instruction introduced in ISA 3.0, else just return default <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>.</p>


<p>This is essentially any shuffle of v8i16 vectors that just inserts one element from one vector into the other.</p>


<p>Declaration at line 1473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 10094 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### lowerToXXSPLTI32DX() {#a198c03e70cbea965e47222809c97f37a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::lowerToXXSPLTI32DX (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>lowerToXXSPLTI32DX - Return the <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if this VECTOR_SHUFFLE can be handled by the XXSPLTI32DX instruction introduced in ISA 3.1.</p>


<p>lowerToXXSPLTI32DX - Return the <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if this VECTOR_SHUFFLE can be handled by the XXSPLTI32DX instruction introduced in ISA 3.1, otherwise return the default <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>.</p>


<p>Declaration at line 1482 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 10206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerTRUNCATE() {#a0a178df209b8c9568a179e308fa55321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerTRUNCATE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerTRUNCATEVector() {#a95f6bdc591f283e0a285d693314e08ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerTRUNCATEVector (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerUaddo() {#af1dc4e6d14a38bf29c5ee48571780521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerUaddo (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 12038 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVAARG() {#a8b574774c5d768e63533fc1296eefb97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerVAARG (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3825 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVACOPY() {#a88438bd1ec337381ff86d3f32c701a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerVACOPY (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 3924 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVASTART() {#a0bf516b68c8bb624b6000579e33957d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerVASTART (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 4033 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVECTOR\_SHUFFLE() {#ac4b256bde82d233d1a18729d0be1edd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerVECTOR_SHUFFLE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LowerVECTOR_SHUFFLE - Return the code we lower for VECTOR_SHUFFLE.</p>


<p>If this is a shuffle we can handle in a single instruction, return it. Otherwise, return the code it can be lowered into. Worst case, it can always be lowered into a vperm.</p>


<p>Declaration at line 1312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 10311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVectorLoad() {#a8c03e1007e384aefa7ad1055fe69cc1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerVectorLoad (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 11783 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVectorStore() {#a04f4c9a7a840484c4272cab00d67a341}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerVectorStore (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 11828 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVPERM() {#af74e485a4d4f42d7faa05ecaa3b0c3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCTargetLowering::LowerVPERM (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; PermMask, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> V1, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> V2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 10606 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### mayBeEmittedAsTailCall() {#a5f665f37afe6472a71d5112f492387f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTargetLowering::mayBeEmittedAsTailCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *)</td>
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

<p>Return true if the target may be able emit the call instruction as a tail call.</p>


<p>This is used by optimization passes to determine if it's profitable to duplicate return instructions to enable tailcall optimization.</p>


<p>Declaration at line 1487 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 18518 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### spliceIntoChain() {#a8036c6e2ca253282df2cf377c25b337c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCTargetLowering::spliceIntoChain (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ResChain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> NewResChain, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>, definition at line 8661 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddrModesMap {#a3a013160d7e477c636f98070bd83b1e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;PPC::AddrMode, SmallVector&lt;unsigned, 16&gt; &gt; llvm::PPCTargetLowering::AddrModesMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>

</div>
</div>

### Subtarget {#a5875f104559ccf841bd5ed72e85cd6af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCSubtarget&amp; llvm::PPCTargetLowering::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 754 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
