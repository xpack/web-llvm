---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armtargetlowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ARMTargetLowering` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ARMTargetLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">Target/ARM/ARMISelLowering.h</a>"
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a132da2f7fdd456d04553e7bf0fb458e5">RegsToPassVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;, 8 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ByValCopyKind { <a href="#a13d08bccbe19ea45b7318cdb0ba1f673">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa782c58995f9a6e00cf5a8500a9a8508">ARMTargetLowering</a> (const TargetMachine &amp;TM, const ARMSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd1b16a5f1b13b4d1d5fdf835f43791c">getJumpTableEncoding</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the entry encoding for a jump table in the current function. <a href="#abd1b16a5f1b13b4d1d5fdf835f43791c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad605f833179d4fecc1f4e0e8ca0fe2f1">useSoftFloat</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69482bf1572254076b1544aecb6fd46e">LowerOperation</a> (SDValue Op, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is invoked for operations that are unsupported by the target, which are registered to use 'custom' lowering, and whose defined values are all legal. <a href="#a69482bf1572254076b1544aecb6fd46e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28af47b21a8953afd3568b40acf3424d">ReplaceNodeResults</a> (SDNode *N, SmallVectorImpl&lt; SDValue &gt; &amp;Results, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReplaceNodeResults - Replace the results of node with an illegal result type with new values built out of custom code. <a href="#a28af47b21a8953afd3568b40acf3424d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab05dc466c15a454c07f2993dab74472f">getTargetNodeName</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns the name of a target specific DAG node. <a href="#ab05dc466c15a454c07f2993dab74472f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a839aa57e2284019e487e2dc66877e925">isSelectSupported</a> (SelectSupportKind Kind) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02f2e4fa534673c5a1afbba067f81319">isReadOnly</a> (const GlobalValue *GV) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667a905e2496f6b0b9c7915a97f58da1">getSetCCResultType</a> (const DataLayout &amp;DL, LLVMContext &amp;Context, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSetCCResultType - Return the value type to use for <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">ISD::SETCC</a>. <a href="#a667a905e2496f6b0b9c7915a97f58da1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6820d09b4db5654cd1377d3ab63b3e01">EmitInstrWithCustomInserter</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'usesCustomInserter' flag. <a href="#a6820d09b4db5654cd1377d3ab63b3e01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cdddfff71264f7e1e744fdea34085d3">AdjustInstrPostInstrSelection</a> (MachineInstr &amp;MI, SDNode *Node) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'hasPostISelHook' flag. <a href="#a6cdddfff71264f7e1e744fdea34085d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba6b9afcc5b700d4c09664b5fa009d9">PerformCMOVCombine</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PerformCMOVCombine - Target-specific DAG combining for <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aee74cff1cb1ea095617b5fa044e342db">ARMISD::CMOV</a>. <a href="#a4ba6b9afcc5b700d4c09664b5fa009d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab051a4c12430b297d1465afcb7cf8485">PerformBRCONDCombine</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PerformBRCONDCombine - Target-specific DAG combining for <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a4621d333784e3cd8c9f92a1443013dbe">ARMISD::BRCOND</a>. <a href="#ab051a4c12430b297d1465afcb7cf8485">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada7b7dfe4d829cdafff6278e361547df">PerformCMOVToBFICombine</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42aa092f2811f72cad69b42cc2e4bb64">PerformIntrinsicCombine</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PerformIntrinsicCombine - ARM-specific DAG combining for intrinsics. <a href="#a42aa092f2811f72cad69b42cc2e4bb64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a589928ae94c1e14b50e374c6a1146c60">PerformMVEExtCombine</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35a55a457bfc044d33bdeb4811532531">PerformMVETruncCombine</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e96878324f2ca0f847e369f839cfd23">PerformDAGCombine</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be invoked for all target nodes and for any target-independent nodes that the target has registered with invoke it for. <a href="#a8e96878324f2ca0f847e369f839cfd23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a655de0b9ba51c463a01a23651abb0cf7">SimplifyDemandedBitsForTargetNode</a> (SDValue Op, const APInt &amp;OriginalDemandedBits, const APInt &amp;OriginalDemandedElts, KnownBits &amp;Known, TargetLoweringOpt &amp;TLO, unsigned Depth) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to simplify any target nodes based on the demanded bits/elts, returning true on success. <a href="#a655de0b9ba51c463a01a23651abb0cf7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2cd92359d9b981db40c3cc07f20249d">isDesirableToTransformToIntegerOp</a> (unsigned Opc, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable for dag combiner to transform a floating point op of specified opcode to a equivalent op of an integer type. <a href="#ac2cd92359d9b981db40c3cc07f20249d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac897a80df1070effb9d5a5b6a023c5d0">allowsMisalignedMemoryAccesses</a> (EVT VT, unsigned AddrSpace, Align Alignment, MachineMemOperand::Flags Flags, unsigned *Fast) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>allowsMisalignedMemoryAccesses - Returns true if the target allows unaligned memory accesses of the specified type. <a href="#ac897a80df1070effb9d5a5b6a023c5d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd29a7e70a14fb7b45ff277e5c935424">getOptimalMemOpType</a> (const MemOp &amp;Op, const AttributeList &amp;FuncAttributes) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the target specific optimal type for load and store operations as a result of memset, memcpy, and memmove lowering. <a href="#abd29a7e70a14fb7b45ff277e5c935424">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a766bc050b0a294104d02f41e0047e0ba">isTruncateFree</a> (Type *SrcTy, Type *DstTy) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's free to truncate a value of type FromTy to type ToTy. <a href="#a766bc050b0a294104d02f41e0047e0ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f7dae0343b89773eaaea832fc9f3ae5">isTruncateFree</a> (EVT SrcVT, EVT DstVT) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d59d0a2b9e117e74cd61f315aabf247">isZExtFree</a> (SDValue Val, EVT VT2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if zero-extending the specific node Val to type VT2 is free (either because it's implicitly zero-extended such as <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> ldrb / ldrh or because it's folded such as <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> zero-extending loads). <a href="#a8d59d0a2b9e117e74cd61f315aabf247">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab32574e30e8d85eaa2f692d8fc3c6766">shouldConvertSplatType</a> (ShuffleVectorInst *SVI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a shuffle vector SVI representing a vector splat, return a new scalar type of size equal to SVI's scalar type if the new type is more profitable. <a href="#ab32574e30e8d85eaa2f692d8fc3c6766">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a350cbdd9ddbb2a048799fca9d93f3993">isFNegFree</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if an fneg operation is free to the point where it is never worthwhile to replace it with a bitwise operation. <a href="#a350cbdd9ddbb2a048799fca9d93f3993">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb7284db7f63030c26cd605c4afd7fa6">isVectorLoadExtDesirable</a> (SDValue ExtVal) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if folding a vector load into ExtVal (a sign, zero, or any extend node) is profitable. <a href="#acb7284db7f63030c26cd605c4afd7fa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaf74e11d3b6f4feaee9dd7711e92202">allowTruncateForTailCall</a> (Type *Ty1, Type *Ty2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a truncation from FromTy to ToTy is permitted when deciding whether a call is in tail position. <a href="#adaf74e11d3b6f4feaee9dd7711e92202">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14ba388c0893657958340f94a164faa9">isLegalAddressingMode</a> (const DataLayout &amp;DL, const AddrMode &amp;AM, Type *Ty, unsigned AS, Instruction *I=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isLegalAddressingMode - Return true if the addressing mode represented by AM is legal for this target, for a load/store of the specified type. <a href="#a14ba388c0893657958340f94a164faa9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b478e338eb3e2c6ab20ac7462896c58">isLegalT2ScaledAddressingMode</a> (const AddrMode &amp;AM, EVT VT) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a221b01b74bd3f7ddd1779947901f5eec">isLegalT1ScaledAddressingMode</a> (const AddrMode &amp;AM, EVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the addressing mode representing by AM is legal for the Thumb1 target, for a load/store of the specified type. <a href="#a221b01b74bd3f7ddd1779947901f5eec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb7f063013825d86c8d8d483e83d1123">isLegalICmpImmediate</a> (int64_t Imm) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isLegalICmpImmediate - Return true if the specified immediate is legal icmp immediate, that is the target has icmp instructions which can compare a register against the immediate without having to materialize the immediate into a register. <a href="#abb7f063013825d86c8d8d483e83d1123">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dd0b703d836eccdef210b88ea83908b">isLegalAddImmediate</a> (int64_t Imm) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isLegalAddImmediate - Return true if the specified immediate is legal add immediate, that is the target has add instructions which can add a register and the immediate without having to materialize the immediate into a register. <a href="#a2dd0b703d836eccdef210b88ea83908b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22338caf16030dc171ee6dfb5580d308">getPreIndexedAddressParts</a> (SDNode *N, SDValue &amp;Base, SDValue &amp;Offset, ISD::MemIndexedMode &amp;AM, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPreIndexedAddressParts - returns true by value, base pointer and offset pointer and addressing mode by reference if the node's address can be legally represented as pre-indexed load / store address. <a href="#a22338caf16030dc171ee6dfb5580d308">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4269b2cd295687cb69f61729f91de3b">getPostIndexedAddressParts</a> (SDNode *N, SDNode *Op, SDValue &amp;Base, SDValue &amp;Offset, ISD::MemIndexedMode &amp;AM, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPostIndexedAddressParts - returns true by value, base pointer and offset pointer and addressing mode by reference if this node can be combined with a load / store to form a post-indexed load / store. <a href="#af4269b2cd295687cb69f61729f91de3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e4b8ac086cdc9c81f7c2eabd77394fc">computeKnownBitsForTargetNode</a> (const SDValue Op, KnownBits &amp;Known, const APInt &amp;DemandedElts, const SelectionDAG &amp;DAG, unsigned Depth) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine which of the bits specified in Mask are known to be either zero or one and return them in the KnownZero/KnownOne bitsets. <a href="#a3e4b8ac086cdc9c81f7c2eabd77394fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98a503af3a695653b6093323a1c4b9cf">targetShrinkDemandedConstant</a> (SDValue Op, const APInt &amp;DemandedBits, const APInt &amp;DemandedElts, TargetLoweringOpt &amp;TLO) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b23196df4c243ce29f29f54a26cae7e">ExpandInlineAsm</a> (CallInst *CI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook allows the target to expand an inline asm call to be explicit llvm code if it wants to. <a href="#a4b23196df4c243ce29f29f54a26cae7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116">ConstraintType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a367c0fd240000e247269dee3f2db8d7f">getConstraintType</a> (StringRef Constraint) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getConstraintType - Given a constraint letter, return the type of constraint it is for this target. <a href="#a367c0fd240000e247269dee3f2db8d7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abc">ConstraintWeight</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f12063b62264c753e65abb8e9ff29d8">getSingleConstraintMatchWeight</a> (AsmOperandInfo &amp;info, const char *constraint) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine constraint string and operand type and determine a weight value. <a href="#a0f12063b62264c753e65abb8e9ff29d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae36dfcf0bacb4009b75fb2323aba6869">getRegForInlineAsmConstraint</a> (const TargetRegisterInfo *TRI, StringRef Constraint, MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a physical register constraint (e.g. <a href="#ae36dfcf0bacb4009b75fb2323aba6869">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc928b96601086c4735b9ea8331f0b9f">LowerXConstraint</a> (EVT ConstraintVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to replace an X constraint, which matches anything, with another that has more specific requirements based on the type of the corresponding operand. <a href="#abc928b96601086c4735b9ea8331f0b9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb4ff7051f9fd7cfa91a1b20be1ac880">LowerAsmOperandForConstraint</a> (SDValue Op, StringRef Constraint, std::vector&lt; SDValue &gt; &amp;Ops, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerAsmOperandForConstraint - Lower the specified operand into the Ops vector. <a href="#adb4ff7051f9fd7cfa91a1b20be1ac880">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2543fc561fd405e07d0d993a7854b34f">getInlineAsmMemConstraint</a> (StringRef ConstraintCode) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a1a37ae8032008276a560318975cbac">getSubtarget</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83b63333509486d44ab3c289b6119c10">getRegClassFor</a> (MVT VT, bool isDivergent=false) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getRegClassFor - Return the register class that should be used for the specified value type. <a href="#a83b63333509486d44ab3c289b6119c10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26651869531ef2356ef2788595ad7c9c">shouldAlignPointerArgs</a> (CallInst *CI, unsigned &amp;MinSize, Align &amp;PrefAlign) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the pointer arguments to CI should be aligned by aligning the object whose address is being passed. <a href="#a26651869531ef2356ef2788595ad7c9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b62f6b6087313bdaea9534ec0b6f06d">createFastISel</a> (FunctionLoweringInfo &amp;funcInfo, const TargetLibraryInfo *libInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createFastISel - This method returns a target specific <a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> object, or null if the target does not support "fast" ISel. <a href="#a6b62f6b6087313bdaea9534ec0b6f06d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sched/#ab8d854a5ce2331586bcc6830cca52f0f">Sched::Preference</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa16505b46d66798daa417510b68ee4ac">getSchedulingPreference</a> (SDNode *N) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some scheduler, e.g. <a href="#aa16505b46d66798daa417510b68ee4ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4c3b6ad836d26fb542b86fafb89653b">preferZeroCompareBranch</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the heuristic to prefer icmp eq zero should be used in code gen prepare. <a href="#ad4c3b6ad836d26fb542b86fafb89653b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1478848ccc7623d55d4666d293bb6d5">isMaskAndCmp0FoldingBeneficial</a> (const Instruction &amp;AndI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if the target supports combining a chain like: <a href="#af1478848ccc7623d55d4666d293bb6d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a779e5a75f5bf9f3672698656b56663fc">isShuffleMaskLegal</a> (ArrayRef&lt; int &gt; M, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isShuffleMaskLegal - Targets can use this to indicate that they only support <em>some</em> VECTOR_SHUFFLE operations, those with specific masks. <a href="#a779e5a75f5bf9f3672698656b56663fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae88b69738e32f7322b54fd8b57a191a8">isOffsetFoldingLegal</a> (const GlobalAddressSDNode *GA) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if folding a constant offset with the given GlobalAddress is legal. <a href="#ae88b69738e32f7322b54fd8b57a191a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a361a22a9d4bb3a3812c85f56f6b04e08">isFPImmLegal</a> (const APFloat &amp;Imm, EVT VT, bool ForCodeSize=false) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isFPImmLegal - Returns true if the target can instruction select the specified FP immediate natively. <a href="#a361a22a9d4bb3a3812c85f56f6b04e08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75880fa01f2a6719716b1e3ac002f40e">getTgtMemIntrinsic</a> (IntrinsicInfo &amp;Info, const CallInst &amp;I, MachineFunction &amp;MF, unsigned Intrinsic) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getTgtMemIntrinsic - Represent NEON load and store intrinsics as MemIntrinsicNodes. <a href="#a75880fa01f2a6719716b1e3ac002f40e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a185e1e62cf599211822cc65db54242">shouldConvertConstantLoadToIntImm</a> (const APInt &amp;Imm, Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it is beneficial to convert a load of a constant to just the constant itself. <a href="#a7a185e1e62cf599211822cc65db54242">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73ff0ebe4440fb057e9206dd88bb8c7c">isExtractSubvectorCheap</a> (EVT ResVT, EVT SrcVT, unsigned Index) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if EXTRACT_SUBVECTOR is cheap for this result type with this index. <a href="#a73ff0ebe4440fb057e9206dd88bb8c7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b22b5c20474c62fa91bd60e856cec33">shouldFormOverflowOp</a> (unsigned Opcode, EVT VT, bool MathUsed) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to convert math with an overflow comparison into the corresponding DAG node operation. <a href="#a7b22b5c20474c62fa91bd60e856cec33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8df46690eb2ee31ed20a0afe37fc4e48">shouldReassociateReduction</a> (unsigned Opc, EVT VT) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4d962e48053d593dd7f02bb06f5710b">functionArgumentNeedsConsecutiveRegisters</a> (Type *Ty, CallingConv::ID CallConv, bool isVarArg, const DataLayout &amp;DL) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if an argument of type Ty needs to be passed in a contiguous block of registers in calling convention CallConv. <a href="#ae4d962e48053d593dd7f02bb06f5710b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ea645bf4979099839a35654aac5d755">getExceptionPointerRegister</a> (const Constant *PersonalityFn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register, this returns the register that receives the exception address on entry to an EH pad. <a href="#a0ea645bf4979099839a35654aac5d755">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0632dd0936481e952514e2f8e18db07">getExceptionSelectorRegister</a> (const Constant *PersonalityFn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register, this returns the register that receives the exception typeid on entry to a landing pad. <a href="#ab0632dd0936481e952514e2f8e18db07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb0c61c0a16596abc08a5c2dc7fcddd8">makeDMB</a> (IRBuilderBase &amp;Builder, ARM_MB::MemBOpt Domain) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab439771b84f342c37a8823fb2f797642">emitLoadLinked</a> (IRBuilderBase &amp;Builder, Type *ValueTy, Value *Addr, AtomicOrdering Ord) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a load-linked operation on Addr, returning a "Value *" with the corresponding pointee type. <a href="#ab439771b84f342c37a8823fb2f797642">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68bc08431f00987920ce19e9a458e86d">emitStoreConditional</a> (IRBuilderBase &amp;Builder, Value *Val, Value *Addr, AtomicOrdering Ord) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a store-conditional operation to Addr. <a href="#a68bc08431f00987920ce19e9a458e86d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b39ae6869400e3aad61ff8c837d0006">emitAtomicCmpXchgNoStoreLLBalance</a> (IRBuilderBase &amp;Builder) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa79830ec972611f4c1d1f8e23266aa4">emitLeadingFence</a> (IRBuilderBase &amp;Builder, Instruction *Inst, AtomicOrdering Ord) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts in the IR a target-specific intrinsic specifying a fence. <a href="#afa79830ec972611f4c1d1f8e23266aa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ee99baef4e41314544119fa4a0e1ce5">emitTrailingFence</a> (IRBuilderBase &amp;Builder, Instruction *Inst, AtomicOrdering Ord) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a092ffa6880261ef3e0ca4ade2cb075ce">getMaxSupportedInterleaveFactor</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the maximum supported factor for interleaved memory accesses. <a href="#a092ffa6880261ef3e0ca4ade2cb075ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad190bc43c7fc8555debc7228fc5364b9">lowerInterleavedLoad</a> (LoadInst *LI, ArrayRef&lt; ShuffleVectorInst * &gt; Shuffles, ArrayRef&lt; unsigned &gt; Indices, unsigned Factor) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower an interleaved load into a vldN intrinsic. <a href="#ad190bc43c7fc8555debc7228fc5364b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3168bc53fc117710cec207cc6f60518">lowerInterleavedStore</a> (StoreInst *SI, ShuffleVectorInst *SVI, unsigned Factor) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower an interleaved store into a vstN intrinsic. <a href="#aa3168bc53fc117710cec207cc6f60518">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a3f5a90fe18617c18aa780cd9445d57">shouldInsertFencesForAtomic</a> (const Instruction *I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether <a href="/web-llvm/docs/api/classes/llvm/atomicexpandpass">AtomicExpandPass</a> should automatically insert fences and reduce ordering for this atomic. <a href="#a0a3f5a90fe18617c18aa780cd9445d57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLoweringBase::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a17ad44231dd559dedb8ff61bcfe29e">shouldExpandAtomicLoadInIR</a> (LoadInst *LI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the given (atomic) load should be expanded by the IR-level AtomicExpand pass. <a href="#a0a17ad44231dd559dedb8ff61bcfe29e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLoweringBase::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e78ac617e56bd040677cb06a69244b8">shouldExpandAtomicStoreInIR</a> (StoreInst *SI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the given (atomic) store should be expanded by the IR-level AtomicExpand pass into. <a href="#a3e78ac617e56bd040677cb06a69244b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLoweringBase::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ed1fafeaecc08fe13e54b080e259dd2">shouldExpandAtomicRMWInIR</a> (AtomicRMWInst *AI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the IR-level AtomicExpand pass should expand the given AtomicRMW, if at all. <a href="#a6ed1fafeaecc08fe13e54b080e259dd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLoweringBase::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4b5d6d1333be49386e35e56c28647fe">shouldExpandAtomicCmpXchgInIR</a> (AtomicCmpXchgInst *AI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the given atomic cmpxchg should be expanded by the IR-level AtomicExpand pass. <a href="#ac4b5d6d1333be49386e35e56c28647fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a845ff631109e5c60ccdcf8921806ec74">useLoadStackGuardNode</a> (const Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this function returns true, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> emits a LOAD_STACK_GUARD node when it is lowering Intrinsic::stackprotector. <a href="#a845ff631109e5c60ccdcf8921806ec74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f1fdc55e21406f8dd4612925fbe86a8">insertSSPDeclarations</a> (Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts necessary declarations for SSP (stack protection) purpose. <a href="#a3f1fdc55e21406f8dd4612925fbe86a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a549b4bb4e86e927f213a2175401b10e5">getSDagStackGuard</a> (const Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the variable that's previously inserted by insertSSPDeclarations, if any, otherwise return nullptr. <a href="#a549b4bb4e86e927f213a2175401b10e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a6814018ec7443c7df966784ad69064">getSSPStackGuardCheck</a> (const Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the target has a standard stack protection check function that performs validation and error handling, returns the function. <a href="#a3a6814018ec7443c7df966784ad69064">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad07ba9d946b424c9de4782f4ae7879bb">canCombineStoreAndExtract</a> (Type *VectorTy, Value *Idx, unsigned &amp;Cost) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target can combine store(extractelement VectorTy,
Idx). <a href="#ad07ba9d946b424c9de4782f4ae7879bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4d6848e5070beeb8a9d0a8711ecd671">canMergeStoresTo</a> (unsigned AddressSpace, EVT MemVT, const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns if it's reasonable to merge stores to MemVT size. <a href="#ad4d6848e5070beeb8a9d0a8711ecd671">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d9c520e13d0f9fd00d79b2cb1c29a78">isCheapToSpeculateCttz</a> (Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is cheap to speculate a call to intrinsic cttz. <a href="#a8d9c520e13d0f9fd00d79b2cb1c29a78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a918e4a00bbb56e9dbd10ae5c0d054848">isCheapToSpeculateCtlz</a> (Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is cheap to speculate a call to intrinsic ctlz. <a href="#a918e4a00bbb56e9dbd10ae5c0d054848">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f2ba5f07dc33b4bc9b5f75cc71c731d">convertSetCCLogicToBitwiseLogic</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> bitwise logic to make pairs of compares more efficient. <a href="#a8f2ba5f07dc33b4bc9b5f75cc71c731d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f59b975114229e04efb87bbc8662224">supportSwiftError</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports swifterror attribute. <a href="#a2f59b975114229e04efb87bbc8662224">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1e8e3885b9faabcecb0384116e18f9c">hasStandaloneRem</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target can handle a standalone remainder operation. <a href="#af1e8e3885b9faabcecb0384116e18f9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1cfe6f1187d7ab1a0ada9cc119c1b2b4">ShiftLegalizationStrategy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2c8b0d2dd39354fff7d4bb1ab3fa2f3">preferredShiftLegalizationStrategy</a> (SelectionDAG &amp;DAG, SDNode *N, unsigned ExpansionFactor) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7d63117d31743dd436a9011a55275b0">CCAssignFnForCall</a> (CallingConv::ID CC, bool isVarArg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6990f5e5739473df0609344f992051a5">CCAssignFnForReturn</a> (CallingConv::ID CC, bool isVarArg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9518b8cf085f38ae07134937ad85d31">isLegalInterleavedAccessType</a> (unsigned Factor, FixedVectorType *VecTy, Align Alignment, const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">VecTy</span> is a legal interleaved access type. <a href="#ac9518b8cf085f38ae07134937ad85d31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d9d6b4d91e3a1a4ce7ffe8ed701a40e">isMulAddWithConstProfitable</a> (SDValue AddNode, SDValue ConstNode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it may be profitable to transform (mul (add x, c1), c2) -&gt; (add (mul x, c2), c1*c2). <a href="#a2d9d6b4d91e3a1a4ce7ffe8ed701a40e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad86ed5000dd0596a904dab2bb4f3fac1">alignLoopsWithOptSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should loops be aligned even when the function is marked OptSize (but not MinSize). <a href="#ad86ed5000dd0596a904dab2bb4f3fac1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a297f370d16737059a7ff5028b0b39a">getNumInterleavedAccesses</a> (VectorType *VecTy, const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of interleaved accesses that will be generated when lowering accesses of the given type. <a href="#a0a297f370d16737059a7ff5028b0b39a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35198b01162433a12919d5a5947fbe83">finalizeLowering</a> (MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Execute target specific actions to finalize target lowering. <a href="#a35198b01162433a12919d5a5947fbe83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ad154d5668d4704cbe075765d342251">getABIAlignmentForCallingConv</a> (Type *ArgTy, const DataLayout &amp;DL) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the correct alignment for the current calling convention. <a href="#a0ad154d5668d4704cbe075765d342251">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3aa05aca949e6905dcb30c81c679e3">isDesirableToCommuteWithShift</a> (const SDNode *N, CombineLevel Level) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to move this shift by a constant amount through its operand, adjusting any immediate operands as necessary to preserve semantics. <a href="#a0e3aa05aca949e6905dcb30c81c679e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49bbf30468c8d202d88466ff4bfd46dd">isDesirableToCommuteXorWithShift</a> (const SDNode *N) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to combine an XOR of a logical shift to create a logical shift of NOT. <a href="#a49bbf30468c8d202d88466ff4bfd46dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58c6bec36cfce34f95d92841b1d5ef9f">shouldFoldConstantShiftPairToMask</a> (const SDNode *N, CombineLevel Level) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to fold a pair of shifts into a mask. <a href="#a58c6bec36cfce34f95d92841b1d5ef9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aefcfec6c74e86b395e847344a7b189">shouldFoldSelectWithIdentityConstant</a> (unsigned BinOpcode, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if pulling a binary operation into a select with an identity constant is profitable. <a href="#a5aefcfec6c74e86b395e847344a7b189">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36f078885862bc3b837dcfe057d05649">preferIncOfAddToSubOfNot</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These two forms are equivalent: sub y, (xor x, -1) add (add x, 1), y The variant with two add's is IR-canonical. <a href="#a36f078885862bc3b837dcfe057d05649">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae39c938299ddc0dc8534e1a05cb0c2fc">shouldConvertFpToSat</a> (unsigned Op, EVT FPVT, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should we generate fp_to_si_sat and fp_to_ui_sat from type FPVT to type VT from min(max(fptoi)) saturation patterns. <a href="#ae39c938299ddc0dc8534e1a05cb0c2fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5175a0caa4d7785c4da770f497adc3fe">isComplexDeinterleavingSupported</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this target support complex deinterleaving. <a href="#a5175a0caa4d7785c4da770f497adc3fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f55419227d2b25fcfca130f3f1dc63">isComplexDeinterleavingOperationSupported</a> (ComplexDeinterleavingOperation Operation, Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this target support complex deinterleaving with the given operation and type. <a href="#aa8f55419227d2b25fcfca130f3f1dc63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5098d4bb22d4347dc55e1d08dcbe6708">createComplexDeinterleavingIR</a> (IRBuilderBase &amp;B, ComplexDeinterleavingOperation OperationType, ComplexDeinterleavingRotation Rotation, Value *InputA, Value *InputB, Value *Accumulator=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the IR node for the given complex deinterleaving operation. <a href="#a5098d4bb22d4347dc55e1d08dcbe6708">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1a79a0380ffa3c915ddfb6767f24d9b">softPromoteHalfType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bebe089fbc63179232f838dc2d13f45">useFPRegsForHalfType</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *, uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b4bcdae4a907d7a62317ed35092d5bb">findRepresentativeClass</a> (const TargetRegisterInfo *TRI, MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the largest legal super-reg register class of the register class for the specified type and its associated "cost". <a href="#a8b4bcdae4a907d7a62317ed35092d5bb">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f574ab8cc1ea7783c9dd79ee31925f3">addTypeForNEON</a> (MVT VT, MVT PromotedLdStVT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a772686149d1e19a6a4cdcd005b4b475d">addDRTypeForNEON</a> (MVT VT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc194f4f93baee4e019f2765e3ef5582">addQRTypeForNEON</a> (MVT VT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1af6aec3817ec31a795bc58fafb741de">getARMXALUOOp</a> (SDValue Op, SelectionDAG &amp;DAG, SDValue &amp;ARMcc) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4582ee335d2ff673ff37f426705b5f">PassF64ArgInRegs</a> (const SDLoc &amp;dl, SelectionDAG &amp;DAG, SDValue Chain, SDValue &amp;Arg, RegsToPassVector &amp;RegsToPass, CCValAssign &amp;VA, CCValAssign &amp;NextVA, SDValue &amp;StackPtr, SmallVectorImpl&lt; SDValue &gt; &amp;MemOpChains, bool IsTailCall, int SPDiff) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa996f96978f1bc6930db528137255bc">GetF64FormalArgument</a> (CCValAssign &amp;VA, CCValAssign &amp;NextVA, SDValue &amp;Root, SelectionDAG &amp;DAG, const SDLoc &amp;dl) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa25dd0405c2d8bdfdf6659563877b20d">getEffectiveCallingConv</a> (CallingConv::ID CC, bool isVarArg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEffectiveCallingConv - Get the effective calling convention, taking into account presence of floating point hardware and calling convention limitations, such as support for variadic functions. <a href="#aa25dd0405c2d8bdfdf6659563877b20d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63ce9d4816191f6e7d42abb5bb09cdbe">CCAssignFnForNode</a> (CallingConv::ID CC, bool Return, bool isVarArg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CCAssignFnForNode - Selects the correct <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> for the given CallingConvention. <a href="#a63ce9d4816191f6e7d42abb5bb09cdbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10ced4352083b391a681f80d8d7c6999">computeAddrForCallArg</a> (const SDLoc &amp;dl, SelectionDAG &amp;DAG, const CCValAssign &amp;VA, SDValue StackPtr, bool IsTailCall, int SPDiff) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ByValCopyKind</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0477f973df5ccbff82238817c808d4d">ByValNeedsCopyForTailCall</a> (SelectionDAG &amp;DAG, SDValue Src, SDValue Dst, ISD::ArgFlagsTy Flags) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9fcc67120d1a5b40df14fd7e6fed26b">LowerEH_SJLJ_SETJMP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b0b2367996b6f33a3db70bcada3704">LowerEH_SJLJ_LONGJMP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fd6918e0a906252f1f6afee79ad3bd9">LowerEH_SJLJ_SETUP_DISPATCH</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a631cc867edf9c9f2890dd66fad911f1b">LowerINTRINSIC_VOID</a> (SDValue Op, SelectionDAG &amp;DAG, const ARMSubtarget *Subtarget) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25b6f3463f527dbb89303ce43a4b27d7">LowerINTRINSIC_WO_CHAIN</a> (SDValue Op, SelectionDAG &amp;DAG, const ARMSubtarget *Subtarget) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95a555922730edd58d7eb3f7226ef0e4">LowerBlockAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2169680610500918ceee0c5bff13e4e5">LowerConstantPool</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3008862fa1480d1be83cefa97875ba19">LowerGlobalAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a673acfc3cb67bef2f7fea3de62886183">LowerGlobalAddressDarwin</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae964fcb8807f7e6e61772930d5ed9a63">LowerGlobalAddressELF</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742494e812b1e9e6b70c3e7577932591">LowerGlobalAddressWindows</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa49286ce498209939f797f39d44ea419">LowerGlobalTLSAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95d0fac6e16735968fbd8325ff68faef">LowerToTLSGeneralDynamicModel</a> (GlobalAddressSDNode *GA, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b7c52ad6336a9f677a96540aab5425">LowerToTLSExecModels</a> (GlobalAddressSDNode *GA, SelectionDAG &amp;DAG, TLSModel::Model model) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dbcbce1e033b60c540830bb38601e21">LowerGlobalTLSAddressDarwin</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a TLS address reference into the correct sequence of loads and calls to compute the variable's address for Darwin, and return an <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> containing the final node. <a href="#a2dbcbce1e033b60c540830bb38601e21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05929c59f5173372ff77d6d979b3d9ef">LowerGlobalTLSAddressWindows</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7f4f97fd0181da2227396b991ab341b">LowerBR_JT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9952b138aea0cf52f4d1f8e0abecccf9">LowerSignedALUO</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1690bcb25474c6979929abcdfecadaf">LowerUnsignedALUO</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b3ff188883cf05611e3f9c3d2d3624c">LowerSELECT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a634d5b1edf055e17124816c545badcc7">LowerSELECT_CC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a282be0e64fa41462de6c541d5a074218">LowerBRCOND</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0f5922666ccf2b3bd52dfa45d837beb">LowerBR_CC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51993a42ac0fdbadd7f46f2186157f65">LowerFCOPYSIGN</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a8784d435d69fd3150ed322915511d6">LowerRETURNADDR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb71a2ef295f0ce110f9fa14f089e7ca">LowerFRAMEADDR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53fd5ede562a640f2cb7041dfd18b530">LowerShiftRightParts</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerShiftRightParts - Lower SRA_PARTS, which returns two i32 values and take a 2 x i32 value to shift plus a shift amount. <a href="#a53fd5ede562a640f2cb7041dfd18b530">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a873cea6a2a5cb4d6c168c4f965ea8b7a">LowerShiftLeftParts</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerShiftLeftParts - Lower SHL_PARTS, which returns two i32 values and take a 2 x i32 value to shift plus a shift amount. <a href="#a873cea6a2a5cb4d6c168c4f965ea8b7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a137304ab3989feaa7bab755ef508a5dc">LowerGET_ROUNDING</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d3c5b2c9075e29469aa7d8a3a65ebb">LowerSET_ROUNDING</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18d99a8e2d56bcd116335aaa618181c8">LowerSET_FPMODE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38378e40e27adee3793a10bf963b4814">LowerRESET_FPMODE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a871fce7b5d7fd23a8ee426ec861ccd93">LowerConstantFP</a> (SDValue Op, SelectionDAG &amp;DAG, const ARMSubtarget *ST) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6646aa47f093829d2c3844cfb0aa1950">LowerBUILD_VECTOR</a> (SDValue Op, SelectionDAG &amp;DAG, const ARMSubtarget *ST) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f3ba1e97e75af1cc395562e4f7125ad">LowerINSERT_VECTOR_ELT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd7a5c6358256c2295b8597626fc3162">LowerFSINCOS</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ece6203dfa266e06c31e9b124431cfc">LowerDivRem</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15d76106ae330424717631598c42d6c8">LowerDIV_Windows</a> (SDValue Op, SelectionDAG &amp;DAG, bool Signed) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bb5b6982bd11ece0da896aca7f4e4d5">ExpandDIV_Windows</a> (SDValue Op, SelectionDAG &amp;DAG, bool Signed, SmallVectorImpl&lt; SDValue &gt; &amp;Results) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57e45922b1195dcfa1b4cc1367db5a2c">ExpandBITCAST</a> (SDNode *N, SelectionDAG &amp;DAG, const ARMSubtarget *Subtarget) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ExpandBITCAST - If the target supports VFP, this function is called to expand a bit convert where either the source or destination type is i64 to use a VMOVDRR or VMOVRRD node. <a href="#a57e45922b1195dcfa1b4cc1367db5a2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5124d1e0784c65f24e1d1d0f2a969bee">LowerWindowsDIVLibCall</a> (SDValue Op, SelectionDAG &amp;DAG, bool Signed, SDValue &amp;Chain) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ddb264636e9ea0ba5b3672c8365e9fc">LowerREM</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eccdd320eb017b7dd6e158a0adb099e">LowerDYNAMIC_STACKALLOC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9211b2847202828eb88a7bfcfaa9e82">LowerFP_ROUND</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9897472b32b5230a0f78a5f586557b23">LowerFP_EXTEND</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac856116a50b5ab09bcf4fb3c8f8f4c91">LowerFP_TO_INT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04d456aa10a892f7f33b606b1924e2e5">LowerINT_TO_FP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65373dfde88329ccea1039599a3aeb48">LowerFSETCC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5874b3ace9c92e0a853f98a864103b9">LowerSPONENTRY</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1cd1884905c2bad13d5c8582f981227">LowerLOAD</a> (SDNode *N, SmallVectorImpl&lt; SDValue &gt; &amp;Results, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a922daf0d66e6124172d2320e373537">LowerFP_TO_BF16</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42e89d9458ea2af6224c3b56af88f066">getRegisterByName</a> (const char *RegName, LLT VT, const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the name passed in. <a href="#a42e89d9458ea2af6224c3b56af88f066">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e8b4eb968b1f6412b23ef0baa55b6f1">BuildSDIVPow2</a> (SDNode *N, const APInt &amp;Divisor, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDNode * &gt; &amp;Created) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets may override this function to provide custom SDIV lowering for power-of-2 denominators. <a href="#a1e8b4eb968b1f6412b23ef0baa55b6f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac48f419669ab0b9a751f884606ccc49b">isFMAFasterThanFMulAndFAdd</a> (const MachineFunction &amp;MF, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isFMAFasterThanFMulAndFAdd - Return true if an FMA operation is faster than a pair of fmul and fadd instructions. <a href="#ac48f419669ab0b9a751f884606ccc49b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17d9202c0f6ac2746ee40f0e019bc262">MoveToHPR</a> (const SDLoc &amp;dl, SelectionDAG &amp;DAG, MVT LocVT, MVT ValVT, SDValue Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb3e23e27ca252f0f9248eebdc01f1ac">MoveFromHPR</a> (const SDLoc &amp;dl, SelectionDAG &amp;DAG, MVT LocVT, MVT ValVT, SDValue Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a884055cd4febec79f40b2c284f90ddd6">ReconstructShuffle</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace830275fdea087ca4d6f6c52f1e04a1">LowerCallResult</a> (SDValue Chain, SDValue InGlue, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals, bool isThisReturn, SDValue ThisVal, bool isCmseNSCall) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerCallResult - Lower the result values of a call into the appropriate copies out of appropriate physical registers. <a href="#ace830275fdea087ca4d6f6c52f1e04a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56e5bebb5bc62cac9b74ce94786af2b4">supportSplitCSR</a> (MachineFunction *MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports that a subset of CSRs for the given machine function is handled explicitly via copies. <a href="#a56e5bebb5bc62cac9b74ce94786af2b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f893c822505e63e2545ecec9e27e7e1">initializeSplitCSR</a> (MachineBasicBlock *Entry) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform necessary initialization to handle a subset of CSRs explicitly via copies. <a href="#a7f893c822505e63e2545ecec9e27e7e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34789179f0d8d7b94ed6fd3adbc1fe0e">insertCopiesSplitCSR</a> (MachineBasicBlock *Entry, const SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;Exits) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert explicit copies in entry and exit blocks. <a href="#a34789179f0d8d7b94ed6fd3adbc1fe0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f433fadbf766696faf1f5df340cd92e">splitValueIntoRegisterParts</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Val, SDValue *Parts, unsigned NumParts, MVT PartVT, std::optional&lt; CallingConv::ID &gt; CC) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-specific splitting of values into parts that fit a register storing a legal type. <a href="#a0f433fadbf766696faf1f5df340cd92e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec6dd7827fb0a7fae56f6ce5d4903293">joinRegisterPartsIntoValue</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, const SDValue *Parts, unsigned NumParts, MVT PartVT, EVT ValueVT, std::optional&lt; CallingConv::ID &gt; CC) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-specific combining of register parts into its original value. <a href="#aec6dd7827fb0a7fae56f6ce5d4903293">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac23d3c5f6357e58dca0887a532cfc4f8">LowerFormalArguments</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower the incoming (formal) arguments, described by the Ins array, into the specified DAG. <a href="#ac23d3c5f6357e58dca0887a532cfc4f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a871d25d82ea38d53b0dec06d0068e746">StoreByValRegs</a> (CCState &amp;CCInfo, SelectionDAG &amp;DAG, const SDLoc &amp;dl, SDValue &amp;Chain, const Value *OrigArg, unsigned InRegsParamRecordIdx, int ArgOffset, unsigned ArgSize) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c79a1b9dc21e04038393b70f4141dae">VarArgStyleRegisters</a> (CCState &amp;CCInfo, SelectionDAG &amp;DAG, const SDLoc &amp;dl, SDValue &amp;Chain, unsigned ArgOffset, unsigned TotalArgRegsSaveSize, bool ForceMutable=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fc0dc16280b0a77b040182ecfa553b6">LowerCall</a> (TargetLowering::CallLoweringInfo &amp;CLI, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerCall - Lowering a call into a callseq_start &lt;- <a href="/web-llvm/docs/api/namespaces/llvm/armisd">ARMISD</a>:CALL &lt;- callseq_end chain. <a href="#a3fc0dc16280b0a77b040182ecfa553b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0905a31df6247cbe0234417c7bbd689d">HandleByVal</a> (CCState *, unsigned &amp;, Align) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HandleByVal - Target-specific cleanup for ByVal support. <a href="#a0905a31df6247cbe0234417c7bbd689d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7985d6b61d7ad4454debc68df7b66c5c">IsEligibleForTailCallOptimization</a> (TargetLowering::CallLoweringInfo &amp;CLI, CCState &amp;CCInfo, SmallVectorImpl&lt; CCValAssign &gt; &amp;ArgLocs, const bool isIndirect) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsEligibleForTailCallOptimization - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the call is eligible for tail call optimization. <a href="#a7985d6b61d7ad4454debc68df7b66c5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f51a2a30fc4f094416e0f26bc9a662c">CanLowerReturn</a> (CallingConv::ID CallConv, MachineFunction &amp;MF, bool isVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, LLVMContext &amp;Context, const Type *RetTy) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook should be implemented to check whether the return values described by the Outs array can fit into the return registers. <a href="#a8f51a2a30fc4f094416e0f26bc9a662c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab70b9f5bdfbcb2da38b472944170d0cb">LowerReturn</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; SDValue &gt; &amp;OutVals, const SDLoc &amp;dl, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower outgoing return values, described by the Outs array, into the specified DAG. <a href="#ab70b9f5bdfbcb2da38b472944170d0cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5afa9e78790088d5ff897bbfda692ea2">isUsedByReturnOnly</a> (SDNode *N, SDValue &amp;Chain) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if result of the specified node is used by a return node only. <a href="#a5afa9e78790088d5ff897bbfda692ea2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbb1a5566c3284376a54bf371a819867">mayBeEmittedAsTailCall</a> (const CallInst *CI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target may be able emit the call instruction as a tail call. <a href="#acbb1a5566c3284376a54bf371a819867">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a7f3a0127fc2621b8a5c1cc413e663f">shouldConsiderGEPOffsetSplit</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a026fddfc3c2731eb86202c49d48acc80">isUnsupportedFloatingType</a> (EVT VT) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc177b05ec8021482d8e9f68f6b8622e">getCMOV</a> (const SDLoc &amp;dl, EVT VT, SDValue FalseVal, SDValue TrueVal, SDValue ARMcc, SDValue Flags, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ba004626656f316777a3653cdace220">getARMCmp</a> (SDValue LHS, SDValue RHS, ISD::CondCode CC, SDValue &amp;ARMcc, SelectionDAG &amp;DAG, const SDLoc &amp;dl) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns appropriate <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> CMP (cmp) and corresponding condition code for the given operands. <a href="#a2ba004626656f316777a3653cdace220">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82c95e144a0b2664e06f4ac192816b48">getVFPCmp</a> (SDValue LHS, SDValue RHS, SelectionDAG &amp;DAG, const SDLoc &amp;dl, bool Signaling=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a appropriate VFP CMP (fcmp{s|d}+fmstat) for the given operands. <a href="#a82c95e144a0b2664e06f4ac192816b48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57080f36f8a167615995084afbdc55a5">OptimizeVFPBrcond</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OptimizeVFPBrcond - With -enable-unsafe-fp-math, it's legal to optimize some f32 and even f64 comparisons to integer ones. <a href="#a57080f36f8a167615995084afbdc55a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af585f97d03559f473ecfacc16189d998">SetupEntryBlockForSjLj</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB, MachineBasicBlock *DispatchBB, int FI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SetupEntryBlockForSjLj - Insert code into the entry block that creates and registers the function context. <a href="#af585f97d03559f473ecfacc16189d998">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a6eebb750ae8942e6a9074b71c15f5f">EmitSjLjDispatchBlock</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab400019546a5c0de6a4b29960fdb287c">EmitStructByval</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b33868c828458f055b989c08b7ad513">EmitLowered__chkstk</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51ad4afc48a9a86013cd21f534842cdd">EmitLowered__dbzchk</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae65f0d269ecefa64da1246db7134eec7">addMVEVectorTypes</a> (bool HasMVEFP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a6eb2899b9a24ed9063e600c2a79af">addAllExtLoads</a> (const MVT From, const MVT To, LegalizeAction Action)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eadc96f61d20a21fce5437a2f32ff84">setAllExpand</a> (MVT VT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adad0a13862540448dc499b968825db2f">Subtarget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtarget - Keep a pointer to the <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> around so that we can make the right decision when generating code for different targets. <a href="#adad0a13862540448dc499b968825db2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8060c65d0518e0adb371e6c77016cb29">RegInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a991cd453a4ab09cfdfa0a54f04a93d7f">Itins</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae46dcbe9fa686bfd30f96f741e568ce0">InsertFencesForAtomic</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a959d52fdd37e3368d62d803c8ccfef1b">HasStandaloneRem</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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


<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### RegsToPassVector {#a132da2f7fdd456d04553e7bf0fb458e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ARMTargetLowering::RegsToPassVector =  SmallVector&lt;std::pair&lt;unsigned, SDValue&gt;, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### ByValCopyKind {#a13d08bccbe19ea45b7318cdb0ba1f673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMTargetLowering::ByValCopyKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoCopy<a id="a13d08bccbe19ea45b7318cdb0ba1f673ae97e02b4d71dc307c2a4b7e608673047"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CopyOnce<a id="a13d08bccbe19ea45b7318cdb0ba1f673a4bb1eea28271fe2cf0d38a6f00901827"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CopyViaTemp<a id="a13d08bccbe19ea45b7318cdb0ba1f673a730b2af59d9ba19dd57bfe9f0bcdeaec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ARMTargetLowering() {#aa782c58995f9a6e00cf5a8500a9a8508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMTargetLowering::ARMTargetLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> &amp; STI)</td>
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



<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7c45a718f16057459d95d09d42ec6902">llvm::TargetLoweringBase::addRegisterClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca6460922e7050fc0dcff22631e4bc7fdb">llvm::CallingConv::ARM_AAPCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf5725080d76d25fff371be12a0bf29f4">llvm::CallingConv::ARM_AAPCS_VFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca39e4f9a6d108588930a09d779d4e812f">llvm::CallingConv::ARM_APCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9c91befeca2a25c8050d4c3dff8b6d67">llvm::ISD::ATOMIC_CMP_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a385d7f9c63f921a2b28e8426e4101de8">llvm::ISD::ATOMIC_FENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c47226f266248f4b8c155b83601b109">llvm::ISD::ATOMIC_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf5f612de1a25451c9a0c33d77bf3e74">llvm::ISD::ATOMIC_LOAD_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a905925a49cdc6b4a6017d215820dad30">llvm::ISD::ATOMIC_LOAD_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1cf8547d612d954d34aab1d4f78e7fa1">llvm::ISD::ATOMIC_LOAD_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7049708cb0e0703a467b95a506293aec">llvm::ISD::ATOMIC_LOAD_MIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a13a3e6402abf972278c6a7d5ee509f9d">llvm::ISD::ATOMIC_LOAD_NAND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4112a866197a97a70bdc78ef92c79b4c">llvm::ISD::ATOMIC_LOAD_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3d12dbff6e50803982d0e92768a1479">llvm::ISD::ATOMIC_LOAD_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ca44a643714809ef384e7494604db14">llvm::ISD::ATOMIC_LOAD_UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1ff6f20a9255f7a333f4c9d25393674c">llvm::ISD::ATOMIC_LOAD_UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a428ec1341b34eafa63518914e7f5ddf0">llvm::ISD::ATOMIC_LOAD_XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1db943abc1bf78a911daeb7b03d81de8">llvm::ISD::ATOMIC_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad728a4b56d49f39375881511d8d3118d">llvm::ISD::ATOMIC_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdae7178e801a788f47e55ad3db3ee6a">llvm::ISD::BF16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeea401cc0b7fa5aa6f4d3a0612140e1d">llvm::ISD::BITREVERSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb">llvm::ISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716d19ebad1927a2e8dd5fe3f951f882">llvm::ISD::BR_JT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6df03220bbe2ea3cfb905f36fb26822c">llvm::TargetLoweringBase::computeRegisterProperties</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1be4c8da7c68a4c683de1a98b5cc5b9d">llvm::ISD::ConstantFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c">llvm::ISD::CTLZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0340c8d57d1dcebc43a00412989583d3">llvm::ISD::CTLZ_ZERO_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a991d07d163bd4d9984cf1ef36e92c214">llvm::ISD::CTPOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6da41a113af0909470baea7486b3386b">llvm::ISD::CTTZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a601e66a26efd05520f7cb26aef3af340">llvm::ISD::CTTZ_ZERO_UNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa3441acf8576e4bbf48e9bd73ca3c0d8c">llvm::TargetLoweringBase::Custom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a967fcb624e84458e135a763d1c11346a">llvm::ISD::DEBUGTRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa71ac22470bf853868fe6b39a25bac72">llvm::ISD::DYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada924e855250645672a493841803ff91ad5865a4955dbe66e3ad828972652afc8">llvm::EABI4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada924e855250645672a493841803ff91a1dd7700dd895cad56315f984f1d24c23">llvm::EABI5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a122a450e069003dc86859ef47ab6e278">llvm::ISD::EH_SJLJ_LONGJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae5a57fe9fd413df909ab121ca1a813c7">llvm::ISD::EH_SJLJ_SETJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2e0f3a93e85a46b2ebac7330c2a0c581">llvm::ISD::EH_SJLJ_SETUP_DISPATCH</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa4b85349547c5b6126817e10152007931">llvm::TargetLoweringBase::Expand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">llvm::ISD::EXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2b4d07600495a563319d6a3dda8dc44d">llvm::ISD::FABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad56e9199ae3993a09af36ff41d327a11">llvm::ISD::FCEIL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeffc3319657e213a530ce583603f7221">llvm::ISD::FCOPYSIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9133d7cfb6a66404ff7757b699bc3941">llvm::ISD::FCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abc6c09c7af98236460f0b020eb3be94e">llvm::ISD::FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad49a46d391f73aa96002adbdd0cf03f5">llvm::ISD::FEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a37c80ce3312d3fc5b925e326a16fff20">llvm::ISD::FEXP10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af3542a99501ffb93cee4aae9d1ec2d05">llvm::ISD::FEXP2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4336c27826676e1ef61383cafa999219">llvm::ISD::FFLOOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad9e6c8353bc9d023077590083cfce89c">llvm::ISD::FFREXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a130b6a6d409367c8a61dd14dfa39785c">llvm::ISD::FGETSIGN</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a850652b63276e9d79e6c1e05146c84c0">llvm::MVT::fixedlen_vector_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a455f49e18d470b97cd293acd7fbdf169">llvm::ISD::FLDEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac82d37f93ae4420659acdd03f79b15e0">llvm::ISD::FLOG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0d05d4a5cd10a46f69f9e62d49d275bb">llvm::ISD::FLOG10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a558dc710055f9d60cc3c0893bc29a72d">llvm::ISD::FLOG2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3dfd1b187d121c0e214698eef1c20f53">llvm::ISD::FMAXIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a632dd4bb044d5cd11f671d176ef495f2">llvm::ISD::FMAXNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac27a43f98abb2d1ee2f2ce99a0b34b36">llvm::ISD::FMINIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9f59cc264907eb86e29564d5f6a5b213">llvm::ISD::FMINNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178">llvm::ISD::FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2dc876d6cc16ac04376483552292f9f4">llvm::ISD::FNEARBYINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d26c45c040d8f85d577a5f645261d1a">llvm::ISD::FNEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3e12fcc9960ef3bf0ae5876382d4c66f">llvm::ISD::FP16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0bb173b5a879225092abdeaba1394839">llvm::ISD::FP_TO_BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a38f379e4fddf750c36f1323a04d12171">llvm::ISD::FP_TO_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae4a4e2126c6db34e2dfd71b6bd0408ee">llvm::ISD::FP_TO_SINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98661814400e72a77f5ed4e088c06937">llvm::ISD::FP_TO_UINT_SAT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#adfa86eda5d29b10227c46b4d8f071148">llvm::MVT::fp_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1a6952b1572a4ce241cc3cf45a9ab071">llvm::ISD::FPOW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a66b7368b776f6aff492cf970db3df548">llvm::ISD::FPOWI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdd7bbb76dac7962dda6e116e33699da">llvm::ISD::FREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a68014623710f7a44c808cd412236d6a1">llvm::ISD::FRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a87b7dd3d6a9b68d1558fc6b4706708b0">llvm::ISD::FROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad46ae9fdfe20cd04f7fda7ccbb937543">llvm::ISD::FSIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6ba8fc92ee5081d3e533cb5322f74f29">llvm::ISD::FSINCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae1118ddac1ce0af8e9f7cc16c9e94fc0">llvm::ISD::FSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad">llvm::ISD::FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9edaaccfce9ddf3113d737686f0a019e">llvm::ISD::FTAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1e92ea554489509b0ad970901bcc715b">llvm::ISD::FTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8ca22b32a18bb7959b6f6f9b18d14ec0">llvm::ISD::GET_FPENV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8ba51b127e01a9e6412e7629c70ec4a1">llvm::ISD::GET_FPMODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89f3afc3fa907ff83759c6c76d97a973">llvm::ISD::GET_ROUNDING</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae365cf8f9a6844685be3fd9f12956c33">llvm::TargetLoweringBase::getLibcallName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/floatabi/#aea077c52d84934aabf9445cef9eab2e2a52066a0a0a66d77e9451d36b978b9a99">llvm::FloatABI::Hard</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sched/#ab8d854a5ce2331586bcc6830cca52f0fa6530ebdb4e713581540e6ceb88897acb">llvm::Sched::Hybrid</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a2239343bf72ef6a991165363ac0386c3">im</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">llvm::ISD::INSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a19cb5cb13066089592de60118998d9f8">llvm::MVT::integer_fixedlen_vector_valuetypes</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7b339f69bc3995d23399a85f81af6018">llvm::MVT::integer_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0248ed29f933c5faa55cbdfebf3139bd">llvm::TargetLoweringBase::isOperationExpand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ae0010333b4e1424ce473b508d802bbbd">llvm::ISD::LAST_INDEXED_MODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aafb9a152dd1ee4089f5fc96a33c5c90d2">llvm::TargetLoweringBase::LibCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aefbee33131c130f8f691c9a482f5fc40">llvm::TargetLoweringBase::MaxStoresPerMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1695feb44cd6dd30c64697360f1e76d3">llvm::TargetLoweringBase::MaxStoresPerMemcpyOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6d0f43699563375800a45f45bc11ff49">llvm::TargetLoweringBase::MaxStoresPerMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7800cede44a09d00fcc61b9087c20d85">llvm::TargetLoweringBase::MaxStoresPerMemmoveOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9830bda9bf50bfdab4c10954cc6fb1ac">llvm::TargetLoweringBase::MaxStoresPerMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a67f472063b7db365d0b5da597871e03d">llvm::TargetLoweringBase::MaxStoresPerMemsetOptSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa2a7c3eccf06b41e4275bbeadb46d22e">llvm::ISD::MULHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8a80d3b085af08f0dce1724207ef99b5">llvm::ISD::MULHU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31a866c29237765ff291c9503abbdca60e1">llvm::ISD::POST_INC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31ab5bb854fadd42503c849c4a48d7f3d90">llvm::ISD::PRE_INC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cc366cf4e0b825191ca9babcf290286">llvm::TargetLoweringBase::PredictableSelectIsExpensive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a691a4c9004e9bd04d1c0bebc5df57443">llvm::ISD::PREFETCH</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aaba91ac521e4f01f57413216273fd7b7f">llvm::TargetLoweringBase::Promote</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92fceabd268d62ef2c95799a102b8abf">llvm::ISD::READ_REGISTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac43f9bea13e29622bbf18c861b52144d">llvm::ISD::READCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sched/#ab8d854a5ce2331586bcc6830cca52f0fa5b5fba18a61456ef5858005d9f7b153e">llvm::Sched::RegPressure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a23914569caa5dbe0d340c3fbfc277efc">llvm::ISD::RESET_FPENV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a386314479bc7963a544ed142866e7ece">llvm::ISD::RESET_FPMODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715">llvm::ISD::ROTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a863ec6ebb75bf89cfea14da646d77e92">llvm::ISD::SADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af1b946afff631cee7aa6de570bef7785">llvm::ISD::SADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a874f66e1efe5be79552bbe7ee3121a">llvm::ISD::SDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a07fcb2d341fc6f3db309618b30e358a8">llvm::ISD::SET_FPENV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a26b34eddab8969a79fd3cda432471809">llvm::ISD::SET_FPMODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4fe6c878350458de2c3182392f830988">llvm::ISD::SET_ROUNDING</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6b928e5a6718acab4fa0030ce9198e8a">llvm::TargetLoweringBase::setBooleanContents</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0662d63e058816bf77a5b8f35331bd9d">llvm::TargetLoweringBase::setBooleanVectorContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07aeded54fe1be320194e9ff0f5825df0e5">llvm::ISD::SETCC_INVALID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6bb33e400f29724907dc27ced04e9038">llvm::ISD::SETCCCARRY</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a11d5723c448d435dce77417ce2b8cb01">llvm::TargetLoweringBase::setCmpLibcallCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4978da84fa67e0aa3a513c27e6367e91">llvm::TargetLoweringBase::setIndexedLoadAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8257b6c2db03e8af1a87bb4d7cb8c878">llvm::TargetLoweringBase::setIndexedStoreAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3b258bf80e376a39c623bf880461894b">llvm::TargetLoweringBase::setLibcallCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8b36797b46a42e7b489e47c2d009bc1d">llvm::TargetLoweringBase::setLibcallName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad1d4d71bf37fea6a3170f27438d41e6d">llvm::TargetLoweringBase::setLoadExtAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4df001a3c611cc8b423ca0e54560210f">llvm::TargetLoweringBase::setMaxAtomicSizeInBitsSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a09373cbbdb4326098156b8dfdad4e8b2">llvm::TargetLoweringBase::setMaxDivRemBitWidthSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6566d8c65c03ad2f7b18ed08f0e7f208">llvm::TargetLoweringBase::setMinFunctionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a2544bef91bdf3e85c561e59a0e662292">llvm::TargetLoweringBase::setMinStackArgumentAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a07c0c67913bb543fc45ce9ef65ef260a">llvm::TargetLoweringBase::setOperationAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8bb50938977c871d4dfa617d1b759a9a">llvm::TargetLoweringBase::setPrefFunctionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4aebe88e5c44bdb37513651bc72c2889">llvm::TargetLoweringBase::setPrefLoopAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af2a24aed2ba5d4f9c8db9904df6fa635">llvm::TargetLoweringBase::setSchedulingPreference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab8a44fb1f49bcfbed806fef69301a67a">llvm::TargetLoweringBase::setStackPointerRegisterToSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac87dc82fa9f824a797198e7b0e16141d">llvm::TargetLoweringBase::setTargetDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa243085e56636cc454143f916686c190">llvm::TargetLoweringBase::setTruncStoreAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af3b59179b6fcbc89463181015ace8e9b">llvm::ISD::SMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaac895215ecbb3c411c957c8beb39b70">llvm::ISD::SMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1354c6f8508d6cd697dc89a5d9a52dfd">llvm::ISD::SMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6efe16ea597cfd8eeac26516fc992ee7">llvm::ISD::SSUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a77984d86d70df1f3229da7a5119652a9">llvm::ISD::SSUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a023a9de787026fe61b024476bf9c32cb">llvm::ISD::STACKRESTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a031ce694e40832d40a163d7254a8df14">llvm::ISD::STACKSAVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110addd63c6d866c8a8020a0cc4de467b285">llvm::ISD::STRICT_FLDEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac47e026e409ff39f319cbb3b096863e6">llvm::ISD::STRICT_FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2273d9cd04ba6e4a7c1a4b28ab1aaba">llvm::ISD::STRICT_FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed">llvm::ISD::STRICT_FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf955b4b70f63865e022c329d1775579">llvm::ISD::STRICT_FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0466b21bfb4f3596e41380d8e2d1956f">llvm::ISD::STRICT_FSETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c8d07d668872f2176fb34724cd799c4">llvm::ISD::STRICT_FSETCCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aaa96f111a59a7a2e7f9c689b344543df">llvm::TargetLowering::TargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac5fb8808f3dcb9f0a83f1fc2e7747485">llvm::ISD::TRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1ddf36330110b4abea43fe390bea9ef9">llvm::ISD::UADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0f1e3ed26108fec69eb97209c0e39bf">llvm::ISD::UADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5e433873c201ad85c30e42da1ae05977">llvm::ISD::UADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a257ffa49107e2db978e8a6e2688ada">llvm::ISD::UDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af675e759c0ffff8d48ea14a60fe3517b">llvm::ISD::UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a17126302da6199930e55e841ca1b082d">llvm::ISD::UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a79c959df09509d7ff66d9b04bc40d18d">llvm::ISD::UMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28">llvm::ISD::UREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4ffc75d65231b55461c0ba4f36a3e500">llvm::ISD::USUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac81ebcd59d629d8680e50ffba9855255">llvm::ISD::USUBO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89166b38f12c0bd3e8a61d8f1a5a8bc8">llvm::ISD::USUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae77d03846b31c41c4860bcd96d780a78">llvm::ISD::VAARG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a804c1960ac64628cdd1f74d7de885284">llvm::ISD::VACOPY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1aadbb14ab26b74d841ac003363e3a5d">llvm::ISD::VAEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adfe32beaa596a1512b17e66b46e773ed">llvm::ISD::VASTART</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89a8ec08f6908a989c2d0198ae8851f9">llvm::ISD::VECREDUCE_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c057571f4591494880ec0bba023e0c2">llvm::ISD::VECREDUCE_SMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a11825b59a52b4f5a73c0b877e1ba0e70">llvm::ISD::VECREDUCE_SMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7ce9f75eaf17256deb960b11d1930040">llvm::ISD::VECREDUCE_UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab67678c3310e505df1a3f7677b14cfb0">llvm::ISD::VECREDUCE_UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0b7d2c769fd0fbaab3c4a2fc8e7ea0c">llvm::ISD::VSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a61a1595d03afe86764ad7625d358608e">llvm::ISD::WRITE_REGISTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a695a19c9c3ae14638be151add82755cb">llvm::TargetLoweringBase::ZeroOrNegativeOneBooleanContent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a0e2d72cfdcc49d2d189f440b3cc31dff">llvm::TargetLoweringBase::ZeroOrOneBooleanContent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AdjustInstrPostInstrSelection() {#a6cdddfff71264f7e1e744fdea34085d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::AdjustInstrPostInstrSelection (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
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

<p>This method should be implemented by targets that mark instructions with the 'hasPostISelHook' flag.</p>


<p>These instructions must be adjusted after instruction selection by target hooks. e.g. To fill in optional defs for <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> 's' setting instructions.</p>


<p>Declaration at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 12452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af4262eaffe5f263e48ab59372d7c8acb">attachMEMCPYScratchRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af38d3efc162ab4c4fc14f9220c142b91">llvm::convertAddSubFlagsOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aed8d139ece631812f972a8cc074adc55">llvm::MachineOperand::setIsDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#aaa8eb58fd1b8466eb64a43df890cb8c1ae01b27a05209c02ca1bdb5a6033731fb">llvm::MCOI::TIED_TO</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### alignLoopsWithOptSize() {#ad86ed5000dd0596a904dab2bb4f3fac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::alignLoopsWithOptSize ()</td>
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

<p>Should loops be aligned even when the function is marked OptSize (but not MinSize).</p>

<p>Declaration at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### allowsMisalignedMemoryAccesses() {#ac897a80df1070effb9d5a5b6a023c5d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::allowsMisalignedMemoryAccesses (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, unsigned AddrSpace, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dd">MachineMemOperand::Flags</a> Flags, unsigned * Fast)</td>
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

<p>allowsMisalignedMemoryAccesses - Returns true if the target allows unaligned memory accesses of the specified type.</p>


<p>Returns whether it is "fast" by reference in the second argument.</p>


<p>Declaration at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>


<p>Referenced by <a href="#abd29a7e70a14fb7b45ff277e5c935424">getOptimalMemOpType</a>.</p>

</div>
</div>

### allowTruncateForTailCall() {#adaf74e11d3b6f4feaee9dd7711e92202}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::allowTruncateForTailCall (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * FromTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ToTy)</td>
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

<p>Return true if a truncation from FromTy to ToTy is permitted when deciding whether a call is in tail position.</p>


<p>Typically this means that both results would be assigned to the same register or stack slot, but it could mean the target performs adequate checks of its own before proceeding with the tail call. Targets must return false when FromTy &lt;= ToTy.</p>


<p>Declaration at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>.</p>

</div>
</div>

### canCombineStoreAndExtract() {#ad07ba9d946b424c9de4782f4ae7879bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::canCombineStoreAndExtract (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * VectorTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Idx, unsigned &amp; Cost)</td>
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

<p>Return true if the target can combine store(extractelement VectorTy,
Idx).</p>


<p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a></span>[out] gives the cost of that transformation when this is true.</p>


<p>Declaration at line 699 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad0709baa705ae62c4e09cdd47fb4b420">llvm::Type::isFPOrFPVectorTy</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>.</p>

</div>
</div>

### canMergeStoresTo() {#ad4d6848e5070beeb8a9d0a8711ecd671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMTargetLowering::canMergeStoresTo (unsigned AS, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> MemVT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Returns if it's reasonable to merge stores to MemVT size.</p>

<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>.</p>

</div>
</div>

### CCAssignFnForCall() {#ac7d63117d31743dd436a9011a55275b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCAssignFn * ARMTargetLowering::CCAssignFnForCall (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, bool isVarArg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 2150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>.</p>

</div>
</div>

### CCAssignFnForReturn() {#a6990f5e5739473df0609344f992051a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCAssignFn * ARMTargetLowering::CCAssignFnForReturn (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, bool isVarArg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 2155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>.</p>

</div>
</div>

### computeKnownBitsForTargetNode() {#a3e4b8ac086cdc9c81f7c2eabd77394fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::computeKnownBitsForTargetNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth)</td>
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


<p>Declaration at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19995 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a7a4bd85cb03fa4d3b2c5c67cd4af39a5">llvm::KnownBits::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a41f4297f00dc6d8d7445d13daf7eba26">llvm::ARMISD::ADDC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a38281aedc70f7c707027367acd3234cb">llvm::ARMISD::ADDE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a109dda4df2be3a46022e3600484f4efb">llvm::ARMISD::BFI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aee74cff1cb1ea095617b5fa044e342db">llvm::ARMISD::CMOV</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38abc844212c86a5d4665e522f7a7de6610">llvm::ARMISD::CSINC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7fa873eda688ec241983ec07abb187bb">llvm::ARMISD::CSINV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a2f975a28397d8aaddaf658d8f09f0086">llvm::ARMISD::CSNEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a74b17cf9d0ee8268a5b38bbb896a30ba">llvm::ConstantSDNode::getAPIntValue</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a4fdc09049a61f952b5d52788dbd2f69b">llvm::KnownBits::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adcb96bd09d7c75c7669fa5f9d1190899">llvm::APInt::getHighBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a5cb49674ec65724b4d9aecb48588a13a">llvm::ConstantSDNode::getZExtValue</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a76e45a40f2f0b5b09132d1de119765e8">llvm::KnownBits::intersectWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a86775f3d85d98a31b2751e1eb348ea">llvm::isNullConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a28cf355963391ab8781b2347d495553d">llvm::KnownBits::isUnknown</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a066220c7a472d8793de64a0ad23487d2">llvm::KnownBits::makeConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#abd85d08f35600dd19615a1efe9cacb1d">llvm::KnownBits::mul</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a538f22b4ea2ff04a0b41403f26eaeb67">llvm::KnownBits::resetAll</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a781ca23d84995ffb2efaa51267053c19">llvm::KnownBits::sext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9cfc13d8dfcbb7d035be110b619ea741">llvm::ARMISD::SUBC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a06e89dbcfaf0ceca94295988d35809c2">llvm::ARMISD::SUBE</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a29bc6cd8219e70572b8b113c230fea6e">llvm::ARMISD::VGETLANEs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ad78d1cfc271b51dc1c87c91401b87c57">llvm::ARMISD::VGETLANEu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a3b1cd1c01c04128536b9cbe473629904">llvm::ARMISD::VMOVrh</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a51c3c203b80468b8761416d14e6f5b7f">llvm::KnownBits::zext</a>.</p>

</div>
</div>

### convertSetCCLogicToBitwiseLogic() {#a8f2ba5f07dc33b4bc9b5f75cc71c731d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMTargetLowering::convertSetCCLogicToBitwiseLogic (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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


<p>Definition at line 711 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#ad958859a7af278dd5ea2b593c2b25050">llvm::EVT::isScalarInteger</a>.</p>

</div>
</div>

### createComplexDeinterleavingIR() {#a5098d4bb22d4347dc55e1d08dcbe6708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ARMTargetLowering::createComplexDeinterleavingIR (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764">ComplexDeinterleavingOperation</a> OperationType, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ffbf98bd55746f804742b79f524ac7f">ComplexDeinterleavingRotation</a> Rotation, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * InputA, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * InputB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Accumulator=nullptr)</td>
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

<p>Create the IR node for the given complex deinterleaving operation.</p>


<p>If one cannot be created using all the given inputs, nullptr should be returned.</p>


<p>Declaration at line 772 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 22047 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#abb0a82cf9ab3cf0c256918c17512f987aa66d3974b6f2e3a542f896da144cd297">Accumulator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a8a6707a9048ed67adda5b5ade0ecdd41">llvm::CAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a9088901adcdb08d0856fd32e6e61e320">llvm::CMulPartial</a>, <a href="#a5098d4bb22d4347dc55e1d08dcbe6708">createComplexDeinterleavingIR</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ffbf98bd55746f804742b79f524ac7fa982956baaa7aa7989b38a9378f00bdbd">llvm::Rotation_270</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ffbf98bd55746f804742b79f524ac7fad3d2ab4f01286661a3d4e97a4b362b9c">llvm::Rotation_90</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a886094eaed7ce32029ea52a641142b88">llvm::to_vector</a>.</p>


<p>Referenced by <a href="#a5098d4bb22d4347dc55e1d08dcbe6708">createComplexDeinterleavingIR</a>.</p>

</div>
</div>

### createFastISel() {#a6b62f6b6087313bdaea9534ec0b6f06d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastISel * ARMTargetLowering::createFastISel (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; funcInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * libInfo)</td>
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

<p>createFastISel - This method returns a target specific <a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> object, or null if the target does not support "fast" ISel.</p>

<p>Declaration at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 1981 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aa23959d9b3463aec95209a1fe73c1e3f">llvm::ARM::createFastISel</a>.</p>

</div>
</div>

### emitAtomicCmpXchgNoStoreLLBalance() {#a2b39ae6869400e3aad61ff8c837d0006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::emitAtomicCmpXchgNoStoreLLBalance (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder)</td>
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



<p>Declaration at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21479 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>.</p>

</div>
</div>

### EmitInstrWithCustomInserter() {#a6820d09b4db5654cd1377d3ab63b3e01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * ARMTargetLowering::EmitInstrWithCustomInserter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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


<p>Declaration at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 12038 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acce9c12cc977a88dc7bc51493ce7681c">llvm::MachineBasicBlock::addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae565d45627e1678a3e37bd6a016c561c">llvm::MachineInstrBuilder::addMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a5ffb77c69d69a5beff906caaecfd7be4">llvm::MachineBasicBlock::canFallThrough</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a551cf4f2a46a96b347d222acc8df059c">checkAndUpdateCPSRKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad84ebe08bb098cd283e922fd186f77e9">llvm::MachineInstrBuilder::cloneMemRefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad2c3e98260a6eb6daa3ba1da72a45e05">llvm::condCodeOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a4f1d9a9a0660bc80837984980c7ba402">llvm::ARMCC::EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad26bff839257f220557ce812b2159c72">llvm::MachineBasicBlock::erase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a451ac66d74cbee6582c570a71254ae26">genTPEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afd62dcc07699f0f98ae897208c1529ae">genTPLoopBody</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a29a2545f60f5e7f7cffd5e66b0d4cf87">llvm::ARM_AM::getAM2Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#acda0e957b0c23c9beaa0d98238e140f3">llvm::ARM_AM::getAM2Op</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4874816314c3308be0bf1e71de2078d8">llvm::MachineBasicBlock::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a31aa2680ec79198a4c94f35b3a1ad97e">llvm::MachineBasicBlock::getFallThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#a4bd63de978510703f28cd98ea7c0ffa5">llvm::ARMCC::getOppositeCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac1f888bba00f32cb4f9a0010c958f397">llvm::MachineFunction::getProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6af6284b830f5e4fe2a8ddb9ff1a25ee46">llvm::ARMCC::MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#af3c2dc75190645b72eee3c416cd14885">llvm::MachineBasicBlock::moveAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6ae08639a6e0f682daf9d9b4809ee0cf7c">llvm::ARMCC::NE</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a76eece0bfd57256980609b66faaef22c">llvm::MachineFunctionProperties::NoPHIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8b40fbeafc509f3002aa980e2a0662a1">OtherSucc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a70b0525ecc6022336feb019ff63c934c">llvm::MachineFunction::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#af2f789465ed765ac2795381e8b91b902">llvm::MachineFunctionProperties::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4472755d36621c5e2d056eec5056202e">llvm::MachineBasicBlock::setCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ac0bfa894f538166cb476b439a2cb0aea">llvm::MachineBasicBlock::splitAt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">llvm::ARM_AM::sub</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### emitLeadingFence() {#afa79830ec972611f4c1d1f8e23266aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * ARMTargetLowering::emitLeadingFence (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ord)</td>
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


<p>Declaration at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a960fbd067612ca87e16d5dfdb12fe40a">llvm::AcquireRelease</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a409415e274680c5d72d3272a1cee3d95">llvm::Instruction::hasAtomicStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-mb/#ad70272e2a9ec2a7e3a497458e1edbc85a5d590944cad68ea77c8645fef111801e">llvm::ARM_MB::ISH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-mb/#ad70272e2a9ec2a7e3a497458e1edbc85a8a7f29f5965f4969d7a34c42ad38b6b1">llvm::ARM_MB::ISHST</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#abb0c61c0a16596abc08a5c2dc7fcddd8">makeDMB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a14194d0b2e6c6680067975517cd58eac">llvm::Monotonic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>

</div>
</div>

### emitLoadLinked() {#ab439771b84f342c37a8823fb2f797642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ARMTargetLowering::emitLoadLinked (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValueTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ord)</td>
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

<p>Perform a load-linked operation on Addr, returning a "Value *" with the corresponding pointee type.</p>


<p>This may entail some non-trivial operations to truncate or reconstruct types that will be illegal in the backend. See ARMISelLowering for an example implementation.</p>


<p>Declaration at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21444 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae5d05ec2b9a60806746addff3f2a71a9">llvm::CallBase::addParamAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ade4ee38419ac3921c718b634571033e4">llvm::IRBuilderBase::CreateTruncOrBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abbc497e16b1809ff526b1c755483d35c">llvm::isAcquireOrStronger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### emitStoreConditional() {#a68bc08431f00987920ce19e9a458e86d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ARMTargetLowering::emitStoreConditional (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ord)</td>
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

<p>Perform a store-conditional operation to Addr.</p>


<p>Return the status of the store. This should be 0 if the store succeeded, non-zero otherwise.</p>


<p>Declaration at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21486 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae5d05ec2b9a60806746addff3f2a71a9">llvm::CallBase::addParamAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a0032ae544ae429aaf1053767da90426d">llvm::IRBuilderBase::CreateZExtOrBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a1e415dc42f391c1d0cfcc1c28c00b2f4">llvm::FunctionType::getParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a586359566c841c85abfd8922e220213e">llvm::isReleaseOrStronger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### emitTrailingFence() {#a2ee99baef4e41314544119fa4a0e1ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * ARMTargetLowering::emitTrailingFence (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ord)</td>
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



<p>Declaration at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a960fbd067612ca87e16d5dfdb12fe40a">llvm::AcquireRelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-mb/#ad70272e2a9ec2a7e3a497458e1edbc85a5d590944cad68ea77c8645fef111801e">llvm::ARM_MB::ISH</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#abb0c61c0a16596abc08a5c2dc7fcddd8">makeDMB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a14194d0b2e6c6680067975517cd58eac">llvm::Monotonic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>

</div>
</div>

### ExpandInlineAsm() {#a4b23196df4c243ce29f29f54a26cae7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::ExpandInlineAsm (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *)</td>
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

<p>This hook allows the target to expand an inline asm call to be explicit llvm code if it wants to.</p>


<p>This is useful for turning simple inline asms into LLVM intrinsics, which gives the compiler more information about the behavior of the code.</p>


<p>Declaration at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a8d13199cbf4d080d3b5dcf330dad5d2c">llvm::CallBase::getCalledOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a1e07c1aec365d4862fe2edef28aeec38">llvm::IntrinsicLowering::LowerToByteSwap</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### finalizeLowering() {#a35198b01162433a12919d5a5947fbe83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::finalizeLowering (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Execute target specific actions to finalize target lowering.</p>


<p>This is used to set extra flags in MachineFrameInformation and freezing the set of reserved registers. The default implementation just freezes the set of reserved registers.</p>


<p>Declaration at line 747 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 22013 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a12da92f702a20d5337a5258038968d09">llvm::MachineFrameInfo::computeMaxCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a07e9067b95ae52ee880a08c7d132fd56">llvm::TargetLoweringBase::finalizeLowering</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>.</p>

</div>
</div>

### functionArgumentNeedsConsecutiveRegisters() {#ae4d962e48053d593dd7f02bb06f5710b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::functionArgumentNeedsConsecutiveRegisters (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Returns true if an argument of type Ty needs to be passed in a contiguous block of registers in calling convention CallConv.</p>


<p>Return true if a type is an AAPCS-VFP homogeneous aggregate or one of [N x i32] or [N x i64].</p>


<p>This allows front-ends to skip emitting padding when passing according to AAPCS rules.</p>


<p>Declaration at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21936 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf5725080d76d25fff371be12a0bf29f4">llvm::CallingConv::ARM_AAPCS_VFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a07f7c1d7e1a6e7f3be716a64dd3ccdb4ae3bddfb340dcfb58ede9f8455313d4c4">HA_UNKNOWN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae5128b768e54a43398c3d13bd6643de0">isHomogeneousAggregate</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### getABIAlignmentForCallingConv() {#a0ad154d5668d4704cbe075765d342251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align ARMTargetLowering::getABIAlignmentForCallingConv (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ArgTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Return the correct alignment for the current calling convention.</p>

<p>Declaration at line 750 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21920 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>.</p>

</div>
</div>

### getConstraintType() {#a367c0fd240000e247269dee3f2db8d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMTargetLowering::ConstraintType ARMTargetLowering::getConstraintType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint)</td>
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

<p>getConstraintType - Given a constraint letter, return the type of constraint it is for this target.</p>

<p>Declaration at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a7bc0fe0fa6be5eaabb77e46c8d9ab2c8">llvm::TargetLowering::C_Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a420d729d2e7d056ec884c094ccdc4467">llvm::TargetLowering::C_Memory</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a1d7718fd43ac0a5c715686a76f9cfd89">llvm::TargetLowering::C_RegisterClass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a45b2deb637d370d68d3bd3786c21e415">llvm::TargetLowering::getConstraintType</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### getExceptionPointerRegister() {#a0ea645bf4979099839a35654aac5d755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register ARMTargetLowering::getExceptionPointerRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PersonalityFn)</td>
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

<p>Declaration at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21952 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>

</div>
</div>

### getExceptionSelectorRegister() {#ab0632dd0936481e952514e2f8e18db07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register ARMTargetLowering::getExceptionSelectorRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PersonalityFn)</td>
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

<p>Declaration at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21959 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>

</div>
</div>

### getInlineAsmMemConstraint() {#a2543fc561fd405e07d0d993a7854b34f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAsm::ConstraintCode llvm::ARMTargetLowering::getInlineAsmMemConstraint (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ConstraintCode)</td>
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



<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a3acbc2d34d9a6d35b63a04f0ae20136c">llvm::TargetLowering::getInlineAsmMemConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0af09564c9ca56850d4cd6b3319e541aee">llvm::InlineAsm::Q</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a96bc320e4d72edda450c7a9abc8a214f">llvm::InlineAsm::Um</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a80a9a9f289a503c7e4218d1c34e05a02">llvm::InlineAsm::Un</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a278aaecf82149517409e1b5ad208d723">llvm::InlineAsm::Uq</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a85e8f233669adc62acf13417cb9649ca">llvm::InlineAsm::Us</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a51de5514f3c808babd19f42217fcba49">llvm::InlineAsm::Ut</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a4efc6436bf7fb6078171376735b85588">llvm::InlineAsm::Uv</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0adac43929efc16c2681ae620d0602b299">llvm::InlineAsm::Uy</a>.</p>

</div>
</div>

### getJumpTableEncoding() {#abd1b16a5f1b13b4d1d5fdf835f43791c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMTargetLowering::getJumpTableEncoding ()</td>
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


<p>Declaration at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 3611 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#aaa21facdbb167f7c33d21907b8e5b9d3ab0c4687afc1a6858d37711a814f8f5b3">llvm::MachineJumpTableInfo::EK_BlockAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#aaa21facdbb167f7c33d21907b8e5b9d3a0c8edab8f0150200196e0c217e343058">llvm::MachineJumpTableInfo::EK_Inline</a>.</p>

</div>
</div>

### getMaxSupportedInterleaveFactor() {#a092ffa6880261ef3e0ca4ade2cb075ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMTargetLowering::getMaxSupportedInterleaveFactor ()</td>
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

<p>Get the maximum supported factor for interleaved memory accesses.</p>


<p>Default to be the minimum interleave factor: 2.</p>


<p>Declaration at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21569 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9217d0c83a31e23a74c96c313b8c2601">llvm::TargetLoweringBase::getMaxSupportedInterleaveFactor</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac41a147e82b88d9ad55a4542e765468a">MVEMaxSupportedInterleaveFactor</a>.</p>


<p>Referenced by <a href="#ad190bc43c7fc8555debc7228fc5364b9">lowerInterleavedLoad</a> and <a href="#aa3168bc53fc117710cec207cc6f60518">lowerInterleavedStore</a>.</p>

</div>
</div>

### getNumInterleavedAccesses() {#a0a297f370d16737059a7ff5028b0b39a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ARMTargetLowering::getNumInterleavedAccesses (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VecTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of interleaved accesses that will be generated when lowering accesses of the given type.</p>


<p>A helper function for determining the number of interleaved accesses we will generate when lowering accesses of the given type.</p>


<p>Declaration at line 744 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21528 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>


<p>Referenced by <a href="#ad190bc43c7fc8555debc7228fc5364b9">lowerInterleavedLoad</a> and <a href="#aa3168bc53fc117710cec207cc6f60518">lowerInterleavedStore</a>.</p>

</div>
</div>

### getOptimalMemOpType() {#abd29a7e70a14fb7b45ff277e5c935424}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT ARMTargetLowering::getOptimalMemOpType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memop">MemOp</a> &amp; Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &amp;)</td>
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

<p>Returns the target specific optimal type for load and store operations as a result of memset, memcpy, and memmove lowering.</p>


<p>It returns EVT::Other if the type should be determined using generic target-independent logic.</p>


<p>Declaration at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="#ac897a80df1070effb9d5a5b6a023c5d0">allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a61054ea97168f709c1e46345f80c16a3">llvm::AttributeList::hasFnAttr</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">llvm::MachineMemOperand::MONone</a>.</p>

</div>
</div>

### getPostIndexedAddressParts() {#af4269b2cd295687cb69f61729f91de3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::getPostIndexedAddressParts (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31">ISD::MemIndexedMode</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>getPostIndexedAddressParts - returns true by value, base pointer and offset pointer and addressing mode by reference if this node can be combined with a load / store to form a post-indexed load / store.</p>

<p>Declaration at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19906 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac7734fe83bba82dacf7ebb09a8376f17">getARMIndexedAddressParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac1e54d0f4e825bd61384555fc2bd1cf7">getMVEIndexedAddressParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a928bff6cd07e2f5de0e1eb5311c2cba9">getT2IndexedAddressParts</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6aacde2c67988b43a261a7f7ceac4be3">llvm::ISD::NON_EXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31a10a4094c81c0b9cd5e82e53b48932203">llvm::ISD::POST_DEC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31a866c29237765ff291c9503abbdca60e1">llvm::ISD::POST_INC</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### getPreIndexedAddressParts() {#a22338caf16030dc171ee6dfb5580d308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::getPreIndexedAddressParts (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31">ISD::MemIndexedMode</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19846 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac7734fe83bba82dacf7ebb09a8376f17">getARMIndexedAddressParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac1e54d0f4e825bd61384555fc2bd1cf7">getMVEIndexedAddressParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a928bff6cd07e2f5de0e1eb5311c2cba9">getT2IndexedAddressParts</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31a57c3822f99653c422d5a21206adc6e42">llvm::ISD::PRE_DEC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31ab5bb854fadd42503c849c4a48d7f3d90">llvm::ISD::PRE_INC</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>.</p>

</div>
</div>

### getRegClassFor() {#a83b63333509486d44ab3c289b6119c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * ARMTargetLowering::getRegClassFor (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, bool isDivergent=false)</td>
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

<p>getRegClassFor - Return the register class that should be used for the specified value type.</p>

<p>Declaration at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 1943 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1a78b9f867cb5be3a052d6ad972484ca">llvm::TargetLoweringBase::getRegClassFor</a>.</p>

</div>
</div>

### getRegForInlineAsmConstraint() {#ae36dfcf0bacb4009b75fb2323aba6869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RCPair ARMTargetLowering::getRegForInlineAsmConstraint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
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


<p>Declaration at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#af09507c47dcb4cdb2a13064aaa6d5243">llvm::TargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getSchedulingPreference() {#aa16505b46d66798daa417510b68ee4ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Sched::Preference ARMTargetLowering::getSchedulingPreference (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *)</td>
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


<p>Declaration at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 1986 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sched/#ab8d854a5ce2331586bcc6830cca52f0fac4801b47c85ae3044251c5ca7443b1df">llvm::Sched::ILP</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3cb888a2ce8e95e0d9769687a5e2f7d8">llvm::EVT::isFloatingPoint</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sched/#ab8d854a5ce2331586bcc6830cca52f0fa5b5fba18a61456ef5858005d9f7b153e">llvm::Sched::RegPressure</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getSDagStackGuard() {#a549b4bb4e86e927f213a2175401b10e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ARMTargetLowering::getSDagStackGuard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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


<p>Declaration at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a40e9675119de3bcd2fd05b549994a17d">llvm::TargetLoweringBase::getSDagStackGuard</a>.</p>

</div>
</div>

### getSetCCResultType() {#a667a905e2496f6b0b9c7915a97f58da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT ARMTargetLowering::getSetCCResultType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>getSetCCResultType - Return the value type to use for <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">ISD::SETCC</a>.</p>

<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 1925 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a0351571482fea42a3b326147fb2ce9e2">llvm::EVT::changeVectorElementTypeToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3d102abca1c9c95f36546dff2f39273b">llvm::EVT::getVectorElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### getSingleConstraintMatchWeight() {#a0f12063b62264c753e65abb8e9ff29d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::ConstraintWeight ARMTargetLowering::getSingleConstraintMatchWeight (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a> &amp; info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * constraint)</td>
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


<p>Declaration at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abcad4df0dd48c58dea43776a5a77e74ba76">llvm::TargetLowering::CW_Default</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abca2a03cc05a305d0cd861ff2d070da40ca">llvm::TargetLowering::CW_Invalid</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abcaa36ab38b266c612487d9ff61df7475af">llvm::TargetLowering::CW_Register</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abca8f769b6cac1ebb4de9412ecfe92fe20d">llvm::TargetLowering::CW_SpecificReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#afaa66a325b7b8c5c79eb2c8e9822ffd2">llvm::TargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>.</p>

</div>
</div>

### getSSPStackGuardCheck() {#a3a6814018ec7443c7df966784ad69064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * ARMTargetLowering::getSSPStackGuardCheck (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>If the target has a standard stack protection check function that performs validation and error handling, returns the function.</p>


<p>Otherwise, returns nullptr. Must be previously inserted by insertSSPDeclarations. Should be used only when getIRStackGuard returns nullptr.</p>


<p>Declaration at line 697 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a8743c58384e11cb6228f6f871304ad35">llvm::Function::getFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a5cc7ede2e4ce0498c628270ca97ed75c">llvm::TargetLoweringBase::getSSPStackGuardCheck</a>.</p>

</div>
</div>

### getSubtarget() {#a1a1a37ae8032008276a560318975cbac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMSubtarget * llvm::ARMTargetLowering::getSubtarget ()</td>
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



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac6767d87d6d42330fa8e29e15bb105b1">promoteToConstantPool</a>.</p>

</div>
</div>

### getTargetNodeName() {#ab05dc466c15a454c07f2993dab74472f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * ARMTargetLowering::getTargetNodeName (unsigned Opcode)</td>
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

<p>This method returns the name of a target specific DAG node.</p>

<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 1711 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a41f4297f00dc6d8d7445d13daf7eba26">llvm::ARMISD::ADDC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a38281aedc70f7c707027367acd3234cb">llvm::ARMISD::ADDE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ae943be65cd3ae29f0032ad56a3875c42">llvm::ARMISD::ASRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a2bb669fe5faf69d683427c11ccea256f">llvm::ARMISD::ASRS1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a93de4757f6b73b98f83df6c84ba335fe">llvm::ARMISD::BCC_i64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a109dda4df2be3a46022e3600484f4efb">llvm::ARMISD::BFI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38abacb1d6d27b76e9aeb011e2302033470">llvm::ARMISD::BR2_JT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a8dfd4ea5a4e33bdb35fcafb11d1073cb">llvm::ARMISD::BR_JT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a4621d333784e3cd8c9f92a1443013dbe">llvm::ARMISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9b3b5c8aca58fc851520aab312b46637">llvm::ARMISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a2af8075cd139f844ae07ed7988cbb2b7">llvm::ARMISD::CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ab204e019469f4548ac436586a605f41f">llvm::ARMISD::CALL_NOLINK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ace024bb2e9c3935008e16e7be869af98">llvm::ARMISD::CALL_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a73bd03dfbab0f65cbd59365be36c9637">llvm::ARMISD::CMN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aee74cff1cb1ea095617b5fa044e342db">llvm::ARMISD::CMOV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aaed0e0931ede9056a03d792401e655a9">llvm::ARMISD::CMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38acefb30e98102150caa66322bfa40dd50">llvm::ARMISD::CMPFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a3bfec195f10a9950076570fda7745484">llvm::ARMISD::CMPFPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38af8ad86574b674ce3ed7a491df714b3d1">llvm::ARMISD::CMPFPEw0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a28ca54417ad23eee114779d2bb800ff0">llvm::ARMISD::CMPFPw0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ab7f9acd96e942ca625335c36de28e60e">llvm::ARMISD::CMPZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a58ca12649e834dcfac522cec82df3793">llvm::ARMISD::COPY_STRUCT_BYVAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38abc844212c86a5d4665e522f7a7de6610">llvm::ARMISD::CSINC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7fa873eda688ec241983ec07abb187bb">llvm::ARMISD::CSINV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a2f975a28397d8aaddaf658d8f09f0086">llvm::ARMISD::CSNEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a91cab2531250dcbe6ff4002d96ba1f5a">llvm::ARMISD::DYN_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9060e4d9fd2c82efb5271a282b477e6d">llvm::ARMISD::EH_SJLJ_LONGJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ac40d2d97a5232355c7e4356a5b1b348f">llvm::ARMISD::EH_SJLJ_SETJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a415b28d48c69281b494b5676513b9729">llvm::ARMISD::EH_SJLJ_SETUP_DISPATCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a2da4296d7bd9b77819b2684f456cb3ab">llvm::ARMISD::FIRST_NUMBER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a6b4121a8201ef54013a43cce7972b532">llvm::ARMISD::FMSTAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ad1ceedbd26427868e0370cbbeed597f3">llvm::ARMISD::INTRET_GLUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38af367450e974cd6c5a4d38caf2ac57f40">llvm::ARMISD::LDRD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38adaeab816ead72a28ed9c4282edcf2130">llvm::ARMISD::LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a4dee32244ce74164a053c8c25bea9226">llvm::ARMISD::LOOP_DEC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a3e9bf86bbbfea029b1f065cc6fbab978">llvm::ARMISD::LSLL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a84182cd89ac8df2cb9309ad6e30181fd">llvm::ARMISD::LSLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ab729d2ded9bb455206f7944e09444c73">llvm::ARMISD::LSRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a5aef4524ffbb7e5e7ccd6a073c9f6a2c">llvm::ARMISD::LSRS1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8fb469989985105371cdb192ac9a26f1">MAKE_CASE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7a2ddf62b8434c6d91a878826c541dad">llvm::ARMISD::MEMBARRIER_MCR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aec586817cf51a463ca101fab0ce085da">llvm::ARMISD::MEMCPY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a98b514a4c87eb38220d1b8636145e6b2">llvm::ARMISD::MEMCPYLOOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a8de12fac953b4c453629b726bc9e1f5f">llvm::ARMISD::MEMSETLOOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9326d7ebc2b118b134db7934f6fa4713">llvm::ARMISD::MVESEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38afcd7b69a3ab8e9b9c40b7a973d961b05">llvm::ARMISD::MVETRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ad0fc91cb6c69b2e9e9ef67d896bd76a5">llvm::ARMISD::MVEZEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a5bc71a39554a14104bfd1011dffbed0b">llvm::ARMISD::PIC_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a1e452bb26851eafc6364ba340c36ecf0">llvm::ARMISD::PREDICATE_CAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a07da1ed30667d9280b73a46ef24e5fac">llvm::ARMISD::PRELOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a83728aad1cd6a81514525c49fc23ce17">llvm::ARMISD::QADD16b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38af914da04c6db0f9697158bf86d51bd02">llvm::ARMISD::QADD8b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aad9651faf4a6694a93228858973219b5">llvm::ARMISD::QSUB16b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a41ec5a4a3fcc7e41263a4bc0b6a69c65">llvm::ARMISD::QSUB8b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a672872cbaad3c84753f0d5a8f70ae17d">llvm::ARMISD::RET_GLUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ae14aa6c4f09a840b110709145e862660">llvm::ARMISD::RRX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aa8f29efa4adf770c4f955fc8f0da06dc">llvm::ARMISD::SERET_GLUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aa174d9797327e782f169f497338fac95">llvm::ARMISD::SMLAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a5faaa77b1082966846b8847f5d53479d">llvm::ARMISD::SMLALBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9982953b4608d6356bd7fe3c4c4fe9c0">llvm::ARMISD::SMLALBT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a644e5045736cf38a240f0dfca62326a8">llvm::ARMISD::SMLALD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a5641512dd01cc6fe498224ca1eba86fb">llvm::ARMISD::SMLALDX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7304a9dad68e35cedd3286fc2d51bee5">llvm::ARMISD::SMLALTB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a33ecfe3938a12d2b6b83a69094a33d29">llvm::ARMISD::SMLALTT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a480659fe96e678969ce3c1a631e48bb0">llvm::ARMISD::SMLSLD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38adb2fe2066e41ba120b8fb629da865cfd">llvm::ARMISD::SMLSLDX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a729d32c1741fc630eb5a56a1b49a82ab">llvm::ARMISD::SMMLAR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a3987385722cf9bbe7ea0d090bc06b722">llvm::ARMISD::SMMLSR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aed7b9527784ba4e06dcf95704002dc24">llvm::ARMISD::SMULWB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a8193c5897199f248b53c6fff20ce18f2">llvm::ARMISD::SMULWT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aa173c041ee452fcdffb797075a892b84">llvm::ARMISD::SSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a8a90f7542d552553f83027180bce5ca8">llvm::ARMISD::STRD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9cfc13d8dfcbb7d035be110b619ea741">llvm::ARMISD::SUBC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a06e89dbcfaf0ceca94295988d35809c2">llvm::ARMISD::SUBE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a11eb299481204e113f0518f48d6ad65d">llvm::ARMISD::t2CALL_BTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ae8db6245139cf9e51bf5d85ddb4aa40f">llvm::ARMISD::TC_RETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a663f1912d43363b57a06adfaabf0fedb">llvm::ARMISD::THREAD_POINTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38af37e43d1efe2f7cdddcd4a7626fb5612">llvm::ARMISD::tSECALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ac3dd723ee353ee1368f2ff900ed799b5">llvm::ARMISD::UMAAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a8d9d96ad008a475ebbff8e366bbc1eb6">llvm::ARMISD::UMLAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ad0f2aceb3ee7cd23f8b352d8580169a4">llvm::ARMISD::UQADD16b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a2ffd7790f42a2c3092b83e37c7fe3da9">llvm::ARMISD::UQADD8b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aeff71ef40fdc565429b4de72440a8500">llvm::ARMISD::UQSUB16b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ae378627a128dd34c938348e5552bd468">llvm::ARMISD::UQSUB8b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ae60ed52746753eeb5502fcfceb13f2fe">llvm::ARMISD::USAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a245dab1b37a3890669c0d774172abfe7">llvm::ARMISD::VADDLVAps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a148d0603e46bd5ffddda6bbc2c835158">llvm::ARMISD::VADDLVApu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a359ec09c5b0bea8d8e73795738c74b8f">llvm::ARMISD::VADDLVAs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ac255df83083c0579aa5acc39a0a53b92">llvm::ARMISD::VADDLVAu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38add9d7dd92c2e0454947271184f9cea92">llvm::ARMISD::VADDLVps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38adeeb8ac961b16f30b10b1dc668788211">llvm::ARMISD::VADDLVpu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7f60e06779eb757bcaadbbc7f1b38de2">llvm::ARMISD::VADDLVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a28b0ceeefba427b139e09b5850ab9389">llvm::ARMISD::VADDLVu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a4c7e4505cb2d2b464754f62cd8656c5c">llvm::ARMISD::VADDVps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a242d064c1ca083654f87ca5f7278fff9">llvm::ARMISD::VADDVpu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a2c3d99682d5c725adcbe430bc69b9c99">llvm::ARMISD::VADDVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ada29df039613d536f11af709cf7691ee">llvm::ARMISD::VADDVu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aeb5a51baba9276b3e2ea25b7ac5b8806">llvm::ARMISD::VBICIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38acc417089525086253ff4296bd2f07f0b">llvm::ARMISD::VBSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7c288956c8c8e43434e6ae8633daab64">llvm::ARMISD::VCMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a4ca5c4fa27f6ef68b659e9deaf7545c2">llvm::ARMISD::VCMPZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a99edb50eab987b63533cb44fe744a28e">llvm::ARMISD::VCVTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9a82260a4232967f7e3cf177fa2e8ced">llvm::ARMISD::VCVTN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a50bbb022c555743f1805d3df3ee98adb">llvm::ARMISD::VDUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a64c0bb0345ba1b69528dd52da797f6a7">llvm::ARMISD::VDUPLANE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a40f2efa7d8c9b15db57cc3500bba1f09">llvm::ARMISD::VECTOR_REG_CAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ad428215f2bb2c30a97d6de6d14d6ccdf">llvm::ARMISD::VEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a29bc6cd8219e70572b8b113c230fea6e">llvm::ARMISD::VGETLANEs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ad78d1cfc271b51dc1c87c91401b87c57">llvm::ARMISD::VGETLANEu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a6fb8d68b511745372ea9df95347a6ea4">llvm::ARMISD::VIDUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aeb657e0aaf4405a13d3379c9ef08c5e1">llvm::ARMISD::VLD1_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a736037fbdc5e0e5d5c0fff76584255d4">llvm::ARMISD::VLD1DUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a78c1ef042ed87df90fd74a2b0aa328af">llvm::ARMISD::VLD1DUP_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a45f54d04d055263cfafa769c509612fd">llvm::ARMISD::VLD1x2_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a0d8581feb563228efaea68ab27e9c4d8">llvm::ARMISD::VLD1x3_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a3b00cfff1a8708169d95c639b46e54ac">llvm::ARMISD::VLD1x4_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a3e74c01534bbe58a9716c4ed9afb552b">llvm::ARMISD::VLD2_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a81b77974c326f91d888b4f7c7346440d">llvm::ARMISD::VLD2DUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aeecdd98f156fccc64b091ed05e2a7fa2">llvm::ARMISD::VLD2DUP_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aef111725b7a6bc348025dbe88c610e52">llvm::ARMISD::VLD2LN_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a2dcef9e9a88a5601e3615bd024f89ebc">llvm::ARMISD::VLD3_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aeb8a7ec48dfdbb30f676f1f9ed78515e">llvm::ARMISD::VLD3DUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a55c84e4b70ccda76faa80ac003a66b86">llvm::ARMISD::VLD3DUP_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ad1a20b1fad0a456eeea32953e3711d67">llvm::ARMISD::VLD3LN_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38acbc76b0e9da47cff86f227b76a101877">llvm::ARMISD::VLD4_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a682019fb60ebfdcb1b6c12bef90e81d1">llvm::ARMISD::VLD4DUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a8cae6c5ad12cf66a9b86fe48082bd9d1">llvm::ARMISD::VLD4DUP_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38af06cac064eb63dda89fc54210230c6c7">llvm::ARMISD::VLD4LN_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a609627e5fb4559af076d1b1dbb0ff536">llvm::ARMISD::VMAXVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a78c333b77e384722c73b2f1ecf172160">llvm::ARMISD::VMAXVu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7f9beb5d6e4fe4922bf922562b678d54">llvm::ARMISD::VMINVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7c4161403878bfbc24c4d805a52f86a6">llvm::ARMISD::VMINVu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9ae951d2026826f66fdf04140182f172">llvm::ARMISD::VMLALVAps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a0577099955f7fe7aa79056f0806e05b6">llvm::ARMISD::VMLALVApu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aa21f7a01a26f04604b61652864d577c1">llvm::ARMISD::VMLALVAs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a3fe835d935b0d36f42b92c9da35f3d03">llvm::ARMISD::VMLALVAu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a57f53fc571f810653378d8d37eac942f">llvm::ARMISD::VMLALVps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aed2014a73c494554ab58c7e78e321c0c">llvm::ARMISD::VMLALVpu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a214985f7b88b1d15a7103b432dba2dbb">llvm::ARMISD::VMLALVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ab4543c9ea891307c00d497963828365c">llvm::ARMISD::VMLALVu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ae82b066f510c369e1b2547cb8a79e1da">llvm::ARMISD::VMLAVps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a0fe5e78ddb0f285dc76fcb5205114739">llvm::ARMISD::VMLAVpu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a67e82cfd8b584d35f5de2e40870dbde5">llvm::ARMISD::VMLAVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a5ba46f411106d2444bd93b563cf6da00">llvm::ARMISD::VMLAVu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a0791f9172a1b74506504d1f22d81f389">llvm::ARMISD::VMOVDRR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a242d9487902c3ae2a3d9c3d1355f8246">llvm::ARMISD::VMOVFPIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38acb6fa97139e090fff02bc421e02451ed">llvm::ARMISD::VMOVhr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a5efe47c12d5ebca8c56bd48eb9d612fc">llvm::ARMISD::VMOVIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ac2f455684efb89d120029b7a65acd013">llvm::ARMISD::VMOVN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a3b1cd1c01c04128536b9cbe473629904">llvm::ARMISD::VMOVrh</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7f93dc1b4123a3d49e2a544960758ef1">llvm::ARMISD::VMOVRRD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a240b00dd73991507ba0171aaad5613c2">llvm::ARMISD::VMOVSR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38af545e63f1ef20c06d5a6dbe6c1ec2097">llvm::ARMISD::VMULLs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38af8c95bf2b6ad98c19fbaeaef1e82dd28">llvm::ARMISD::VMULLu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ae3708ea7a9abaabaa0a7ae12fa5b5c4e">llvm::ARMISD::VMVNIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a4fdb743470b16a85839369a93cc26368">llvm::ARMISD::VORRIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a0ea65604b43fdf53982b2e0c2622abcc">llvm::ARMISD::VQDMULH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a883cd6fb091beb1d5da94e6bf2eb086a">llvm::ARMISD::VQMOVNs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38af1218b9767cbe26dbbbd375286b55c0a">llvm::ARMISD::VQMOVNu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a3bed0337c3e72d48b7acb7d944bc92a4">llvm::ARMISD::VQRSHRNsIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a8bbaf9840d99cfe346344a0fccf67870">llvm::ARMISD::VQRSHRNsuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a28fd5ec0d2731c2711f5019e65ea17fa">llvm::ARMISD::VQRSHRNuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a0cd0628ba1ee0cbe2f3b27056d84e31d">llvm::ARMISD::VQSHLsIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38adf824fd0265a67f9e20a992536543787">llvm::ARMISD::VQSHLsuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a49f0f08f662ff51ecc3221cee92c5ede">llvm::ARMISD::VQSHLuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9cecd45f88e494fe8828dd3b7e566547">llvm::ARMISD::VQSHRNsIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a1f8d979594f9d98e26744923151e7248">llvm::ARMISD::VQSHRNsuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a1241f4af5ed5a4f37eed9e1490a3754e">llvm::ARMISD::VQSHRNuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a612cd894d3df73b6e47707d1fc1da974">llvm::ARMISD::VREV16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a96babbe11f5e86cf3b02a0064c03c84e">llvm::ARMISD::VREV32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aed9adca906655e17ad5db993e80cc90f">llvm::ARMISD::VREV64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a88fe6ff9aa04ed53f2d31971d85523c7">llvm::ARMISD::VRSHRNIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ae43d68e08454b25bde1237df049d4bfc">llvm::ARMISD::VRSHRsIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aeb906d5db57d71d1b2adf555f95ced45">llvm::ARMISD::VRSHRuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aee85fe37c0da86af1536a98c888f9150">llvm::ARMISD::VSHLIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a1a032e767ce6dc5a014b6cb6a980e15f">llvm::ARMISD::VSHLs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a051f7f7ea4fa4d22680fe300119e3b46">llvm::ARMISD::VSHLu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a1eb3012ff65d306c3bfcda64ca53a17c">llvm::ARMISD::VSHRsIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ac2cc71438511eab862a4040d7dbdedc9">llvm::ARMISD::VSHRuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a1d077dec7708f42d7317b676157efc93">llvm::ARMISD::VSLIIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aa51bd387b70ce9454c4a1360f3479e1c">llvm::ARMISD::VSRIIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a66260b6c8cb9ac5ae51cb28d85f8609a">llvm::ARMISD::VST1_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aec8fdde21c8237d416596c48a6c860b1">llvm::ARMISD::VST1x2_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ae328404e440614fcb54df7ac51f11044">llvm::ARMISD::VST1x3_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a38899d122ffababe99e5c66ba98a5c4a">llvm::ARMISD::VST1x4_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38af6a4c6bf81470b0f47fb5ea7d02c9422">llvm::ARMISD::VST2_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a4fb391704986986d277b0e9f9defe47d">llvm::ARMISD::VST2LN_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a46ce1e04c61117e5b760e27351c2c209">llvm::ARMISD::VST3_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a0e4c9035a762f061faadf268d28ed841">llvm::ARMISD::VST3LN_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a8994129f9ac9818ba7865a6df6194a15">llvm::ARMISD::VST4_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a1d949f0d6adbeca42c5d9084223611fa">llvm::ARMISD::VST4LN_UPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a23b7689832a24fd3eea55be8583bee87">llvm::ARMISD::VTBL1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38abf641d085a1191fdfe9f91624d8078a6">llvm::ARMISD::VTBL2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a78557d58c18ae631207ea472be421497">llvm::ARMISD::VTRN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a5878903e0ec87cb695f22d4851889df4">llvm::ARMISD::VTST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a3d175a42f3d21e9d95bc684768de999a">llvm::ARMISD::VUZP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a2ce278a3ff293b574f11d4ee0276770d">llvm::ARMISD::VZIP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a6143acc30126957cfa4330ffa4383ba5">llvm::ARMISD::WIN__CHKSTK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a62d363916df0556c38dd1014c45b7a46">llvm::ARMISD::WIN__DBZCHK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a83135d8a8ab6d3b2bdc77560e7088a36">llvm::ARMISD::WLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ac09bfe85bbfd03505987fdae620a20bb">llvm::ARMISD::WLSSETUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a029f48a0b5e0d471de85baca7745d1a0">llvm::ARMISD::Wrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a114c5ea64df684330a0ec619fed19ffd">llvm::ARMISD::WrapperJT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a6a715cec66d0a16ea7b9fde9958f1546">llvm::ARMISD::WrapperPIC</a>.</p>

</div>
</div>

### getTgtMemIntrinsic() {#a75880fa01f2a6719716b1e3ac002f40e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::getTgtMemIntrinsic (<a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/intrinsicinfo">IntrinsicInfo</a> &amp; Info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned Intrinsic)</td>
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

<p>getTgtMemIntrinsic - Represent NEON load and store intrinsics as MemIntrinsicNodes.</p>


<p>The associated MachineMemOperands record the alignment specified in the intrinsic calls.</p>


<p>Declaration at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20933 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a210ba6b43ba451b698857dd9de71bd15">llvm::EVT::getVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a56bb53e2d0b01c78c8c538f903fd45b8">llvm::MVT::getVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda796891d6ca349b671fce24b6d01d77a8">llvm::MachineMemOperand::MOVolatile</a>.</p>

</div>
</div>

### hasStandaloneRem() {#af1e8e3885b9faabcecb0384116e18f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMTargetLowering::hasStandaloneRem (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if the target can handle a standalone remainder operation.</p>

<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>

</div>
</div>

### insertSSPDeclarations() {#a3f1fdc55e21406f8dd4612925fbe86a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::insertSSPDeclarations (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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


<p>Declaration at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncallee/#ac5d8da677233fa2e1e7039508ed56e0e">llvm::FunctionCallee::getCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af3e31a71f6d0e55d41956d5b20ed7989">llvm::TargetLoweringBase::insertSSPDeclarations</a>.</p>

</div>
</div>

### isCheapToSpeculateCtlz() {#a918e4a00bbb56e9dbd10ae5c0d054848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isCheapToSpeculateCtlz (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Return true if it is cheap to speculate a call to intrinsic ctlz.</p>

<p>Declaration at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21416 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### isCheapToSpeculateCttz() {#a8d9c520e13d0f9fd00d79b2cb1c29a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isCheapToSpeculateCttz (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Return true if it is cheap to speculate a call to intrinsic cttz.</p>

<p>Declaration at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### isComplexDeinterleavingOperationSupported() {#aa8f55419227d2b25fcfca130f3f1dc63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isComplexDeinterleavingOperationSupported (<a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764">ComplexDeinterleavingOperation</a> Operation, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Does this target support complex deinterleaving with the given operation and type.</p>

<p>Declaration at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 22022 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a8a6707a9048ed67adda5b5ade0ecdd41">llvm::CAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a5b2aa9d3f9f3a7b2d123fef7c5328b8f">Operation</a>.</p>

</div>
</div>

### isComplexDeinterleavingSupported() {#a5175a0caa4d7785c4da770f497adc3fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isComplexDeinterleavingSupported ()</td>
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

<p>Does this target support complex deinterleaving.</p>

<p>Declaration at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 22018 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### isDesirableToCommuteWithShift() {#a0e3aa05aca949e6905dcb30c81c679e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isDesirableToCommuteWithShift (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7a">CombineLevel</a> Level)</td>
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

<p>Return true if it is profitable to move this shift by a constant amount through its operand, adjusting any immediate operands as necessary to preserve semantics.</p>


<p>This transformation may not be desirable if it disrupts a particularly auspicious target-specific tree (e.g. bitfield extraction in <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a>). By default, it returns true.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p>the shift node</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Level</td>
<td class="doxyParamItemDescription"><p>the current DAGCombine legalization level.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 13853 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7aa9386e6e4a4c86dabf136bc0fc9f6cf3b">llvm::BeforeLegalizeTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a295d0b84f4e63438c0edb0021c41d47a">llvm::SDNode::hasOneUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>.</p>

</div>
</div>

### isDesirableToCommuteXorWithShift() {#a49bbf30468c8d202d88466ff4bfd46dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isDesirableToCommuteXorWithShift (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Return true if it is profitable to combine an XOR of a logical shift to create a logical shift of NOT.</p>


<p>This transformation may not be desirable if it disrupts a particularly auspicious target-specific tree (e.g. BIC on ARM/AArch64). By default, it returns true.</p>


<p>Declaration at line 756 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 13900 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>.</p>

</div>
</div>

### isDesirableToTransformToIntegerOp() {#ac2cd92359d9b981db40c3cc07f20249d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isDesirableToTransformToIntegerOp (unsigned, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
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

<p>Return true if it is profitable for dag combiner to transform a floating point op of specified opcode to a equivalent op of an integer type.</p>


<p>e.g. f32 load -&gt; i32 load can be profitable on <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a>.</p>


<p>Declaration at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>.</p>

</div>
</div>

### isExtractSubvectorCheap() {#a73ff0ebe4440fb057e9206dd88bb8c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isExtractSubvectorCheap (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ResVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SrcVT, unsigned Index)</td>
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

<p>Return true if EXTRACT_SUBVECTOR is cheap for this result type with this index.</p>

<p>Declaration at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa93fbbc66d52a51d178af8ac4398ec05">llvm::TargetLoweringBase::isOperationLegalOrCustom</a>.</p>

</div>
</div>

### isFNegFree() {#a350cbdd9ddbb2a048799fca9d93f3993}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isFNegFree (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if an fneg operation is free to the point where it is never worthwhile to replace it with a bitwise operation.</p>

<p>Declaration at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>

</div>
</div>

### isFPImmLegal() {#a361a22a9d4bb3a3812c85f56f6b04e08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isFPImmLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Imm, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, bool ForCodeSize=false)</td>
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

<p>isFPImmLegal - Returns true if the target can instruction select the specified FP immediate natively.</p>


<p>If false, the legalizer will materialize the FP immediate as a load from a constant pool.</p>


<p>Declaration at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20914 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a6d6612ebe88f532f464ff1275ed58d1b">llvm::ARM_AM::getFP16Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a9ee19d38a1e1584e356c193d30417733">llvm::ARM_AM::getFP32FP16Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a0ff84c673da1cdc12d7061d663a686a5">llvm::ARM_AM::getFP32Imm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5b469aea8a344952b8effedd56336182">llvm::ARM_AM::getFP64Imm</a>.</p>

</div>
</div>

### isLegalAddImmediate() {#a2dd0b703d836eccdef210b88ea83908b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isLegalAddImmediate (int64_t Imm)</td>
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


<p>isLegalAddImmediate - Return true if the specified immediate is a legal add <em>or sub</em> immediate, that is the target has add or sub instructions which can add a register with the immediate without having to materialize the immediate into a register.</p>


<p>Declaration at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19669 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a0f3447f06da0010c13eeb865004f71ca">llvm::ARM_AM::getSOImmVal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a3d6b5f20dd274d971ef924f3e2a29d1a">llvm::ARM_AM::getT2SOImmVal</a>.</p>


<p>Referenced by <a href="#a2d9d6b4d91e3a1a4ce7ffe8ed701a40e">isMulAddWithConstProfitable</a>.</p>

</div>
</div>

### isLegalAddressingMode() {#a14ba388c0893657958340f94a164faa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isLegalAddressingMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode">AddrMode</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned AS, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
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

<p>Declaration at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19587 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a2d775e3fd8ebcd0941d1e12cbfccda3d">llvm::TargetLoweringBase::AddrMode::BaseGV</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a115ffe6d615735fbe8b1bf31877565ba">llvm::TargetLoweringBase::AddrMode::BaseOffs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a126c61d55fb4d2e509537ce68e8b6400">llvm::TargetLoweringBase::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8868c35de6c36dc0d57e84f256c4ffde">llvm::TargetLoweringBase::AddrMode::HasBaseReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad09933ec95486d26cd31cf1536190091">isLegalAddressImmediate</a>, <a href="#a221b01b74bd3f7ddd1779947901f5eec">isLegalT1ScaledAddressingMode</a>, <a href="#a1b478e338eb3e2c6ab20ac7462896c58">isLegalT2ScaledAddressingMode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8ea7d02f0e4b0c1d37d6986ec9f7f5c0">llvm::TargetLoweringBase::AddrMode::Scale</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>

</div>
</div>

### isLegalICmpImmediate() {#abb7f063013825d86c8d8d483e83d1123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isLegalICmpImmediate (int64_t Imm)</td>
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

<p>Declaration at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19653 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a0f3447f06da0010c13eeb865004f71ca">llvm::ARM_AM::getSOImmVal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a3d6b5f20dd274d971ef924f3e2a29d1a">llvm::ARM_AM::getT2SOImmVal</a>.</p>

</div>
</div>

### isLegalInterleavedAccessType() {#ac9518b8cf085f38ae07134937ad85d31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isLegalInterleavedAccessType (unsigned Factor, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> * VecTy, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">VecTy</span> is a legal interleaved access type.</p>


<p>This function checks the vector element type and the overall width of the vector.</p>


<p>Declaration at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21533 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a1893caf878859959ba6a3d5442ef1439">llvm::FixedVectorType::getNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a8cf1f36cc41c466e66d6467e40554841">llvm::Type::isHalfTy</a>.</p>


<p>Referenced by <a href="#ad190bc43c7fc8555debc7228fc5364b9">lowerInterleavedLoad</a> and <a href="#aa3168bc53fc117710cec207cc6f60518">lowerInterleavedStore</a>.</p>

</div>
</div>

### isLegalT1ScaledAddressingMode() {#a221b01b74bd3f7ddd1779947901f5eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isLegalT1ScaledAddressingMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode">AddrMode</a> &amp; AM, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the addressing mode representing by AM is legal for the Thumb1 target, for a load/store of the specified type.</p>

<p>Declaration at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19570 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8868c35de6c36dc0d57e84f256c4ffde">llvm::TargetLoweringBase::AddrMode::HasBaseReg</a> and <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8ea7d02f0e4b0c1d37d6986ec9f7f5c0">llvm::TargetLoweringBase::AddrMode::Scale</a>.</p>


<p>Referenced by <a href="#a14ba388c0893657958340f94a164faa9">isLegalAddressingMode</a>.</p>

</div>
</div>

### isLegalT2ScaledAddressingMode() {#a1b478e338eb3e2c6ab20ac7462896c58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isLegalT2ScaledAddressingMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode">AddrMode</a> &amp; AM, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19532 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8868c35de6c36dc0d57e84f256c4ffde">llvm::TargetLoweringBase::AddrMode::HasBaseReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8ea7d02f0e4b0c1d37d6986ec9f7f5c0">llvm::TargetLoweringBase::AddrMode::Scale</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>


<p>Referenced by <a href="#a14ba388c0893657958340f94a164faa9">isLegalAddressingMode</a>.</p>

</div>
</div>

### isMaskAndCmp0FoldingBeneficial() {#af1478848ccc7623d55d4666d293bb6d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isMaskAndCmp0FoldingBeneficial (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; AndI)</td>
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


<p>Declaration at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a0f3447f06da0010c13eeb865004f71ca">llvm::ARM_AM::getSOImmVal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a3d6b5f20dd274d971ef924f3e2a29d1a">llvm::ARM_AM::getT2SOImmVal</a>.</p>

</div>
</div>

### isMulAddWithConstProfitable() {#a2d9d6b4d91e3a1a4ce7ffe8ed701a40e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isMulAddWithConstProfitable (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> AddNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ConstNode)</td>
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

<p>Return true if it may be profitable to transform (mul (add x, c1), c2) -&gt; (add (mul x, c2), c1*c2).</p>


<p>This may not be true if c1 and c2 can be represented as immediates but c1*c2 cannot, for example. The target should check if c1, c2 and c1*c2 can be represented as immediates, or have to be materialized into registers. If it is not sure about some cases, a default true can be returned to let the DAGCombiner decide. AddNode is (add x, c1), and ConstNode is c2.</p>


<p>Declaration at line 737 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19683 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabff304f51525ece8028bf8e9b1c3614">llvm::ConstantMaterializationCost</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a74b17cf9d0ee8268a5b38bbb896a30ba">llvm::ConstantSDNode::getAPIntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a75d113cb1b8cc3c14b601d928dccee40">llvm::ConstantSDNode::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="#a2dd0b703d836eccdef210b88ea83908b">isLegalAddImmediate</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### isOffsetFoldingLegal() {#ae88b69738e32f7322b54fd8b57a191a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isOffsetFoldingLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * GA)</td>
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


<p>Declaration at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20897 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### isReadOnly() {#a02f2e4fa534673c5a1afbba067f81319}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isReadOnly (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4009 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### isSelectSupported() {#a839aa57e2284019e487e2dc66877e925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMTargetLowering::isSelectSupported (<a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a575e134a5e8414029a5c4a284858e6cd">SelectSupportKind</a> Kind)</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a575e134a5e8414029a5c4a284858e6cda14714058f9e9eb27b0a4ec62d23bddd5">llvm::TargetLoweringBase::ScalarCondVectorVal</a>.</p>

</div>
</div>

### isShuffleMaskLegal() {#a779e5a75f5bf9f3672698656b56663fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isShuffleMaskLegal (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; M, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>isShuffleMaskLegal - Targets can use this to indicate that they only support <em>some</em> VECTOR_SHUFFLE operations, those with specific masks.</p>


<p>By default, if a target supports the VECTOR_SHUFFLE node, all mask values are assumed to be legal.</p>


<p>Declaration at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 8461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6db1f207286bd8bc6a978593a55955e9">llvm::EVT::is128BitVector</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#afa40b0ea2c1858e1e297227cc17d77db">llvm::EVT::is64BitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a81aa4ff7f63f7988abea1abbe9eb0342">llvm::ShuffleVectorInst::isIdentityMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a821ff31497263e443e24b91307e659f2">isLegalMVEShuffleOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac68f0500f422be0226b6227f29907243">isNEONTwoResultShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2b8fb99a1e250aac47d7fc77425edc8e">isReverseMask</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#a00abad87897a8bf77c53b38666451400">llvm::ShuffleVectorSDNode::isSplatMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a79bc1802f4c2b4a2523206b0df1f959a">isTruncMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a76388bd3043bf7119606cfec35ffb544">isVEXTMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa47d7aa438a94dc4bdc96008c058d675">isVMOVNMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5ed6a1c7f9a09c16fc02c716d3f32f9">llvm::isVREVMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a0dc61d50e79e0b7cb176bceb399b0862">isVTBLMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afd6bd47b0848ff6057b0fe117cffd1db">llvm::PerfectShuffleTable</a>.</p>

</div>
</div>

### isTruncateFree() {#a766bc050b0a294104d02f41e0047e0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isTruncateFree (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * FromTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ToTy)</td>
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

<p>Return true if it's free to truncate a value of type FromTy to type ToTy.</p>


<p>e.g. On x86 it's free to truncate a i32 value in register EAX to i16 by referencing its sub-register AX. Targets must return false when FromTy &lt;= ToTy.</p>


<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>.</p>

</div>
</div>

### isTruncateFree() {#a1f7dae0343b89773eaaea832fc9f3ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isTruncateFree (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SrcVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> DstVT)</td>
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



<p>Declaration at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### isVectorLoadExtDesirable() {#acb7284db7f63030c26cd605c4afd7fa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isVectorLoadExtDesirable (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ExtVal)</td>
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

<p>Return true if folding a vector load into ExtVal (a sign, zero, or any extend node) is profitable.</p>

<p>Declaration at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a2998329e16665f7101fac0ae9faee5c7">llvm::SDNode::isOnlyUserOf</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7d150e94e3cd7f6681fa07ea2b72da14">llvm::SDNode::use_empty</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ae04dc684fcd3d20b890bbf44e4a28395">llvm::SDNode::user_begin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aee85fe37c0da86af1536a98c888f9150">llvm::ARMISD::VSHLIMM</a>.</p>

</div>
</div>

### isZExtFree() {#a8d59d0a2b9e117e74cd61f315aabf247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isZExtFree (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT2)</td>
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

<p>Declaration at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>

</div>
</div>

### LowerAsmOperandForConstraint() {#adb4ff7051f9fd7cfa91a1b20be1ac880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::LowerAsmOperandForConstraint (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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


<p>If it is invalid, don't add anything to Ops. If hasMemory is true it means one of the asm constraint of the inline asm instruction being processed is 'm'.</p>


<p>If it is invalid, don't add anything to Ops.</p>


<p>Declaration at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20430 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7fc96403de39ca28a30bf2a4a38b113f">llvm::SelectionDAG::getSignedTargetConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a0f3447f06da0010c13eeb865004f71ca">llvm::ARM_AM::getSOImmVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a3d6b5f20dd274d971ef924f3e2a29d1a">llvm::ARM_AM::getT2SOImmVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a2cd3a9f6f0047c1989e09ba2e317fe64">llvm::ARM_AM::isThumbImmShiftedVal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ad3f2eb78e627fd0d785fd4119d299558">llvm::TargetLowering::LowerAsmOperandForConstraint</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### lowerInterleavedLoad() {#ad190bc43c7fc8555debc7228fc5364b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::lowerInterleavedLoad (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> * &gt; Shuffles, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Indices, unsigned Factor)</td>
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

<p>Lower an interleaved load into a vldN intrinsic.</p>


<p>E.g. Lower an interleaved load (Factor = 2): wide.vec = load &lt;8 x i32&gt;, &lt;8 x i32&gt;* ptr, align 4 v0 = shuffle wide.vec, undef, &lt;0, 2, 4, 6&gt; ; Extract even elements v1 = shuffle wide.vec, undef, &lt;1, 3, 5, 7&gt; ; Extract odd elements</p>


<p>Into: vld2 = { &lt;4 x i32&gt;, &lt;4 x i32&gt; } call llvm.arm.neon.vld2(ptr, 4) vec0 = extractelement { &lt;4 x i32&gt;, &lt;4 x i32&gt; } vld2, i32 0 vec1 = extractelement { &lt;4 x i32&gt;, &lt;4 x i32&gt; } vld2, i32 1</p>


<p>Declaration at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4288169d91ab0f0f01405115fd2931a7">llvm::concatenateVectors</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1ac3f0b68c9c78c4f9e1eb09cd415db8">llvm::IRBuilderBase::CreateConstGEP1_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a5f96cb150ec8f59c2799d902cf4a3f6a">createLoadIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#af51c113a039c82f6870df5dc9666b5e3">llvm::LoadInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="#a092ffa6880261ef3e0ca4ade2cb075ce">getMaxSupportedInterleaveFactor</a>, <a href="#a0a297f370d16737059a7ff5028b0b39a">getNumInterleavedAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a161c2db145827f4e181e7fe662b53a81">llvm::LoadInst::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2d1ff28d6923802e165905b8d1766e76">llvm::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab73bb6948312ca0f98055c6a74c37045">llvm::IRBuilderBase::getPtrTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a59c34209e9206120edf7ce3c5da4f872">llvm::ShuffleVectorInst::getType</a>, <a href="#ac9518b8cf085f38ae07134937ad85d31">isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>

</div>
</div>

### lowerInterleavedStore() {#aa3168bc53fc117710cec207cc6f60518}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::lowerInterleavedStore (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> * SVI, unsigned Factor)</td>
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

<p>Lower an interleaved store into a vstN intrinsic.</p>


<p>E.g. Lower an interleaved store (Factor = 3): i.vec = shuffle &lt;8 x i32&gt; v0, &lt;8 x i32&gt; v1, &lt;0, 4, 8, 1, 5, 9, 2, 6, 10, 3, 7, 11&gt; store &lt;12 x i32&gt; i.vec, &lt;12 x i32&gt;* ptr, align 4</p>


<p>Into: sub.v0 = shuffle &lt;8 x i32&gt; v0, &lt;8 x i32&gt; v1, &lt;0, 1, 2, 3&gt; sub.v1 = shuffle &lt;8 x i32&gt; v0, &lt;8 x i32&gt; v1, &lt;4, 5, 6, 7&gt; sub.v2 = shuffle &lt;8 x i32&gt; v0, &lt;8 x i32&gt; v1, &lt;8, 9, 10, 11&gt; call void llvm.arm.neon.vst3(ptr, sub.v0, sub.v1, sub.v2, 4)</p>


<p>Note that the new shufflevectors will be removed and we'll only generate one vst3 instruction in CodeGen.</p>


<p>Example for a more general valid mask (Factor 3). Lower: i.vec = shuffle &lt;32 x i32&gt; v0, &lt;32 x i32&gt; v1, &lt;4, 32, 16, 5, 33, 17, 6, 34, 18, 7, 35, 19&gt; store &lt;12 x i32&gt; i.vec, &lt;12 x i32&gt;* ptr</p>


<p>Into: sub.v0 = shuffle &lt;32 x i32&gt; v0, &lt;32 x i32&gt; v1, &lt;4, 5, 6, 7&gt; sub.v1 = shuffle &lt;32 x i32&gt; v0, &lt;32 x i32&gt; v1, &lt;32, 33, 34, 35&gt; sub.v2 = shuffle &lt;32 x i32&gt; v0, &lt;32 x i32&gt; v1, &lt;16, 17, 18, 19&gt; call void llvm.arm.neon.vst3(ptr, sub.v0, sub.v1, sub.v2, 4)</p>


<p>Declaration at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21731 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1ac3f0b68c9c78c4f9e1eb09cd415db8">llvm::IRBuilderBase::CreateConstGEP1_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af00a6f39da9d94ec387a366ade60aea5">llvm::createSequentialMask</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a8ac476789127304744e70130f40fa079">createStoreIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="#a092ffa6880261ef3e0ca4ade2cb075ce">getMaxSupportedInterleaveFactor</a>, <a href="#a0a297f370d16737059a7ff5028b0b39a">getNumInterleavedAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab73bb6948312ca0f98055c6a74c37045">llvm::IRBuilderBase::getPtrTy</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a6eaff12d0d3ead952f2a2a2781df56ac">llvm::ShuffleVectorInst::getShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a59c34209e9206120edf7ce3c5da4f872">llvm::ShuffleVectorInst::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#ac9518b8cf085f38ae07134937ad85d31">isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### LowerOperation() {#a69482bf1572254076b1544aecb6fd46e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerOperation (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>This callback is invoked for operations that are unsupported by the target, which are registered to use 'custom' lowering, and whose defined values are all legal.</p>


<p>If the target has no operations that require custom lowering, it need not implement this. The default implementation of this aborts.</p>


<p>Declaration at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 10618 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a385d7f9c63f921a2b28e8426e4101de8">llvm::ISD::ATOMIC_FENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c47226f266248f4b8c155b83601b109">llvm::ISD::ATOMIC_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1db943abc1bf78a911daeb7b03d81de8">llvm::ISD::ATOMIC_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb">llvm::ISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716d19ebad1927a2e8dd5fe3f951f882">llvm::ISD::BR_JT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5">llvm::ISD::CONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1be4c8da7c68a4c683de1a98b5cc5b9d">llvm::ISD::ConstantFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a991d07d163bd4d9984cf1ef36e92c214">llvm::ISD::CTPOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6da41a113af0909470baea7486b3386b">llvm::ISD::CTTZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a601e66a26efd05520f7cb26aef3af340">llvm::ISD::CTTZ_ZERO_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa71ac22470bf853868fe6b39a25bac72">llvm::ISD::DYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a122a450e069003dc86859ef47ab6e278">llvm::ISD::EH_SJLJ_LONGJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae5a57fe9fd413df909ab121ca1a813c7">llvm::ISD::EH_SJLJ_SETJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2e0f3a93e85a46b2ebac7330c2a0c581">llvm::ISD::EH_SJLJ_SETUP_DISPATCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeffc3319657e213a530ce583603f7221">llvm::ISD::FCOPYSIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0bb173b5a879225092abdeaba1394839">llvm::ISD::FP_TO_BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae4a4e2126c6db34e2dfd71b6bd0408ee">llvm::ISD::FP_TO_SINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98661814400e72a77f5ed4e088c06937">llvm::ISD::FP_TO_UINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdb38c8daa8c1ab881007062d113cef3">llvm::ISD::FRAMEADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6ba8fc92ee5081d3e533cb5322f74f29">llvm::ISD::FSINCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89f3afc3fa907ff83759c6c76d97a973">llvm::ISD::GET_ROUNDING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6512c9219b1c585d57adf5bbf276cba6">LowerADDSUBSAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a44afdb77dfc5779686a8da6ffda6abab">LowerATOMIC_FENCE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91430c6031eee8a1f2ff8e2c147fbdf9">LowerAtomicLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a25018debfdb73e1591f2fef057c92fc2">LowerCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#ade8fbcac63ba4f738ae2de92a195becc">LowerCTPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6fd620f229a9cde3e60fc77ab234cd1e">LowerCTTZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a36623d79590f271aff0f88734e356708">LowerEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a99177f2de5b052f54f240d0299a06650">LowerEXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa9d588deb8a61aba4ae8f3e173df1229">LowerFP_TO_INT_SAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab8bc9452845ce93765def17a42addaed">LowerMLOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab254961e69630f8f3d82f83429dd4be4">LowerMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa32a8c1fba431700b7564e94ea5ab4d2">LowerPredicateLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9b284b652f676b448812e5ba2f1b9c70">LowerPREFETCH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac4178b385d94e8532237daf075efb9eb">LowerSDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad7cb387b4f5b286a70a18c171487c6f6">LowerSETCCCARRY</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a07bef52d3581440af08be07591f29990">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#adb9776e3c9f8cf35e243fe5585cdafd3">LowerSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ade7f9db31555260ac7d00622f0ddfff0">LowerTruncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a000f926363dd7bf704f07931ba721320">LowerUADDSUBO_CARRY</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a64590d098106b6407b1969cd8aa7e0be">LowerUDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcisellowering-cpp/#a9ca04dd1028e57cb539334540a46beea">LowerVASTART</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac7770c117c42378101694b6f865978fc">LowerVecReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afdc256ac9c6d942fa5b2dc65914a3e2c">LowerVecReduceF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8c20dd640b6afb2b2f75fbfb8b5f7428">LowerVecReduceMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a09b35db55ed7bd3a4027630fff72d970">LowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab18e3739ef247af415be89a6d40fc20c">LowerVectorExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad0c1ef61c1fa5a02b8d6d66756b35d18">LowerVSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a547b2fe83de11e49958224425b3662d7">LowerWRITE_REGISTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a112324db3910fea5895514851c387442">llvm::ISD::MLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a691a4c9004e9bd04d1c0bebc5df57443">llvm::ISD::PREFETCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a386314479bc7963a544ed142866e7ece">llvm::ISD::RESET_FPMODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2dfacb29792dd59f2cfbe529206265bc">llvm::ISD::RETURNADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a863ec6ebb75bf89cfea14da646d77e92">llvm::ISD::SADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af1b946afff631cee7aa6de570bef7785">llvm::ISD::SADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a874f66e1efe5be79552bbe7ee3121a">llvm::ISD::SDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a26b34eddab8969a79fd3cda432471809">llvm::ISD::SET_FPMODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4fe6c878350458de2c3182392f830988">llvm::ISD::SET_ROUNDING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6bb33e400f29724907dc27ced04e9038">llvm::ISD::SETCCCARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add9a41fa65a9675200d73710a82b880e">llvm::ISD::SPONENTRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6efe16ea597cfd8eeac26516fc992ee7">llvm::ISD::SSUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a77984d86d70df1f3229da7a5119652a9">llvm::ISD::SSUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac47e026e409ff39f319cbb3b096863e6">llvm::ISD::STRICT_FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2273d9cd04ba6e4a7c1a4b28ab1aaba">llvm::ISD::STRICT_FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed">llvm::ISD::STRICT_FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf955b4b70f63865e022c329d1775579">llvm::ISD::STRICT_FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0466b21bfb4f3596e41380d8e2d1956f">llvm::ISD::STRICT_FSETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c8d07d668872f2176fb34724cd799c4">llvm::ISD::STRICT_FSETCCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1ddf36330110b4abea43fe390bea9ef9">llvm::ISD::UADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0f1e3ed26108fec69eb97209c0e39bf">llvm::ISD::UADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5e433873c201ad85c30e42da1ae05977">llvm::ISD::UADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a257ffa49107e2db978e8a6e2688ada">llvm::ISD::UDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28">llvm::ISD::UREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4ffc75d65231b55461c0ba4f36a3e500">llvm::ISD::USUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac81ebcd59d629d8680e50ffba9855255">llvm::ISD::USUBO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89166b38f12c0bd3e8a61d8f1a5a8bc8">llvm::ISD::USUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adfe32beaa596a1512b17e66b46e773ed">llvm::ISD::VASTART</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa58fe501d4e4fa1b4d19e0ed6b8ee6bd">llvm::ISD::VECREDUCE_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5e28372b4a60bf792da88d9bc8a8d0bf">llvm::ISD::VECREDUCE_FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a323856d66e2d8b1f74e528e3f9fe804d">llvm::ISD::VECREDUCE_FMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6a8980cf09891ec57cbce010ba119f79">llvm::ISD::VECREDUCE_FMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110acf12a2d8b57207c69f92973a1fad520a">llvm::ISD::VECREDUCE_FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab4411563ed11f8df0c6ce7af48ee386f">llvm::ISD::VECREDUCE_MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aafd45b465ac59a1a57b8b9862aef6bed">llvm::ISD::VECREDUCE_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c057571f4591494880ec0bba023e0c2">llvm::ISD::VECREDUCE_SMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a11825b59a52b4f5a73c0b877e1ba0e70">llvm::ISD::VECREDUCE_SMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7ce9f75eaf17256deb960b11d1930040">llvm::ISD::VECREDUCE_UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab67678c3310e505df1a3f7677b14cfb0">llvm::ISD::VECREDUCE_UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9b59fad28698a46c33285083818f6b87">llvm::ISD::VECREDUCE_XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a62d363916df0556c38dd1014c45b7a46">llvm::ARMISD::WIN__DBZCHK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a61a1595d03afe86764ad7625d358608e">llvm::ISD::WRITE_REGISTER</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### LowerXConstraint() {#abc928b96601086c4735b9ea8331f0b9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * ARMTargetLowering::LowerXConstraint (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ConstraintVT)</td>
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

<p>Try to replace an X constraint, which matches anything, with another that has more specific requirements based on the type of the corresponding operand.</p>


<p>This returns null if there is no replacement to make.</p>


<p>Declaration at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3cb888a2ce8e95e0d9769687a5e2f7d8">llvm::EVT::isFloatingPoint</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### makeDMB() {#abb0c61c0a16596abc08a5c2dc7fcddd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * ARMTargetLowering::makeDMB (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/namespaces/llvm/arm-mb/#ad70272e2a9ec2a7e3a497458e1edbc85">ARM_MB::MemBOpt</a> Domain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a4d6da696b3c753c5e5fbcc4d21d4cb71">args</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm-mb/#ad70272e2a9ec2a7e3a497458e1edbc85a0290018b446a2b2a74d37cebe1bec0cb">llvm::ARM_MB::SY</a>.</p>


<p>Referenced by <a href="#afa79830ec972611f4c1d1f8e23266aa4">emitLeadingFence</a> and <a href="#a2ee99baef4e41314544119fa4a0e1ce5">emitTrailingFence</a>.</p>

</div>
</div>

### PerformBRCONDCombine() {#ab051a4c12430b297d1465afcb7cf8485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::PerformBRCONDCombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PerformBRCONDCombine - Target-specific DAG combining for <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a4621d333784e3cd8c9f92a1443013dbe">ARMISD::BRCOND</a>.</p>

<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 18411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a4621d333784e3cd8c9f92a1443013dbe">llvm::ARMISD::BRCOND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aee74cff1cb1ea095617b5fa044e342db">llvm::ARMISD::CMOV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ab7f9acd96e942ca625335c36de28e60e">llvm::ARMISD::CMPZ</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6e64fef2ad2ba4052cd8365e97e8d2">llvm::SDNode::getAsZExtVal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a86775f3d85d98a31b2751e1eb348ea">llvm::isNullConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac926ae0b6871c2207db3e787f6dbcb80">llvm::isOneConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6ae08639a6e0f682daf9d9b4809ee0cf7c">llvm::ARMCC::NE</a>.</p>


<p>Referenced by <a href="#a8e96878324f2ca0f847e369f839cfd23">PerformDAGCombine</a>.</p>

</div>
</div>

### PerformCMOVCombine() {#a4ba6b9afcc5b700d4c09664b5fa009d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::PerformCMOVCombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PerformCMOVCombine - Target-specific DAG combining for <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aee74cff1cb1ea095617b5fa044e342db">ARMISD::CMOV</a>.</p>

<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 18443 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af23301e60475124fd80a2cb51f6ba863">llvm::ISD::AssertZext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aee74cff1cb1ea095617b5fa044e342db">llvm::ARMISD::CMOV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ab7f9acd96e942ca625335c36de28e60e">llvm::ARMISD::CMPZ</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c">llvm::ISD::CTLZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a4f1d9a9a0660bc80837984980c7ba402">llvm::ARMCC::EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6e64fef2ad2ba4052cd8365e97e8d2">llvm::SDNode::getAsZExtVal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#a4bd63de978510703f28cd98ea7c0ffa5">llvm::ARMCC::getOppositeCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4236a4880dff9f75230ffb9d581defaa">IsCMPZCSINC</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a86775f3d85d98a31b2751e1eb348ea">llvm::isNullConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac926ae0b6871c2207db3e787f6dbcb80">llvm::isOneConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a174f58016581c78f194dcc75579abb7d">isPowerOf2Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aae3b959a0a2981340fd03c29f528f2f0">llvm::APInt::logBase2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6ae08639a6e0f682daf9d9b4809ee0cf7c">llvm::ARMCC::NE</a>, <a href="#ada7b7dfe4d829cdafff6278e361547df">PerformCMOVToBFICombine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9cfc13d8dfcbb7d035be110b619ea741">llvm::ARMISD::SUBC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0f1e3ed26108fec69eb97209c0e39bf">llvm::ISD::UADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4ffc75d65231b55461c0ba4f36a3e500">llvm::ISD::USUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac81ebcd59d629d8680e50ffba9855255">llvm::ISD::USUBO_CARRY</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>


<p>Referenced by <a href="#a8e96878324f2ca0f847e369f839cfd23">PerformDAGCombine</a>.</p>

</div>
</div>

### PerformCMOVToBFICombine() {#ada7b7dfe4d829cdafff6278e361547df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::PerformCMOVToBFICombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 18151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a109dda4df2be3a46022e3600484f4efb">llvm::ARMISD::BFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ab7f9acd96e942ca625335c36de28e60e">llvm::ARMISD::CMPZ</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a4f1d9a9a0660bc80837984980c7ba402">llvm::ARMCC::EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3015474e70e59c0a3ed4f9f0e8644b75">llvm::APInt::getActiveBits</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a74b17cf9d0ee8268a5b38bbb896a30ba">llvm::ConstantSDNode::getAPIntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a86775f3d85d98a31b2751e1eb348ea">llvm::isNullConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a174f58016581c78f194dcc75579abb7d">isPowerOf2Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aae3b959a0a2981340fd03c29f528f2f0">llvm::APInt::logBase2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6ae08639a6e0f682daf9d9b4809ee0cf7c">llvm::ARMCC::NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a27ad8ac0b3b15a21f86c5f89e0c9cdd0">llvm::APInt::popcount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>


<p>Referenced by <a href="#a4ba6b9afcc5b700d4c09664b5fa009d9">PerformCMOVCombine</a>.</p>

</div>
</div>

### PerformDAGCombine() {#a8e96878324f2ca0f847e369f839cfd23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::PerformDAGCombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
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


<p>Declaration at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 18936 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a41f4297f00dc6d8d7445d13daf7eba26">llvm::ARMISD::ADDC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a38281aedc70f7c707027367acd3234cb">llvm::ARMISD::ADDE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ae943be65cd3ae29f0032ad56a3875c42">llvm::ARMISD::ASRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a109dda4df2be3a46022e3600484f4efb">llvm::ARMISD::BFI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb">llvm::ISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a4621d333784e3cd8c9f92a1443013dbe">llvm::ARMISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9b3b5c8aca58fc851520aab312b46637">llvm::ARMISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aee74cff1cb1ea095617b5fa044e342db">llvm::ARMISD::CMOV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ab7f9acd96e942ca625335c36de28e60e">llvm::ARMISD::CMPZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38abc844212c86a5d4665e522f7a7de6610">llvm::ARMISD::CSINC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7fa873eda688ec241983ec07abb187bb">llvm::ARMISD::CSINV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a2f975a28397d8aaddaf658d8f09f0086">llvm::ARMISD::CSNEG</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#acf37bd7e831bdb2a5c9da8d63f843101">llvm::TargetLowering::DAGCombinerInfo::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178">llvm::ISD::FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adcb96bd09d7c75c7669fa5f9d1190899">llvm::APInt::getHighBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">llvm::ISD::INSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a3e9bf86bbbfea029b1f065cc6fbab978">llvm::ARMISD::LSLL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ab729d2ded9bb455206f7944e09444c73">llvm::ARMISD::LSRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9326d7ebc2b118b134db7934f6fa4713">llvm::ARMISD::MVESEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38afcd7b69a3ab8e9b9c40b7a973d961b05">llvm::ARMISD::MVETRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ad0fc91cb6c69b2e9e9ef67d896bd76a5">llvm::ARMISD::MVEZEXT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a7ca64b74f25fc6b568b6446883e80379">PerformADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8e48c97fe5cefbf70aa4e9fa0138c99d">PerformAddcSubcCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad951ca5aa57e9482c9d5edfcf7cd1e46">PerformADDECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9dbbe6acb79ab1e69a57634d58edcf4f">PerformAddeSubeCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aec3ab4d2802494bdb8b2c3c5343f8254">PerformANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a407b2b727a4e59f73315d53b9836daf6">PerformARMBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab6bb88ba60ff98b8e2c142d472f53717">PerformBFICombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a51359c8ddfa214a514dbaab1b2ad2d29">PerformBITCASTCombine</a>, <a href="#ab051a4c12430b297d1465afcb7cf8485">PerformBRCONDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afd8034cb60968e67a0b01c4ae93ada12">PerformBUILD_VECTORCombine</a>, <a href="#a4ba6b9afcc5b700d4c09664b5fa009d9">PerformCMOVCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a572a3d6dc485316839e59442fb7dae19">PerformCMPZCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aae8b403580f3136879e238457f94d7ba">PerformCSETCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac2452330035d212f79a73e61ce9b923f">PerformExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a172a1f5983db0d10ae90c0d3f5beccdb">PerformExtractEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae5e5f93737f5c911440a221ddedf8a64">PerformFADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8d527926779350200f34b7c3fc12a95c">PerformFPExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ade8c7b6c75d72baebf1ac6d244b9fca5">PerformHWLoopCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a57984ebd9271c38d02eb92b050f5bcee">PerformInsertEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaece9d12c539bbab91aff76ea7e95096">PerformInsertSubvectorCombine</a>, <a href="#a42aa092f2811f72cad69b42cc2e4bb64">PerformIntrinsicCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4118089abb4cbadaf4b698cbbe05154f">PerformLOADCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a375638c9ba231abce7be8b8130079499">PerformLongShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afe3fc9a96e843f0a30a80d4af77c1b26">PerformMinMaxCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae57c77c91d8ca534534565c26afee2da">PerformMULCombine</a>, <a href="#a589928ae94c1e14b50e374c6a1146c60">PerformMVEExtCombine</a>, <a href="#a35a55a457bfc044d33bdeb4811532531">PerformMVETruncCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a77f2232fb1d07b3f88edaef89e94e673">PerformMVEVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab81a857a51f1d25a352fc51569f079a0">PerformORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1d0f22bfc290fd2cb53c9486286359df">PerformPREDICATE_CASTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ada94cd83b8b150c87b337c156f027c3c">PerformReduceShuffleCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2d87a7cc93a308acb6482288fea2bd7c">PerformSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a391272ef81598a4a25763b2f35809615">PerformShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a82745b7ba6baed8c8e0af284dadb90a5">PerformSignExtendInregCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a111643e86a00d697a134123e45817e14">PerformSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#adac55a5ab0773a88dd987c4610e2ed59">PerformUMLALCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4d29144f0f49ccc2a115d389beaef36e">PerformVCMPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a179a8cd2adc83f28bc70fed3ee8fde0b">PerformVCVTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a153df73802d794646f81fb17c8dc5d17">PerformVDUPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a57a099df9c79ef37ef7f89374247ac0e">PerformVDUPLANECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a90bba043b3ae7c24c251d61798920475">PerformVECREDUCE_ADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a309ad0236599847afc64e0ab08fca23f">PerformVECTOR_REG_CASTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8544593225835a30146f86a3187740e7">PerformVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a7010007dcac40b070c67842b07a3845b">PerformVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ace623ded66eb6a65f791b3ab555337fc">PerformVMOVDRRCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a19d36e331487399aaac4f18bac0c7956">PerformVMOVhrCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaec24048b5502da3e426b474be7e6b4d">PerformVMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a40eb7d32bd58dfbdde6c632446a56828">PerformVMOVrhCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa98ade29969ff63557a3a9594f95891a">PerformVMOVRRDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a30dc6de174502314903dfcbf8d176cea">PerformVMulVCTPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a040e9492b947241650ac7f528bd75c25">PerformVQDMULHCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a87f35b3974b7d383ff5cd70bdfa090ab">PerformVQMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8ee8d90c02a1da62f94c6322a8f004cb">PerformVSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a99f918c3264972ed6aea09c675404952">PerformVSetCCToVCTPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac1399030f41bb48286cffbbfddb29a3f">PerformXORCombine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a1e452bb26851eafc6364ba340c36ecf0">llvm::ARMISD::PREDICATE_CAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a83728aad1cd6a81514525c49fc23ce17">llvm::ARMISD::QADD16b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38af914da04c6db0f9697158bf86d51bd02">llvm::ARMISD::QADD8b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aad9651faf4a6694a93228858973219b5">llvm::ARMISD::QSUB16b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a41ec5a4a3fcc7e41263a4bc0b6a69c65">llvm::ARMISD::QSUB8b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ab2fd70d9aeac9343fa8f00ccdeff7f0b">llvm::TargetLowering::SimplifyDemandedBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af3b59179b6fcbc89463181015ace8e9b">llvm::ISD::SMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaac895215ecbb3c411c957c8beb39b70">llvm::ISD::SMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a5faaa77b1082966846b8847f5d53479d">llvm::ARMISD::SMLALBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9982953b4608d6356bd7fe3c4c4fe9c0">llvm::ARMISD::SMLALBT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7304a9dad68e35cedd3286fc2d51bee5">llvm::ARMISD::SMLALTB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a33ecfe3938a12d2b6b83a69094a33d29">llvm::ARMISD::SMLALTT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aed7b9527784ba4e06dcf95704002dc24">llvm::ARMISD::SMULWB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a8193c5897199f248b53c6fff20ce18f2">llvm::ARMISD::SMULWT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9cfc13d8dfcbb7d035be110b619ea741">llvm::ARMISD::SUBC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a06e89dbcfaf0ceca94295988d35809c2">llvm::ARMISD::SUBE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af675e759c0ffff8d48ea14a60fe3517b">llvm::ISD::UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a17126302da6199930e55e841ca1b082d">llvm::ISD::UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a8d9d96ad008a475ebbff8e366bbc1eb6">llvm::ARMISD::UMLAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ad0f2aceb3ee7cd23f8b352d8580169a4">llvm::ARMISD::UQADD16b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a2ffd7790f42a2c3092b83e37c7fe3da9">llvm::ARMISD::UQADD8b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aeff71ef40fdc565429b4de72440a8500">llvm::ARMISD::UQSUB16b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ae378627a128dd34c938348e5552bd468">llvm::ARMISD::UQSUB8b</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a359ec09c5b0bea8d8e73795738c74b8f">llvm::ARMISD::VADDLVAs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ac255df83083c0579aa5acc39a0a53b92">llvm::ARMISD::VADDLVAu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7f60e06779eb757bcaadbbc7f1b38de2">llvm::ARMISD::VADDLVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a28b0ceeefba427b139e09b5850ab9389">llvm::ARMISD::VADDLVu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a2c3d99682d5c725adcbe430bc69b9c99">llvm::ARMISD::VADDVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ada29df039613d536f11af709cf7691ee">llvm::ARMISD::VADDVu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38acc417089525086253ff4296bd2f07f0b">llvm::ARMISD::VBSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7c288956c8c8e43434e6ae8633daab64">llvm::ARMISD::VCMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a50bbb022c555743f1805d3df3ee98adb">llvm::ARMISD::VDUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a64c0bb0345ba1b69528dd52da797f6a7">llvm::ARMISD::VDUPLANE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89a8ec08f6908a989c2d0198ae8851f9">llvm::ISD::VECREDUCE_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a40f2efa7d8c9b15db57cc3500bba1f09">llvm::ARMISD::VECTOR_REG_CAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a736037fbdc5e0e5d5c0fff76584255d4">llvm::ARMISD::VLD1DUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a81b77974c326f91d888b4f7c7346440d">llvm::ARMISD::VLD2DUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aeb8a7ec48dfdbb30f676f1f9ed78515e">llvm::ARMISD::VLD3DUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a682019fb60ebfdcb1b6c12bef90e81d1">llvm::ARMISD::VLD4DUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aa21f7a01a26f04604b61652864d577c1">llvm::ARMISD::VMLALVAs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a3fe835d935b0d36f42b92c9da35f3d03">llvm::ARMISD::VMLALVAu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a214985f7b88b1d15a7103b432dba2dbb">llvm::ARMISD::VMLALVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ab4543c9ea891307c00d497963828365c">llvm::ARMISD::VMLALVu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a67e82cfd8b584d35f5de2e40870dbde5">llvm::ARMISD::VMLAVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a5ba46f411106d2444bd93b563cf6da00">llvm::ARMISD::VMLAVu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a0791f9172a1b74506504d1f22d81f389">llvm::ARMISD::VMOVDRR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38acb6fa97139e090fff02bc421e02451ed">llvm::ARMISD::VMOVhr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ac2f455684efb89d120029b7a65acd013">llvm::ARMISD::VMOVN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a3b1cd1c01c04128536b9cbe473629904">llvm::ARMISD::VMOVrh</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7f93dc1b4123a3d49e2a544960758ef1">llvm::ARMISD::VMOVRRD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a0ea65604b43fdf53982b2e0c2622abcc">llvm::ARMISD::VQDMULH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a883cd6fb091beb1d5da94e6bf2eb086a">llvm::ARMISD::VQMOVNs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38af1218b9767cbe26dbbbd375286b55c0a">llvm::ARMISD::VQMOVNu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0b7d2c769fd0fbaab3c4a2fc8e7ea0c">llvm::ISD::VSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### PerformIntrinsicCombine() {#a42aa092f2811f72cad69b42cc2e4bb64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::PerformIntrinsicCombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PerformIntrinsicCombine - ARM-specific DAG combining for intrinsics.</p>

<p>Declaration at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 17552 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a41bd84b853e2c03fb1af1f4ca9ebdcaf">llvm::ISD::BUILD_PAIR</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#acf37bd7e831bdb2a5c9da8d63f843101">llvm::TargetLowering::DAGCombinerInfo::DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad34aa0262dce6014056d3d3be02682af">isVShiftLImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a03ce20d2138535663fed2e0fcc5ec604">isVShiftRImm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ab2fd70d9aeac9343fa8f00ccdeff7f0b">llvm::TargetLowering::SimplifyDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13fac837bff23a12c3735d463020f37979de">Unsigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38add9d7dd92c2e0454947271184f9cea92">llvm::ARMISD::VADDLVps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38adeeb8ac961b16f30b10b1dc668788211">llvm::ARMISD::VADDLVpu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a7f60e06779eb757bcaadbbc7f1b38de2">llvm::ARMISD::VADDLVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a28b0ceeefba427b139e09b5850ab9389">llvm::ARMISD::VADDLVu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a2c3d99682d5c725adcbe430bc69b9c99">llvm::ARMISD::VADDVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ada29df039613d536f11af709cf7691ee">llvm::ARMISD::VADDVu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38acc417089525086253ff4296bd2f07f0b">llvm::ARMISD::VBSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a3bed0337c3e72d48b7acb7d944bc92a4">llvm::ARMISD::VQRSHRNsIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a8bbaf9840d99cfe346344a0fccf67870">llvm::ARMISD::VQRSHRNsuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a28fd5ec0d2731c2711f5019e65ea17fa">llvm::ARMISD::VQRSHRNuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a0cd0628ba1ee0cbe2f3b27056d84e31d">llvm::ARMISD::VQSHLsIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38adf824fd0265a67f9e20a992536543787">llvm::ARMISD::VQSHLsuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a49f0f08f662ff51ecc3221cee92c5ede">llvm::ARMISD::VQSHLuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9cecd45f88e494fe8828dd3b7e566547">llvm::ARMISD::VQSHRNsIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a1f8d979594f9d98e26744923151e7248">llvm::ARMISD::VQSHRNsuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a1241f4af5ed5a4f37eed9e1490a3754e">llvm::ARMISD::VQSHRNuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a88fe6ff9aa04ed53f2d31971d85523c7">llvm::ARMISD::VRSHRNIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ae43d68e08454b25bde1237df049d4bfc">llvm::ARMISD::VRSHRsIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aeb906d5db57d71d1b2adf555f95ced45">llvm::ARMISD::VRSHRuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aee85fe37c0da86af1536a98c888f9150">llvm::ARMISD::VSHLIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a1eb3012ff65d306c3bfcda64ca53a17c">llvm::ARMISD::VSHRsIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ac2cc71438511eab862a4040d7dbdedc9">llvm::ARMISD::VSHRuIMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a1d077dec7708f42d7317b676157efc93">llvm::ARMISD::VSLIIMM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aa51bd387b70ce9454c4a1360f3479e1c">llvm::ARMISD::VSRIIMM</a>.</p>


<p>Referenced by <a href="#a8e96878324f2ca0f847e369f839cfd23">PerformDAGCombine</a>.</p>

</div>
</div>

### PerformMVEExtCombine() {#a589928ae94c1e14b50e374c6a1146c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::PerformMVEExtCombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 18832 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae83b3d8e9a944b5d818e80524a5003e2">llvm::SelectionDAG::CreateStackTemporary</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#acf37bd7e831bdb2a5c9da8d63f843101">llvm::TargetLowering::DAGCombinerInfo::DAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0f68c9c0e4a38aebd5773f80dd5b716">llvm::SelectionDAG::getEntryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a03140e92d989c9a96312035efb8f67fc">llvm::SelectionDAG::getExtLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aee35a362966ced72913881d8a2dc3be8">llvm::EVT::getHalfNumVectorElementsVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a193d4ea30b27a0c86550ae249eefaeaa">llvm::SelectionDAG::getMergeValues</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6a52e913507400fcde94fd2e023a149c">llvm::SelectionDAG::getZeroExtendInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#a2030eb1014aca2732ca4ecfb9ae4b5a0">llvm::TargetLowering::DAGCombinerInfo::isAfterLegalizeDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a9326d7ebc2b118b134db7934f6fa4713">llvm::ARMISD::MVESEXT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af99f8aa9b9d9dddc47ec39b12a1eb02d">PerformSplittingMVEEXTToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a50bbb022c555743f1805d3df3ee98adb">llvm::ARMISD::VDUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a40f2efa7d8c9b15db57cc3500bba1f09">llvm::ARMISD::VECTOR_REG_CAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a612cd894d3df73b6e47707d1fc1da974">llvm::ARMISD::VREV16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a96babbe11f5e86cf3b02a0064c03c84e">llvm::ARMISD::VREV32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>


<p>Referenced by <a href="#a8e96878324f2ca0f847e369f839cfd23">PerformDAGCombine</a>.</p>

</div>
</div>

### PerformMVETruncCombine() {#a35a55a457bfc044d33bdeb4811532531}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::PerformMVETruncCombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 18663 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae83b3d8e9a944b5d818e80524a5003e2">llvm::SelectionDAG::CreateStackTemporary</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#acf37bd7e831bdb2a5c9da8d63f843101">llvm::TargetLowering::DAGCombinerInfo::DAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5d154312bef0ed1a6bacfcb52b7cf8eb">llvm::SelectionDAG::getBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0f68c9c0e4a38aebd5773f80dd5b716">llvm::SelectionDAG::getEntryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aee35a362966ced72913881d8a2dc3be8">llvm::EVT::getHalfNumVectorElementsVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8063c77c39146c0790e66f5e0679475c">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b0e59823444a55c295af279611a9d24">llvm::SelectionDAG::getUNDEF</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#a2030eb1014aca2732ca4ecfb9ae4b5a0">llvm::TargetLowering::DAGCombinerInfo::isAfterLegalizeDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a875013a3b871d454c0029aa65e124667">isVMOVNTruncMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38afcd7b69a3ab8e9b9c40b7a973d961b05">llvm::ARMISD::MVETRUNC</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38a40f2efa7d8c9b15db57cc3500bba1f09">llvm::ARMISD::VECTOR_REG_CAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ac2f455684efb89d120029b7a65acd013">llvm::ARMISD::VMOVN</a>.</p>


<p>Referenced by <a href="#a8e96878324f2ca0f847e369f839cfd23">PerformDAGCombine</a>.</p>

</div>
</div>

### preferIncOfAddToSubOfNot() {#a36f078885862bc3b837dcfe057d05649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::preferIncOfAddToSubOfNot (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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


<p>Declaration at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 13946 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#ad958859a7af278dd5ea2b593c2b25050">llvm::EVT::isScalarInteger</a>.</p>

</div>
</div>

### preferredShiftLegalizationStrategy() {#af2c8b0d2dd39354fff7d4bb1ab3fa2f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::ShiftLegalizationStrategy ARMTargetLowering::preferredShiftLegalizationStrategy (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned ExpansionFactor)</td>
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



<p>Declaration at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21436 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1cfe6f1187d7ab1a0ada9cc119c1b2b4a9774fd1a96085b8680d017dd42652bc1">llvm::TargetLoweringBase::LowerToLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa88eb4ddf2a7c4d5d5482c9fc0b9090a">llvm::TargetLoweringBase::preferredShiftLegalizationStrategy</a>.</p>

</div>
</div>

### preferZeroCompareBranch() {#ad4c3b6ad836d26fb542b86fafb89653b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMTargetLowering::preferZeroCompareBranch ()</td>
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

<p>Return true if the heuristic to prefer icmp eq zero should be used in code gen prepare.</p>

<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>

</div>
</div>

### ReplaceNodeResults() {#a28af47b21a8953afd3568b40acf3424d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::ReplaceNodeResults (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Declaration at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 10778 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9c91befeca2a25c8050d4c3dff8b6d67">llvm::ISD::ATOMIC_CMP_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af06754acf6dbda0709a6cda0b11cdab5">Expand64BitShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a399ea332dd7c5c88085dd03e09152545">ExpandREAD_REGISTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae4a4e2126c6db34e2dfd71b6bd0408ee">llvm::ISD::FP_TO_SINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98661814400e72a77f5ed4e088c06937">llvm::ISD::FP_TO_UINT_SAT</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#af6fe41bd1c6914242c20b4917de0d3f4">llvm::SDValue::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6512c9219b1c585d57adf5bbf276cba6">LowerADDSUBSAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa9d588deb8a61aba4ae8f3e173df1229">LowerFP_TO_INT_SAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ade7f9db31555260ac7d00622f0ddfff0">LowerTruncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab18e3739ef247af415be89a6d40fc20c">LowerVectorExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92fceabd268d62ef2c95799a102b8abf">llvm::ISD::READ_REGISTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac43f9bea13e29622bbf18c861b52144d">llvm::ISD::READCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9edb7bbdf708d2f51e1cab727a105fdc">ReplaceCMP_SWAP_64Results</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a663a00cee8894f834358261a64ea7c7e">ReplaceLongIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a953988fc960bc5ff29afff3ded965e9d">ReplaceREADCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af1b946afff631cee7aa6de570bef7785">llvm::ISD::SADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a874f66e1efe5be79552bbe7ee3121a">llvm::ISD::SDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a77984d86d70df1f3229da7a5119652a9">llvm::ISD::SSUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5e433873c201ad85c30e42da1ae05977">llvm::ISD::UADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a257ffa49107e2db978e8a6e2688ada">llvm::ISD::UDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28">llvm::ISD::UREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89166b38f12c0bd3e8a61d8f1a5a8bc8">llvm::ISD::USUBSAT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### shouldAlignPointerArgs() {#a26651869531ef2356ef2788595ad7c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::shouldAlignPointerArgs (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *, unsigned &amp;, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp;)</td>
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

<p>Return true if the pointer arguments to CI should be aligned by aligning the object whose address is being passed.</p>


<p>If so then MinSize is set to the minimum size the object must be to be aligned and PrefAlign is set to the preferred alignment.</p>


<p>Declaration at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 1967 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### shouldConvertConstantLoadToIntImm() {#a7a185e1e62cf599211822cc65db54242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::shouldConvertConstantLoadToIntImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Declaration at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### shouldConvertFpToSat() {#ae39c938299ddc0dc8534e1a05cb0c2fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::shouldConvertFpToSat (unsigned Op, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> FPVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Should we generate fp_to_si_sat and fp_to_ui_sat from type FPVT to type VT from min(max(fptoi)) saturation patterns.</p>

<p>Declaration at line 766 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 13955 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa93fbbc66d52a51d178af8ac4398ec05">llvm::TargetLoweringBase::isOperationLegalOrCustom</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>

</div>
</div>

### shouldConvertSplatType() {#ab32574e30e8d85eaa2f692d8fc3c6766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * ARMTargetLowering::shouldConvertSplatType (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> * SVI)</td>
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

<p>Given a shuffle vector SVI representing a vector splat, return a new scalar type of size equal to SVI's scalar type if the new type is more profitable.</p>


<p>Returns nullptr otherwise. For example under MVE float splats are converted to integer to prevent the need to move from SPR to GPR registers.</p>


<p>Declaration at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a87f56db834c58ca630624956ecf6972f">llvm::Type::getInt16Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a59c34209e9206120edf7ce3c5da4f872">llvm::ShuffleVectorInst::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3ffc75c3a4cb82ba307a3334483eb4ac">llvm::Type::isFloatTy</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a8cf1f36cc41c466e66d6467e40554841">llvm::Type::isHalfTy</a>.</p>

</div>
</div>

### shouldExpandAtomicCmpXchgInIR() {#ac4b5d6d1333be49386e35e56c28647fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AtomicExpansionKind ARMTargetLowering::shouldExpandAtomicCmpXchgInIR (<a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst">AtomicCmpXchgInst</a> * AI)</td>
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

<p>Declaration at line 691 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a2985b9c595be648a72a6dd08268c2218">llvm::TargetLoweringBase::LLSC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a6adf97f83acf6453d4a6a4b1070f3754">llvm::TargetLoweringBase::None</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### shouldExpandAtomicLoadInIR() {#a0a17ad44231dd559dedb8ff61bcfe29e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AtomicExpansionKind ARMTargetLowering::shouldExpandAtomicLoadInIR (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI)</td>
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

<p>Returns how the given (atomic) load should be expanded by the IR-level AtomicExpand pass.</p>

<p>Declaration at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a4cf4a97fbc85619dbd1e34842a54bdba">llvm::TargetLoweringBase::LLOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a6adf97f83acf6453d4a6a4b1070f3754">llvm::TargetLoweringBase::None</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### shouldExpandAtomicRMWInIR() {#a6ed1fafeaecc08fe13e54b080e259dd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AtomicExpansionKind ARMTargetLowering::shouldExpandAtomicRMWInIR (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * RMW)</td>
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


<p>Declaration at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a369f472273bc816735055f13a6e6fd6c">llvm::TargetLoweringBase::CmpXChg</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a667d327df48643f4d2111a0065b192f2">llvm::AtomicRMWInst::isFloatingPointOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a2985b9c595be648a72a6dd08268c2218">llvm::TargetLoweringBase::LLSC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a6adf97f83acf6453d4a6a4b1070f3754">llvm::TargetLoweringBase::None</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### shouldExpandAtomicStoreInIR() {#a3e78ac617e56bd040677cb06a69244b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLoweringBase::AtomicExpansionKind ARMTargetLowering::shouldExpandAtomicStoreInIR (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI)</td>
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

<p>Returns how the given (atomic) store should be expanded by the IR-level AtomicExpand pass into.</p>


<p>For instance <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a8098b34f582537833b36b58273c3545b">AtomicExpansionKind::Expand</a> will try to use an atomicrmw xchg.</p>


<p>Declaration at line 687 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a8098b34f582537833b36b58273c3545b">llvm::TargetLoweringBase::Expand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a6adf97f83acf6453d4a6a4b1070f3754">llvm::TargetLoweringBase::None</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### shouldFoldConstantShiftPairToMask() {#a58c6bec36cfce34f95d92841b1d5ef9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::shouldFoldConstantShiftPairToMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7a">CombineLevel</a> Level)</td>
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

<p>Return true if it is profitable to fold a pair of shifts into a mask.</p>


<p>This is usually true on most targets. But some targets, like Thumb1, have immediate shift instructions, but no immediate "and" instruction; this makes the fold unprofitable.</p>


<p>Declaration at line 758 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 13924 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7aa9386e6e4a4c86dabf136bc0fc9f6cf3b">llvm::BeforeLegalizeTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>.</p>

</div>
</div>

### shouldFoldSelectWithIdentityConstant() {#a5aefcfec6c74e86b395e847344a7b189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::shouldFoldSelectWithIdentityConstant (unsigned BinOpcode, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if pulling a binary operation into a select with an identity constant is profitable.</p>


<p>This is the inverse of an IR transform. Example: X + (Cond ? Y : 0) --&gt; Cond ? (X + Y) : X</p>


<p>Declaration at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 13941 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>.</p>

</div>
</div>

### shouldFormOverflowOp() {#a7b22b5c20474c62fa91bd60e856cec33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMTargetLowering::shouldFormOverflowOp (unsigned Opcode, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, bool MathUsed)</td>
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

<p>Try to convert math with an overflow comparison into the corresponding DAG node operation.</p>


<p>Targets may want to override this independently of whether the operation is legal/custom for the given type because it may obscure matching of other patterns.</p>


<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1b6f74fbe8b15567434fa5d20a540c5c">llvm::TargetLoweringBase::shouldFormOverflowOp</a>.</p>

</div>
</div>

### shouldInsertFencesForAtomic() {#a0a3f5a90fe18617c18aa780cd9445d57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::shouldInsertFencesForAtomic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Whether <a href="/web-llvm/docs/api/classes/llvm/atomicexpandpass">AtomicExpandPass</a> should automatically insert fences and reduce ordering for this atomic.</p>


<p>This should be true for most architectures with weak memory ordering. Defaults to false.</p>


<p>Declaration at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### shouldReassociateReduction() {#a8df46690eb2ee31ed20a0afe37fc4e48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMTargetLowering::shouldReassociateReduction (unsigned Opc, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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



<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89a8ec08f6908a989c2d0198ae8851f9">llvm::ISD::VECREDUCE_ADD</a>.</p>

</div>
</div>

### SimplifyDemandedBitsForTargetNode() {#a655de0b9ba51c463a01a23651abb0cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::SimplifyDemandedBitsForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO, unsigned Depth)</td>
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

<p>Attempt to simplify any target nodes based on the demanded bits/elts, returning true on success.</p>


<p>Otherwise, analyze the expression and return a mask of KnownOne and KnownZero bits for the expression (used to simplify the caller). The KnownZero/One bits may only be accurate for those bits in the Demanded masks.</p>


<p>Declaration at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ae943be65cd3ae29f0032ad56a3875c42">llvm::ARMISD::ASRL</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#a75c3b728d0f9ba68b58c71a4940aedab">llvm::TargetLowering::TargetLoweringOpt::CombineTo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#a15f606b1ca13c24d23039809f667daeb">llvm::TargetLowering::TargetLoweringOpt::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a1142830159ad93c394b72a09905a51fd">llvm::ARM_AM::decodeVMOVModImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acfae9bdee6027ffa8ffe244cc22e3a76">llvm::APInt::isSubsetOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38ab729d2ded9bb455206f7944e09444c73">llvm::ARMISD::LSRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a1bb3f6ea028996773613a5f135b4d083">llvm::TargetLowering::SimplifyDemandedBitsForTargetNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armisd/#a4097c262adca175c068cc59fa984dc38aeb5a51baba9276b3e2ea25b7ac5b8806">llvm::ARMISD::VBICIMM</a>.</p>

</div>
</div>

### softPromoteHalfType() {#af1a79a0380ffa3c915ddfb6767f24d9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMTargetLowering::softPromoteHalfType ()</td>
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



<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>

</div>
</div>

### supportSwiftError() {#a2f59b975114229e04efb87bbc8662224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMTargetLowering::supportSwiftError ()</td>
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

<p>Return true if the target supports swifterror attribute.</p>


<p>It optimizes loads and stores to reading and writing a specific register.</p>


<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a8ae827683289cd88fddbe641f8608b9b">llvm::ARMBaseRegisterInfo::getCalleeSavedRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#abb9d03a862069b7f3c4f446e0be8b826">llvm::ARMBaseRegisterInfo::getCallPreservedMask</a>.</p>

</div>
</div>

### targetShrinkDemandedConstant() {#a98a503af3a695653b6093323a1c4b9cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::targetShrinkDemandedConstant (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO)</td>
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



<p>Declaration at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#a75c3b728d0f9ba68b58c71a4940aedab">llvm::TargetLowering::TargetLoweringOpt::CombineTo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#a15f606b1ca13c24d23039809f667daeb">llvm::TargetLowering::TargetLoweringOpt::DAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a> and <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#aa945b77fd77cdc5cf80e7b7f6ae78a98">llvm::TargetLowering::TargetLoweringOpt::LegalOps</a>.</p>

</div>
</div>

### useFPRegsForHalfType() {#a3bebe089fbc63179232f838dc2d13f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMTargetLowering::useFPRegsForHalfType ()</td>
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



<p>Definition at line 779 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>

</div>
</div>

### useLoadStackGuardNode() {#a845ff631109e5c60ccdcf8921806ec74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::useLoadStackGuardNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>If this function returns true, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> emits a LOAD_STACK_GUARD node when it is lowering Intrinsic::stackprotector.</p>

<p>Declaration at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### useSoftFloat() {#ad605f833179d4fecc1f4e0e8ca0fe2f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::useSoftFloat ()</td>
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



<p>Declaration at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 1659 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### findRepresentativeClass() {#a8b4bcdae4a907d7a62317ed35092d5bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const TargetRegisterClass *, uint8_t &gt; ARMTargetLowering::findRepresentativeClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the largest legal super-reg register class of the register class for the specified type and its associated "cost".</p>


<p>findRepresentativeClass - Return the largest legal super-reg register class of the register class for the specified type and its associated "cost".</p>


<p>Declaration at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 1674 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac1cbaebc2a18476b73105d6916a56664">llvm::TargetLoweringBase::findRepresentativeClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addAllExtLoads() {#af9a6eb2899b9a24ed9063e600c2a79af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::addAllExtLoads (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> To, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a> Action)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1005 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### addDRTypeForNEON() {#a772686149d1e19a6a4cdcd005b4b475d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::addDRTypeForNEON (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### addMVEVectorTypes() {#ae65f0d269ecefa64da1246db7134eec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::addMVEVectorTypes (bool HasMVEFP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1004 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### addQRTypeForNEON() {#afc194f4f93baee4e019f2765e3ef5582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::addQRTypeForNEON (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 803 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### addTypeForNEON() {#a4f574ab8cc1ea7783c9dd79ee31925f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::addTypeForNEON (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> PromotedLdStVT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### BuildSDIVPow2() {#a1e8b4eb968b1f6412b23ef0baa55b6f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::BuildSDIVPow2 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Divisor, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; Created)</td>
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


<p>Declaration at line 896 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 10083 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### ByValNeedsCopyForTailCall() {#ab0477f973df5ccbff82238817c808d4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMTargetLowering::ByValCopyKind ARMTargetLowering::ByValNeedsCopyForTailCall (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Dst, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 827 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 2348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### CanLowerReturn() {#a8f51a2a30fc4f094416e0f26bc9a662c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::CanLowerReturn (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy)</td>
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


<p>Declaration at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 3246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### CCAssignFnForNode() {#a63ce9d4816191f6e7d42abb5bb09cdbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCAssignFn * ARMTargetLowering::CCAssignFnForNode (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, bool Return, bool isVarArg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CCAssignFnForNode - Selects the correct <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> for the given CallingConvention.</p>

<p>Declaration at line 821 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 2162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### computeAddrForCallArg() {#a10ced4352083b391a681f80d8d7c6999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, MachinePointerInfo &gt; ARMTargetLowering::computeAddrForCallArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> StackPtr, bool IsTailCall, int SPDiff)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 824 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 2315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### EmitLowered\_\_chkstk() {#a6b33868c828458f055b989c08b7ad513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * ARMTargetLowering::EmitLowered__chkstk (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 11757 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### EmitLowered\_\_dbzchk() {#a51ad4afc48a9a86013cd21f534842cdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * ARMTargetLowering::EmitLowered__dbzchk (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1002 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 11832 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### EmitSjLjDispatchBlock() {#a6a6eebb750ae8942e6a9074b71c15f5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::EmitSjLjDispatchBlock (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 995 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 10979 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### EmitStructByval() {#ab400019546a5c0de6a4b29960fdb287c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * ARMTargetLowering::EmitStructByval (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 997 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 11513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### ExpandBITCAST() {#a57e45922b1195dcfa1b4cc1367db5a2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::ExpandBITCAST (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> * Subtarget)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ExpandBITCAST - If the target supports VFP, this function is called to expand a bit convert where either the source or destination type is i64 to use a VMOVDRR or VMOVRRD node.</p>


<p>This should not be done when the non-i64 operand type is illegal (e.g., v2f32 for a target that doesn't support vectors), since the legalizer won't know what to do with that.</p>


<p>Declaration at line 877 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 6300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### ExpandDIV\_Windows() {#a5bb5b6982bd11ece0da896aca7f4e4d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::ExpandDIV_Windows (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool Signed, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 875 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 10144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### getARMCmp() {#a2ba004626656f316777a3653cdace220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::getARMCmp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> CC, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; ARMcc, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns appropriate <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> CMP (cmp) and corresponding condition code for the given operands.</p>

<p>Declaration at line 985 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4844 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### getARMXALUOOp() {#a1af6aec3817ec31a795bc58fafb741de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; ARMTargetLowering::getARMXALUOOp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; ARMcc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4999 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### getCMOV() {#afc177b05ec8021482d8e9f68f6b8622e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::getCMOV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> FalseVal, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> TrueVal, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ARMcc, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 983 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 5317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### getEffectiveCallingConv() {#aa25dd0405c2d8bdfdf6659563877b20d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallingConv::ID ARMTargetLowering::getEffectiveCallingConv (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, bool isVarArg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getEffectiveCallingConv - Get the effective calling convention, taking into account presence of floating point hardware and calling convention limitations, such as support for variadic functions.</p>

<p>Declaration at line 819 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 2108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### GetF64FormalArgument() {#afa996f96978f1bc6930db528137255bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::GetF64FormalArgument (<a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; NextVA, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Root, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 815 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### getRegisterByName() {#a42e89d9458ea2af6224c3b56af88f066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register ARMTargetLowering::getRegisterByName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RegName, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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


<p>Declaration at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 6214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### getVFPCmp() {#a82c95e144a0b2664e06f4ac192816b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::getVFPCmp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, bool Signaling=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a appropriate VFP CMP (fcmp{s|d}+fmstat) for the given operands.</p>

<p>Declaration at line 987 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4980 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### HandleByVal() {#a0905a31df6247cbe0234417c7bbd689d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::HandleByVal (<a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> * State, unsigned &amp; Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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

<p>HandleByVal - Target-specific cleanup for ByVal support.</p>


<p>HandleByVal - Every parameter <em>after</em> a byval parameter is passed on the stack.</p>


<p>Remember the next parameter register to allocate, and then confiscate the rest of the parameter registers to insure this.</p>


<p>Declaration at line 956 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 3056 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### initializeSplitCSR() {#a7f893c822505e63e2545ecec9e27e7e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::initializeSplitCSR (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Entry)</td>
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

<p>Perform necessary initialization to handle a subset of CSRs explicitly via copies.</p>


<p>This function is called at the beginning of instruction selection.</p>


<p>Declaration at line 921 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21966 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### insertCopiesSplitCSR() {#a34789179f0d8d7b94ed6fd3adbc1fe0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::insertCopiesSplitCSR (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Entry, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; Exits)</td>
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

<p>Insert explicit copies in entry and exit blocks.</p>


<p>We copy a subset of CSRs to virtual registers in the entry block, and copy them back to physical registers in the exit blocks. This function is called at the end of instruction selection.</p>


<p>Declaration at line 922 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 21972 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### IsEligibleForTailCallOptimization() {#a7985d6b61d7ad4454debc68df7b66c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::IsEligibleForTailCallOptimization (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">TargetLowering::CallLoweringInfo</a> &amp; CLI, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; CCInfo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &gt; &amp; ArgLocs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool isIndirect)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsEligibleForTailCallOptimization - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the call is eligible for tail call optimization.</p>


<p>Targets which want to do tail call optimization should implement this function.</p>


<p>Targets which want to do tail call optimization should implement this function. Note that this function also processes musttail calls, so when this function returns false on a valid musttail call, a fatal backend error occurs.</p>


<p>Declaration at line 961 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 3111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### isFMAFasterThanFMulAndFAdd() {#ac48f419669ab0b9a751f884606ccc49b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isFMAFasterThanFMulAndFAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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


<p><a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> supports both fused and unfused multiply-add operations; we already lower a pair of fmul and fadd to the latter so it's not clear that there would be a gain or that the gain would be worthwhile enough to risk correctness bugs.</p>


<p>For MVE, we set this to true as it helps simplify the need for some patterns (and we don't have the non-fused floating point instruction).</p>


<p>Declaration at line 899 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 19393 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### isUnsupportedFloatingType() {#a026fddfc3c2731eb86202c49d48acc80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isUnsupportedFloatingType (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 5481 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### isUsedByReturnOnly() {#a5afa9e78790088d5ff897bbfda692ea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::isUsedByReturnOnly (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;)</td>
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

<p>Return true if result of the specified node is used by a return node only.</p>


<p>It also compute and return the input chain for the tail call.</p>


<p>This is used to determine whether it is possible to codegen a libcall as tail call at legalization time.</p>


<p>Declaration at line 975 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 3465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### joinRegisterPartsIntoValue() {#aec6dd7827fb0a7fae56f6ce5d4903293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::joinRegisterPartsIntoValue (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> * Parts, unsigned NumParts, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> PartVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ValueVT, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> &gt; CC)</td>
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

<p>Target-specific combining of register parts into its original value.</p>

<p>Declaration at line 931 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4573 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBlockAddress() {#a95a555922730edd58d7eb3f7226ef0e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerBlockAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 837 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 3620 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBR\_CC() {#af0f5922666ccf2b3bd52dfa45d837beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerBR_CC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 857 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 5804 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBR\_JT() {#af7f4f97fd0181da2227396b991ab341b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerBR_JT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 5882 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBRCOND() {#a282be0e64fa41462de6c541d5a074218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerBRCOND (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 856 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 5768 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBUILD\_VECTOR() {#a6646aa47f093829d2c3844cfb0aa1950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerBUILD_VECTOR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> * ST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 869 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 7954 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCall() {#a3fc0dc16280b0a77b040182ecfa553b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerCall (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">TargetLowering::CallLoweringInfo</a> &amp; CLI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals)</td>
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

<p>LowerCall - Lowering a call into a callseq_start &lt;- <a href="/web-llvm/docs/api/namespaces/llvm/armisd">ARMISD</a>:CALL &lt;- callseq_end chain.</p>


<p>Also add input and output parameter nodes.</p>


<p>Declaration at line 952 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 2434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCallResult() {#ace830275fdea087ca4d6f6c52f1e04a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerCallResult (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> InGlue, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals, bool isThisReturn, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ThisVal, bool isCmseNSCall)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LowerCallResult - Lower the result values of a call into the appropriate copies out of appropriate physical registers.</p>

<p>Declaration at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 2218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerConstantFP() {#a871fce7b5d7fd23a8ee426ec861ccd93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerConstantFP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> * ST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 867 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 7177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerConstantPool() {#a2169680610500918ceee0c5bff13e4e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerConstantPool (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 3569 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerDIV\_Windows() {#a15d76106ae330424717631598c42d6c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerDIV_Windows (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool Signed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 874 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 10121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerDivRem() {#a4ece6203dfa266e06c31e9b124431cfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerDivRem (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 873 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20637 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerDYNAMIC\_STACKALLOC() {#a1eccdd320eb017b7dd6e158a0adb099e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerDYNAMIC_STACKALLOC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 882 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20763 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerEH\_SJLJ\_LONGJMP() {#a00b0b2367996b6f33a3db70bcada3704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerEH_SJLJ_LONGJMP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 831 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerEH\_SJLJ\_SETJMP() {#ae9fcc67120d1a5b40df14fd7e6fed26b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerEH_SJLJ_SETJMP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 830 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerEH\_SJLJ\_SETUP\_DISPATCH() {#a8fd6918e0a906252f1f6afee79ad3bd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerEH_SJLJ_SETUP_DISPATCH (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 832 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFCOPYSIGN() {#a51993a42ac0fdbadd7f46f2186157f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerFCOPYSIGN (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 858 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 6088 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFormalArguments() {#ac23d3c5f6357e58dca0887a532cfc4f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerFormalArguments (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;)</td>
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


<p>Declaration at line 937 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4589 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_EXTEND() {#a9897472b32b5230a0f78a5f586557b23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerFP_EXTEND (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 884 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20804 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_ROUND() {#ae9211b2847202828eb88a7bfcfaa9e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerFP_ROUND (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 883 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20863 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_TO\_BF16() {#a2a922daf0d66e6124172d2320e373537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerFP_TO_BF16 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 891 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 10607 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_TO\_INT() {#ac856116a50b5ab09bcf4fb3c8f8f4c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerFP_TO_INT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 885 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 5948 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFRAMEADDR() {#adb71a2ef295f0ce110f9fa14f089e7ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerFRAMEADDR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 6194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFSETCC() {#a65373dfde88329ccea1039599a3aeb48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerFSETCC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 887 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 10560 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFSINCOS() {#abd7a5c6358256c2295b8597626fc3162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerFSINCOS (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 872 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 9966 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGET\_ROUNDING() {#a137304ab3989feaa7bab755ef508a5dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerGET_ROUNDING (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 863 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 6454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalAddress() {#a3008862fa1480d1be83cefa97875ba19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerGlobalAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 839 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4018 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalAddressDarwin() {#a673acfc3cb67bef2f7fea3de62886183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerGlobalAddressDarwin (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 840 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4098 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalAddressELF() {#ae964fcb8807f7e6e61772930d5ed9a63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerGlobalAddressELF (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 841 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4031 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalAddressWindows() {#a742494e812b1e9e6b70c3e7577932591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerGlobalAddressWindows (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 842 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalTLSAddress() {#aa49286ce498209939f797f39d44ea419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerGlobalTLSAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 843 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 3869 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalTLSAddressDarwin() {#a2dbcbce1e033b60c540830bb38601e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerGlobalTLSAddressDarwin (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert a TLS address reference into the correct sequence of loads and calls to compute the variable's address for Darwin, and return an <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> containing the final node.</p>


<p>Darwin only has one TLS scheme which must be capable of dealing with the fully general situation, in the worst case. This means:</p>


<ul class="doxyList ">
<li>"extern __thread" declaration.</li>
<li>Defined in a possibly unknown dynamic library.</li>
</ul>

<p>The general system is that each __thread variable has a [3 x i32] descriptor which contains information used by the runtime to calculate the address. The only part of this the compiler needs to know about is the first word, which contains a function pointer that must be called with the address of the entire descriptor in "r0".</p>


<p>Since this descriptor may be in a different unit, in general access must proceed along the usual <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> rules. A common sequence to produce is:</p>



<pre><code>movw rT1, :lower16:_var$non_lazy_ptr
movt rT1, :upper16:_var$non_lazy_ptr
ldr r0, [rT1]
ldr rT2, [r0]
blx rT2
[...address now in r0...]
</code></pre>


<p>Declaration at line 849 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 3675 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalTLSAddressWindows() {#a05929c59f5173372ff77d6d979b3d9ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerGlobalTLSAddressWindows (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 850 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 3719 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINSERT\_VECTOR\_ELT() {#a8f3ba1e97e75af1cc395562e4f7125ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerINSERT_VECTOR_ELT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 871 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 9100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINT\_TO\_FP() {#a04d456aa10a892f7f33b606b1924e2e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerINT_TO_FP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 886 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 6068 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINTRINSIC\_VOID() {#a631cc867edf9c9f2890dd66fad911f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerINTRINSIC_VOID (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> * Subtarget)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 833 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINTRINSIC\_WO\_CHAIN() {#a25b6f3463f527dbb89303ce43a4b27d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerINTRINSIC_WO_CHAIN (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> * Subtarget)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerLOAD() {#af1cd1884905c2bad13d5c8582f981227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::LowerLOAD (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 889 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 10204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerREM() {#a5ddb264636e9ea0ba5b3672c8365e9fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerREM (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 20710 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerRESET\_FPMODE() {#a38378e40e27adee3793a10bf963b4814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerRESET_FPMODE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 866 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 6547 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerReturn() {#ab70b9f5bdfbcb2da38b472944170d0cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerReturn (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
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


<p>Declaration at line 970 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 3289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerRETURNADDR() {#a6a8784d435d69fd3150ed322915511d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerRETURNADDR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 859 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 6170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSELECT() {#a4b3ff188883cf05611e3f9c3d2d3624c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerSELECT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 854 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 5205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSELECT\_CC() {#a634d5b1edf055e17124816c545badcc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerSELECT_CC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 855 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 5491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSET\_FPMODE() {#a18d99a8e2d56bcd116335aaa618181c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerSET_FPMODE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 865 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 6519 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSET\_ROUNDING() {#a05d3c5b2c9075e29469aa7d8a3a65ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerSET_ROUNDING (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 864 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 6477 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerShiftLeftParts() {#a873cea6a2a5cb4d6c168c4f965ea8b7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerShiftLeftParts (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LowerShiftLeftParts - Lower SHL_PARTS, which returns two i32 values and take a 2 x i32 value to shift plus a shift amount.</p>

<p>Declaration at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 6418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerShiftRightParts() {#a53fd5ede562a640f2cb7041dfd18b530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerShiftRightParts (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LowerShiftRightParts - Lower SRA_PARTS, which returns two i32 values and take a 2 x i32 value to shift plus a shift amount.</p>

<p>Declaration at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 6375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSignedALUO() {#a9952b138aea0cf52f4d1f8e0abecccf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerSignedALUO (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 5069 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSPONENTRY() {#ab5874b3ace9c92e0a853f98a864103b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerSPONENTRY (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 888 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 10598 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerToTLSExecModels() {#ae5b7c52ad6336a9f677a96540aab5425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerToTLSExecModels (<a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * GA, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120">TLSModel::Model</a> model)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 846 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 3817 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerToTLSGeneralDynamicModel() {#a95d0fac6e16735968fbd8325ff68faef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerToTLSGeneralDynamicModel (<a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * GA, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 844 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 3776 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerUnsignedALUO() {#aa1690bcb25474c6979929abcdfecadaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerUnsignedALUO (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 853 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 5114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### LowerWindowsDIVLibCall() {#a5124d1e0784c65f24e1d1d0f2a969bee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::LowerWindowsDIVLibCall (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool Signed, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 879 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 10041 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### mayBeEmittedAsTailCall() {#acbb1a5566c3284376a54bf371a819867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::mayBeEmittedAsTailCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *)</td>
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


<p>Declaration at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 3537 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### MoveFromHPR() {#adb3e23e27ca252f0f9248eebdc01f1ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::MoveFromHPR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> ValVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 904 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 2201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### MoveToHPR() {#a17d9202c0f6ac2746ee40f0e019bc262}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::MoveToHPR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> ValVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 902 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 2187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### OptimizeVFPBrcond() {#a57080f36f8a167615995084afbdc55a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::OptimizeVFPBrcond (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OptimizeVFPBrcond - With -enable-unsafe-fp-math, it's legal to optimize some f32 and even f64 comparisons to integer ones.</p>

<p>Declaration at line 990 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 5720 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### PassF64ArgInRegs() {#a3f4582ee335d2ff673ff37f426705b5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::PassF64ArgInRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Arg, <a href="/web-llvm/docs/api/classes/llvm/smallvector">RegsToPassVector</a> &amp; RegsToPass, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; NextVA, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; StackPtr, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; MemOpChains, bool IsTailCall, int SPDiff)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 808 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 2395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### ReconstructShuffle() {#a884055cd4febec79f40b2c284f90ddd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue ARMTargetLowering::ReconstructShuffle (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 907 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 8224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### setAllExpand() {#a5eadc96f61d20a21fce5437a2f32ff84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::setAllExpand (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1006 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### SetupEntryBlockForSjLj() {#af585f97d03559f473ecfacc16189d998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::SetupEntryBlockForSjLj (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DispatchBB, int FI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SetupEntryBlockForSjLj - Insert code into the entry block that creates and registers the function context.</p>

<p>Declaration at line 992 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 10851 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### shouldConsiderGEPOffsetSplit() {#a5a7f3a0127fc2621b8a5c1cc413e663f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMTargetLowering::shouldConsiderGEPOffsetSplit ()</td>
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



<p>Definition at line 979 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>

</div>
</div>

### splitValueIntoRegisterParts() {#a0f433fadbf766696faf1f5df340cd92e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMTargetLowering::splitValueIntoRegisterParts (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> * Parts, unsigned NumParts, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> PartVT, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> &gt; CC)</td>
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

<p>Declaration at line 926 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4557 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### StoreByValRegs() {#a871d25d82ea38d53b0dec06d0068e746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ARMTargetLowering::StoreByValRegs (<a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; CCInfo, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OrigArg, unsigned InRegsParamRecordIdx, int ArgOffset, unsigned ArgSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 942 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4484 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

### supportSplitCSR() {#a56e5bebb5bc62cac9b74ce94786af2b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMTargetLowering::supportSplitCSR (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Return true if the target supports that a subset of CSRs for the given machine function is handled explicitly via copies.</p>

<p>Definition at line 916 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>

</div>
</div>

### VarArgStyleRegisters() {#a7c79a1b9dc21e04038393b70f4141dae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetLowering::VarArgStyleRegisters (<a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; CCInfo, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, unsigned ArgOffset, unsigned TotalArgRegsSaveSize, bool ForceMutable=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 947 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>, definition at line 4538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HasStandaloneRem {#a959d52fdd37e3368d62d803c8ccfef1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMTargetLowering::HasStandaloneRem = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>

</div>
</div>

### InsertFencesForAtomic {#ae46dcbe9fa686bfd30f96f741e568ce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMTargetLowering::InsertFencesForAtomic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>

</div>
</div>

### Itins {#a991cd453a4ab09cfdfa0a54f04a93d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrItineraryData* llvm::ARMTargetLowering::Itins</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>

</div>
</div>

### RegInfo {#a8060c65d0518e0adb371e6c77016cb29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::ARMTargetLowering::RegInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>

</div>
</div>

### Subtarget {#adad0a13862540448dc499b968825db2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMSubtarget* llvm::ARMTargetLowering::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subtarget - Keep a pointer to the <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> around so that we can make the right decision when generating code for different targets.</p>

<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp">ARMISelLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
