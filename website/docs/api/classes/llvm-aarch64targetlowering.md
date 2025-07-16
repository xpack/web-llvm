---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aarch64targetlowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AArch64TargetLowering` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AArch64TargetLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">Target/AArch64/AArch64ISelLowering.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf8f1219dc8b656e8e11c4b08edc8979">AArch64TargetLowering</a> (const TargetMachine &amp;TM, const AArch64Subtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2c86e7c50d41494cc2acb0f1f3ba23c">isReassocProfitable</a> (SelectionDAG &amp;DAG, SDValue N0, SDValue N1) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Control the following reassociation of operands: (op (op x, c1), y) -&gt; (op (op x, y), c1) where N0 is (op x, c1) and N1 is y. <a href="#ab2c86e7c50d41494cc2acb0f1f3ba23c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52a3cbd48589c37855abca181342ccb7">CCAssignFnForCall</a> (CallingConv::ID CC, bool IsVarArg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Selects the correct <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> for a given CallingConvention value. <a href="#a52a3cbd48589c37855abca181342ccb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ed0e25160d3a3323c87794e593b364a">CCAssignFnForReturn</a> (CallingConv::ID CC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Selects the correct <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> for a given CallingConvention value. <a href="#a4ed0e25160d3a3323c87794e593b364a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16eb7e7dd4fd476ad2fa83cfb84c068d">computeKnownBitsForTargetNode</a> (const SDValue Op, KnownBits &amp;Known, const APInt &amp;DemandedElts, const SelectionDAG &amp;DAG, unsigned Depth=0) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine which of the bits specified in Mask are known to be either zero or one and return them in the KnownZero/KnownOne bitsets. <a href="#a16eb7e7dd4fd476ad2fa83cfb84c068d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec59d76b8a13655705b0c55d99edf165">ComputeNumSignBitsForTargetNode</a> (SDValue Op, const APInt &amp;DemandedElts, const SelectionDAG &amp;DAG, unsigned Depth) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method can be implemented by targets that want to expose additional information about sign bits to the DAG <a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a>. <a href="#aec59d76b8a13655705b0c55d99edf165">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa11502fbc6bf582057507658bd9682a9">getPointerTy</a> (const DataLayout &amp;DL, uint32_t AS=0) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the pointer type for the given address space, defaults to the pointer type from the data layout. <a href="#aa11502fbc6bf582057507658bd9682a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca53f243b0008543a30a78356ac59010">targetShrinkDemandedConstant</a> (SDValue Op, const APInt &amp;DemandedBits, const APInt &amp;DemandedElts, TargetLoweringOpt &amp;TLO) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4df626bbb6ef71e104c49d823e9e37e">getScalarShiftAmountTy</a> (const DataLayout &amp;DL, EVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type to use for a scalar shift opcode, given the shifted amount type. <a href="#af4df626bbb6ef71e104c49d823e9e37e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a815d0ad0c6f04717c0dd61b12b44095b">allowsMisalignedMemoryAccesses</a> (EVT VT, unsigned AddrSpace=0, Align Alignment=Align(1), MachineMemOperand::Flags Flags=MachineMemOperand::MONone, unsigned *Fast=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target allows unaligned memory accesses of the specified type. <a href="#a815d0ad0c6f04717c0dd61b12b44095b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ecd479d22b89a38549d035861ce1d84">allowsMisalignedMemoryAccesses</a> (LLT Ty, unsigned AddrSpace, Align Alignment, MachineMemOperand::Flags Flags, unsigned *Fast=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> variant. <a href="#a8ecd479d22b89a38549d035861ce1d84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40581570b38300f3a21e2e8ec8c80839">LowerOperation</a> (SDValue Op, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide custom lowering hooks for some operations. <a href="#a40581570b38300f3a21e2e8ec8c80839">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fa8b499e0abef24aa5d61c4ee8172d0">getTargetNodeName</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns the name of a target specific DAG node. <a href="#a6fa8b499e0abef24aa5d61c4ee8172d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a960012b61a9977dc7c2d3af3943da953">PerformDAGCombine</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be invoked for all target nodes and for any target-independent nodes that the target has registered with invoke it for. <a href="#a960012b61a9977dc7c2d3af3943da953">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50cc068b91154ae6f285c1f435203121">createFastISel</a> (FunctionLoweringInfo &amp;funcInfo, const TargetLibraryInfo *libInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns a target specific <a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> object, or null if the target does not support "fast" ISel. <a href="#a50cc068b91154ae6f285c1f435203121">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8512586d0b4ed30ba87cc919f0cfec5">isOffsetFoldingLegal</a> (const GlobalAddressSDNode *GA) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if folding a constant offset with the given GlobalAddress is legal. <a href="#ab8512586d0b4ed30ba87cc919f0cfec5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b5597ce1a7049500d0b30bef14951ca">isFPImmLegal</a> (const APFloat &amp;Imm, EVT VT, bool ForCodeSize) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target can instruction select the specified FP immediate natively. <a href="#a0b5597ce1a7049500d0b30bef14951ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c7cb6b368ef7cba8da95f1f11ed4fc0">isShuffleMaskLegal</a> (ArrayRef&lt; int &gt; M, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given shuffle mask can be codegen'd directly, or if it should be stack expanded. <a href="#a1c7cb6b368ef7cba8da95f1f11ed4fc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5676e13b5fb0a05c7a58b70f335ae7c">isVectorClearMaskLegal</a> (ArrayRef&lt; int &gt; M, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to isShuffleMaskLegal. <a href="#ad5676e13b5fb0a05c7a58b70f335ae7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fce00050967f2d8237319f1912a0103">getSetCCResultType</a> (const DataLayout &amp;DL, LLVMContext &amp;Context, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">ISD::SETCC</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a>. <a href="#a4fce00050967f2d8237319f1912a0103">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94825933fbeecbda802a1c22c46a524d">ReconstructShuffle</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6a60676cdf39d45ae2ec66a7ea4aada">EmitF128CSEL</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87a3c3fc7fc8bc05db24005a6d38b5b2">EmitLoweredCatchRet</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af661669ba4d45cdb471e79bddb6975af">EmitDynamicProbedAlloc</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34c1693d3ce9979ba45e1e9425cc806e">EmitTileLoad</a> (unsigned Opc, unsigned BaseReg, MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa92b03a9781f6914ffdef83ecf323708">EmitFill</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20e848fbe4dcba24cc443837166728a8">EmitZAInstr</a> (unsigned Opc, unsigned BaseReg, MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa695d49f883b21889c91b61d86437995">EmitZTInstr</a> (MachineInstr &amp;MI, MachineBasicBlock *BB, unsigned Opcode, bool Op0IsDef) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94b0ff91bd18235291da52ddf1e7cc1a">EmitZero</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed887f0677d391bc6f9d7e77b761695">EmitInitTPIDR2Object</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a65a8c0739a72de196022849b4ee67">EmitAllocateZABuffer</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab812d774aa563ffc2c67030a9ba1be39">EmitAllocateSMESaveBuffer</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfee0aff6a62996ec1dbee56ef35ad88">EmitGetSMESaveSize</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add09df38070887ea74972930f1c9ce83">EmitInstrWithCustomInserter</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'usesCustomInserter' flag. <a href="#add09df38070887ea74972930f1c9ce83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a798a85d56b9dc609e615130607563819">getTgtMemIntrinsic</a> (IntrinsicInfo &amp;Info, const CallInst &amp;I, MachineFunction &amp;MF, unsigned Intrinsic) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getTgtMemIntrinsic - Represent NEON load and store intrinsics as MemIntrinsicNodes. <a href="#a798a85d56b9dc609e615130607563819">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa03cec0d3e2e816167f41ac37995f274">shouldReduceLoadWidth</a> (SDNode *Load, ISD::LoadExtType ExtTy, EVT NewVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to reduce a load to a smaller type. <a href="#aa03cec0d3e2e816167f41ac37995f274">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a6ec610f1626d7d5198a8d06e9eba18">shouldRemoveRedundantExtend</a> (SDValue Op) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true (the default) if it is profitable to remove a sext_inreg(x) where the sext is redundant, and use x directly. <a href="#a4a6ec610f1626d7d5198a8d06e9eba18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01cb590e9c05c3675fe75693d84b3120">isTruncateFree</a> (Type *Ty1, Type *Ty2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's free to truncate a value of type FromTy to type ToTy. <a href="#a01cb590e9c05c3675fe75693d84b3120">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ee90d2d8bdc505c6422560cd54d4a54">isTruncateFree</a> (EVT VT1, EVT VT2) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d2e61bef8fbdb714e9f0a739bf49a58">isProfitableToHoist</a> (Instruction *I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if it is profitable to hoist instruction in then/else to if. <a href="#a9d2e61bef8fbdb714e9f0a739bf49a58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9140f89a634da6fe469d0faa0843a976">isZExtFree</a> (Type *Ty1, Type *Ty2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if any actual instruction that defines a value of type FromTy implicitly zero-extends the value to ToTy in the result register. <a href="#a9140f89a634da6fe469d0faa0843a976">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02e65e6f505c44832bf833b385e51ba6">isZExtFree</a> (EVT VT1, EVT VT2) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b70a67bb5d182866c5485835286509">isZExtFree</a> (SDValue Val, EVT VT2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if zero-extending the specific node Val to type VT2 is free (either because it's implicitly zero-extended such as <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> ldrb / ldrh or because it's folded such as <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> zero-extending loads). <a href="#ac7b70a67bb5d182866c5485835286509">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50016fb8102156a9c168cfd348b3509a">optimizeExtendOrTruncateConversion</a> (Instruction *I, Loop *L, const TargetTransformInfo &amp;TTI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to optimize extending or truncating conversion instructions (like zext, trunc, fptoui, uitofp) for the target. <a href="#a50016fb8102156a9c168cfd348b3509a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb51326eb72adb30e442667892c1f5ae">hasPairedLoad</a> (EVT LoadedType, Align &amp;RequiredAligment) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supplies and combines to a paired load two loaded values of type LoadedType next to each other in memory. <a href="#acb51326eb72adb30e442667892c1f5ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84bb66973746f769109266358c463c68">getMaxSupportedInterleaveFactor</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the maximum supported factor for interleaved memory accesses. <a href="#a84bb66973746f769109266358c463c68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cbcd096f254563525e65e58557ed901">lowerInterleavedLoad</a> (LoadInst *LI, ArrayRef&lt; ShuffleVectorInst * &gt; Shuffles, ArrayRef&lt; unsigned &gt; Indices, unsigned Factor) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower an interleaved load into a ldN intrinsic. <a href="#a6cbcd096f254563525e65e58557ed901">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4094e6b2a8203e5c8b67ecf186d51a9">lowerInterleavedStore</a> (StoreInst *SI, ShuffleVectorInst *SVI, unsigned Factor) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower an interleaved store into a stN intrinsic. <a href="#aa4094e6b2a8203e5c8b67ecf186d51a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac66d3f15510c7402f2a85a87c69f1603">lowerDeinterleaveIntrinsicToLoad</a> (LoadInst *LI, ArrayRef&lt; Value * &gt; DeinterleaveValues) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower a deinterleave intrinsic to a target specific load intrinsic. <a href="#ac66d3f15510c7402f2a85a87c69f1603">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2d9e284d06499be56d61b876e86dc8a">lowerInterleaveIntrinsicToStore</a> (StoreInst *SI, ArrayRef&lt; Value * &gt; InterleaveValues) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower an interleave intrinsic to a target specific store intrinsic. <a href="#ac2d9e284d06499be56d61b876e86dc8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad37b1f031f487d6e69553ec06518c219">isLegalAddImmediate</a> (int64_t) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified immediate is legal add immediate, that is the target has add instructions which can add a register with the immediate without having to materialize the immediate into a register. <a href="#ad37b1f031f487d6e69553ec06518c219">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7adb0b5b92d80f462efda5c7f99b9077">isLegalAddScalableImmediate</a> (int64_t) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if adding the specified scalable immediate is legal, that is the target has add instructions which can add a register with the immediate (multiplied by vscale) without having to materialize the immediate into a register. <a href="#a7adb0b5b92d80f462efda5c7f99b9077">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c0904d6c43a3efd717031d09178dcc3">isLegalICmpImmediate</a> (int64_t) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified immediate is legal icmp immediate, that is the target has icmp instructions which can compare a register against the immediate without having to materialize the immediate into a register. <a href="#a5c0904d6c43a3efd717031d09178dcc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8e97755935ce2a3c03a0ba055b310c2">isMulAddWithConstProfitable</a> (SDValue AddNode, SDValue ConstNode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it may be profitable to transform (mul (add x, c1), c2) -&gt; (add (mul x, c2), c1*c2). <a href="#af8e97755935ce2a3c03a0ba055b310c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b9542cd71de589d049139d68ab6589">shouldConsiderGEPOffsetSplit</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5de718ef1b1e3a0da7a3f35a139d5197">getOptimalMemOpType</a> (const MemOp &amp;Op, const AttributeList &amp;FuncAttributes) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the target specific optimal type for load and store operations as a result of memset, memcpy, and memmove lowering. <a href="#a5de718ef1b1e3a0da7a3f35a139d5197">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab72c286743e675ffbe81f7c9e9771fa5">getOptimalMemOpLLT</a> (const MemOp &amp;Op, const AttributeList &amp;FuncAttributes) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> returning variant. <a href="#ab72c286743e675ffbe81f7c9e9771fa5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae854a8e8c09efe0960eaae718304b77d">isLegalAddressingMode</a> (const DataLayout &amp;DL, const AddrMode &amp;AM, Type *Ty, unsigned AS, Instruction *I=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the addressing mode represented by AM is legal for this target, for a load/store of the specified type. <a href="#ae854a8e8c09efe0960eaae718304b77d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2789f36b6ade6b507b2fb7cf6e4f49e9">getPreferredLargeGEPBaseOffset</a> (int64_t MinOffset, int64_t MaxOffset) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the prefered common base offset. <a href="#a2789f36b6ade6b507b2fb7cf6e4f49e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5bf9253e7424a041215974fc5696ac8">isFMAFasterThanFMulAndFAdd</a> (const MachineFunction &amp;MF, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if an FMA operation is faster than a pair of fmul and fadd instructions. <a href="#aa5bf9253e7424a041215974fc5696ac8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e54ea4387c8bf1f3d8c5ebfb563c222">isFMAFasterThanFMulAndFAdd</a> (const Function &amp;F, Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IR version. <a href="#a7e54ea4387c8bf1f3d8c5ebfb563c222">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaa0f01ce8216a0cc8704e2a086805c2">generateFMAsInMachineCombiner</a> (EVT VT, CodeGenOptLevel OptLevel) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a4450c23fda81ec84bce1eed78f67d4">isTypeDesirableForOp</a> (unsigned Opc, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target has native support for the specified value type and it is 'desirable' to use the type for the given node type. <a href="#a7a4450c23fda81ec84bce1eed78f67d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad687d3401b5b0769d08e78fcdb51acb2">getScratchRegisters</a> (CallingConv::ID CC) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a 0 terminated array of registers that can be safely used as scratch registers. <a href="#ad687d3401b5b0769d08e78fcdb51acb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae33d5b14ea69e8e72a00f6531649c92a">getRoundingControlRegisters</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a 0 terminated array of rounding control registers that can be attached into strict FP call. <a href="#ae33d5b14ea69e8e72a00f6531649c92a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecbd41e7754d9ca4d664dfa0d9df8510">isDesirableToCommuteWithShift</a> (const SDNode *N, CombineLevel Level) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns false if N is a bit extraction pattern of (X &gt;&gt; C) &amp; Mask. <a href="#aecbd41e7754d9ca4d664dfa0d9df8510">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7385539857df582900994505040ae3f">isDesirableToPullExtFromShl</a> (const MachineInstr &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GlobalISel - return true if it's profitable to perform the combine: shl ([sza]ext x), y =&gt; zext (shl x, y) <a href="#ab7385539857df582900994505040ae3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec5f3889dfe7e8587557d1addb3a367c">isDesirableToCommuteXorWithShift</a> (const SDNode *N) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns false if N is a bit extraction pattern of (X &gt;&gt; C) &amp; Mask. <a href="#aec5f3889dfe7e8587557d1addb3a367c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acefcea723a8cd3136dae2d39a8dd7ca9">shouldFoldConstantShiftPairToMask</a> (const SDNode *N, CombineLevel Level) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to fold a pair of shifts into a mask. <a href="#acefcea723a8cd3136dae2d39a8dd7ca9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06dd823fa615051cc96e1d7b9de7a2bb">shouldFoldSelectWithIdentityConstant</a> (unsigned BinOpcode, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if pulling a binary operation into a select with an identity constant is profitable. <a href="#a06dd823fa615051cc96e1d7b9de7a2bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b40229ffa0ce512148acc985d56136c">shouldConvertConstantLoadToIntImm</a> (const APInt &amp;Imm, Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it is beneficial to convert a load of a constant to just the constant itself. <a href="#a3b40229ffa0ce512148acc985d56136c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1f54fa7a42bfe0913b9fe2e869a958c">isExtractSubvectorCheap</a> (EVT ResVT, EVT SrcVT, unsigned Index) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if EXTRACT_SUBVECTOR is cheap for this result type with this index. <a href="#ae1f54fa7a42bfe0913b9fe2e869a958c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b9dee3428eaf04d856ffd6dab85b024">shouldFormOverflowOp</a> (unsigned Opcode, EVT VT, bool MathUsed) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to convert math with an overflow comparison into the corresponding DAG node operation. <a href="#a7b9dee3428eaf04d856ffd6dab85b024">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8631130c37aa54ae6c9127abc5fe392a">emitLoadLinked</a> (IRBuilderBase &amp;Builder, Type *ValueTy, Value *Addr, AtomicOrdering Ord) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a load-linked operation on Addr, returning a "Value *" with the corresponding pointee type. <a href="#a8631130c37aa54ae6c9127abc5fe392a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6245f16ff5b8230d2ed89127bf27efa8">emitStoreConditional</a> (IRBuilderBase &amp;Builder, Value *Val, Value *Addr, AtomicOrdering Ord) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a store-conditional operation to Addr. <a href="#a6245f16ff5b8230d2ed89127bf27efa8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8f3e687e3d51ff7367011e81564c20e">emitAtomicCmpXchgNoStoreLLBalance</a> (IRBuilderBase &amp;Builder) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace4241dfdb194e5c81c875b5be782213">isOpSuitableForLDPSTP</a> (const Instruction *I) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0a106d77d380a71597433b5ac286ca">isOpSuitableForLSE128</a> (const Instruction *I) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f1799dbf712799df049d22347e1362e">isOpSuitableForRCPC3</a> (const Instruction *I) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1d674bbe9aa52ee2ee2d2a3b6442e33">shouldInsertFencesForAtomic</a> (const Instruction *I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether <a href="/web-llvm/docs/api/classes/llvm/atomicexpandpass">AtomicExpandPass</a> should automatically insert fences and reduce ordering for this atomic. <a href="#ab1d674bbe9aa52ee2ee2d2a3b6442e33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29af3321cb077df4a9d6f4a981366fdc">shouldInsertTrailingFenceForAtomicStore</a> (const Instruction *I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether <a href="/web-llvm/docs/api/classes/llvm/atomicexpandpass">AtomicExpandPass</a> should automatically insert a trailing fence without reducing the ordering for this atomic. <a href="#a29af3321cb077df4a9d6f4a981366fdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLoweringBase::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62ca2fe454c98ca30dd17d0b37ba3534">shouldExpandAtomicLoadInIR</a> (LoadInst *LI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the given (atomic) load should be expanded by the IR-level AtomicExpand pass. <a href="#a62ca2fe454c98ca30dd17d0b37ba3534">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLoweringBase::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5564f8fe97e73dd2f2cb8a76bbd3474">shouldExpandAtomicStoreInIR</a> (StoreInst *SI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the given (atomic) store should be expanded by the IR-level AtomicExpand pass into. <a href="#ab5564f8fe97e73dd2f2cb8a76bbd3474">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLoweringBase::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c188b2e9f8e7ab4da2a49c83acd299c">shouldExpandAtomicRMWInIR</a> (AtomicRMWInst *AI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the IR-level AtomicExpand pass should expand the given AtomicRMW, if at all. <a href="#a7c188b2e9f8e7ab4da2a49c83acd299c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLoweringBase::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70a83c8d008bb40c08c02d3238a992a3">shouldExpandAtomicCmpXchgInIR</a> (AtomicCmpXchgInst *AI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the given atomic cmpxchg should be expanded by the IR-level AtomicExpand pass. <a href="#a70a83c8d008bb40c08c02d3238a992a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc38e57cd913199ae05e57970421f100">useLoadStackGuardNode</a> (const Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this function returns true, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> emits a LOAD_STACK_GUARD node when it is lowering Intrinsic::stackprotector. <a href="#adc38e57cd913199ae05e57970421f100">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681">TargetLoweringBase::LegalizeTypeAction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1885796ae6d5528e9544ad558881e46b">getPreferredVectorAction</a> (MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the preferred vector type legalization action. <a href="#a1885796ae6d5528e9544ad558881e46b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac887f4f420c78b4d95f669030c4c4464">getIRStackGuard</a> (IRBuilderBase &amp;IRB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the target has a standard location for the stack protector cookie, returns the address of that location. <a href="#ac887f4f420c78b4d95f669030c4c4464">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a859081e342a8a97b3648873ae3df252d">insertSSPDeclarations</a> (Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts necessary declarations for SSP (stack protection) purpose. <a href="#a859081e342a8a97b3648873ae3df252d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af493092261037debb1fad82108301fdf">getSDagStackGuard</a> (const Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the variable that's previously inserted by insertSSPDeclarations, if any, otherwise return nullptr. <a href="#af493092261037debb1fad82108301fdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aeb9c73ff9505a01d6bef9d1f6f6c6e">getSSPStackGuardCheck</a> (const Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the target has a standard stack protection check function that performs validation and error handling, returns the function. <a href="#a7aeb9c73ff9505a01d6bef9d1f6f6c6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98a5a7a00d7d117c9560524236a559d0">getSafeStackPointerLocation</a> (IRBuilderBase &amp;IRB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the target has a standard location for the unsafe stack pointer, returns the address of that location. <a href="#a98a5a7a00d7d117c9560524236a559d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01a1d1b02c449d7e82f517e549cd68a6">getExceptionPointerRegister</a> (const Constant *PersonalityFn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register, this returns the register that receives the exception address on entry to an EH pad. <a href="#a01a1d1b02c449d7e82f517e549cd68a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb10389377e757d4042fe9c16fa449ca">getExceptionSelectorRegister</a> (const Constant *PersonalityFn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register, this returns the register that receives the exception typeid on entry to a landing pad. <a href="#adb10389377e757d4042fe9c16fa449ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a494cbaa147365ad6fd75c3bb3297c8bd">isIntDivCheap</a> (EVT VT, AttributeList Attr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if integer divide is usually cheaper than a sequence of several shifts, adds, and multiplies for this target. <a href="#a494cbaa147365ad6fd75c3bb3297c8bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40bdcac44bd6d189cc6b65984baf3303">canMergeStoresTo</a> (unsigned AddressSpace, EVT MemVT, const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns if it's reasonable to merge stores to MemVT size. <a href="#a40bdcac44bd6d189cc6b65984baf3303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa15ed7ca8d8275ec7a500744af929f25">isCheapToSpeculateCttz</a> (Type *) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is cheap to speculate a call to intrinsic cttz. <a href="#aa15ed7ca8d8275ec7a500744af929f25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9e23630139a36d636d43c0084ed4c85">isCheapToSpeculateCtlz</a> (Type *) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is cheap to speculate a call to intrinsic ctlz. <a href="#aa9e23630139a36d636d43c0084ed4c85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a2764d23b64e6bb68a0025d4eab6b29">isMaskAndCmp0FoldingBeneficial</a> (const Instruction &amp;AndI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if the target supports combining a chain like: <a href="#a9a2764d23b64e6bb68a0025d4eab6b29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17675bf9596afe087d90140ef0e52485">hasAndNotCompare</a> (SDValue V) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target should transform: (X &amp; Y) == Y ---&gt; (~X &amp; Y) == 0 (X &amp; Y) != Y ---&gt; (~X &amp; Y) != 0. <a href="#a17675bf9596afe087d90140ef0e52485">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa69a30633eb175372a93a42bfc5d89f2">hasAndNot</a> (SDValue Y) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target has a bitwise and-not operation: X = ~A &amp; B This can be used to simplify select or other instructions. <a href="#aa69a30633eb175372a93a42bfc5d89f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7ba1399d23ed2bdf2123d00db72cee2">shouldProduceAndByConstByHoistingConstFromShiftsLHSOfAnd</a> (SDValue X, ConstantSDNode *XC, ConstantSDNode *CC, SDValue Y, unsigned OldShiftOpcode, unsigned NewShiftOpcode, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given the pattern (X &amp; (C l&gt;&gt;/&lt;&lt; Y)) ==/!= 0 return true if it should be transformed into: ((X &lt;&lt;/l&gt;&gt; Y) &amp; C) ==/!= 0 WARNING: if 'X' is a constant, the fold may deadlock! <a href="#ab7ba1399d23ed2bdf2123d00db72cee2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1cfe6f1187d7ab1a0ada9cc119c1b2b4">ShiftLegalizationStrategy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6667df004a39c249e82595e8c06841ca">preferredShiftLegalizationStrategy</a> (SelectionDAG &amp;DAG, SDNode *N, unsigned ExpansionFactor) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3e6a84b6c78f3b26132a2f124749347">shouldTransformSignedTruncationCheck</a> (EVT XVT, unsigned KeptBits) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should we tranform the IR-optimal check for whether given truncation down into KeptBits would be truncating or not: (add x, (1 &lt;&lt; (KeptBits-1))) srccond (1 &lt;&lt; KeptBits) Into it's more traditional form: ((x &lt;&lt; C) a&gt;&gt; C) dstcond x Return true if we should transform. <a href="#ad3e6a84b6c78f3b26132a2f124749347">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6249d1435318ffc44640d1b46f4ac294">preferIncOfAddToSubOfNot</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These two forms are equivalent: sub y, (xor x, -1) add (add x, 1), y The variant with two add's is IR-canonical. <a href="#a6249d1435318ffc44640d1b46f4ac294">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a406599321c7231224a41d58cbe973b15">shouldConvertFpToSat</a> (unsigned Op, EVT FPVT, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should we generate fp_to_si_sat and fp_to_ui_sat from type FPVT to type VT from min(max(fptoi)) saturation patterns. <a href="#a406599321c7231224a41d58cbe973b15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ce9ba59f8e02ebc4646f41ee4d57f8a">shouldExpandCmpUsingSelects</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should we expand [US]CMP nodes using two selects and two compares, or by doing arithmetic on boolean types. <a href="#a3ce9ba59f8e02ebc4646f41ee4d57f8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f7195ae01dbf398aa952b18f7ac28b2">isComplexDeinterleavingSupported</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this target support complex deinterleaving. <a href="#a8f7195ae01dbf398aa952b18f7ac28b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaa6c3509bbddcd993aeec7334361c9d">isComplexDeinterleavingOperationSupported</a> (ComplexDeinterleavingOperation Operation, Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this target support complex deinterleaving with the given operation and type. <a href="#acaa6c3509bbddcd993aeec7334361c9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ea782436f7a688ebb717a91808b9c5d">createComplexDeinterleavingIR</a> (IRBuilderBase &amp;B, ComplexDeinterleavingOperation OperationType, ComplexDeinterleavingRotation Rotation, Value *InputA, Value *InputB, Value *Accumulator=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the IR node for the given complex deinterleaving operation. <a href="#a7ea782436f7a688ebb717a91808b9c5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a049804b3fe8b5e8ddea9a1d2c15882b9">supportSplitCSR</a> (MachineFunction *MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports that a subset of CSRs for the given machine function is handled explicitly via copies. <a href="#a049804b3fe8b5e8ddea9a1d2c15882b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15bcdc727d8a841f1bc89a276b7eab72">initializeSplitCSR</a> (MachineBasicBlock *Entry) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform necessary initialization to handle a subset of CSRs explicitly via copies. <a href="#a15bcdc727d8a841f1bc89a276b7eab72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23393317cdaeed97903d191dcc6c84f8">insertCopiesSplitCSR</a> (MachineBasicBlock *Entry, const SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;Exits) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert explicit copies in entry and exit blocks. <a href="#a23393317cdaeed97903d191dcc6c84f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeed6ff19584b28f6a534e1aa8ed60037">supportSwiftError</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports swifterror attribute. <a href="#aeed6ff19584b28f6a534e1aa8ed60037">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f303cd09f748c952cf97d194397bb7f">supportPtrAuthBundles</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports ptrauth operand bundles. <a href="#a4f303cd09f748c952cf97d194397bb7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af881f3ff352fcf2103ed1f1e8df2eea7">supportKCFIBundles</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports kcfi operand bundles. <a href="#af881f3ff352fcf2103ed1f1e8df2eea7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6e03361f09a5b06dc299f6ee1c76ca4">EmitKCFICheck</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::instr_iterator &amp;MBBI, const TargetInstrInfo *TII) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af35d763b74cc1ae6f4da3a698b6e3027">enableAggressiveFMAFusion</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable aggressive FMA fusion on targets that want it. <a href="#af35d763b74cc1ae6f4da3a698b6e3027">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a205e757ebb66d5477f9ec152d6adcf8b">getVaListSizeInBits</a> (const DataLayout &amp;DL) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size of the platform's va_list object. <a href="#a205e757ebb66d5477f9ec152d6adcf8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85764bb37db07737ed0058c352f4c3b7">isLegalInterleavedAccessType</a> (VectorType *VecTy, const DataLayout &amp;DL, bool &amp;UseScalable) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">VecTy</span> is a legal interleaved access type. <a href="#a85764bb37db07737ed0058c352f4c3b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a365f29ab21721393fe82ff3ae4554e5e">getNumInterleavedAccesses</a> (VectorType *VecTy, const DataLayout &amp;DL, bool UseScalable) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of interleaved accesses that will be generated when lowering accesses of the given type. <a href="#a365f29ab21721393fe82ff3ae4554e5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dd">MachineMemOperand::Flags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55ec39e405ec6b7dca5cdd266ced41ed">getTargetMMOFlags</a> (const Instruction &amp;I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is used to inspect load/store instructions and add target-specific <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> flags to them. <a href="#a55ec39e405ec6b7dca5cdd266ced41ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85b96f315b961f037b6aedfca25133c5">functionArgumentNeedsConsecutiveRegisters</a> (Type *Ty, CallingConv::ID CallConv, bool isVarArg, const DataLayout &amp;DL) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For some targets, an LLVM struct type must be broken down into multiple simple types, but the calling convention specifies that the entire struct must be passed in a block of consecutive registers. <a href="#a85b96f315b961f037b6aedfca25133c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab85e6fcf7b8d3785c437808d101bd14f">needsFixedCatchObjects</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used for exception handling on Win64. <a href="#ab85e6fcf7b8d3785c437808d101bd14f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a790e9b70f12899a4cb2aefd33826ee7d">fallBackToDAGISel</a> (const Instruction &amp;Inst) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff2977da8eaad9875d1b5c9d3401e452">mergeStoresAfterLegalization</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SVE code generation for fixed length vectors does not custom lower BUILD_VECTOR. <a href="#aff2977da8eaad9875d1b5c9d3401e452">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4502ed00aa357af2b923730584885d7">getRedZoneSize</a> (const Function &amp;F) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7774721462886f7e79d72a94a121721">isAllActivePredicate</a> (SelectionDAG &amp;DAG, SDValue N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bdd144ce64dea5afb172d742184c997">getPromotedVTForPredicate</a> (EVT VT) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9409a43cdbf7e602589114de4e2daf4d">getAsmOperandValueType</a> (const DataLayout &amp;DL, Type *Ty, bool AllowUnknown=false) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af86f6febc25487d02d7904252e2a107d">shouldExpandGetActiveLaneMask</a> (EVT VT, EVT OpVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the @llvm.get.active.lane.mask intrinsic should be expanded using generic code in <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a>. <a href="#af86f6febc25487d02d7904252e2a107d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c9502505ab5e9910350e241f20d976a">shouldExpandPartialReductionIntrinsic</a> (const IntrinsicInst *I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the @llvm.experimental.vector.partial.reduce. <a href="#a0c9502505ab5e9910350e241f20d976a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b885204397a6fe1874c2c784015eb83">shouldExpandCttzElements</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the @llvm.experimental.cttz.elts intrinsic should be expanded using generic code in <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a>. <a href="#a2b885204397a6fe1874c2c784015eb83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab04eee3cccc4fdfad42939e3b6a1378e">shouldExpandVectorMatch</a> (EVT VT, unsigned SearchSize) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the @llvm.experimental.vector.match intrinsic should be expanded for vector type ‘VT` and search size ‘SearchSize` using generic code in <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a>. <a href="#ab04eee3cccc4fdfad42939e3b6a1378e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af745858766f8ab9fd5ef15335bd011f2">changeStreamingMode</a> (SelectionDAG &amp;DAG, SDLoc DL, bool Enable, SDValue Chain, SDValue InGlue, unsigned Condition, SDValue PStateSM=SDValue()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a change in streaming mode is required on entry to/return from a function call it emits and returns the corresponding SMSTART or SMSTOP node. <a href="#af745858766f8ab9fd5ef15335bd011f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e9dd7ae294939f7a90d9dc64148ddc1">isVScaleKnownToBeAPowerOfTwo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true only if vscale must be a power of two. <a href="#a6e9dd7ae294939f7a90d9dc64148ddc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa8bfec034d066ec24d18d3fd76ac590">useSVEForFixedLengthVectorVT</a> (EVT VT, bool OverrideNEON=false) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f1ad23af20c2a0b3e3f5c0a995c1969">getRegisterTypeForCallingConv</a> (LLVMContext &amp;Context, CallingConv::ID CC, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Certain combinations of ABIs, Targets and features require that types are legal for some operations and not for other operations. <a href="#a0f1ad23af20c2a0b3e3f5c0a995c1969">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4445d350e1253b4c05ab25011d766d">getNumRegistersForCallingConv</a> (LLVMContext &amp;Context, CallingConv::ID CC, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Certain targets require unusual breakdowns of certain types. <a href="#a3f4445d350e1253b4c05ab25011d766d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac477f229337de92be9c48dae99bf5546">getVectorTypeBreakdownForCallingConv</a> (LLVMContext &amp;Context, CallingConv::ID CC, EVT VT, EVT &amp;IntermediateVT, unsigned &amp;NumIntermediates, MVT &amp;RegisterVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Certain targets such as MIPS require that some types such as vectors are always broken down into scalars in some contexts. <a href="#ac477f229337de92be9c48dae99bf5546">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58613f0e5460e846c1753949ec0d8aff">hasInlineStackProbe</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if stack clash protection is enabled for this functions. <a href="#a58613f0e5460e846c1753949ec0d8aff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab30bbf3bcf699a32f7113173b5cee991">verifyTargetSDNode</a> (const SDNode *N) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> the given <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>. Aborts if it is invalid. <a href="#ab30bbf3bcf699a32f7113173b5cee991">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0523712fa8c0ccc2c1a13110303fe07">isExtFreeImpl</a> (const Instruction *Ext) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the extension represented by <span class="doxyComputerOutput">I</span> is free. <a href="#ad0523712fa8c0ccc2c1a13110303fe07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e4e3535343601fee67d7c303e81478">addTypeForNEON</a> (MVT VT)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85c14b1dd6d933addae9fbbfb9e70c5b">addTypeForFixedLengthSVE</a> (MVT VT)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a026c8ea412494113475433b9e65aba50">addDRType</a> (MVT VT)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad510fa340d170f5bd6da1d024bc6f4fe">addQRType</a> (MVT VT)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b0c22ee470e91ea51efea814d08583b">shouldExpandBuildVectorWithShuffles</a> (EVT, unsigned) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91193d9e304f1486bfedfd84ec1fdbe9">LowerFormalArguments</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;DL, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower the incoming (formal) arguments, described by the Ins array, into the specified DAG. <a href="#a91193d9e304f1486bfedfd84ec1fdbe9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7109c8327caf2c5922f32aba0681156f">AdjustInstrPostInstrSelection</a> (MachineInstr &amp;MI, SDNode *Node) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'hasPostISelHook' flag. <a href="#a7109c8327caf2c5922f32aba0681156f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a930ea974499fcf244a3d5f696297de8b">LowerCall</a> (CallLoweringInfo &amp;, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerCall - Lower a call to a callseq_start + CALL + callseq_end chain, and add input and output parameter nodes. <a href="#a930ea974499fcf244a3d5f696297de8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afce14aea3bb1c7424d49561471be6637">LowerCallResult</a> (SDValue Chain, SDValue InGlue, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; CCValAssign &gt; &amp;RVLocs, const SDLoc &amp;DL, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals, bool isThisReturn, SDValue ThisVal, bool RequiresSMChange) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerCallResult - Lower the result values of a call into the appropriate copies out of appropriate physical registers. <a href="#afce14aea3bb1c7424d49561471be6637">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae74c22d7977560d651482ac8de85521">LowerLOAD</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c9b6194deb9ce89c72508ab7e137d3f">LowerSTORE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc8630b70dbb5b7acba30f36814ef61">LowerStore128</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower atomic or volatile 128-bit stores to a single STP instruction. <a href="#a7bc8630b70dbb5b7acba30f36814ef61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4024437327f3e76b575c1154cbfa5c1">LowerABS</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa91f332cb0f1985edd7125c2b3bcf5a8">LowerMGATHER</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ec1240ecf04168f0a1da569d7f9a729">LowerMSCATTER</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a958c3a9a1a65caf6b9f9e5110c989dc1">LowerMLOAD</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a005e5eb0e954e153b8463195b636aa42">LowerVECTOR_COMPRESS</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac16d4410fc3149f5f34e9e0821610c4d">LowerINTRINSIC_W_CHAIN</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adabca41e48b08718f47108e7464b772f">LowerINTRINSIC_WO_CHAIN</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e51235f2814ef7f947d835fe852d567">LowerINTRINSIC_VOID</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfd7276491ae7ad730c3e14362d247b9">isEligibleForTailCallOptimization</a> (const CallLoweringInfo &amp;CLI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ababf41cb888755410b7d5c6539c41d0e">addTokenForArgument</a> (SDValue Chain, SelectionDAG &amp;DAG, MachineFrameInfo &amp;MFI, int ClobberedFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds the incoming stack arguments which overlap the given fixed stack object and incorporates their load into the current chain. <a href="#ababf41cb888755410b7d5c6539c41d0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08a3256c4a1cc109afc072ac00e9b590">DoesCalleeRestoreStack</a> (CallingConv::ID CallCC, bool TailCallOpt) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf295e86e6b556affb7ebbc204087e7e">saveVarArgRegisters</a> (CCState &amp;CCInfo, SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue &amp;Chain) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ee1c2e421af7bccd71bfdf9809df927">CanLowerReturn</a> (CallingConv::ID CallConv, MachineFunction &amp;MF, bool isVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, LLVMContext &amp;Context, const Type *RetTy) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook should be implemented to check whether the return values described by the Outs array can fit into the return registers. <a href="#a5ee1c2e421af7bccd71bfdf9809df927">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b2c89d5e08d65a6bc259d07f3d46a9a">LowerReturn</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; SDValue &gt; &amp;OutVals, const SDLoc &amp;DL, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower outgoing return values, described by the Outs array, into the specified DAG. <a href="#a6b2c89d5e08d65a6bc259d07f3d46a9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe8de1d17ad89e06a8324e5a95e9bc88">getTargetNode</a> (GlobalAddressSDNode *N, EVT Ty, SelectionDAG &amp;DAG, unsigned Flag) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ebf5412f732d157b98e17c53e98d56e">getTargetNode</a> (JumpTableSDNode *N, EVT Ty, SelectionDAG &amp;DAG, unsigned Flag) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98ac0dd0c8badc55b17cd416dff219a5">getTargetNode</a> (ConstantPoolSDNode *N, EVT Ty, SelectionDAG &amp;DAG, unsigned Flag) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a136723ae26be2eacd93d87174893ab07">getTargetNode</a> (BlockAddressSDNode *N, EVT Ty, SelectionDAG &amp;DAG, unsigned Flag) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b6df02da4d0da31a9597f2706faa8c">getTargetNode</a> (ExternalSymbolSDNode *N, EVT Ty, SelectionDAG &amp;DAG, unsigned Flag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a32a57dad3d930193e959438aa2082021">getGOT</a> (NodeTy *N, SelectionDAG &amp;DAG, unsigned Flags=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a019eb50c151f7f279a1da60360116b47">getAddrLarge</a> (NodeTy *N, SelectionDAG &amp;DAG, unsigned Flags=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab89b4ad91eeedf0fca3f22a969d43418">getAddr</a> (NodeTy *N, SelectionDAG &amp;DAG, unsigned Flags=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a770378b0bf0d331f67c099ccc6bf6c0a">getAddrTiny</a> (NodeTy *N, SelectionDAG &amp;DAG, unsigned Flags=0) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac334b69492fdf29d91ceff0577c9098">LowerADDROFRETURNADDR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09748e380d9c85c0bb1a1470a45f212c">LowerGlobalAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81d984b4ee481099df27bca63a3c1f0d">LowerGlobalTLSAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83b26d99127d678349cf67b58cf97230">LowerDarwinGlobalTLSAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a TLS address reference into the correct sequence of loads and calls to compute the variable's address (for Darwin, currently) and return an <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> containing the final node. <a href="#a83b26d99127d678349cf67b58cf97230">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a797a2e3922a5e091e6e5cfb01d0a7588">LowerELFGlobalTLSAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613aae161a403151b644b1297f3676b9">LowerELFTLSLocalExec</a> (const GlobalValue *GV, SDValue ThreadBase, const SDLoc &amp;DL, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a thread-local variable reference into a sequence of instructions to compute the variable's address for the local exec TLS model of <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets. <a href="#a613aae161a403151b644b1297f3676b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a74994b3cfdaedb1beffaccf3c2112d">LowerELFTLSDescCallSeq</a> (SDValue SymAddr, const SDLoc &amp;DL, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When accessing thread-local variables under either the general-dynamic or local-dynamic system, we make a "TLS-descriptor" call. <a href="#a4a74994b3cfdaedb1beffaccf3c2112d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55f4b80584ad352b3d449f5a9b3deab3">LowerWindowsGlobalTLSAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dbaf43996da76acc3a908198e1e0b35">LowerPtrAuthGlobalAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec7895d5365c75539c1390fce8d52c06">LowerSETCC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e7efeefc9e5acd96404abf803aa1425">LowerSETCCCARRY</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e83939584f31a2ef02bc152784d92e5">LowerBR_CC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f314f791d5497519c5dcd14ee1c068f">LowerSELECT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1141ffd30e0929e184698c3b5a8bc27d">LowerSELECT_CC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa811c7c8bf987f11de7cff51e650711a">LowerSELECT_CC</a> (ISD::CondCode CC, SDValue LHS, SDValue RHS, SDValue TVal, SDValue FVal, const SDLoc &amp;dl, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d5be73d60ed495dfe9f6216df0a3907">LowerINIT_TRAMPOLINE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fd0b04b195d11d0c224a7f1f4bc49c6">LowerADJUST_TRAMPOLINE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b87094ab97a0cec1d6c5d3e8d8c8e39">LowerJumpTable</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab981bc579cae5ddba558dac4a6caa2a5">LowerBR_JT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6e950c2e731ddec21609eb6929a7141">LowerBRIND</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43ff6547eda6d335f89ca89f7cb48652">LowerConstantPool</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8924310554d164a33cc2748170a48101">LowerBlockAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e2c03794ff682ee5937754ed244ee16">LowerAAPCS_VASTART</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42d19190ba08f80b14d4f32c618795d7">LowerDarwin_VASTART</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebccf8543adbfef2fad2e7bd03e1dbe6">LowerWin64_VASTART</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a028c754ec1043aae81cf9bc5f075be6a">LowerVASTART</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a381e5da7458f8babfae2ad446587d849">LowerVACOPY</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad11c5a92cf1f808046a60fb7f55be1">LowerVAARG</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e2683a403aef34e8626a00880d20c26">LowerFRAMEADDR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a388b7fbe4a9bcf215cf6a23894ecae9f">LowerSPONENTRY</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4faca15afd55e2c3e9e68d5c678ab24">LowerRETURNADDR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25c07eae9a05b0fd519e28bde680af5e">LowerGET_ROUNDING</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6aa5c1c05559be441d4f9626fde1400">LowerSET_ROUNDING</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92bd218f47ba32a74d7ca85e18f2ad13">LowerGET_FPMODE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9154379c700e4c06c4d8992daa39778">LowerSET_FPMODE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72c0ded2bdf5343c0b481da714b74a84">LowerRESET_FPMODE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfa7cc98beacefaa0f8ab14879c2657b">LowerINSERT_VECTOR_ELT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30f3d867bec51d15847e56935d963c3b">LowerEXTRACT_VECTOR_ELT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf06dc096fd1ed0fbd8ebdbd971611a0">LowerBUILD_VECTOR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5d6e174e4955f6320f22ad135585a98">LowerZERO_EXTEND_VECTOR_INREG</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed28aba46e00c555b6a3ab7eab351c1d">LowerVECTOR_SHUFFLE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae240072fae01c4881c43782447bee611">LowerSPLAT_VECTOR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68a1ef7b833350467f1e3f33321172a9">LowerDUPQLane</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80535ff2e20df287726ab1d9a2cd8185">LowerToPredicatedOp</a> (SDValue Op, SelectionDAG &amp;DAG, unsigned NewOp) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b98af07e953a8f928ff6033e82d05e9">LowerToScalableOp</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a007d794f5c57e9e3e28e99532ca850b8">LowerVECTOR_SPLICE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee74073dca2cbc912d08febd1f0ed336">LowerEXTRACT_SUBVECTOR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3832243cbcd2d1750ec80bd72e94b9c">LowerINSERT_SUBVECTOR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f07d4d1f38c61b8b8f25cdfc1e8cb73">LowerVECTOR_DEINTERLEAVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e8c06c910f2e0725374a1876e0bac54">LowerVECTOR_INTERLEAVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e84f5f3a3e1b308c281e9f137ce0308">LowerVECTOR_HISTOGRAM</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad18fa82a4be2a76552da11cfada2362">LowerDIV</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de86f3b070a451e5485db7af82e37dc">LowerMUL</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61a805c5091de8b268d7ca7194b6a02c">LowerVectorSRA_SRL_SHL</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7874379fd6d6e266a0e0f71ec5cbdb4e">LowerShiftParts</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerShiftParts - Lower SHL_PARTS/SRA_PARTS/SRL_PARTS, which returns two i32 values and take a 2 x i32 value to shift plus a shift amount. <a href="#a7874379fd6d6e266a0e0f71ec5cbdb4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6c686b83925d61ba52ed54d522b62e5">LowerVSETCC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81a37fc038b29b804de7fcbb4f828408">LowerCTPOP_PARITY</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae356249a51754e3a82d988a27463fdbe">LowerCTTZ</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16a191948677bcfe69eccf0322e02b79">LowerBitreverse</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64e54884be7e33b543bdf8bcddbfbb2c">LowerMinMax</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b1664b8bc1787f48713d3e88c8497b">LowerFCOPYSIGN</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9edd44b5410f2b0aa8b896efe6a0b6f0">LowerFP_EXTEND</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a959d57b11b4e1d6141b73dc0c4758d53">LowerFP_ROUND</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f8a2fd6639002107169b958acc35548">LowerVectorFP_TO_INT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2aec72420b02edc0cb8a90513b44cfe">LowerVectorFP_TO_INT_SAT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d4fc21b2cc981172b0524587d689510">LowerFP_TO_INT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fcace2b9b6eae23371eea1550fe2748">LowerFP_TO_INT_SAT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a422d5a82ecb9cbbb1bb50b1910afb426">LowerVectorXRINT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac219f9ce6262358e59cdf918d8b9b59">LowerINT_TO_FP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c1b63ae762fe1dfae053cdab5ade32d">LowerVectorINT_TO_FP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a075a7ab0c4d34a65598156869f68ec4d">LowerVectorOR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada5ae42dc1f07e304ce9417b794ee0d9">LowerXOR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01b14350d7abf282001bf0455db9f172">LowerCONCAT_VECTORS</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab322431069592ccfd10d6aece55e68a0">LowerFSINCOS</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9abbd30e6ddde662f7d58def93e17a1e">LowerBITCAST</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6f327f5b2f3791e4d4e59565ec614e3">LowerVSCALE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0173c44fc0dee5e6d3e6e3186da8da">LowerTRUNCATE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5928136dca5d338b28355f94e66acb58">LowerVECREDUCE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f5c20380a3c53b28c66ff1b00de8b9">LowerATOMIC_LOAD_AND</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab27d9247786dc51e03654aff9d9c050">LowerWindowsDYNAMIC_STACKALLOC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06c98aca6c62d4ef3a3c0d9592e0946d">LowerInlineDYNAMIC_STACKALLOC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a776d185a104a5d00ced5924ae68dac9d">LowerDYNAMIC_STACKALLOC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed0b7409c8911010997242d8dbf42874">LowerAVG</a> (SDValue Op, SelectionDAG &amp;DAG, unsigned NewOp) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb01dd42f233f24b1bda38edcecb39d">LowerFixedLengthVectorIntDivideToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8191643cae54feb576332888eb55109">LowerFixedLengthVectorIntExtendToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b0f39a3585e1d4e64c73860b9aada7a">LowerFixedLengthVectorLoadToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e3555b0572261374f4ad6cbf690ce64">LowerFixedLengthVectorMLoadToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaadd336e2a5007e22f1cc743e44dfdbf">LowerVECREDUCE_SEQ_FADD</a> (SDValue ScalarOp, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c00923bade8cc4323f7d93e9652f7fa">LowerPredReductionToSVE</a> (SDValue ScalarOp, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48dac748ef81c9744d8da006bebcd86f">LowerReductionToSVE</a> (unsigned Opcode, SDValue ScalarOp, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade90770d4c77b5f495c08c4aec20c4ea">LowerFixedLengthVectorSelectToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a7c7f2068b5a7e6e044bc7bf02f6f4f">LowerFixedLengthVectorSetccToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06bd58d45fac0086f21b03496c81d721">LowerFixedLengthVectorStoreToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addd7e04e0d2fe74726ed2c19ca3443eb">LowerFixedLengthVectorMStoreToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb99d5ab85ff8ad6bf8912d372b93455">LowerFixedLengthVectorTruncateToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a093052942180cfb1cbaafb2b20d7aa57">LowerFixedLengthExtractVectorElt</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c2b012d902848e5bc7dcf519e3ff69a">LowerFixedLengthInsertVectorElt</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a367dc2b505f8bb3fa3f83e20bb0aaab4">LowerFixedLengthBitcastToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a289bf418d32a00df50eb32678e54962e">LowerFixedLengthConcatVectorsToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee48f50853ef3b0875bcac7b1ff3373f">LowerFixedLengthFPExtendToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a914a87e7efb93688ed68cb5a1ec45c1c">LowerFixedLengthFPRoundToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a611ab1c301b9eac417fbce54084a1b">LowerFixedLengthIntToFPToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9973c45ed11d90cece35cc62ac6d8699">LowerFixedLengthFPToIntToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2700e981c7d14ac405513444afda913f">LowerFixedLengthVECTOR_SHUFFLEToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa807450905c6c9d94044a677e37b5496">LowerFixedLengthBuildVectorToSVE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ee57538321e485ddbf68a752ae8f6b4">BuildSDIVPow2</a> (SDNode *N, const APInt &amp;Divisor, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDNode * &gt; &amp;Created) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets may override this function to provide custom SDIV lowering for power-of-2 denominators. <a href="#a9ee57538321e485ddbf68a752ae8f6b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ad1e460577077c916a65968f1fa4ad">BuildSREMPow2</a> (SDNode *N, const APInt &amp;Divisor, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDNode * &gt; &amp;Created) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets may override this function to provide custom SREM lowering for power-of-2 denominators. <a href="#a54ad1e460577077c916a65968f1fa4ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af46a036204c00ae8f16cf50790839095">getSqrtEstimate</a> (SDValue Operand, SelectionDAG &amp;DAG, int Enabled, int &amp;ExtraSteps, bool &amp;UseOneConst, bool Reciprocal) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hooks for building estimates in place of slower divisions and square roots. <a href="#af46a036204c00ae8f16cf50790839095">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea9587751619171e83cce9d14fe5c7aa">getRecipEstimate</a> (SDValue Operand, SelectionDAG &amp;DAG, int Enabled, int &amp;ExtraSteps) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reciprocal estimate value for the input operand. <a href="#aea9587751619171e83cce9d14fe5c7aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1c70298f44453860125d2305651b48f">getSqrtInputTest</a> (SDValue Operand, SelectionDAG &amp;DAG, const DenormalMode &amp;Mode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a target-dependent comparison result if the input operand is suitable for use with a square root estimate calculation. <a href="#ae1c70298f44453860125d2305651b48f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e35d9a74a44c02751ca8041e10ec2">getSqrtResultForDenormInput</a> (SDValue Operand, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a target-dependent result if the input operand is not suitable for use with a square root estimate calculation. <a href="#ad78e35d9a74a44c02751ca8041e10ec2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a46a7d1d4b30c365a5b0c16faeb1a06">combineRepeatedFPDivisors</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate whether this target prefers to combine FDIVs with the same divisor. <a href="#a2a46a7d1d4b30c365a5b0c16faeb1a06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116">ConstraintType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b0be789b677413965f96cbd82416342">getConstraintType</a> (StringRef Constraint) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getConstraintType - Given a constraint letter, return the type of constraint it is for this target. <a href="#a8b0be789b677413965f96cbd82416342">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a6ca5a86a7bb284087e0013b1529792">getRegisterByName</a> (const char *RegName, LLT VT, const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the name passed in. <a href="#a7a6ca5a86a7bb284087e0013b1529792">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abc">ConstraintWeight</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a811f55416153ed06594f5d61f57d0d85">getSingleConstraintMatchWeight</a> (AsmOperandInfo &amp;info, const char *constraint) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine constraint string and operand type and determine a weight value. <a href="#a811f55416153ed06594f5d61f57d0d85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61c6ff5f4875a5a048462f94278f60ce">getRegForInlineAsmConstraint</a> (const TargetRegisterInfo *TRI, StringRef Constraint, MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a physical register constraint (e.g. <a href="#a61c6ff5f4875a5a048462f94278f60ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac894c9f07fd0c5af812818eac7839de1">LowerXConstraint</a> (EVT ConstraintVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to replace an X constraint, which matches anything, with another that has more specific requirements based on the type of the corresponding operand. <a href="#ac894c9f07fd0c5af812818eac7839de1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a653d460e1a9fa5b210e4336c52267b35">LowerAsmOperandForConstraint</a> (SDValue Op, StringRef Constraint, std::vector&lt; SDValue &gt; &amp;Ops, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerAsmOperandForConstraint - Lower the specified operand into the Ops vector. <a href="#a653d460e1a9fa5b210e4336c52267b35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1074d1b213893f53b6a37a9f2a53fedc">getInlineAsmMemConstraint</a> (StringRef ConstraintCode) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf448af1fb6a9c142d8806b8edd115a">LowerAsmOutputForConstraint</a> (SDValue &amp;Chain, SDValue &amp;Flag, const SDLoc &amp;DL, const AsmOperandInfo &amp;Constraint, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle Lowering flag assembly outputs. <a href="#a0cf448af1fb6a9c142d8806b8edd115a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bb63d9c10cea2e2af535f9d2b6b4e56">shouldExtendGSIndex</a> (EVT VT, EVT &amp;EltTy) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the index type for a masked gather/scatter requires extending. <a href="#a3bb63d9c10cea2e2af535f9d2b6b4e56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a194a96b437faf888dcb1dd4bb3a31d85">shouldRemoveExtendFromGSIndex</a> (SDValue Extend, EVT DataVT) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf44b880e2d3d4ae5b318181a0263b82">isVectorLoadExtDesirable</a> (SDValue ExtVal) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if folding a vector load into ExtVal (a sign, zero, or any extend node) is profitable. <a href="#adf44b880e2d3d4ae5b318181a0263b82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa769f5ac07ae2b4e287c71e8efcad7b">isUsedByReturnOnly</a> (SDNode *N, SDValue &amp;Chain) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if result of the specified node is used by a return node only. <a href="#aaa769f5ac07ae2b4e287c71e8efcad7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43ba19c62a3955754bb400923b1bfab1">mayBeEmittedAsTailCall</a> (const CallInst *CI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target may be able emit the call instruction as a tail call. <a href="#a43ba19c62a3955754bb400923b1bfab1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a566cba125e6bae4fa579e585a35d5b18">getIndexedAddressParts</a> (SDNode *N, SDNode *Op, SDValue &amp;Base, SDValue &amp;Offset, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6968e1aa7f22c75ecd405bf5ba8c933">getPreIndexedAddressParts</a> (SDNode *N, SDValue &amp;Base, SDValue &amp;Offset, ISD::MemIndexedMode &amp;AM, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true by value, base pointer and offset pointer and addressing mode by reference if the node's address can be legally represented as pre-indexed load / store address. <a href="#ab6968e1aa7f22c75ecd405bf5ba8c933">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90bc20a9bf01f9ce5548201a670867b7">getPostIndexedAddressParts</a> (SDNode *N, SDNode *Op, SDValue &amp;Base, SDValue &amp;Offset, ISD::MemIndexedMode &amp;AM, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true by value, base pointer and offset pointer and addressing mode by reference if this node can be combined with a load / store to form a post-indexed load / store. <a href="#a90bc20a9bf01f9ce5548201a670867b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a424546d4a8647dc9f2c78befcf790fe1">isIndexingLegal</a> (MachineInstr &amp;MI, Register Base, Register Offset, bool IsPre, MachineRegisterInfo &amp;MRI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified base+offset is a legal indexed addressing mode for this target. <a href="#a424546d4a8647dc9f2c78befcf790fe1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2996ad730f39f10d1f88157709a302af">ReplaceNodeResults</a> (SDNode *N, SmallVectorImpl&lt; SDValue &gt; &amp;Results, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is invoked when a node result type is illegal for the target, and the operation was registered to use 'custom' lowering for that result type. <a href="#a2996ad730f39f10d1f88157709a302af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2fc37cebc11869e096bbcc810ca9961">ReplaceBITCASTResults</a> (SDNode *N, SmallVectorImpl&lt; SDValue &gt; &amp;Results, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53e1aa06384ce7ae8901856b77eca01a">ReplaceExtractSubVectorResults</a> (SDNode *N, SmallVectorImpl&lt; SDValue &gt; &amp;Results, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a68789b0668c98f7088a6cb3f4c9614">shouldNormalizeToSelectSequence</a> (LLVMContext &amp;, EVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we should normalize select(N0&amp;N1, X, Y) =&gt; select(N0, select(N1, X, Y), Y) and select(N0|N1, X, Y) =&gt; select(N0, select(N1, X, Y, Y)) if it is likely that it saves us from materializing N0 and N1 in an integer register. <a href="#a9a68789b0668c98f7088a6cb3f4c9614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e4061660a028461c831ee59526f05cd">finalizeLowering</a> (MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Execute target specific actions to finalize target lowering. <a href="#a8e4061660a028461c831ee59526f05cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a656c4ad00931beff8c0c2d5e5ee91066">shouldLocalize</a> (const MachineInstr &amp;MI, const TargetTransformInfo *TTI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not <span class="doxyComputerOutput">MI</span> needs to be moved close to its uses. <a href="#a656c4ad00931beff8c0c2d5e5ee91066">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac597a3f3ab29584848ef10f346aa75ee">SimplifyDemandedBitsForTargetNode</a> (SDValue Op, const APInt &amp;OriginalDemandedBits, const APInt &amp;OriginalDemandedElts, KnownBits &amp;Known, TargetLoweringOpt &amp;TLO, unsigned Depth) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to simplify any target nodes based on the demanded bits/elts, returning true on success. <a href="#ac597a3f3ab29584848ef10f346aa75ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd930cb28acdccb4c0251cb932cf190a">isTargetCanonicalConstantNode</a> (SDValue Op) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given Opc is considered a canonical constant for the target, which should not be transformed back into a BUILD_VECTOR. <a href="#abd930cb28acdccb4c0251cb932cf190a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe495b1e29519b957bc911f6bf505b20">getSVESafeBitCast</a> (EVT VT, SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d758d2ef3debc9f9f885ad01fdb406e">getRuntimePStateSM</a> (SelectionDAG &amp;DAG, SDValue Chain, SDLoc DL, EVT VT) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6f426df2cb3f8ca0a5d33617ffade81">preferScalarizeSplat</a> (SDNode *N) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c8e6dd249e825f4b945f4d33621d2b1">getMinimumJumpTableEntries</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return lower limit for number of blocks in a jump table. <a href="#a5c8e6dd249e825f4b945f4d33621d2b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56942071a0d88366724a8c7477728cf2">softPromoteHalfType</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a704a52de47d9799d238e5ae1bcbf43">shouldScalarizeBinop</a> (SDValue VecOp) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to convert an extract element of a vector binary operation into an extract element followed by a scalar operation. <a href="#a5a704a52de47d9799d238e5ae1bcbf43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f48f162b567cbab885913376db0fac1">Subtarget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep a pointer to the <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> around so that we can make the right decision when generating code for different targets. <a href="#a5f48f162b567cbab885913376db0fac1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">llvm::BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64747852028af5890d0089b384f1429f">BumpAlloc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringsaver">llvm::StringSaver</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3e0f0f1192eb7448df84112877020e">Saver</a> {BumpAlloc}</td>
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


<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64TargetLowering() {#acf8f1219dc8b656e8e11c4b08edc8979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64TargetLowering::AArch64TargetLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> &amp; STI)</td>
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



<p>Declaration at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af798622367e75c5536666dbfec5d5ea3">llvm::ISD::ABDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff129f5ab4fbc8279e7aaacb45f840b1">llvm::ISD::ABDU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a35c1cf0dd553444732dba8e8b9be0f6b">llvm::ISD::ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7c45a718f16057459d95d09d42ec6902">llvm::TargetLoweringBase::addRegisterClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af7bfad446dfd85837fe7ff904ebb1aff">llvm::ISD::ADJUST_TRAMPOLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9c91befeca2a25c8050d4c3dff8b6d67">llvm::ISD::ATOMIC_CMP_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c47226f266248f4b8c155b83601b109">llvm::ISD::ATOMIC_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf5f612de1a25451c9a0c33d77bf3e74">llvm::ISD::ATOMIC_LOAD_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a905925a49cdc6b4a6017d215820dad30">llvm::ISD::ATOMIC_LOAD_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8ceaa81a8088781e5efec0886ffe86be">llvm::ISD::ATOMIC_LOAD_CLR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4112a866197a97a70bdc78ef92c79b4c">llvm::ISD::ATOMIC_LOAD_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3d12dbff6e50803982d0e92768a1479">llvm::ISD::ATOMIC_LOAD_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a428ec1341b34eafa63518914e7f5ddf0">llvm::ISD::ATOMIC_LOAD_XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1db943abc1bf78a911daeb7b03d81de8">llvm::ISD::ATOMIC_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad728a4b56d49f39375881511d8d3118d">llvm::ISD::ATOMIC_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a55a4b1d94ca6176bcb5449196d67e798">llvm::ISD::AVGCEILS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8489c40b1b3f92b0c4fc98d06099c441">llvm::ISD::AVGCEILU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110acc5444f2e2933b551e3afbdd93a9bfc8">llvm::ISD::AVGFLOORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5096628a43b16ff34ace64193ded1c93">llvm::ISD::AVGFLOORU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeea401cc0b7fa5aa6f4d3a0612140e1d">llvm::ISD::BITREVERSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb">llvm::ISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716d19ebad1927a2e8dd5fe3f951f882">llvm::ISD::BR_JT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716765ad6ce5be71f987cd2097b1cdbf">llvm::ISD::BRIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a41bd84b853e2c03fb1af1f4ca9ebdcaf">llvm::ISD::BUILD_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a477ef80c70c7359199eace0e5d3133b1">llvm::ISD::BUILTIN_OP_END</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6df03220bbe2ea3cfb905f36fb26822c">llvm::TargetLoweringBase::computeRegisterProperties</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5">llvm::ISD::CONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1be4c8da7c68a4c683de1a98b5cc5b9d">llvm::ISD::ConstantFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c">llvm::ISD::CTLZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a991d07d163bd4d9984cf1ef36e92c214">llvm::ISD::CTPOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6da41a113af0909470baea7486b3386b">llvm::ISD::CTTZ</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa3441acf8576e4bbf48e9bd73ca3c0d8c">llvm::TargetLoweringBase::Custom</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a967fcb624e84458e135a763d1c11346a">llvm::ISD::DEBUGTRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa71ac22470bf853868fe6b39a25bac72">llvm::ISD::DYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80ebe2acf36317f888422a345e90ba87">llvm::TargetLoweringBase::EnableExtLdPromotion</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa4b85349547c5b6126817e10152007931">llvm::TargetLoweringBase::Expand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae243ce466d350b1aca774a6ae9aea81c">llvm::ISD::EXPERIMENTAL_VECTOR_HISTOGRAM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">llvm::ISD::EXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2b4d07600495a563319d6a3dda8dc44d">llvm::ISD::FABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3bd30fa450385ee74c9b275ba5f8d1c7">llvm::ISD::FACOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a62bcf7e98c551eddfe028e6ad6565215">llvm::ISD::FASIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3ec6f3b872819089911699ea156e6fc7">llvm::ISD::FATAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2a69cbb602c143642c1fe014bce6d44d">llvm::ISD::FATAN2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a74a787311d3ab9a17ee0acde7b6a6b14">llvm::ISD::FCANONICALIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad56e9199ae3993a09af36ff41d327a11">llvm::ISD::FCEIL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeffc3319657e213a530ce583603f7221">llvm::ISD::FCOPYSIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9133d7cfb6a66404ff7757b699bc3941">llvm::ISD::FCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30da9fef8027cdf8a719bdacb5300df8">llvm::ISD::FCOSH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abc6c09c7af98236460f0b020eb3be94e">llvm::ISD::FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad49a46d391f73aa96002adbdd0cf03f5">llvm::ISD::FEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a37c80ce3312d3fc5b925e326a16fff20">llvm::ISD::FEXP10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af3542a99501ffb93cee4aae9d1ec2d05">llvm::ISD::FEXP2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4336c27826676e1ef61383cafa999219">llvm::ISD::FFLOOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad9e6c8353bc9d023077590083cfce89c">llvm::ISD::FFREXP</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a850652b63276e9d79e6c1e05146c84c0">llvm::MVT::fixedlen_vector_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a455f49e18d470b97cd293acd7fbdf169">llvm::ISD::FLDEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac82d37f93ae4420659acdd03f79b15e0">llvm::ISD::FLOG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0d05d4a5cd10a46f69f9e62d49d275bb">llvm::ISD::FLOG10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a558dc710055f9d60cc3c0893bc29a72d">llvm::ISD::FLOG2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3dfd1b187d121c0e214698eef1c20f53">llvm::ISD::FMAXIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a632dd4bb044d5cd11f671d176ef495f2">llvm::ISD::FMAXNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a25e670389809910f59726e8a11fa82e0">llvm::ISD::FMAXNUM_IEEE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac27a43f98abb2d1ee2f2ce99a0b34b36">llvm::ISD::FMINIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9f59cc264907eb86e29564d5f6a5b213">llvm::ISD::FMINNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a907932b29f929b1827b1b93171dcaa3c">llvm::ISD::FMINNUM_IEEE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178">llvm::ISD::FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2dc876d6cc16ac04376483552292f9f4">llvm::ISD::FNEARBYINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d26c45c040d8f85d577a5f645261d1a">llvm::ISD::FNEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#af5e14144ddcc0caf0b4c461f9bc687d1">llvm::MVT::fp_fixedlen_vector_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae4a4e2126c6db34e2dfd71b6bd0408ee">llvm::ISD::FP_TO_SINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98661814400e72a77f5ed4e088c06937">llvm::ISD::FP_TO_UINT_SAT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#adfa86eda5d29b10227c46b4d8f071148">llvm::MVT::fp_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1a6952b1572a4ce241cc3cf45a9ab071">llvm::ISD::FPOW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a66b7368b776f6aff492cf970db3df548">llvm::ISD::FPOWI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdd7bbb76dac7962dda6e116e33699da">llvm::ISD::FREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a68014623710f7a44c808cd412236d6a1">llvm::ISD::FRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a87b7dd3d6a9b68d1558fc6b4706708b0">llvm::ISD::FROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab3cb85375f983765b93341d57a2f3838">llvm::ISD::FROUNDEVEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a822b0d02b601898e2d6db5b39e12cc8a">llvm::ISD::FSHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a874350de5b4f6b8f4db13940e17ed81b">llvm::ISD::FSHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad46ae9fdfe20cd04f7fda7ccbb937543">llvm::ISD::FSIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6ba8fc92ee5081d3e533cb5322f74f29">llvm::ISD::FSINCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8c5012dcc326bb95fc45b1f2e80dbda">llvm::ISD::FSINH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae1118ddac1ce0af8e9f7cc16c9e94fc0">llvm::ISD::FSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad">llvm::ISD::FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9edaaccfce9ddf3113d737686f0a019e">llvm::ISD::FTAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7d675a8da9b3fa2ee3a15b3932eef38a">llvm::ISD::FTANH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1e92ea554489509b0ad970901bcc715b">llvm::ISD::FTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8ba51b127e01a9e6412e7629c70ec4a1">llvm::ISD::GET_FPMODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89f3afc3fa907ff83759c6c76d97a973">llvm::ISD::GET_ROUNDING</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae365cf8f9a6844685be3fd9f12956c33">llvm::TargetLoweringBase::getLibcallName</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a6d48d262c4d851861f24550fb1014164">llvm::AArch64Subtarget::getMaxBytesForLoopAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a428f4cfc3de60a3999ac03dc56072bf6">llvm::AArch64Subtarget::getMaximumJumpTableSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4b7d8d1b98f160a4b807187194b99d96">llvm::TargetLoweringBase::getMaximumJumpTableSize</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a6b171f93524a8d0d1c0772479a1703c5">llvm::AArch64Subtarget::getPrefFunctionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a66c91211a6770a537c3cfc057cabd1fa">llvm::AArch64Subtarget::getPrefLoopAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sched/#ab8d854a5ce2331586bcc6830cca52f0fa6530ebdb4e713581540e6ceb88897acb">llvm::Sched::Hybrid</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a2239343bf72ef6a991165363ac0386c3">im</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4534a6db2862a28324932a8ea1cb54d6">llvm::ISD::INIT_TRAMPOLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">llvm::ISD::INSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a19cb5cb13066089592de60118998d9f8">llvm::MVT::integer_fixedlen_vector_valuetypes</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7b339f69bc3995d23399a85f81af6018">llvm::MVT::integer_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0248ed29f933c5faa55cbdfebf3139bd">llvm::TargetLoweringBase::isOperationExpand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#adfe2696265f6b0a7cd08bb6159fb9db4">llvm::TargetLoweringBase::IsStrictFPEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0c70100db6ddc0b37b56feb242145cf4">llvm::ISD::JumpTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ae0010333b4e1424ce473b508d802bbbd">llvm::ISD::LAST_INDEXED_MODE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3e769d29cd5e6ae3becf6fc0afec9e06">LCALLNAME4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aeb3aa65ce9bb27dc1f4c2ecd0bb4f641">LCALLNAME5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aafb9a152dd1ee4089f5fc96a33c5c90d2">llvm::TargetLoweringBase::LibCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a25eed965b36ce43fc8b9daa2774dfad8">llvm::ISD::LLRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4e2fdf7d4dbc04469cf6a920262c82c8">llvm::ISD::LLROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a05f23e2cd900dc8f1dbf6702ab12423b">llvm::ISD::LRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adb1de74d602ef905e06785e0052b55bf">llvm::ISD::LROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a341640d7d2de863af77af238f5a5ff94">llvm::TargetLoweringBase::MaxGluedStoresPerMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3111deca0523de0afcc110cf020ebaaf">llvm::TargetLoweringBase::MaxLoadsPerMemcmp</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aae9cf790eaa990b803a93058582d78e8">llvm::TargetLoweringBase::MaxLoadsPerMemcmpOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aefbee33131c130f8f691c9a482f5fc40">llvm::TargetLoweringBase::MaxStoresPerMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1695feb44cd6dd30c64697360f1e76d3">llvm::TargetLoweringBase::MaxStoresPerMemcpyOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6d0f43699563375800a45f45bc11ff49">llvm::TargetLoweringBase::MaxStoresPerMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7800cede44a09d00fcc61b9087c20d85">llvm::TargetLoweringBase::MaxStoresPerMemmoveOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9830bda9bf50bfdab4c10954cc6fb1ac">llvm::TargetLoweringBase::MaxStoresPerMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a67f472063b7db365d0b5da597871e03d">llvm::TargetLoweringBase::MaxStoresPerMemsetOptSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab4685260a7e506fe51f17d9b600349c8">llvm::ISD::MGATHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a112324db3910fea5895514851c387442">llvm::ISD::MLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab179d7f42562bbb315a6b0589a25f733">llvm::ISD::MSCATTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9add598de9e0a49cbb8fb19adf495051">llvm::ISD::MSTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa2a7c3eccf06b41e4275bbeadb46d22e">llvm::ISD::MULHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8a80d3b085af08f0dce1724207ef99b5">llvm::ISD::MULHU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa47439d20ce0879ea68ca293e018b4f5">llvm::ISD::PARITY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31ab5bb854fadd42503c849c4a48d7f3d90">llvm::ISD::PRE_INC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cc366cf4e0b825191ca9babcf290286">llvm::TargetLoweringBase::PredictableSelectIsExpensive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a691a4c9004e9bd04d1c0bebc5df57443">llvm::ISD::PREFETCH</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aaba91ac521e4f01f57413216273fd7b7f">llvm::TargetLoweringBase::Promote</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8df1b84ea64ad5048f27873205c8ab89">llvm::ISD::PtrAuthGlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac43f9bea13e29622bbf18c861b52144d">llvm::ISD::READCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a386314479bc7963a544ed142866e7ece">llvm::ISD::RESET_FPMODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715">llvm::ISD::ROTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a863ec6ebb75bf89cfea14da646d77e92">llvm::ISD::SADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af9eda6a77c3228cd36537469a7425133">llvm::ISD::SADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af1b946afff631cee7aa6de570bef7785">llvm::ISD::SADDSAT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a82c533fb7034a000f6a86f60c0642dc3">llvm::MVT::scalable_vector_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a874f66e1efe5be79552bbe7ee3121a">llvm::ISD::SDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a26b34eddab8969a79fd3cda432471809">llvm::ISD::SET_FPMODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4fe6c878350458de2c3182392f830988">llvm::ISD::SET_ROUNDING</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6b928e5a6718acab4fa0030ce9198e8a">llvm::TargetLoweringBase::setBooleanContents</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0662d63e058816bf77a5b8f35331bd9d">llvm::TargetLoweringBase::setBooleanVectorContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6bb33e400f29724907dc27ced04e9038">llvm::ISD::SETCCCARRY</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#abbec47c0a3f39ed8fa200ccc9933318f">llvm::TargetLoweringBase::setCondCodeAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3eae9a1850a035894e633aef9d5fbacd">llvm::TargetLoweringBase::setHasExtractBitsInsn</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4978da84fa67e0aa3a513c27e6367e91">llvm::TargetLoweringBase::setIndexedLoadAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8257b6c2db03e8af1a87bb4d7cb8c878">llvm::TargetLoweringBase::setIndexedStoreAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ab49f81c2ecbbff3d0fbe55dd46353774">llvm::ISD::SETLE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8b36797b46a42e7b489e47c2d009bc1d">llvm::TargetLoweringBase::setLibcallName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad1d4d71bf37fea6a3170f27438d41e6d">llvm::TargetLoweringBase::setLoadExtAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a6f05a09edb671910f85f8665981cbde9">llvm::ISD::SETLT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4df001a3c611cc8b423ca0e54560210f">llvm::TargetLoweringBase::setMaxAtomicSizeInBitsSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3ddb810ec23c0f90abd0d5085e86ed50">llvm::TargetLoweringBase::setMaxBytesForAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a09373cbbdb4326098156b8dfdad4e8b2">llvm::TargetLoweringBase::setMaxDivRemBitWidthSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a2daba03291ed357d731e42824d8ba4b1">llvm::TargetLoweringBase::setMaximumJumpTableSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6566d8c65c03ad2f7b18ed08f0e7f208">llvm::TargetLoweringBase::setMinFunctionAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a71f916390487bb109d9968c72553eaf4">llvm::ISD::SETO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a1febf3bac2f3d7d98ec19f1ff5c385ea">llvm::ISD::SETOLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a20257a4d3833cf88afd42caeaed70dde">llvm::ISD::SETOLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a57c68bf7ef20bd558854a24d5b0c1e72">llvm::ISD::SETONE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a07c0c67913bb543fc45ce9ef65ef260a">llvm::TargetLoweringBase::setOperationAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a357d8fa7fd274fd0fd281e19d468d92b">llvm::TargetLoweringBase::setOperationPromotedToType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8bb50938977c871d4dfa617d1b759a9a">llvm::TargetLoweringBase::setPrefFunctionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4aebe88e5c44bdb37513651bc72c2889">llvm::TargetLoweringBase::setPrefLoopAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af2a24aed2ba5d4f9c8db9904df6fa635">llvm::TargetLoweringBase::setSchedulingPreference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab8a44fb1f49bcfbed806fef69301a67a">llvm::TargetLoweringBase::setStackPointerRegisterToSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac87dc82fa9f824a797198e7b0e16141d">llvm::TargetLoweringBase::setTargetDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa243085e56636cc454143f916686c190">llvm::TargetLoweringBase::setTruncStoreAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a0deb50cd2f3f8e4a94eef4cdf769b848">llvm::ISD::SETUEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a9dff1dcbac65852b71473818c11869b1">llvm::ISD::SETUGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a292be4a9782030bfad637581d25a5897">llvm::ISD::SETUGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ac538f0b432df970cbaaf6b81d777c6a7">llvm::ISD::SETULE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a473200f06bdd611fdbed43d908b84305">llvm::ISD::SETULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af3b59179b6fcbc89463181015ace8e9b">llvm::ISD::SMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaac895215ecbb3c411c957c8beb39b70">llvm::ISD::SMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1354c6f8508d6cd697dc89a5d9a52dfd">llvm::ISD::SMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa35d0a58fdded3d225d512a60aea0951">llvm::ISD::SMULO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">llvm::ISD::SPLAT_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6efe16ea597cfd8eeac26516fc992ee7">llvm::ISD::SSUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a139dc5419039d94496e69dbb264251b5">llvm::ISD::SSUBO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a77984d86d70df1f3229da7a5119652a9">llvm::ISD::SSUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a023a9de787026fe61b024476bf9c32cb">llvm::ISD::STACKRESTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a031ce694e40832d40a163d7254a8df14">llvm::ISD::STACKSAVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a73ec2109e5056d5cb07dad24ddd848c3">llvm::ISD::STEP_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc1699b53cce73a1a89fa9190db8f2f8">llvm::ISD::STRICT_FACOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad11fa7fd2a91d210ecbdf09d56cd9f42">llvm::ISD::STRICT_FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a548c5ee9bfffd516c18b0844d8916d98">llvm::ISD::STRICT_FASIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5fc35989024437e6878d228dce85b34d">llvm::ISD::STRICT_FATAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1c24a514835d74a2a0b441825a622cef">llvm::ISD::STRICT_FATAN2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1fb1e48394636004fd75f5916f0d730f">llvm::ISD::STRICT_FCEIL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae2047d551dd66943aa285b4c7eab0766">llvm::ISD::STRICT_FCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac9090021eb9a063125475a3d2f380af2">llvm::ISD::STRICT_FCOSH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4151e13f7626f6d790d58c0fa444f32e">llvm::ISD::STRICT_FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aba2dfbb2100ec6aee6e5b52bc713c26a">llvm::ISD::STRICT_FEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad5d3bf9997ecfea792abc058e7d39e72">llvm::ISD::STRICT_FEXP2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab74cbb3933c5f5d2cc90d299836c05cc">llvm::ISD::STRICT_FFLOOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110addd63c6d866c8a8020a0cc4de467b285">llvm::ISD::STRICT_FLDEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad795680a8d2d37bdede6696d72f41c35">llvm::ISD::STRICT_FLOG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad227f160898f13eeb05150f03de8d40b">llvm::ISD::STRICT_FLOG10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a409f18d3c3acb29ab844e9942441cc4b">llvm::ISD::STRICT_FLOG2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a26ff7f7547f66e1a4f6d5e7efe4b2f59">llvm::ISD::STRICT_FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a917038ef7ae3264e336457da0f75e95b">llvm::ISD::STRICT_FMAXIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92f7a0e4dfe860ff938d463d84270ba3">llvm::ISD::STRICT_FMAXNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3093a04e2918e155f32d435e2f974e88">llvm::ISD::STRICT_FMINIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98f18e85e4e6421f5c859680602a4c1f">llvm::ISD::STRICT_FMINNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4b912b6be299d30d75b876e939d16fd6">llvm::ISD::STRICT_FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae463c3e40819d6e9de30d7d858867ef4">llvm::ISD::STRICT_FNEARBYINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac47e026e409ff39f319cbb3b096863e6">llvm::ISD::STRICT_FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2273d9cd04ba6e4a7c1a4b28ab1aaba">llvm::ISD::STRICT_FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed">llvm::ISD::STRICT_FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf955b4b70f63865e022c329d1775579">llvm::ISD::STRICT_FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a65a342694a17f4a1db771dbc36d31cc9">llvm::ISD::STRICT_FPOW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7acf26c84b90a50efe9898bc9bcd8d18">llvm::ISD::STRICT_FPOWI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aacf4034f48b7e32a9e20bfedbb5502bd">llvm::ISD::STRICT_FREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af57a22f2843a1c3a79d17350945ede58">llvm::ISD::STRICT_FRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0953e80e4e94f6ded9680e64c5df5cc">llvm::ISD::STRICT_FROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab7d5c27c800b79a02a1492f1965af72f">llvm::ISD::STRICT_FROUNDEVEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0466b21bfb4f3596e41380d8e2d1956f">llvm::ISD::STRICT_FSETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c8d07d668872f2176fb34724cd799c4">llvm::ISD::STRICT_FSETCCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a06c721642eadaa31c37384b39fe11387">llvm::ISD::STRICT_FSIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9b07fb8cd5a1230b0f736489ddd9eebc">llvm::ISD::STRICT_FSINH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a476844aad24870fab3d132b5fe6b1f37">llvm::ISD::STRICT_FSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad6192a54cb1dfeca8173749cc735269a">llvm::ISD::STRICT_FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8ae8131038d9b94abd2880812bf5b0e">llvm::ISD::STRICT_FTAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a244401fe9aee94da72b7f0fb6b095a45">llvm::ISD::STRICT_FTANH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a883c1084962f12018ca0fe3e1222fa7d">llvm::ISD::STRICT_FTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad4892124e4817d9807dcf39808016bc4">llvm::ISD::STRICT_LLRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adef1eba7d8c2a0db4a94d7327d217c90">llvm::ISD::STRICT_LLROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa7fc883444df66de315a684ecf5f5e2d">llvm::ISD::STRICT_LRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6bd04c8da718875a071107ede0f362d6">llvm::ISD::STRICT_LROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab38d2af541b99492acf69c041c98bcb6">llvm::ISD::STRICT_SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a56735332b7dc26b4e164035831fb40ab">llvm::ISD::STRICT_UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aaa96f111a59a7a2e7f9c689b344543df">llvm::TargetLowering::TargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac5fb8808f3dcb9f0a83f1fc2e7747485">llvm::ISD::TRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af78365e835dbc10df18c1cd5d8853fd0">llvm::ISD::TRUNCATE_SSAT_S</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a694c9a71596643f6ddd4ee767666cf43">llvm::ISD::TRUNCATE_SSAT_U</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af81ec85e716e986c5555135612f62b29">llvm::ISD::TRUNCATE_USAT_U</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1ddf36330110b4abea43fe390bea9ef9">llvm::ISD::UADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0f1e3ed26108fec69eb97209c0e39bf">llvm::ISD::UADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5e433873c201ad85c30e42da1ae05977">llvm::ISD::UADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa110c932d4027fe4043cceb7a579e5ee">llvm::ISD::UBSANTRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a257ffa49107e2db978e8a6e2688ada">llvm::ISD::UDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af675e759c0ffff8d48ea14a60fe3517b">llvm::ISD::UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a17126302da6199930e55e841ca1b082d">llvm::ISD::UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a79c959df09509d7ff66d9b04bc40d18d">llvm::ISD::UMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7800622851751b8ae318b41f4096830e">llvm::ISD::UMULO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28">llvm::ISD::UREM</a>, <a href="#afa8bfec034d066ec24d18d3fd76ac590">useSVEForFixedLengthVectorVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4ffc75d65231b55461c0ba4f36a3e500">llvm::ISD::USUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac81ebcd59d629d8680e50ffba9855255">llvm::ISD::USUBO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89166b38f12c0bd3e8a61d8f1a5a8bc8">llvm::ISD::USUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae77d03846b31c41c4860bcd96d780a78">llvm::ISD::VAARG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a804c1960ac64628cdd1f74d7de885284">llvm::ISD::VACOPY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1aadbb14ab26b74d841ac003363e3a5d">llvm::ISD::VAEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adfe32beaa596a1512b17e66b46e773ed">llvm::ISD::VASTART</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89a8ec08f6908a989c2d0198ae8851f9">llvm::ISD::VECREDUCE_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa58fe501d4e4fa1b4d19e0ed6b8ee6bd">llvm::ISD::VECREDUCE_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5e28372b4a60bf792da88d9bc8a8d0bf">llvm::ISD::VECREDUCE_FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a323856d66e2d8b1f74e528e3f9fe804d">llvm::ISD::VECREDUCE_FMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a355892ae7349b089e0bd24b3087d9c75">llvm::ISD::VECREDUCE_FMAXIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6a8980cf09891ec57cbce010ba119f79">llvm::ISD::VECREDUCE_FMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae526df97bcbda2419acf8cf105c95e8e">llvm::ISD::VECREDUCE_FMINIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aafd45b465ac59a1a57b8b9862aef6bed">llvm::ISD::VECREDUCE_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0b3085a54414d7e8ae7c13f5aeadb9da">llvm::ISD::VECREDUCE_SEQ_FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c057571f4591494880ec0bba023e0c2">llvm::ISD::VECREDUCE_SMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a11825b59a52b4f5a73c0b877e1ba0e70">llvm::ISD::VECREDUCE_SMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7ce9f75eaf17256deb960b11d1930040">llvm::ISD::VECREDUCE_UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab67678c3310e505df1a3f7677b14cfb0">llvm::ISD::VECREDUCE_UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9b59fad28698a46c33285083818f6b87">llvm::ISD::VECREDUCE_XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adb06c311948bd9fb944ab3c433138181">llvm::ISD::VECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af5b978686fa3409a40ce3abe447db653">llvm::ISD::VECTOR_DEINTERLEAVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7314e9c42c2c93e3786adfd12aee39d7">llvm::ISD::VECTOR_INTERLEAVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad55a17543ef86f6d46aebb45028a9067">llvm::ISD::VECTOR_SPLICE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9b2378721f79f5b72a6398dce97b3a42">llvm::ISD::VSCALE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0b7d2c769fd0fbaab3c4a2fc8e7ea0c">llvm::ISD::VSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a695a19c9c3ae14638be151add82755cb">llvm::TargetLoweringBase::ZeroOrNegativeOneBooleanContent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a0e2d72cfdcc49d2d189f440b3cc31dff">llvm::TargetLoweringBase::ZeroOrOneBooleanContent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allowsMisalignedMemoryAccesses() {#a815d0ad0c6f04717c0dd61b12b44095b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::allowsMisalignedMemoryAccesses (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, unsigned AddrSpace=0, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(1), <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dd">MachineMemOperand::Flags</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">MachineMemOperand::MONone</a>, unsigned * Fast=nullptr)</td>
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

<p>Returns true if the target allows unaligned memory accesses of the specified type.</p>

<p>Declaration at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2579 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a1572b31fadbd0d758314b8d35a050410">llvm::EVT::getStoreSize</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#ab8967b7214f38cdea9c0158dbe2ffa31">llvm::EVT::isScalableVector</a>.</p>


<p>Referenced by <a href="#ab72c286743e675ffbe81f7c9e9771fa5">getOptimalMemOpLLT</a> and <a href="#a5de718ef1b1e3a0da7a3f35a139d5197">getOptimalMemOpType</a>.</p>

</div>
</div>

### allowsMisalignedMemoryAccesses() {#a8ecd479d22b89a38549d035861ce1d84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::allowsMisalignedMemoryAccesses (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, unsigned AddrSpace, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dd">MachineMemOperand::Flags</a> Flags, unsigned * Fast=nullptr)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> variant.</p>

<p>Declaration at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2617 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>.</p>

</div>
</div>

### canMergeStoresTo() {#a40bdcac44bd6d189cc6b65984baf3303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::canMergeStoresTo (unsigned AS, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> MemVT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Returns if it's reasonable to merge stores to MemVT size.</p>

<p>Declaration at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#a920f0719057d7352f9da10908859368d">llvm::EVT::isFixedLengthVector</a>.</p>

</div>
</div>

### CCAssignFnForCall() {#a52a3cbd48589c37855abca181342ccb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCAssignFn * AArch64TargetLowering::CCAssignFnForCall (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, bool IsVarArg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Selects the correct <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> for a given CallingConvention value.</p>

<p>Declaration at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 7746 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca7c23dce1e95fc36e9d2c168f9e036cc7">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca963e14ac38d6e3b63f8e37085702951c">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca72069ecfe852db0ea1f10c1549989424">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca300efd85d130657d0d06f0469980bd0f">llvm::CallingConv::AArch64_SVE_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca0e62ecb2c693281fafd77f39b2ddd284">llvm::CallingConv::AArch64_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca047fefb5017b2873eb2e88f1a27fb14a">llvm::CallingConv::ARM64EC_Thunk_Native</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf80cc3a71c40926e6c35a60ccdc6428e">llvm::CallingConv::ARM64EC_Thunk_X64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a801ce153568c325d0456bca73ad60048">llvm::CC_AArch64_AAPCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add46321d83d3ce4afda6b454dace1914">llvm::CC_AArch64_Arm64EC_CFGuard_Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7956cf6435b4ad57dea517e9d15db8bf">llvm::CC_AArch64_Arm64EC_Thunk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7480b4f25ca1c3370da6cf87ea83f348">llvm::CC_AArch64_Arm64EC_Thunk_Native</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5449de4d7d9d52e4085e6b183be015f1">llvm::CC_AArch64_Arm64EC_VarArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab29a24e9bc5ca4a3916771b6a26d9331">llvm::CC_AArch64_DarwinPCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfa280a237d9d6440646a84b66add3a9">llvm::CC_AArch64_DarwinPCS_ILP32_VarArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c90fda6284918b945fb5225a83f7c7e">llvm::CC_AArch64_DarwinPCS_VarArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a09143d946f7d94cb279828e088c50d19">llvm::CC_AArch64_GHC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a547ae5e1b1a64aea325282f37ae90672">llvm::CC_AArch64_Preserve_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a34d93b678d192c6bca4f91ec5c918ded">llvm::CC_AArch64_Win64_CFGuard_Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6a7156d44206f906ee4f4108ca4457ce">llvm::CC_AArch64_Win64_VarArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a214f428cb6628b20196dbb60d75c40d7">llvm::CC_AArch64_Win64PCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b">llvm::CallingConv::CFGuard_Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca75c7c151466ad7e041e9ed8aa4d5a4bf">llvm::CallingConv::CXX_FAST_TLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae9c6786f93f1d156d2b40ecc6be438bb">llvm::CallingConv::GRAAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca9f6ac05d37c2fbf197de42295c23fd6e">llvm::CallingConv::PreserveAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4eeb29fe27dc20afa4f443765f45f9a5">llvm::CallingConv::PreserveMost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad5385f408f537fc279d485c77d2463ce">llvm::CallingConv::PreserveNone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca2740493172a4ce246941c8cff95e0f83">llvm::CallingConv::Swift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa">llvm::CallingConv::SwiftTail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad6e9c0ff694f0fca0222e79e772b647e">llvm::CallingConv::Tail</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae41511c1ad4197da36cef403f34bac72">llvm::CallingConv::Win64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bf014c51371fcfb7c32e932c2d3b1d6">analyzeCallOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp/#a0d6af68066457ccc3a8ddcd68d142853">finishStackBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#aa990c8b0771ccafcaded5c6ebb3cbc20">getAssignFnsForCC</a>.</p>

</div>
</div>

### CCAssignFnForReturn() {#a4ed0e25160d3a3323c87794e593b364a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCAssignFn * AArch64TargetLowering::CCAssignFnForReturn (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Selects the correct <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> for a given CallingConvention value.</p>

<p>Declaration at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 7809 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf80cc3a71c40926e6c35a60ccdc6428e">llvm::CallingConv::ARM64EC_Thunk_X64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b">llvm::CallingConv::CFGuard_Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05e34e567c905a27a39b062b561a42f4">llvm::RetCC_AArch64_AAPCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26d7268e015424db9c8551f681904e91">llvm::RetCC_AArch64_Arm64EC_CFGuard_Check</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a867f5bae5db71bdcfe835f2937c7054f">llvm::RetCC_AArch64_Arm64EC_Thunk</a>.</p>

</div>
</div>

### changeStreamingMode() {#af745858766f8ab9fd5ef15335bd011f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::changeStreamingMode (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> DL, bool Enable, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> InGlue, unsigned Condition, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> PStateSM=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a change in streaming mode is required on entry to/return from a function call it emits and returns the corresponding SMSTART or SMSTOP node.</p>


<p><span class="doxyComputerOutput">Condition</span> should be one of the enum values from <a href="/web-llvm/docs/api/namespaces/llvm/aarch64sme/#a1f949bc853d6cb91d7e45607d0253cb3">AArch64SME::ToggleCondition</a>.</p>


<p>Declaration at line 1005 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 8868 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64sme/#a1f949bc853d6cb91d7e45607d0253cb3a5ff61076bd563ad92f9ec55bb839e0bc">llvm::AArch64SME::Always</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">llvm::Enable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acfe1250a2214797a59c6457dd2180df9">llvm::SelectionDAG::getRegisterMask</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a195e0238576389dfb91a8610b0e881d2">llvm::AArch64ISD::SMSTART</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19afa0e42f3d1f5a26bbf63a2e6ad1125ca">llvm::AArch64ISD::SMSTOP</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### computeKnownBitsForTargetNode() {#a16eb7e7dd4fd476ad2fa83cfb84c068d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::computeKnownBitsForTargetNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth=0)</td>
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


<p>computeKnownBitsForTargetNode - Determine which of the bits specified in Mask are known to be either zero or one and return them Known.</p>


<p>Declaration at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a64a83c4bc05c2caeca43015fda341f45">llvm::AArch64ISD::ADDlow</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a1f1be83c0efdaff4af051b7a45faaba7">llvm::KnownBits::ashr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9e2fdd4065ecdc6146b74253f5591ed5">llvm::AArch64ISD::ASSERT_ZEXT_BOOL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad6ab97e04848339b891365ffbcc1a0fc">llvm::AArch64ISD::BICi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aeaea22b21177ff390559a1314dbf6947">llvm::AArch64ISD::CSEL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9e0955df410f281dcdb5272e0ab9ce3d">llvm::AArch64ISD::DUP</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a4fdc09049a61f952b5d52788dbd2f69b">llvm::KnownBits::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adcb96bd09d7c75c7669fa5f9d1190899">llvm::APInt::getHighBitsSet</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a76e45a40f2f0b5b09132d1de119765e8">llvm::KnownBits::intersectWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19adfb5f0cc680a060e5ca88e6e923d7183">llvm::AArch64ISD::LOADgot</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a5c34f40ce539320222a15a88ebcef716">llvm::KnownBits::lshr</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a066220c7a472d8793de64a0ad23487d2">llvm::KnownBits::makeConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a91a9a99c6c9977fcb422a33cedb64baa">llvm::AArch64ISD::MOVI</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ae9ffa8b50ca6095202b2e8e7686c10b8">llvm::KnownBits::shl</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a40a666d8a3b58f5eca5d7f9f26796bc7">llvm::KnownBits::trunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a794f9f6bbb4013df844fce71137cb255">llvm::AArch64ISD::VASHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4318caf60a3c8fb3a95e336e55457763">llvm::AArch64ISD::VLSHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19afb30ccc51f3686858a621b86f7171087">llvm::AArch64ISD::VSHL</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>

</div>
</div>

### ComputeNumSignBitsForTargetNode() {#aec59d76b8a13655705b0c55d99edf165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64TargetLowering::ComputeNumSignBitsForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth)</td>
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

<p>This method can be implemented by targets that want to expose additional information about sign bits to the DAG <a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a>.</p>


<p>The DemandedElts argument allows us to only collect the minimum sign bits that are shared by the requested vector elements.</p>


<p>Declaration at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2537 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4dfc32c20ebb97a98e406c25891d43c9">llvm::AArch64ISD::CMEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a253c60efdc75571e3bc8a58dd59becaf">llvm::AArch64ISD::CMEQz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac14d53a0ab8efc58263ff49cdc148af4">llvm::AArch64ISD::CMGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19adbfcc48de5a86d26dad681e5ab4ae73b">llvm::AArch64ISD::CMGEz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a28bb858be63e74941b0dcd6754d4c1f8">llvm::AArch64ISD::CMGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae0425e98d56c0083b583f1c5c714efd9">llvm::AArch64ISD::CMGTz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a28b81ba2a9cf5507fa21cf8341e1464f">llvm::AArch64ISD::CMHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a3a4c664b8c91eb49caa763b8b1076171">llvm::AArch64ISD::CMHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af534c8b3b04bafe5c651e83dd0e83ef6">llvm::AArch64ISD::CMLEz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a655dffaac8a992d3a612963917df3a63">llvm::AArch64ISD::CMLTz</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac01c66c983bfbac05a0cf903f08417df">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae57993c65e826491faff8e9f23ae2b94">llvm::AArch64ISD::FCMEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6ffcbbcb6e2951b44a89f04a89507a0c">llvm::AArch64ISD::FCMEQz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a49584572cc555ded4c292404822bff1c">llvm::AArch64ISD::FCMGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a7c644e021148062cb8186d06335d6c5b">llvm::AArch64ISD::FCMGEz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a967eebc9c3cd77d0eddf5a53bda3e9ac">llvm::AArch64ISD::FCMGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac7807ff6ae2440eb553822033f355ceb">llvm::AArch64ISD::FCMGTz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae8eea7e42467af1888111d30aa1ffc9a">llvm::AArch64ISD::FCMLEz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac4260922a57a444b076d7680cdfaed32">llvm::AArch64ISD::FCMLTz</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a794f9f6bbb4013df844fce71137cb255">llvm::AArch64ISD::VASHR</a>.</p>

</div>
</div>

### createComplexDeinterleavingIR() {#a7ea782436f7a688ebb717a91808b9c5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AArch64TargetLowering::createComplexDeinterleavingIR (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764">ComplexDeinterleavingOperation</a> OperationType, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ffbf98bd55746f804742b79f524ac7f">ComplexDeinterleavingRotation</a> Rotation, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * InputA, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * InputB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Accumulator=nullptr)</td>
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


<p>Declaration at line 916 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29797 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#abb0a82cf9ab3cf0c256918c17512f987aa66d3974b6f2e3a542f896da144cd297">Accumulator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a8a6707a9048ed67adda5b5ade0ecdd41">llvm::CAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a499d32d25a946dc992b9b13e2941a2a5">llvm::CDot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a9088901adcdb08d0856fd32e6e61e320">llvm::CMulPartial</a>, <a href="#a7ea782436f7a688ebb717a91808b9c5d">createComplexDeinterleavingIR</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a12589d52afe7ea72485b0a431327a6e6">llvm::VectorType::getHalfElementsVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">llvm::Intrinsic::not_intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ffbf98bd55746f804742b79f524ac7fa982956baaa7aa7989b38a9378f00bdbd">llvm::Rotation_270</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ffbf98bd55746f804742b79f524ac7fad3d2ab4f01286661a3d4e97a4b362b9c">llvm::Rotation_90</a>.</p>


<p>Referenced by <a href="#a7ea782436f7a688ebb717a91808b9c5d">createComplexDeinterleavingIR</a>.</p>

</div>
</div>

### createFastISel() {#a50cc068b91154ae6f285c1f435203121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastISel * AArch64TargetLowering::createFastISel (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; funcInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * libInfo)</td>
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

<p>This method returns a target specific <a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> object, or null if the target does not support "fast" ISel.</p>

<p>Declaration at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2643 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#ad6a46b5fa0c0be4df0f957b751654025">llvm::AArch64::createFastISel</a>.</p>

</div>
</div>

### EmitAllocateSMESaveBuffer() {#ab812d774aa563ffc2c67030a9ba1be39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * AArch64TargetLowering::EmitAllocateSMESaveBuffer (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 3249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab9af51d42f8f27a88d68ee1d1deb5eb7">llvm::MachineFrameInfo::CreateVariableSizedObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a35905b769bf1afa2cc7e2a223191e57e">llvm::AArch64_AM::getArithExtendImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a05fb81a3747dd4f76894a66c574cf99e">llvm::AArch64Subtarget::isTargetWindows</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a1590a6d5d0f6d95dda90f2cf8954f3fb">llvm::MachineBasicBlock::remove_instr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1ad2f6771d4027a09ba1d0de2e5ea54470">llvm::AArch64_AM::UXTX</a>.</p>


<p>Referenced by <a href="#add09df38070887ea74972930f1c9ce83">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### EmitAllocateZABuffer() {#ab9a65a8c0739a72de196022849b4ee67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * AArch64TargetLowering::EmitAllocateZABuffer (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 3204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab9af51d42f8f27a88d68ee1d1deb5eb7">llvm::MachineFrameInfo::CreateVariableSizedObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a05fb81a3747dd4f76894a66c574cf99e">llvm::AArch64Subtarget::isTargetWindows</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a1590a6d5d0f6d95dda90f2cf8954f3fb">llvm::MachineBasicBlock::remove_instr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/structs/llvm/tpidr2object/#a09a61f23c30af2dd9b8c7afd4ed304a1">llvm::TPIDR2Object::Uses</a>.</p>


<p>Referenced by <a href="#add09df38070887ea74972930f1c9ce83">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### emitAtomicCmpXchgNoStoreLLBalance() {#ad8f3e687e3d51ff7367011e81564c20e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::emitAtomicCmpXchgNoStoreLLBalance (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder)</td>
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



<p>Declaration at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27885 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>.</p>

</div>
</div>

### EmitDynamicProbedAlloc() {#af661669ba4d45cdb471e79bddb6975af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * AArch64TargetLowering::EmitDynamicProbedAlloc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 3057 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#add09df38070887ea74972930f1c9ce83">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### EmitF128CSEL() {#ab6a60676cdf39d45ae2ec66a7ea4aada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * AArch64TargetLowering::EmitF128CSEL (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2989 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acce9c12cc977a88dc7bc51493ce7681c">llvm::MachineBasicBlock::addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a>.</p>


<p>Referenced by <a href="#add09df38070887ea74972930f1c9ce83">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### EmitFill() {#aa92b03a9781f6914ffdef83ecf323708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * AArch64TargetLowering::EmitFill (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 3091 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#add09df38070887ea74972930f1c9ce83">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### EmitGetSMESaveSize() {#acfee0aff6a62996ec1dbee56ef35ad88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * AArch64TargetLowering::EmitGetSMESaveSize (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 3280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca963e14ac38d6e3b63f8e37085702951c">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X1</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a30a1feca92679c24a46b0b824a6de269">llvm::MachineInstrBuilder::addExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a8880ccaea51a4ee9b48c3c8d7fbfebf4">llvm::MachineInstrBuilder::addRegMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a1590a6d5d0f6d95dda90f2cf8954f3fb">llvm::MachineBasicBlock::remove_instr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#add09df38070887ea74972930f1c9ce83">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### EmitInitTPIDR2Object() {#a2ed887f0677d391bc6f9d7e77b761695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * AArch64TargetLowering::EmitInitTPIDR2Object (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 3174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a86a93dd8ddbce120d8c3101c16bc3cc6">llvm::MachineInstrBuilder::addFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a1590a6d5d0f6d95dda90f2cf8954f3fb">llvm::MachineBasicBlock::remove_instr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab356eaffcc04362671e727900a65ac52">llvm::MachineFrameInfo::RemoveStackObject</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#add09df38070887ea74972930f1c9ce83">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### EmitInstrWithCustomInserter() {#add09df38070887ea74972930f1c9ce83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * AArch64TargetLowering::EmitInstrWithCustomInserter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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


<p>Declaration at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 3305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="#ab812d774aa563ffc2c67030a9ba1be39">EmitAllocateSMESaveBuffer</a>, <a href="#ab9a65a8c0739a72de196022849b4ee67">EmitAllocateZABuffer</a>, <a href="#af661669ba4d45cdb471e79bddb6975af">EmitDynamicProbedAlloc</a>, <a href="#ab6a60676cdf39d45ae2ec66a7ea4aada">EmitF128CSEL</a>, <a href="#aa92b03a9781f6914ffdef83ecf323708">EmitFill</a>, <a href="#acfee0aff6a62996ec1dbee56ef35ad88">EmitGetSMESaveSize</a>, <a href="#a2ed887f0677d391bc6f9d7e77b761695">EmitInitTPIDR2Object</a>, <a href="#a87a3c3fc7fc8bc05db24005a6d38b5b2">EmitLoweredCatchRet</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="#a34c1693d3ce9979ba45e1e9425cc806e">EmitTileLoad</a>, <a href="#a20e848fbe4dcba24cc443837166728a8">EmitZAInstr</a>, <a href="#a94b0ff91bd18235291da52ddf1e7cc1a">EmitZero</a>, <a href="#aa695d49f883b21889c91b61d86437995">EmitZTInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a0ffbe496b7d5843d2beb9b4054b080da">llvm::AArch64::getSMEPseudoMap</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#aa0d273e9581758beab0f2fae0f04c34ca7880d5bd9d368e1478d58c8ba6c2c0cd">llvm::AArch64::SMEMatrixArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#aa0d273e9581758beab0f2fae0f04c34ca26cc0741b10bb30bdc3ecfbe57a00bb4">llvm::AArch64::SMEMatrixTileB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#aa0d273e9581758beab0f2fae0f04c34ca20d3d584b9dfef1378e9cbe2850c9cff">llvm::AArch64::SMEMatrixTileD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#aa0d273e9581758beab0f2fae0f04c34cad7cdfa4c052e2d822501a828a121ebed">llvm::AArch64::SMEMatrixTileH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#aa0d273e9581758beab0f2fae0f04c34ca536b8a43821c271ac2ac93c470fcae37">llvm::AArch64::SMEMatrixTileQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#aa0d273e9581758beab0f2fae0f04c34ca8c396337dc8d5ade1c935d04c45f3610">llvm::AArch64::SMEMatrixTileS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#aa0d273e9581758beab0f2fae0f04c34caf68cf94f58139b71c80a13c6d21e43c1">llvm::AArch64::SMEMatrixTypeMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### EmitKCFICheck() {#ae6e03361f09a5b06dc299f6ee1c76ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * AArch64TargetLowering::EmitKCFICheck (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a> &amp; MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII)</td>
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



<p>Declaration at line 938 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af066b2b6a1013299bfca84fe8b798a0b">llvm::MachineInstrBuilder::getInstr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### emitLoadLinked() {#a8631130c37aa54ae6c9127abc5fe392a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AArch64TargetLowering::emitLoadLinked (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValueTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ord)</td>
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


<p>Declaration at line 799 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27843 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae5d05ec2b9a60806746addff3f2a71a9">llvm::CallBase::addParamAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30ab2a65707a06849653fb5931411193">llvm::Type::getInt128Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a31e2db8d1b315202d2c19e711b5365fd">llvm::IRBuilderBase::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abbc497e16b1809ff526b1c755483d35c">llvm::isAcquireOrStronger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>.</p>

</div>
</div>

### EmitLoweredCatchRet() {#a87a3c3fc7fc8bc05db24005a6d38b5b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * AArch64TargetLowering::EmitLoweredCatchRet (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 3048 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a6f77e4e800ba4dffd63e8ddb330062aa">llvm::Function::getPersonalityFn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c9fb92464f96c0e0f326d624e82eab">llvm::isAsynchronousEHPersonality</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#add09df38070887ea74972930f1c9ce83">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### emitStoreConditional() {#a6245f16ff5b8230d2ed89127bf27efa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AArch64TargetLowering::emitStoreConditional (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ord)</td>
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


<p>Declaration at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27890 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae5d05ec2b9a60806746addff3f2a71a9">llvm::CallBase::addParamAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a0032ae544ae429aaf1053767da90426d">llvm::IRBuilderBase::CreateZExtOrBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30ab2a65707a06849653fb5931411193">llvm::Type::getInt128Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a31e2db8d1b315202d2c19e711b5365fd">llvm::IRBuilderBase::getIntNTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a1e415dc42f391c1d0cfcc1c28c00b2f4">llvm::FunctionType::getParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a586359566c841c85abfd8922e220213e">llvm::isReleaseOrStronger</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>

</div>
</div>

### EmitTileLoad() {#a34c1693d3ce9979ba45e1e9425cc806e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * AArch64TargetLowering::EmitTileLoad (unsigned Opc, unsigned BaseReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 662 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 3073 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#add09df38070887ea74972930f1c9ce83">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### EmitZAInstr() {#a20e848fbe4dcba24cc443837166728a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * AArch64TargetLowering::EmitZAInstr (unsigned Opc, unsigned BaseReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 3123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#add09df38070887ea74972930f1c9ce83">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### EmitZero() {#a94b0ff91bd18235291da52ddf1e7cc1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * AArch64TargetLowering::EmitZero (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 3157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#add09df38070887ea74972930f1c9ce83">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### EmitZTInstr() {#aa695d49f883b21889c91b61d86437995}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * AArch64TargetLowering::EmitZTInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, unsigned Opcode, bool Op0IsDef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 3106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#add09df38070887ea74972930f1c9ce83">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### enableAggressiveFMAFusion() {#af35d763b74cc1ae6f4da3a698b6e3027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::enableAggressiveFMAFusion (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Enable aggressive FMA fusion on targets that want it.</p>

<p>Declaration at line 943 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#a3cb888a2ce8e95e0d9769687a5e2f7d8">llvm::EVT::isFloatingPoint</a>.</p>

</div>
</div>

### fallBackToDAGISel() {#a790e9b70f12899a4cb2aefd33826ee7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::fallBackToDAGISel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Inst)</td>
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



<p>Declaration at line 969 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abb8d1b9b7c4af638307e2d5d62f87082">EnableSVEGISel</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a2ff127c9924cd3337080c4445c324aea">llvm::Type::isScalableTy</a>.</p>

</div>
</div>

### functionArgumentNeedsConsecutiveRegisters() {#a85b96f315b961f037b6aedfca25133c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::functionArgumentNeedsConsecutiveRegisters (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>For some targets, an LLVM struct type must be broken down into multiple simple types, but the calling convention specifies that the entire struct must be passed in a block of consecutive registers.</p>

<p>Declaration at line 962 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27932 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad78da75bd1f157e72100f97d1ecdc756">llvm::all_equal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab99618b3d8988b758a67f5a1a6071095">llvm::ComputeValueVTs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>.</p>

</div>
</div>

### generateFMAsInMachineCombiner() {#acaa0f01ce8216a0cc8704e2a086805c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::generateFMAsInMachineCombiner (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OptLevel)</td>
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



<p>Declaration at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17905 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab8967b7214f38cdea9c0158dbe2ffa31">llvm::EVT::isScalableVector</a> and <a href="#afa8bfec034d066ec24d18d3fd76ac590">useSVEForFixedLengthVectorVT</a>.</p>

</div>
</div>

### getAsmOperandValueType() {#a9409a43cdbf7e602589114de4e2daf4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT AArch64TargetLowering::getAsmOperandValueType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool AllowUnknown=false)</td>
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



<p>Declaration at line 989 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 12542 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aee7335adfdf89d9bc00d567a1e53db23">llvm::TargetLoweringBase::getAsmOperandValueType</a>.</p>

</div>
</div>

### getExceptionPointerRegister() {#a01a1d1b02c449d7e82f517e549cd68a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register AArch64TargetLowering::getExceptionPointerRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PersonalityFn)</td>
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

<p>Declaration at line 842 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28029 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getExceptionSelectorRegister() {#adb10389377e757d4042fe9c16fa449ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register AArch64TargetLowering::getExceptionSelectorRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PersonalityFn)</td>
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

<p>Declaration at line 847 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28037 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getIRStackGuard() {#ac887f4f420c78b4d95f669030c4c4464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AArch64TargetLowering::getIRStackGuard (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; IRB)</td>
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

<p>If the target has a standard location for the stack protector cookie, returns the address of that location.</p>


<p>Otherwise, returns nullptr.</p>


<p>Declaration at line 829 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27961 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a784589f886057bdb03273b8bb07deb2b">llvm::TargetLoweringBase::getIRStackGuard</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aadfa6a6899cb32e0b249dfe7d5ab904b">UseTlsOffset</a>.</p>

</div>
</div>

### getMaxSupportedInterleaveFactor() {#a84bb66973746f769109266358c463c68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64TargetLowering::getMaxSupportedInterleaveFactor ()</td>
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

<p>Get the maximum supported factor for interleaved memory accesses.</p>


<p>Default to be the minimum interleave factor: 2.</p>


<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>


<p>Referenced by <a href="#a6cbcd096f254563525e65e58557ed901">lowerInterleavedLoad</a> and <a href="#aa4094e6b2a8203e5c8b67ecf186d51a9">lowerInterleavedStore</a>.</p>

</div>
</div>

### getNumInterleavedAccesses() {#a365f29ab21721393fe82ff3ae4554e5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64TargetLowering::getNumInterleavedAccesses (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VecTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, bool UseScalable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of interleaved accesses that will be generated when lowering accesses of the given type.</p>


<p>A helper function for determining the number of interleaved accesses we will generate when lowering accesses of the given type.</p>


<p>Declaration at line 956 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17024 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a59632c5deb0423a518ad984bdd04d41f">llvm::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#ac66d3f15510c7402f2a85a87c69f1603">lowerDeinterleaveIntrinsicToLoad</a>, <a href="#a6cbcd096f254563525e65e58557ed901">lowerInterleavedLoad</a>, <a href="#aa4094e6b2a8203e5c8b67ecf186d51a9">lowerInterleavedStore</a> and <a href="#ac2d9e284d06499be56d61b876e86dc8a">lowerInterleaveIntrinsicToStore</a>.</p>

</div>
</div>

### getNumRegistersForCallingConv() {#a3f4445d350e1253b4c05ab25011d766d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64TargetLowering::getNumRegistersForCallingConv (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Certain targets require unusual breakdowns of certain types.</p>


<p>For MIPS, this occurs when a vector type is used, as vector are passed through the integer register set.</p>


<p>Declaration at line 1019 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29939 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a315b23c0819f55fa9e7473c21992fc12">llvm::TargetLoweringBase::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3d102abca1c9c95f36546dff2f39273b">llvm::EVT::getVectorElementCount</a>, <a href="#ac477f229337de92be9c48dae99bf5546">getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a920f0719057d7352f9da10908859368d">llvm::EVT::isFixedLengthVector</a> and <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>.</p>

</div>
</div>

### getOptimalMemOpLLT() {#ab72c286743e675ffbe81f7c9e9771fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT AArch64TargetLowering::getOptimalMemOpLLT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memop">MemOp</a> &amp; Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &amp;)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> returning variant.</p>

<p>Declaration at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17664 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="#a815d0ad0c6f04717c0dd61b12b44095b">allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a61054ea97168f709c1e46345f80c16a3">llvm::AttributeList::hasFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">llvm::MachineMemOperand::MONone</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>

</div>
</div>

### getOptimalMemOpType() {#a5de718ef1b1e3a0da7a3f35a139d5197}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT AArch64TargetLowering::getOptimalMemOpType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memop">MemOp</a> &amp; Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &amp;)</td>
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


<p>Declaration at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17634 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="#a815d0ad0c6f04717c0dd61b12b44095b">allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a61054ea97168f709c1e46345f80c16a3">llvm::AttributeList::hasFnAttr</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">llvm::MachineMemOperand::MONone</a>.</p>

</div>
</div>

### getPointerTy() {#aa11502fbc6bf582057507658bd9682a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::AArch64TargetLowering::getPointerTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, uint32_t AS=0)</td>
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

<p>Return the pointer type for the given address space, defaults to the pointer type from the data layout.</p>


<p>FIXME: The default needs to be removed once all the code is updated.</p>


<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af13091d8b3eced08538be82392dc7d43">emitSMEStateSaveRestore</a> and <a href="#a205e757ebb66d5477f9ec152d6adcf8b">getVaListSizeInBits</a>.</p>

</div>
</div>

### getPreferredLargeGEPBaseOffset() {#a2789f36b6ade6b507b2fb7cf6e4f49e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t AArch64TargetLowering::getPreferredLargeGEPBaseOffset (int64_t MinOffset, int64_t MaxOffset)</td>
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

<p>Return the prefered common base offset.</p>

<p>Declaration at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17858 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="#ad37b1f031f487d6e69553ec06518c219">isLegalAddImmediate</a>.</p>

</div>
</div>

### getPreferredVectorAction() {#a1885796ae6d5528e9544ad558881e46b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLoweringBase::LegalizeTypeAction AArch64TargetLowering::getPreferredVectorAction (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
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

<p>Return the preferred vector type legalization action.</p>

<p>Declaration at line 825 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a59ae7f93fccb0ae431e82f8d74ba443c">llvm::TargetLoweringBase::getPreferredVectorAction</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681a5290057031a9bc71850f61e757cb940e">llvm::TargetLoweringBase::TypeWidenVector</a>.</p>

</div>
</div>

### getPromotedVTForPredicate() {#a1bdd144ce64dea5afb172d742184c997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT AArch64TargetLowering::getPromotedVTForPredicate (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 987 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29663 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getRedZoneSize() {#aa4502ed00aa357af2b923730584885d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64TargetLowering::getRedZoneSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a81242a6cd5fbec123c8ed582bab0f26c">llvm::AArch64FrameLowering::canUseRedZone</a>.</p>

</div>
</div>

### getRegisterTypeForCallingConv() {#a0f1ad23af20c2a0b3e3f5c0a995c1969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT AArch64TargetLowering::getRegisterTypeForCallingConv (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Certain combinations of ABIs, Targets and features require that types are legal for some operations and not for other operations.</p>


<p>For MIPS all vector types must be passed through the integer register set.</p>


<p>Declaration at line 1017 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29923 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a347d293012b5070f6833926f3d2e50d7">llvm::TargetLoweringBase::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3d102abca1c9c95f36546dff2f39273b">llvm::EVT::getVectorElementCount</a>, <a href="#ac477f229337de92be9c48dae99bf5546">getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a920f0719057d7352f9da10908859368d">llvm::EVT::isFixedLengthVector</a> and <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>.</p>

</div>
</div>

### getRoundingControlRegisters() {#ae33d5b14ea69e8e72a00f6531649c92a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; AArch64TargetLowering::getRoundingControlRegisters ()</td>
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

<p>Returns a 0 terminated array of rounding control registers that can be attached into strict FP call.</p>

<p>Declaration at line 762 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17922 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getSafeStackPointerLocation() {#a98a5a7a00d7d117c9560524236a559d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AArch64TargetLowering::getSafeStackPointerLocation (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; IRB)</td>
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

<p>If the target has a standard location for the unsafe stack pointer, returns the address of that location.</p>


<p>Otherwise, returns nullptr.</p>


<p>Declaration at line 837 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28012 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1b127c37d77da045cea07e787e2d1e48">llvm::TargetLoweringBase::getSafeStackPointerLocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aadfa6a6899cb32e0b249dfe7d5ab904b">UseTlsOffset</a>.</p>

</div>
</div>

### getScalarShiftAmountTy() {#af4df626bbb6ef71e104c49d823e9e37e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT AArch64TargetLowering::getScalarShiftAmountTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
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

<p>Return the type to use for a scalar shift opcode, given the shifted amount type.</p>


<p>Targets should return a legal type if the input type is legal. Targets can return a type that is too small if the input type is illegal.</p>


<p>Declaration at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2574 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### getScratchRegisters() {#ad687d3401b5b0769d08e78fcdb51acb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg * AArch64TargetLowering::getScratchRegisters (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
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

<p>Declaration at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17912 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getSDagStackGuard() {#af493092261037debb1fad82108301fdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AArch64TargetLowering::getSDagStackGuard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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


<p>Declaration at line 832 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27997 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a40e9675119de3bcd2fd05b549994a17d">llvm::TargetLoweringBase::getSDagStackGuard</a>.</p>

</div>
</div>

### getSetCCResultType() {#a4fce00050967f2d8237319f1912a0103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT AArch64TargetLowering::getSetCCResultType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">ISD::SETCC</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a>.</p>

<p>Declaration at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a0351571482fea42a3b326147fb2ce9e2">llvm::EVT::changeVectorElementTypeToInteger</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3d102abca1c9c95f36546dff2f39273b">llvm::EVT::getVectorElementCount</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a210ba6b43ba451b698857dd9de71bd15">llvm::EVT::getVectorVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab8967b7214f38cdea9c0158dbe2ffa31">llvm::EVT::isScalableVector</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### getSSPStackGuardCheck() {#a7aeb9c73ff9505a01d6bef9d1f6f6c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * AArch64TargetLowering::getSSPStackGuardCheck (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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


<p>Declaration at line 833 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28004 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a8743c58384e11cb6228f6f871304ad35">llvm::Function::getFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a5cc7ede2e4ce0498c628270ca97ed75c">llvm::TargetLoweringBase::getSSPStackGuardCheck</a>.</p>

</div>
</div>

### getTargetMMOFlags() {#a55ec39e405ec6b7dca5cdd266ced41ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineMemOperand::Flags AArch64TargetLowering::getTargetMMOFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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

<p>This callback is used to inspect load/store instructions and add target-specific <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> flags to them.</p>


<p>The default implementation does nothing.</p>


<p>Declaration at line 959 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17035 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-h/#a309185dacbbc2610d98ea8130927f3b3">FALKOR_STRIDED_ACCESS_MD</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">llvm::MachineMemOperand::MONone</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adcbbc11398a037540fd4fbab96e6f6a4">llvm::MOStridedAccess</a>.</p>

</div>
</div>

### getTargetNodeName() {#a6fa8b499e0abef24aa5d61c4ee8172d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * AArch64TargetLowering::getTargetNodeName (unsigned Opcode)</td>
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

<p>Declaration at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2648 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a41558bfb98ed3b2341959aa622dc2495">llvm::AArch64ISD::ABDS_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a45354be2b9fb574b34b8e38f6fbdf15a">llvm::AArch64ISD::ABDU_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a23379b95ff6faf89e6fad047bfb0ac1b">llvm::AArch64ISD::ABS_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a570a73eb4f12ab7c7db1e81f280b363c">llvm::AArch64ISD::ADC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ab98a7740ca34fec72ed6e3b38760b2b1">llvm::AArch64ISD::ADCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a64a83c4bc05c2caeca43015fda341f45">llvm::AArch64ISD::ADDlow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac2b2c785ce82d3782f292a3f9c2803e2">llvm::AArch64ISD::ADDP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a61ede97ea8fc84f9f11d6478d5d214a6">llvm::AArch64ISD::ADDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a8ee06ddad96ab8a83a8513e4b5b49717">llvm::AArch64ISD::ADR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa2e9d9d7c30818fd5ba551f8d3f0af34">llvm::AArch64ISD::ADRP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a708cfb0f0b290388103fab23b2df11b8">llvm::AArch64ISD::ALLOC_SME_SAVE_BUFFER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19abed4fc5cfb6475d3141b7a9d51c8d0d5">llvm::AArch64ISD::ALLOCATE_ZA_BUFFER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af36f36b0406330ead921ee1fb07de2cd">llvm::AArch64ISD::ANDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a233bc9367b23f2632c606088f60495a2">llvm::AArch64ISD::ANDV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9e2fdd4065ecdc6146b74253f5591ed5">llvm::AArch64ISD::ASSERT_ZEXT_BOOL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a3d25de941ed197fd00717b8024be207c">llvm::AArch64ISD::AUTH_CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a5517cf2a434cad2e6738d97d7bb2ecf1">llvm::AArch64ISD::AUTH_CALL_RVMARKER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a412d284f54ae9192c798a55786c47a7d">llvm::AArch64ISD::AUTH_TC_RETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa13d0bd502aeac8ee6bfdb48903a47db">llvm::AArch64ISD::BIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad6ab97e04848339b891365ffbcc1a0fc">llvm::AArch64ISD::BICi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a921a34e318b619f9c1973aa431fa2a7c">llvm::AArch64ISD::BITREVERSE_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1dd8fc0bc13596b74da85b07a1ee5dd2">llvm::AArch64ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a21d1b00201e7e4cb249066ba0da2dd0e">llvm::AArch64ISD::BSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a2ca380dca8a9dd681808096bfdd62695">llvm::AArch64ISD::BSWAP_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1506f6dab9103c66c2463fdded31a599">llvm::AArch64ISD::CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19abf20adf1123111c49f741eb7c622210a">llvm::AArch64ISD::CALL_ARM64EC_TO_X64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19adc79ed255f1706e125f05ac99a7341c4">llvm::AArch64ISD::CALL_BTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a95e48c51e4bf205ee490105e96350bbc">llvm::AArch64ISD::CALL_RVMARKER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1ace695a3a0de6c36056b46791fdbd53">llvm::AArch64ISD::CBNZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac723fb32863b8b811d1f5e20a9d29b83">llvm::AArch64ISD::CBZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a8deb26c97d84f931bdfb22aee53cebbc">llvm::AArch64ISD::CCMN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a82c3a82c9284fc5edff2a96dec362f57">llvm::AArch64ISD::CCMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aae0756f28d186b8713f960df55dc15b3">llvm::AArch64ISD::CLASTA_N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af47f2fa02f0c000b2bb2713f4044ca55">llvm::AArch64ISD::CLASTB_N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4dfc32c20ebb97a98e406c25891d43c9">llvm::AArch64ISD::CMEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a253c60efdc75571e3bc8a58dd59becaf">llvm::AArch64ISD::CMEQz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac14d53a0ab8efc58263ff49cdc148af4">llvm::AArch64ISD::CMGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19adbfcc48de5a86d26dad681e5ab4ae73b">llvm::AArch64ISD::CMGEz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a28bb858be63e74941b0dcd6754d4c1f8">llvm::AArch64ISD::CMGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae0425e98d56c0083b583f1c5c714efd9">llvm::AArch64ISD::CMGTz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a28b81ba2a9cf5507fa21cf8341e1464f">llvm::AArch64ISD::CMHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a3a4c664b8c91eb49caa763b8b1076171">llvm::AArch64ISD::CMHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af534c8b3b04bafe5c651e83dd0e83ef6">llvm::AArch64ISD::CMLEz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a655dffaac8a992d3a612963917df3a63">llvm::AArch64ISD::CMLTz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a047ba44fc28cdb42e45b171b4c871513">llvm::AArch64ISD::COALESCER_BARRIER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aeaea22b21177ff390559a1314dbf6947">llvm::AArch64ISD::CSEL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4a963d58bfd84cd339df4a7c57f8764e">llvm::AArch64ISD::CSINC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a87407f364bf7154debfe6a3008760e8c">llvm::AArch64ISD::CSINV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a7749b66ee4fb30ffb40a30f5ef67b46f">llvm::AArch64ISD::CSNEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a7423f39e91075c53373cbc86362ddfb6">llvm::AArch64ISD::CTLZ_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6dc4d1d9ec66f752416aaa390a8dfdcb">llvm::AArch64ISD::CTPOP_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19adc867f8bbfd796edbf20fd98de8e275b">llvm::AArch64ISD::CTTZ_ELTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9e0955df410f281dcdb5272e0ab9ce3d">llvm::AArch64ISD::DUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aeeea721755ccf2b778a95b42ff8eb55c">llvm::AArch64ISD::DUP_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a5dea2cc356e551e1a38be00f441d0aed">llvm::AArch64ISD::DUPLANE128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a63256211d7e9fcab596baa05d672db8d">llvm::AArch64ISD::DUPLANE16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a5d3f342d733ac020d495e08094c201bb">llvm::AArch64ISD::DUPLANE32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a626e899c69c3bfdbdbb094dd1c43bcc5">llvm::AArch64ISD::DUPLANE64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9e5cc09bf44571679cb7abc733bca21b">llvm::AArch64ISD::DUPLANE8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19accc2b0352ba19606af1040c262293f09">llvm::AArch64ISD::EORV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a489b5bf6d9df2ae4dac6fce059b91bda">llvm::AArch64ISD::EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a95126578449c59d8c182dcaec35c447c">llvm::AArch64ISD::FABS_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a79b964a205e8af1c7d40c1c7ea27cbeb">llvm::AArch64ISD::FADD_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a672ec7ad6023bc5e6288c32f9d0b65a3">llvm::AArch64ISD::FADDA_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6efdb0e8c7f9876a8c7d5018948e0acd">llvm::AArch64ISD::FADDV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af6319439dbf716e743039fae1f75a4fc">llvm::AArch64ISD::FCCMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6683923954c2104dc5500772c896891f">llvm::AArch64ISD::FCEIL_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae57993c65e826491faff8e9f23ae2b94">llvm::AArch64ISD::FCMEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6ffcbbcb6e2951b44a89f04a89507a0c">llvm::AArch64ISD::FCMEQz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a49584572cc555ded4c292404822bff1c">llvm::AArch64ISD::FCMGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a7c644e021148062cb8186d06335d6c5b">llvm::AArch64ISD::FCMGEz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a967eebc9c3cd77d0eddf5a53bda3e9ac">llvm::AArch64ISD::FCMGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac7807ff6ae2440eb553822033f355ceb">llvm::AArch64ISD::FCMGTz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae8eea7e42467af1888111d30aa1ffc9a">llvm::AArch64ISD::FCMLEz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac4260922a57a444b076d7680cdfaed32">llvm::AArch64ISD::FCMLTz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19adee98654dac93ffd21f1b9a129ec40e2">llvm::AArch64ISD::FCMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a80c54a646e51ad20866f14d0315cb0bd">llvm::AArch64ISD::FCVTX_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af6764ee93df826e9e67f63452a71cf13">llvm::AArch64ISD::FCVTXN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a736e40ee8bf80d195036bf07fee64f8c">llvm::AArch64ISD::FCVTZS_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae42c77576ffd4957708a186a3d262a49">llvm::AArch64ISD::FCVTZU_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a236b6f5a3fa768b9338169585b94d31e">llvm::AArch64ISD::FDIV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6e4af32448924c58cb4a748a07864bea">llvm::AArch64ISD::FFLOOR_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4e6bee589f2340d206010f5ac573708b">llvm::AArch64ISD::FIRST_NUMBER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a26eebef9ecd023d56a0d1f5659c6d56f">llvm::AArch64ISD::FMA_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae188e1a972d14cacb4b25aaa08c03fe7">llvm::AArch64ISD::FMAX_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a06e995899e91ad228e89b42a733a9fc8">llvm::AArch64ISD::FMAXNM_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ade8465168b90801e75f1d747b3a869db">llvm::AArch64ISD::FMAXNMV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a852f902347015cf35be53ca82a2d36eb">llvm::AArch64ISD::FMAXV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1280ffb064fa61a167776c1714f8c115">llvm::AArch64ISD::FMIN_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a13039ac177cb3a515571da75980a41bc">llvm::AArch64ISD::FMINNM_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a19b22d25633ae42d72b6b5e81baccca5">llvm::AArch64ISD::FMINNMV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac69039ab54d0e64408e26e1e82dbf857">llvm::AArch64ISD::FMINV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a02e94d994c40b37bc4cf95827982393d">llvm::AArch64ISD::FMOV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a92132db91b6ec7e16a2d779bcc78385e">llvm::AArch64ISD::FMUL_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a685ce754a67e5cb56d1ef4093e6bf4fe">llvm::AArch64ISD::FNEARBYINT_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac13d816d2cb81731c25f88a756f78b75">llvm::AArch64ISD::FNEG_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a2af744ee43acb71c6a7b2792a4bc7e0b">llvm::AArch64ISD::FP_EXTEND_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a2f6610e806b817c326a00ba86c3c39ae">llvm::AArch64ISD::FP_ROUND_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1e640c0d1dfbd984946b94c00bb08e42">llvm::AArch64ISD::FRECPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a584f88016830e5aed58404ed12f9b3e1">llvm::AArch64ISD::FRECPS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae20731453b229dcb3d378c282b68fe8e">llvm::AArch64ISD::FRECPX_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a43d0d40d03e4d03b0512a74db902be45">llvm::AArch64ISD::FRINT_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a7c0da9722d4fb6b68c096e15b50bdbac">llvm::AArch64ISD::FROUND_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4ce802350a14f6dd022c1d2dd87ec7b6">llvm::AArch64ISD::FROUNDEVEN_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a3ad8163d9a9b7beace806694b5818168">llvm::AArch64ISD::FRSQRTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a2b59dada319a790ce5397dc4f8f02a8c">llvm::AArch64ISD::FRSQRTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac51e55480048612eede3cb1b18513b22">llvm::AArch64ISD::FSQRT_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a05dd7344f5aef716731bf261a43f218c">llvm::AArch64ISD::FSUB_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9fb341bd2a710ddf055b0545efc68fc0">llvm::AArch64ISD::FTRUNC_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a7d73c0d4c5c8077d7c6e89e4c970714b">llvm::AArch64ISD::GET_SME_SAVE_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a7923f428f833cc997e1f5ecf0993f90e">llvm::AArch64ISD::GLD1_IMM_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a17e64b48fdac9928b6a0a092c5af7dc9">llvm::AArch64ISD::GLD1_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac8f6f034b1c865aa8e77ccaebda32218">llvm::AArch64ISD::GLD1_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a74b91234a131f53b9a68a9ca4cd26c87">llvm::AArch64ISD::GLD1_SXTW_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1e9d1eebf5bf9d4ff49ef45d7880e4ba">llvm::AArch64ISD::GLD1_SXTW_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19afa65635052abba7d2eb891eb24706af9">llvm::AArch64ISD::GLD1_UXTW_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad79b28d6740520761635d67c6c3c5dc9">llvm::AArch64ISD::GLD1_UXTW_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a3521337d037a29d43555c7ea1b96f75d">llvm::AArch64ISD::GLD1Q_INDEX_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a0bfe9e8819e5c1bfb6ab5515936a69ba">llvm::AArch64ISD::GLD1Q_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac11bd3bd817019b249d11d7f12aedd31">llvm::AArch64ISD::GLD1S_IMM_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9be68046aad6ca20ef30d451f3ab9eb5">llvm::AArch64ISD::GLD1S_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac1b72bf6c7bc204136030e0ae144f3de">llvm::AArch64ISD::GLD1S_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a558ddabda114cddf991cf8052babf0da">llvm::AArch64ISD::GLD1S_SXTW_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af263284586304c99345ed0c663ea2e3c">llvm::AArch64ISD::GLD1S_SXTW_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19acc129ce1cfc16e162528c86841b10e32">llvm::AArch64ISD::GLD1S_UXTW_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a5ca98fbce7ddde8900dfd68b03a5b76f">llvm::AArch64ISD::GLD1S_UXTW_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a94f47573b2939ef71e656156bc5cd991">llvm::AArch64ISD::GLDFF1_IMM_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aec4b3e29e4c750748f6eec345d2ecfe7">llvm::AArch64ISD::GLDFF1_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a0d5ecaf42b919f021d7f90a1b17d3d4e">llvm::AArch64ISD::GLDFF1_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a637b9743c971911cbd50d1f7205db274">llvm::AArch64ISD::GLDFF1_SXTW_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a33060aa53377821ae236cdcdc6234f21">llvm::AArch64ISD::GLDFF1_SXTW_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa63ddb8204981576c188ecd594ec388a">llvm::AArch64ISD::GLDFF1_UXTW_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a68588f7134c66b9586fa7ad3d9720258">llvm::AArch64ISD::GLDFF1_UXTW_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6702dc1bf5b9209ddf6d77196b38181e">llvm::AArch64ISD::GLDFF1S_IMM_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa631fe3aedf8ad98d00b72a60a83331b">llvm::AArch64ISD::GLDFF1S_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6860799327fcd8cec080e54dc44657ca">llvm::AArch64ISD::GLDFF1S_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a0a33fd3f562a7cd1aa496e8c99023e53">llvm::AArch64ISD::GLDFF1S_SXTW_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa9468a8cff4e6e8565df6264690cd325">llvm::AArch64ISD::GLDFF1S_SXTW_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa02c6d9794c8cb1e8ef9cbedd506e8a4">llvm::AArch64ISD::GLDFF1S_UXTW_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6cd3f502d5d40edc8c908a6dcea9502f">llvm::AArch64ISD::GLDFF1S_UXTW_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a658fff45ec5b54f450348d849379d5e7">llvm::AArch64ISD::GLDNT1_INDEX_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a148014182bdd341f262ef4d64969bb72">llvm::AArch64ISD::GLDNT1_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9bbaca23753c5b631bf9a62f3a730fe6">llvm::AArch64ISD::GLDNT1S_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6ee732dc403611ea57c638c36abde989">llvm::AArch64ISD::HADDS_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a0a20600fa3b8b7576ef1e7a16f0c8351">llvm::AArch64ISD::HADDU_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a22122a4f0234fbe3b44057ba8d742148">llvm::AArch64ISD::INDEX_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9e45b2b2b8505169eda1ba9272a908e2">llvm::AArch64ISD::INIT_TPIDR2OBJ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19afe73a33ffb540dcae45e6c1fcf2ae167">llvm::AArch64ISD::INSR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a71296993893d456da697d6a6e1c5c81b">llvm::AArch64ISD::LASTA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aceba80367c90c9597740f44793a920a5">llvm::AArch64ISD::LASTB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4e624e8cd76c2c489fc4a426687a5004">llvm::AArch64ISD::LD1_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a0b3f053c7801048ee58d05f6877995d0">llvm::AArch64ISD::LD1DUPpost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af9aa22215f868a0dcc94cf13bc459460">llvm::AArch64ISD::LD1LANEpost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9fb6eadbeea30022b1d1e4eb86494c38">llvm::AArch64ISD::LD1RO_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa3aa3cc3b66896fabee5c23c3f3c3f10">llvm::AArch64ISD::LD1RQ_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa98c8308b08e86e1e953f273207b0528">llvm::AArch64ISD::LD1S_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4a633f62fc41f2022fe2170031a65d0e">llvm::AArch64ISD::LD1x2post</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a28800ddf447359f84e24d7314ccb98de">llvm::AArch64ISD::LD1x3post</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1e3fbe83f867fe16454d9928afa4b29f">llvm::AArch64ISD::LD1x4post</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a68a32966ba07f4efbe2397915501622f">llvm::AArch64ISD::LD2DUPpost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19acffc300e996f001cf3bbbf1e25c7b974">llvm::AArch64ISD::LD2LANEpost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a611efefd07581a309272ce3604a444f1">llvm::AArch64ISD::LD2post</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a74c7f6579312bce1adcf3adf0f3ca33a">llvm::AArch64ISD::LD3DUPpost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aec77dff21e4270304e2569473d701994">llvm::AArch64ISD::LD3LANEpost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a10515cb929353e22ba15cf55d9d8b67a">llvm::AArch64ISD::LD3post</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9d12cf233445b196a30a2cb5e339b6dc">llvm::AArch64ISD::LD4DUPpost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a5323cab8ff6fd076ef57c895a0965f62">llvm::AArch64ISD::LD4LANEpost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa6617bab04266e3a038086c0e27fe5a0">llvm::AArch64ISD::LD4post</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a866e96767e66fab323aa11daa967334d">llvm::AArch64ISD::LDFF1_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a8e7f7012e9567f0e2a466ff0fa38753b">llvm::AArch64ISD::LDFF1S_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a45e4c2a81a1d0bc6e191eb1a11e41020">llvm::AArch64ISD::LDIAPP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac2a18bdf7917f763d050a81ab0762d91">llvm::AArch64ISD::LDNF1_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6824f40cd97f2889787f803af41de828">llvm::AArch64ISD::LDNF1S_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a3cabad4255ec575c6df049ad5c3c8568">llvm::AArch64ISD::LDNP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6c9a44d7fa618f0161949ff4d455db12">llvm::AArch64ISD::LDP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19adfb5f0cc680a060e5ca88e6e923d7183">llvm::AArch64ISD::LOADgot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a2af2841f081fa05b7343e785ac360633">llvm::AArch64ISD::LS64_BUILD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac22f87518ea997c68c74ba353797e025">llvm::AArch64ISD::LS64_EXTRACT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8fb469989985105371cdb192ac9a26f1">MAKE_CASE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a91a9a99c6c9977fcb422a33cedb64baa">llvm::AArch64ISD::MOVI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a56f30b92d605204b6d1e8f6736f5b45c">llvm::AArch64ISD::MOVIedit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4298c4f3218b85d0754a31c3bc49dd38">llvm::AArch64ISD::MOVImsl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a7eec025fe97bc08e06bd04b45390cbbc">llvm::AArch64ISD::MOVIshift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad0d9536662de9b7080a988a986f7ab1e">llvm::AArch64ISD::MRRS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a0767ec4421b5ce84bb44f55969d6bea8">llvm::AArch64ISD::MRS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a2486a390b5849a760c293a7aa8a569f8">llvm::AArch64ISD::MSRR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ace3d70db16ae903ef91f4848cf3c7485">llvm::AArch64ISD::MUL_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4b0056cc9bd2dd8caad14edf30f960a3">llvm::AArch64ISD::MULHS_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ab1654eebeb0da72fb694cad7ccc65836">llvm::AArch64ISD::MULHU_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19afb280860060c7afbb8c931e5ab7fade9">llvm::AArch64ISD::MVNImsl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa4493521473b54b2568fb53290007104">llvm::AArch64ISD::MVNIshift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4e506b3ba0ddd0fc4041cdd4656dee37">llvm::AArch64ISD::NEG_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a79512f79cb3d87ff14fd966207218ca5">llvm::AArch64ISD::NVCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6390897d4e079aa4d38ce5a5fd206b2b">llvm::AArch64ISD::ORRi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac239596aafdd24f4101f56f205fe8e7f">llvm::AArch64ISD::ORV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a52bd6aa1392a591e5727dfd0d0e880ba">llvm::AArch64ISD::PMULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a710b6a09ffa3675a809f5560d18eb69b">llvm::AArch64ISD::PREFETCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19adebd178a2fa65f2846ffe7985061b29c">llvm::AArch64ISD::PROBED_ALLOCA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa32899962a2e5c6828f51d4183e4a3a8">llvm::AArch64ISD::PTEST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a55a346ec47012d131cd5068a91bfd35e">llvm::AArch64ISD::PTEST_ANY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a83d0adb1d7f20d5a28003d08814e828a">llvm::AArch64ISD::PTRUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1f75be7ca0afb86d4ed6696a290d4b39">llvm::AArch64ISD::RDSVL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6ee026906ebb33819f0452450d5bc4ef">llvm::AArch64ISD::REINTERPRET_CAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9fe0a6fd20f3c4e41ce8cecbde8d06e8">llvm::AArch64ISD::RESTORE_ZA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a20a4c4ed442a366739eb8383950fa95e">llvm::AArch64ISD::RESTORE_ZT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a42e72f1d9f66fe07d466b88a92920c22">llvm::AArch64ISD::RET_GLUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19afae32e400e4bc01cc4673f48e856472d">llvm::AArch64ISD::REV16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a44e0c654278b7245da534b69f2a290a3">llvm::AArch64ISD::REV32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a227cc47204e0e6af51133e52dbda3cad">llvm::AArch64ISD::REV64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a111ab9bf74b48fddceb457cbe3d9b2b2">llvm::AArch64ISD::REVD_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a2b59bac19683a082e19a41340bfd7be0">llvm::AArch64ISD::REVH_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a2b9e9a63926146d3d7d738850ac2e402">llvm::AArch64ISD::REVW_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a06dadc5c6f83ab133efe7d629fa0ce54">llvm::AArch64ISD::RHADDS_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a472127f5c49ffe5d374d554b6fb69252">llvm::AArch64ISD::RHADDU_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae932a885fc5b27453c0530e88c4363b0">llvm::AArch64ISD::RSHRNB_I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19afda36640e88b2cdaef1df445d425b4a9">llvm::AArch64ISD::SADDLP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad112f423ccad26e1e2802c343f2c4d90">llvm::AArch64ISD::SADDLV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a3390d467679dbd70e70dab4d9b89fdd7">llvm::AArch64ISD::SADDV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1b407df6fb5622c341022152b51143e6">llvm::AArch64ISD::SADDV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a63c6337ab1a4098be3b02a65477f4c5c">llvm::AArch64ISD::SADDWB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af8d0dfb8e455b848875a7c0c87cbf851">llvm::AArch64ISD::SADDWT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1748c672ccffe764a0bcc1fdfe16c9f6">llvm::AArch64ISD::SAVE_ZT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a3e0f0bc95b04d7de664c53bb98ec888b">llvm::AArch64ISD::SBC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a3ce7d4f224730b380e96d3e674ef269c">llvm::AArch64ISD::SBCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a69fe576c392c2f7ac25f62a38d5b5fc9">llvm::AArch64ISD::SDIV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a602b2e270a81071e70ed8e06d9a715b2">llvm::AArch64ISD::SDOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac148c71eaed20be4b9ea132008532d8d">llvm::AArch64ISD::SETCC_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a981ab95d67a836e9429e0e630293a927">llvm::AArch64ISD::SHL_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa560a9bc62116f8349176c8303745d0b">llvm::AArch64ISD::SIGN_EXTEND_INREG_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad72f64d0c5da384ad511761d2c9d43f0">llvm::AArch64ISD::SINT_TO_FP_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6a32a9de2d68106613af27a4b5287b08">llvm::AArch64ISD::SITOF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6294f6cf79e63b6c350709ec5548e4e5">llvm::AArch64ISD::SMAX_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19acf7722d737cd958a55d56d66b37b1d0a">llvm::AArch64ISD::SMAXV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a226820ffad10c7875d1595c4863135fc">llvm::AArch64ISD::SMAXV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ab691f36326443f587301f2e094d9d941">llvm::AArch64ISD::SME_ZA_LDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9d2511e25a56a5cae1526e6cc7917221">llvm::AArch64ISD::SME_ZA_STR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a14342e3e6a442d9ecebef1bae5f148a8">llvm::AArch64ISD::SMIN_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4e18ab55d69c25d612218c79b2085610">llvm::AArch64ISD::SMINV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a7cab9fec71264bcc17aa00de077beb8f">llvm::AArch64ISD::SMINV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a195e0238576389dfb91a8610b0e881d2">llvm::AArch64ISD::SMSTART</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19afa0e42f3d1f5a26bbf63a2e6ad1125ca">llvm::AArch64ISD::SMSTOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a088ad415e58a6fbb41ded8063e26bca6">llvm::AArch64ISD::SMULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a210b1c8a403932ae546ed0b54128cdda">llvm::AArch64ISD::SPLICE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a73276e2beba77ee68e34de9f315b1dbb">llvm::AArch64ISD::SQSHL_I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a60ba9419992364c7fa566dbe626f91b0">llvm::AArch64ISD::SQSHLU_I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1b64a920259075393097452bf7a007bf">llvm::AArch64ISD::SRA_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af4a48a9cc4383907e6a5d4bc64decb49">llvm::AArch64ISD::SRAD_MERGE_OP1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ab191c27a034857539bdaa17d122c8523">llvm::AArch64ISD::SRL_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a22c1b5a92aba9ebf969a2f0235b9094c">llvm::AArch64ISD::SRSHR_I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a85ed05e5b6525f68f560aeec26360a9f">llvm::AArch64ISD::SST1_IMM_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a228badaf4ea8fc1855e346884210a40f">llvm::AArch64ISD::SST1_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4c18de870cd5cdb48d13c2554dbe975e">llvm::AArch64ISD::SST1_SCALED_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a63629e520272560bfaa91072ced436db">llvm::AArch64ISD::SST1_SXTW_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aee81f3a7f92882048ae759626cce52fc">llvm::AArch64ISD::SST1_SXTW_SCALED_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19adb25d74321dce9c4a69412fd849e6709">llvm::AArch64ISD::SST1_UXTW_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a31c76b6e0b307a491e2064bdaa55e16d">llvm::AArch64ISD::SST1_UXTW_SCALED_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad1c18847191322766d77b00a67708c9d">llvm::AArch64ISD::SST1Q_INDEX_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a58d30483f428219ebfd40e279db19942">llvm::AArch64ISD::SST1Q_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac59023c7b0b3c6f3fa7ff35406ebe37e">llvm::AArch64ISD::SSTNT1_INDEX_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac790946c00d53a027bcd49843379fb21">llvm::AArch64ISD::SSTNT1_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a8c086cd580aa6cfe36c410ac0eaecffe">llvm::AArch64ISD::ST1_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a5d2518cc25a5983068164109fdd92691">llvm::AArch64ISD::ST1x2post</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a5b1de6bb4e7f7e0cf389ba2f258066e2">llvm::AArch64ISD::ST1x3post</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6d588334989b7663c1d0cdbbbf209f15">llvm::AArch64ISD::ST1x4post</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a293600b79057550d0e087a9aa8be097d">llvm::AArch64ISD::ST2G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a08ec19f37da502bfd936951a14f678c4">llvm::AArch64ISD::ST2LANEpost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ab094a6a98cc4e55bec227f809503a184">llvm::AArch64ISD::ST2post</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a677e79b3b0d2d9969f84dfc567683f2b">llvm::AArch64ISD::ST3LANEpost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a95de67e2367d3060cb2336a6805e48cb">llvm::AArch64ISD::ST3post</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a8f9b927f69d51deab20e1da9cf296300">llvm::AArch64ISD::ST4LANEpost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1a8fa2bbc5e58ecdb4d5405c52165959">llvm::AArch64ISD::ST4post</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa931d46bc7be6ffc74d0673d26fd4b86">llvm::AArch64ISD::STG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9b6a5a5ff693c2554a05274a8107506c">llvm::AArch64ISD::STILP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a7ebbef8c7398740fa451f47dd77fbd58">llvm::AArch64ISD::STNP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a05487d4f8bc52d52005b9f3ccfe9556d">llvm::AArch64ISD::STP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae2e012d1717a5485a8723c1372f0a0ce">llvm::AArch64ISD::STRICT_FCMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ab7831d4deb75f0578e943637e29477ee">llvm::AArch64ISD::STRICT_FCMPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a84ae19f2bf01a162207d82a39b1ba230">llvm::AArch64ISD::STZ2G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad4cde0015d3454bacad2b4d1669608f0">llvm::AArch64ISD::STZG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19acdc788ad7d0ba7ecc3806c90b39b46ff">llvm::AArch64ISD::SUBS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad97a96707d208382bc33f77bbe9f9edd">llvm::AArch64ISD::SUNPKHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aca0f8df53ae7a68829ef5100ee8e133a">llvm::AArch64ISD::SUNPKLO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a80d287373eef2e8f8a71d40c853afb75">llvm::AArch64ISD::SVE_LD2_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a740628cb5637cb8afc89ee4fe2cbaf7a">llvm::AArch64ISD::SVE_LD3_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ab170dcf429997433e64e079c98657d75">llvm::AArch64ISD::SVE_LD4_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4cd6678c26ce1ff7c0b0fab8b53707c9">llvm::AArch64ISD::TBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a31e3eddf628ce0ce1ab1624e731ee92b">llvm::AArch64ISD::TBNZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa7d178f513996b738fea26d693c54e9a">llvm::AArch64ISD::TBZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a0c096147ce35f351a1d0876af1c61501">llvm::AArch64ISD::TC_RETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad25be6e24e6b7104abbf0660c96589e8">llvm::AArch64ISD::THREAD_POINTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af7afca2e2aa18122be22935ca2986ad5">llvm::AArch64ISD::TLSDESC_AUTH_CALLSEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a7053d31b0e2ad10afa17f7cf4332b40b">llvm::AArch64ISD::TLSDESC_CALLSEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a0ad2c68321ce87aa1ddfecd5db5620a8">llvm::AArch64ISD::TRN1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a568bdb1eb9c9d07c9baa011b76a97b06">llvm::AArch64ISD::TRN2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a910ab243c66c6b15ec6db4768b7ea871">llvm::AArch64ISD::UADDLP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aefb2386076002c124b7f4ecc8949ab91">llvm::AArch64ISD::UADDLV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a433c4e85025f39985b0e259cbf6f95ed">llvm::AArch64ISD::UADDV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a8368d7899d9217339a7e13fa3b7dc29e">llvm::AArch64ISD::UADDV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa0008165bc327e2a955dc5c33ebabe07">llvm::AArch64ISD::UADDWB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a83dc1c5f075d4e60118e4f1ca1bc2211">llvm::AArch64ISD::UADDWT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a71288440df1a68bef426732d7bfe6606">llvm::AArch64ISD::UDIV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad96eeee7eab7d3e204af2c4cc2f3f28a">llvm::AArch64ISD::UDOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a45614e13bc7af6996cacd17ad8a0e829">llvm::AArch64ISD::UINT_TO_FP_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a107e9a4d70948139aa83c61738c101c3">llvm::AArch64ISD::UITOF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19afa3fac889eef5ac98a58aa3e11f21425">llvm::AArch64ISD::UMAX_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1267fa1fba459cdc29d3291f477f2050">llvm::AArch64ISD::UMAXV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af368614239dc9c9128bd40dd311092b8">llvm::AArch64ISD::UMAXV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a2fc0cbcf497c726edd333d5c9b0059a8">llvm::AArch64ISD::UMIN_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a232dbb219a38c392daad50613ed1958e">llvm::AArch64ISD::UMINV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad4727f1a13490b87d6c32c6bae2f0a3b">llvm::AArch64ISD::UMINV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae9765ad45095f8a38ed3c365c8b8039a">llvm::AArch64ISD::UMULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1deab4f18a0ec0ad579affbd7e5014dc">llvm::AArch64ISD::UQSHL_I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19abcf28dc2b8c571927124b7d94e5d0003">llvm::AArch64ISD::URSHR_I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad8c685c545945926c56f84910d693898">llvm::AArch64ISD::URSHR_I_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa065b2acf229c3ebfd2af7b406a1abba">llvm::AArch64ISD::USDOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a001f62f9f1eca066cc571960f52dc564">llvm::AArch64ISD::UUNPKHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa5f5eaa830a51e606a1a5749dea7f297">llvm::AArch64ISD::UUNPKLO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4db23bc2ed0cc6a04a5c5d11bb45235f">llvm::AArch64ISD::UZP1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a8aec775bf28196c442cf229cd43db2e3">llvm::AArch64ISD::UZP2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a794f9f6bbb4013df844fce71137cb255">llvm::AArch64ISD::VASHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9437be4c74c2ffdb174275e894a7c634">llvm::AArch64ISD::VG_RESTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a62f802d67d2c02b27555a6a737b955e9">llvm::AArch64ISD::VG_SAVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4318caf60a3c8fb3a95e336e55457763">llvm::AArch64ISD::VLSHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19afb30ccc51f3686858a621b86f7171087">llvm::AArch64ISD::VSHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6d52931686af9b030c3cacbaf6708331">llvm::AArch64ISD::VSLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a77430d9bb48aa864b70bdf019101c653">llvm::AArch64ISD::VSRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a2bac403076acbbf971d9213895e49c4f">llvm::AArch64ISD::WrapperLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a74402c4f59142fad82137878d3d7b41e">llvm::AArch64ISD::ZERO_EXTEND_INREG_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a574234144ef4f4e0115d0ef71a4efd80">llvm::AArch64ISD::ZIP1</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a58511b67177595581d8f94facb3565fe">llvm::AArch64ISD::ZIP2</a>.</p>

</div>
</div>

### getTgtMemIntrinsic() {#a798a85d56b9dc609e615130607563819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::getTgtMemIntrinsic (<a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/intrinsicinfo">IntrinsicInfo</a> &amp; Info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned Intrinsic)</td>
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


<p>Declaration at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a210ba6b43ba451b698857dd9de71bd15">llvm::EVT::getVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a56bb53e2d0b01c78c8c538f903fd45b8">llvm::MVT::getVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda8d09c51969b0954512ed65ee26551081">llvm::MachineMemOperand::MONonTemporal</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda796891d6ca349b671fce24b6d01d77a8">llvm::MachineMemOperand::MOVolatile</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a430025e146710444567fa8bd1da2d3a9">setInfoSVEStN</a> and <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a031e3abd6e1a18f9462f7cee212ba004a33f7f25590a5334874e8a114e6f5e55f">llvm::MemoryLocation::UnknownSize</a>.</p>

</div>
</div>

### getVaListSizeInBits() {#a205e757ebb66d5477f9ec152d6adcf8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64TargetLowering::getVaListSizeInBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Returns the size of the platform's va_list object.</p>

<p>Declaration at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#aa11502fbc6bf582057507658bd9682a9">getPointerTy</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>.</p>

</div>
</div>

### getVectorTypeBreakdownForCallingConv() {#ac477f229337de92be9c48dae99bf5546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64TargetLowering::getVectorTypeBreakdownForCallingConv (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> &amp; IntermediateVT, unsigned &amp; NumIntermediates, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; RegisterVT)</td>
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

<p>Certain targets such as MIPS require that some types such as vectors are always broken down into scalars in some contexts.</p>


<p>This occurs even if the vector type is legal.</p>


<p>Declaration at line 1022 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29953 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a874fbbec4937797974c9d5056769421a">llvm::MVT::getFixedSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af344c6bd2d070c999525df85be7688cf">llvm::TargetLoweringBase::getRegisterType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a5b806e2538d0e91175d970c8232a3099">llvm::TargetLoweringBase::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a210ba6b43ba451b698857dd9de71bd15">llvm::EVT::getVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a98049e07856ff1288295bc58e232518b">llvm::MVT::isFixedLengthVector</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>


<p>Referenced by <a href="#a3f4445d350e1253b4c05ab25011d766d">getNumRegistersForCallingConv</a> and <a href="#a0f1ad23af20c2a0b3e3f5c0a995c1969">getRegisterTypeForCallingConv</a>.</p>

</div>
</div>

### hasAndNot() {#aa69a30633eb175372a93a42bfc5d89f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64TargetLowering::hasAndNot (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> X)</td>
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

<p>Return true if the target has a bitwise and-not operation: X = ~A &amp; B This can be used to simplify select or other instructions.</p>

<p>Definition at line 869 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="#a17675bf9596afe087d90140ef0e52485">hasAndNotCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### hasAndNotCompare() {#a17675bf9596afe087d90140ef0e52485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64TargetLowering::hasAndNotCompare (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Y)</td>
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


<p>Definition at line 864 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>


<p>Referenced by <a href="#aa69a30633eb175372a93a42bfc5d89f2">hasAndNot</a>.</p>

</div>
</div>

### hasInlineStackProbe() {#a58613f0e5460e846c1753949ec0d8aff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::hasInlineStackProbe (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>True if stack clash protection is enabled for this functions.</p>

<p>Declaration at line 1029 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 30019 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a2be9d35aaace9716441da5714f048af9">llvm::AArch64FrameLowering::canUseAsPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a27a80b2fc0f8820ecab9d99312bb4607">llvm::AArch64FrameLowering::eliminateCallFramePseudoInstr</a>.</p>

</div>
</div>

### hasPairedLoad() {#acb51326eb72adb30e442667892c1f5ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::hasPairedLoad (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp;)</td>
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

<p>Return true if the target supplies and combines to a paired load two loaded values of type LoadedType next to each other in memory.</p>


<p>RequiredAlignment gives the minimal alignment constraints that must be met to be able to select this paired load.</p>


<p>This information is <em>not</em> used to generate actual paired loads, but it is used to generate a sequence of loads that is easier to combine into a paired load. For instance, something like this: a = load i64* addr b = trunc i64 a to i32 c = lshr i64 a, 32 d = trunc i64 c to i32 will be optimized into: b = load i32* addr1 d = load i32* addr2 Where addr1 = addr2 +/- sizeof(i32).</p>


<p>In other words, unless the target performs a post-isel load combining, this information should not be provided because it will generate more loads.</p>


<p>Declaration at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17011 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3cb888a2ce8e95e0d9769687a5e2f7d8">llvm::EVT::isFloatingPoint</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>.</p>

</div>
</div>

### initializeSplitCSR() {#a15bcdc727d8a841f1bc89a276b7eab72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::initializeSplitCSR (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Entry)</td>
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


<p>Declaration at line 925 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28079 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a538aa174513553563cbd28d78b7222df">llvm::AArch64FunctionInfo::setIsSplitCSR</a>.</p>

</div>
</div>

### insertCopiesSplitCSR() {#a23393317cdaeed97903d191dcc6c84f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::insertCopiesSplitCSR (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Entry, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; Exits)</td>
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


<p>Declaration at line 926 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28085 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### insertSSPDeclarations() {#a859081e342a8a97b3648873ae3df252d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::insertSSPDeclarations (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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


<p>Declaration at line 831 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27976 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncallee/#ac5d8da677233fa2e1e7039508ed56e0e">llvm::FunctionCallee::getCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af3e31a71f6d0e55d41956d5b20ed7989">llvm::TargetLoweringBase::insertSSPDeclarations</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae41511c1ad4197da36cef403f34bac72">llvm::CallingConv::Win64</a>.</p>

</div>
</div>

### isAllActivePredicate() {#ae7774721462886f7e79d72a94a121721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isAllActivePredicate (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 986 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29658 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isCheapToSpeculateCtlz() {#aa9e23630139a36d636d43c0084ed4c85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64TargetLowering::isCheapToSpeculateCtlz (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Definition at line 858 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>

</div>
</div>

### isCheapToSpeculateCttz() {#aa15ed7ca8d8275ec7a500744af929f25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64TargetLowering::isCheapToSpeculateCttz (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Definition at line 854 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>

</div>
</div>

### isComplexDeinterleavingOperationSupported() {#acaa6c3509bbddcd993aeec7334361c9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isComplexDeinterleavingOperationSupported (<a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764">ComplexDeinterleavingOperation</a> Operation, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Declaration at line 913 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29758 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a499d32d25a946dc992b9b13e2941a2a5">llvm::CDot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a5b2aa9d3f9f3a7b2d123fef7c5328b8f">Operation</a>.</p>

</div>
</div>

### isComplexDeinterleavingSupported() {#a8f7195ae01dbf398aa952b18f7ac28b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isComplexDeinterleavingSupported ()</td>
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

<p>Declaration at line 912 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29753 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### isDesirableToCommuteWithShift() {#aecbd41e7754d9ca4d664dfa0d9df8510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isDesirableToCommuteWithShift (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7a">CombineLevel</a> Level)</td>
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

<p>Returns false if N is a bit extraction pattern of (X &gt;&gt; C) &amp; Mask.</p>

<p>Declaration at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17928 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ac969b6c833cfa44c1b4fcd5790268340">llvm::SDValue::getConstantOperandVal</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a295d0b84f4e63438c0edb0021c41d47a">llvm::SDNode::hasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82a9558b6319303ae62f59dab9669685">llvm::isMask_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>.</p>

</div>
</div>

### isDesirableToCommuteXorWithShift() {#aec5f3889dfe7e8587557d1addb3a367c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isDesirableToCommuteXorWithShift (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Returns false if N is a bit extraction pattern of (X &gt;&gt; C) &amp; Mask.</p>

<p>Declaration at line 773 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>.</p>

</div>
</div>

### isDesirableToPullExtFromShl() {#ab7385539857df582900994505040ae3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64TargetLowering::isDesirableToPullExtFromShl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>GlobalISel - return true if it's profitable to perform the combine: shl ([sza]ext x), y =&gt; zext (shl x, y)</p>

<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isExtractSubvectorCheap() {#ae1f54fa7a42bfe0913b9fe2e869a958c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isExtractSubvectorCheap (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ResVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SrcVT, unsigned Index)</td>
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

<p>Declaration at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 18055 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a53fb11c0140efce7e25ca9ff5ccbac96">llvm::EVT::getVectorMinNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa93fbbc66d52a51d178af8ac4398ec05">llvm::TargetLoweringBase::isOperationLegalOrCustom</a>.</p>

</div>
</div>

### isFMAFasterThanFMulAndFAdd() {#aa5bf9253e7424a041215974fc5696ac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isFMAFasterThanFMulAndFAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if an FMA operation is faster than a pair of fmul and fadd instructions.</p>


<p>fmuladd intrinsics will be expanded to FMAs when this method returns true, otherwise fmuladd is expanded to fmul + fadd.</p>


<p>Declaration at line 749 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17874 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>


<p>Referenced by <a href="#a9d2e61bef8fbdb714e9f0a739bf49a58">isProfitableToHoist</a>.</p>

</div>
</div>

### isFMAFasterThanFMulAndFAdd() {#a7e54ea4387c8bf1f3d8c5ebfb563c222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isFMAFasterThanFMulAndFAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *)</td>
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

<p>Declaration at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17894 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>.</p>

</div>
</div>

### isFPImmLegal() {#a0b5597ce1a7049500d0b30bef14951ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isFPImmLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>, bool ForCodeSize)</td>
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


<p>Declaration at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 12005 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-imm/#a77a4e6615fbc6c2bbcf179370dbd0fa9">llvm::AArch64_IMM::expandMOVImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#ab23f031bf813c9284ac27776b414a867">llvm::AArch64_AM::getFP16Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a5d1d3c98268fd4f6017b99e4bd9415ed">llvm::AArch64_AM::getFP32Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#aa3b818e0d89b7804a311b48c18080a4f">llvm::AArch64_AM::getFP64Imm</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### isIntDivCheap() {#a494cbaa147365ad6fd75c3bb3297c8bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isIntDivCheap (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> Attr)</td>
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

<p>Return true if integer divide is usually cheaper than a sequence of several shifts, adds, and multiplies for this target.</p>


<p>The definition of "cheaper" may depend on whether we're optimizing for speed or for size.</p>


<p>Declaration at line 849 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a61054ea97168f709c1e46345f80c16a3">llvm::AttributeList::hasFnAttr</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### isLegalAddImmediate() {#ad37b1f031f487d6e69553ec06518c219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isLegalAddImmediate (int64_t)</td>
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

<p>Return true if the specified immediate is legal add immediate, that is the target has add instructions which can add a register with the immediate without having to materialize the immediate into a register.</p>

<p>Declaration at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17695 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#a2789f36b6ade6b507b2fb7cf6e4f49e9">getPreferredLargeGEPBaseOffset</a>, <a href="#a5c0904d6c43a3efd717031d09178dcc3">isLegalICmpImmediate</a> and <a href="#af8e97755935ce2a3c03a0ba055b310c2">isMulAddWithConstProfitable</a>.</p>

</div>
</div>

### isLegalAddressingMode() {#ae854a8e8c09efe0960eaae718304b77d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isLegalAddressingMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode">AddrMode</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned AS, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
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

<p>Return true if the addressing mode represented by AM is legal for this target, for a load/store of the specified type.</p>


<p>isLegalAddressingMode - Return true if the addressing mode represented by AM is legal for this target, for a load/store of the specified type.</p>


<p>Declaration at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17779 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a2d775e3fd8ebcd0941d1e12cbfccda3d">llvm::TargetLoweringBase::AddrMode::BaseGV</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a115ffe6d615735fbe8b1bf31877565ba">llvm::TargetLoweringBase::AddrMode::BaseOffs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8868c35de6c36dc0d57e84f256c4ffde">llvm::TargetLoweringBase::AddrMode::HasBaseReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#aac5d77356a7fa4c176fd2835f8fb00cb">llvm::TargetLoweringBase::AddrMode::ScalableOffset</a> and <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8ea7d02f0e4b0c1d37d6986ec9f7f5c0">llvm::TargetLoweringBase::AddrMode::Scale</a>.</p>

</div>
</div>

### isLegalAddScalableImmediate() {#a7adb0b5b92d80f462efda5c7f99b9077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isLegalAddScalableImmediate (int64_t)</td>
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

<p>Return true if adding the specified scalable immediate is legal, that is the target has add instructions which can add a register with the immediate (multiplied by vscale) without having to materialize the immediate into a register.</p>

<p>Declaration at line 723 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17710 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>.</p>

</div>
</div>

### isLegalICmpImmediate() {#a5c0904d6c43a3efd717031d09178dcc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isLegalICmpImmediate (int64_t)</td>
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

<p>Return true if the specified immediate is legal icmp immediate, that is the target has icmp instructions which can compare a register against the immediate without having to materialize the immediate into a register.</p>

<p>Declaration at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17773 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="#ad37b1f031f487d6e69553ec06518c219">isLegalAddImmediate</a>.</p>

</div>
</div>

### isLegalInterleavedAccessType() {#a85764bb37db07737ed0058c352f4c3b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isLegalInterleavedAccessType (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VecTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, bool &amp; UseScalable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">VecTy</span> is a legal interleaved access type.</p>


<p>This function checks the vector element type and the overall width of the vector.</p>


<p>Declaration at line 951 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17042 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a59632c5deb0423a518ad984bdd04d41f">llvm::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a431a33f5942795512f2984bc30aa4c41">llvm::getSVEPredPatternFromNumElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>.</p>


<p>Referenced by <a href="#ac66d3f15510c7402f2a85a87c69f1603">lowerDeinterleaveIntrinsicToLoad</a>, <a href="#a6cbcd096f254563525e65e58557ed901">lowerInterleavedLoad</a>, <a href="#aa4094e6b2a8203e5c8b67ecf186d51a9">lowerInterleavedStore</a> and <a href="#ac2d9e284d06499be56d61b876e86dc8a">lowerInterleaveIntrinsicToStore</a>.</p>

</div>
</div>

### isMaskAndCmp0FoldingBeneficial() {#a9a2764d23b64e6bb68a0025d4eab6b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isMaskAndCmp0FoldingBeneficial (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; AndI)</td>
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


<p>Declaration at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28043 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>

</div>
</div>

### isMulAddWithConstProfitable() {#af8e97755935ce2a3c03a0ba055b310c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isMulAddWithConstProfitable (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> AddNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ConstNode)</td>
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


<p>Declaration at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17745 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-imm/#a77a4e6615fbc6c2bbcf179370dbd0fa9">llvm::AArch64_IMM::expandMOVImm</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a74b17cf9d0ee8268a5b38bbb896a30ba">llvm::ConstantSDNode::getAPIntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a75d113cb1b8cc3c14b601d928dccee40">llvm::ConstantSDNode::getSExtValue</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="#ad37b1f031f487d6e69553ec06518c219">isLegalAddImmediate</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### isOffsetFoldingLegal() {#ab8512586d0b4ed30ba87cc919f0cfec5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isOffsetFoldingLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * GA)</td>
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


<p>Declaration at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11998 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### isOpSuitableForLDPSTP() {#ace4241dfdb194e5c81c875b5be782213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isOpSuitableForLDPSTP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27612 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a62ca2fe454c98ca30dd17d0b37ba3534">shouldExpandAtomicLoadInIR</a>, <a href="#ab5564f8fe97e73dd2f2cb8a76bbd3474">shouldExpandAtomicStoreInIR</a> and <a href="#ab1d674bbe9aa52ee2ee2d2a3b6442e33">shouldInsertFencesForAtomic</a>.</p>

</div>
</div>

### isOpSuitableForLSE128() {#a6b0a106d77d380a71597433b5ac286ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isOpSuitableForLSE128 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27627 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a660a31179bfecd737a256372e5fd6122">llvm::AtomicRMWInst::And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5954f59053121b87ebe0c5fe79942c6e">llvm::AtomicRMWInst::Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77">llvm::AtomicRMWInst::Xchg</a>.</p>


<p>Referenced by <a href="#ab5564f8fe97e73dd2f2cb8a76bbd3474">shouldExpandAtomicStoreInIR</a> and <a href="#ab1d674bbe9aa52ee2ee2d2a3b6442e33">shouldInsertFencesForAtomic</a>.</p>

</div>
</div>

### isOpSuitableForRCPC3() {#a9f1799dbf712799df049d22347e1362e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isOpSuitableForRCPC3 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 808 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27649 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>.</p>


<p>Referenced by <a href="#a62ca2fe454c98ca30dd17d0b37ba3534">shouldExpandAtomicLoadInIR</a>, <a href="#ab5564f8fe97e73dd2f2cb8a76bbd3474">shouldExpandAtomicStoreInIR</a> and <a href="#ab1d674bbe9aa52ee2ee2d2a3b6442e33">shouldInsertFencesForAtomic</a>.</p>

</div>
</div>

### isProfitableToHoist() {#a9d2e61bef8fbdb714e9f0a739bf49a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isProfitableToHoist (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if it is profitable to hoist instruction in then/else to if.</p>


<p>Not profitable if I and it's user can form a FMA instruction because we prefer FMSUB/FMADD.</p>


<p>Declaration at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16586 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fpopfusion/#a9c71bae9f02af273833fde586d529fc5aa9dfaae1f5b7d4ebb31ccf9aee1aacce">llvm::FPOpFusion::Fast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a126c61d55fb4d2e509537ce68e8b6400">llvm::TargetLoweringBase::getValueType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aa5bf9253e7424a041215974fc5696ac8">isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa93fbbc66d52a51d178af8ac4398ec05">llvm::TargetLoweringBase::isOperationLegalOrCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

### isReassocProfitable() {#ab2c86e7c50d41494cc2acb0f1f3ba23c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isReassocProfitable (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N1)</td>
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

<p>Control the following reassociation of operands: (op (op x, c1), y) -&gt; (op (op x, y), c1) where N0 is (op x, c1) and N1 is y.</p>

<p>Declaration at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 7729 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a62766c75f88612ffa652342472e755f6">getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a342c0d4e8e59b30daefe9a05bc2098bd">llvm::SDValue::hasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a088ad415e58a6fbb41ded8063e26bca6">llvm::AArch64ISD::SMULL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae9765ad45095f8a38ed3c365c8b8039a">llvm::AArch64ISD::UMULL</a>.</p>

</div>
</div>

### isShuffleMaskLegal() {#a1c7cb6b368ef7cba8da95f1f11ed4fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isShuffleMaskLegal (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; M, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if the given shuffle mask can be codegen'd directly, or if it should be stack expanded.</p>

<p>Declaration at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 15549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6449d059cd582a222190ee1d70639936">llvm::getPerfectShuffleCost</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6db1f207286bd8bc6a978593a55955e9">llvm::EVT::is128BitVector</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#afa40b0ea2c1858e1e297227cc17d77db">llvm::EVT::is64BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a016f7b15a2e335153beb2421ac622ce5">isConcatMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9ebdafbae1fdc29135b25d537a89cd61">isEXTMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5db00b480bde7c4005a6d9091b8648d2">isINSMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83f67cbf085fcd2c92b4e126c42c779e">llvm::isREVMask</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#a00abad87897a8bf77c53b38666451400">llvm::ShuffleVectorSDNode::isSplatMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad1476240ebd4bc1b48535567993515fb">isTRN_v_undef_Mask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3557bd5bf8d46a334181220040a54407">llvm::isTRNMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3b5254c39b86764ce2ca093701342756">isUZP_v_undef_Mask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a80b0675ed4d93b3ed0728f977e2b75ae">llvm::isUZPMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af9d6419fc209e6d03e89a3bb8b3675a6">isZIP_v_undef_Mask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa8285681750cd2e7633f8737a8e45bf5">llvm::isZIPMask</a> and <a href="#afa8bfec034d066ec24d18d3fd76ac590">useSVEForFixedLengthVectorVT</a>.</p>


<p>Referenced by <a href="#ad5676e13b5fb0a05c7a58b70f335ae7c">isVectorClearMaskLegal</a> and <a href="#a94825933fbeecbda802a1c22c46a524d">ReconstructShuffle</a>.</p>

</div>
</div>

### isTruncateFree() {#a01cb590e9c05c3675fe75693d84b3120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isTruncateFree (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * FromTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ToTy)</td>
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


<p>Declaration at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>.</p>

</div>
</div>

### isTruncateFree() {#a3ee90d2d8bdc505c6422560cd54d4a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isTruncateFree (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT1, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT2)</td>
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



<p>Declaration at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16575 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a7712dd4392b7eb944b709ac8442634d9">llvm::EVT::getFixedSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### isTypeDesirableForOp() {#a7a4450c23fda81ec84bce1eed78f67d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isTypeDesirableForOp (unsigned Opc, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if the target has native support for the specified value type and it is 'desirable' to use the type for the given node type.</p>

<p>Declaration at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 30025 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7c66bde62e1fbe747611b8d385ad6c9a">llvm::TargetLowering::isTypeDesirableForOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af78365e835dbc10df18c1cd5d8853fd0">llvm::ISD::TRUNCATE_SSAT_S</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a694c9a71596643f6ddd4ee767666cf43">llvm::ISD::TRUNCATE_SSAT_U</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af81ec85e716e986c5555135612f62b29">llvm::ISD::TRUNCATE_USAT_U</a>.</p>

</div>
</div>

### isVectorClearMaskLegal() {#ad5676e13b5fb0a05c7a58b70f335ae7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isVectorClearMaskLegal (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; M, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Similar to isShuffleMaskLegal.</p>


<p>Return true is the given 'select with zero' shuffle mask can be codegen'd directly.</p>


<p>Declaration at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 15582 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="#a1c7cb6b368ef7cba8da95f1f11ed4fc0">isShuffleMaskLegal</a>.</p>

</div>
</div>

### isVScaleKnownToBeAPowerOfTwo() {#a6e9dd7ae294939f7a90d9dc64148ddc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64TargetLowering::isVScaleKnownToBeAPowerOfTwo ()</td>
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

<p>Return true only if vscale must be a power of two.</p>

<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>

</div>
</div>

### isZExtFree() {#a9140f89a634da6fe469d0faa0843a976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isZExtFree (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * FromTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ToTy)</td>
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

<p>Return true if any actual instruction that defines a value of type FromTy implicitly zero-extends the value to ToTy in the result register.</p>


<p>The function should return true when it is likely that the truncate can be freely folded with an instruction defining a value of FromTy. If the defining instruction is unknown (because you're looking at a function argument, PHI, etc.) then the target may require an explicit truncate, which is not necessarily free, but this function does not deal with those cases. Targets must return false when FromTy &gt;= ToTy.</p>


<p>Declaration at line 698 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16612 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>.</p>


<p>Referenced by <a href="#ac7b70a67bb5d182866c5485835286509">isZExtFree</a>.</p>

</div>
</div>

### isZExtFree() {#a02e65e6f505c44832bf833b385e51ba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isZExtFree (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT1, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT2)</td>
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



<p>Declaration at line 699 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16619 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### isZExtFree() {#ac7b70a67bb5d182866c5485835286509}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isZExtFree (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT2)</td>
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

<p>Declaration at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16627 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="#a9140f89a634da6fe469d0faa0843a976">isZExtFree</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>.</p>

</div>
</div>

### lowerDeinterleaveIntrinsicToLoad() {#ac66d3f15510c7402f2a85a87c69f1603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; DeinterleaveValues)</td>
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

<p>Lower a deinterleave intrinsic to a target specific load intrinsic.</p>


<p>Return true on success. Currently only supports llvm.vector.deinterleave2</p>


<p><span class="doxyComputerOutput">LI</span> is the accompanying load instruction. <span class="doxyComputerOutput">DeinterleaveValues</span> contains the deinterleaved values.</p>


<p>Declaration at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17496 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73e0482b96d9d0cdfcc90c0a34f5b0db">llvm::IRBuilderBase::CreateGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a28d8fda3ddcb508d0b669cda059ccd4d">llvm::IRBuilderBase::CreateInsertVector</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a40ed7274ff11f079e5b5eae34c818c51">llvm::IRBuilderBase::CreateVectorSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ae7510a639ca53c1bfa1c90c6dfc7eb2e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::divideCoefficientBy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#af7dca9a9e816ef69fd9e9467f64f72b4">llvm::Value::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#abcbe492bce3ccc16e0bbb50292576c5c">llvm::Module::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a59632c5deb0423a518ad984bdd04d41f">llvm::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73f286a780fbb8c82c0a8574540719ea">llvm::IRBuilderBase::getInt64</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a>, <a href="#a365f29ab21721393fe82ff3ae4554e5e">getNumInterleavedAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2d1ff28d6923802e165905b8d1766e76">llvm::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a945c21ff70f310de538153db17e7b857">llvm::LoadInst::getPointerOperandType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a53500398705be6af72f415a563af78a0">getStructuredLoadFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a42ce8aa34864a9d974958b9d3d36ad17">llvm::IRBuilderBase::getTrue</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a85764bb37db07737ed0058c352f4c3b7">isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a2ff127c9924cd3337080c4445c324aea">llvm::Type::isScalableTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a19e092ecf7889abf7277f13824e0c601">replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### lowerInterleavedLoad() {#a6cbcd096f254563525e65e58557ed901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::lowerInterleavedLoad (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> * &gt; Shuffles, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Indices, unsigned Factor)</td>
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

<p>Lower an interleaved load into a ldN intrinsic.</p>


<p>E.g. Lower an interleaved load (Factor = 2): wide.vec = load &lt;8 x i32&gt;, &lt;8 x i32&gt;* ptr v0 = shuffle wide.vec, undef, &lt;0, 2, 4, 6&gt; ; Extract even elements v1 = shuffle wide.vec, undef, &lt;1, 3, 5, 7&gt; ; Extract odd elements</p>


<p>Into: ld2 = { &lt;4 x i32&gt;, &lt;4 x i32&gt; } call llvm.aarch64.neon.ld2(ptr) vec0 = extractelement { &lt;4 x i32&gt;, &lt;4 x i32&gt; } ld2, i32 0 vec1 = extractelement { &lt;4 x i32&gt;, &lt;4 x i32&gt; } ld2, i32 1</p>


<p>Declaration at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4288169d91ab0f0f01405115fd2931a7">llvm::concatenateVectors</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1ac3f0b68c9c78c4f9e1eb09cd415db8">llvm::IRBuilderBase::CreateConstGEP1_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a102aafbf0ca4e05fa1620a24f797fcfb">llvm::IRBuilderBase::CreateExtractVector</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="#a84bb66973746f769109266358c463c68">getMaxSupportedInterleaveFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a>, <a href="#a365f29ab21721393fe82ff3ae4554e5e">getNumInterleavedAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2d1ff28d6923802e165905b8d1766e76">llvm::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a945c21ff70f310de538153db17e7b857">llvm::LoadInst::getPointerOperandType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a53500398705be6af72f415a563af78a0">getStructuredLoadFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a127b3dcb8a8e72d985c53454b7b1f72c">getSVEContainerIRType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a431a33f5942795512f2984bc30aa4c41">llvm::getSVEPredPatternFromNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a59c34209e9206120edf7ce3c5da4f872">llvm::ShuffleVectorInst::getType</a>, <a href="#a85764bb37db07737ed0058c352f4c3b7">isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a997de5064c00da2a575c5fa561dc3c65">llvm::PatternMatch::m_UIToFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### lowerInterleavedStore() {#aa4094e6b2a8203e5c8b67ecf186d51a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::lowerInterleavedStore (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> * SVI, unsigned Factor)</td>
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

<p>Lower an interleaved store into a stN intrinsic.</p>


<p>E.g. Lower an interleaved store (Factor = 3): i.vec = shuffle &lt;8 x i32&gt; v0, &lt;8 x i32&gt; v1, &lt;0, 4, 8, 1, 5, 9, 2, 6, 10, 3, 7, 11&gt; store &lt;12 x i32&gt; i.vec, &lt;12 x i32&gt;* ptr</p>


<p>Into: sub.v0 = shuffle &lt;8 x i32&gt; v0, &lt;8 x i32&gt; v1, &lt;0, 1, 2, 3&gt; sub.v1 = shuffle &lt;8 x i32&gt; v0, &lt;8 x i32&gt; v1, &lt;4, 5, 6, 7&gt; sub.v2 = shuffle &lt;8 x i32&gt; v0, &lt;8 x i32&gt; v1, &lt;8, 9, 10, 11&gt; call void llvm.aarch64.neon.st3(sub.v0, sub.v1, sub.v2, ptr)</p>


<p>Note that the new shufflevectors will be removed and we'll only generate one st3 instruction in CodeGen.</p>


<p>Example for a more general valid mask (Factor 3). Lower: i.vec = shuffle &lt;32 x i32&gt; v0, &lt;32 x i32&gt; v1, &lt;4, 32, 16, 5, 33, 17, 6, 34, 18, 7, 35, 19&gt; store &lt;12 x i32&gt; i.vec, &lt;12 x i32&gt;* ptr</p>


<p>Into: sub.v0 = shuffle &lt;32 x i32&gt; v0, &lt;32 x i32&gt; v1, &lt;4, 5, 6, 7&gt; sub.v1 = shuffle &lt;32 x i32&gt; v0, &lt;32 x i32&gt; v1, &lt;32, 33, 34, 35&gt; sub.v2 = shuffle &lt;32 x i32&gt; v0, &lt;32 x i32&gt; v1, &lt;16, 17, 18, 19&gt; call void llvm.aarch64.neon.st3(sub.v0, sub.v1, sub.v2, ptr)</p>


<p>Declaration at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1ac3f0b68c9c78c4f9e1eb09cd415db8">llvm::IRBuilderBase::CreateConstGEP1_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a28d8fda3ddcb508d0b669cda059ccd4d">llvm::IRBuilderBase::CreateInsertVector</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af00a6f39da9d94ec387a366ade60aea5">llvm::createSequentialMask</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="#a84bb66973746f769109266358c463c68">getMaxSupportedInterleaveFactor</a>, <a href="#a365f29ab21721393fe82ff3ae4554e5e">getNumInterleavedAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a6eaff12d0d3ead952f2a2a2781df56ac">llvm::ShuffleVectorInst::getShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7d366eb4d40575891069ef79b2f9a3bd">getStructuredStoreFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a127b3dcb8a8e72d985c53454b7b1f72c">getSVEContainerIRType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a431a33f5942795512f2984bc30aa4c41">llvm::getSVEPredPatternFromNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a59c34209e9206120edf7ce3c5da4f872">llvm::ShuffleVectorInst::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac195e816d7e264cbe4b74b564fa26985">hasNearbyPairedStore</a>, <a href="#a85764bb37db07737ed0058c352f4c3b7">isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>.</p>

</div>
</div>

### lowerInterleaveIntrinsicToStore() {#ac2d9e284d06499be56d61b876e86dc8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::lowerInterleaveIntrinsicToStore (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; InterleaveValues)</td>
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

<p>Lower an interleave intrinsic to a target specific store intrinsic.</p>


<p>Return true on success. Currently only supports llvm.vector.interleave2</p>


<p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a></span> is the accompanying store instruction <span class="doxyComputerOutput">InterleaveValues</span> contains the interleaved values.</p>


<p>Declaration at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17570 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a102aafbf0ca4e05fa1620a24f797fcfb">llvm::IRBuilderBase::CreateExtractVector</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73e0482b96d9d0cdfcc90c0a34f5b0db">llvm::IRBuilderBase::CreateGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a40ed7274ff11f079e5b5eae34c818c51">llvm::IRBuilderBase::CreateVectorSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ae7510a639ca53c1bfa1c90c6dfc7eb2e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::divideCoefficientBy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a59632c5deb0423a518ad984bdd04d41f">llvm::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73f286a780fbb8c82c0a8574540719ea">llvm::IRBuilderBase::getInt64</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a365f29ab21721393fe82ff3ae4554e5e">getNumInterleavedAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7d366eb4d40575891069ef79b2f9a3bd">getStructuredStoreFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a42ce8aa34864a9d974958b9d3d36ad17">llvm::IRBuilderBase::getTrue</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a85764bb37db07737ed0058c352f4c3b7">isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a2ff127c9924cd3337080c4445c324aea">llvm::Type::isScalableTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### LowerOperation() {#a40581570b38300f3a21e2e8ec8c80839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerOperation (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Provide custom lowering hooks for some operations.</p>

<p>Declaration at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 7312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af798622367e75c5536666dbfec5d5ea3">llvm::ISD::ABDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a41558bfb98ed3b2341959aa622dc2495">llvm::AArch64ISD::ABDS_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff129f5ab4fbc8279e7aaacb45f840b1">llvm::ISD::ABDU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a45354be2b9fb574b34b8e38f6fbdf15a">llvm::AArch64ISD::ABDU_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a35c1cf0dd553444732dba8e8b9be0f6b">llvm::ISD::ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ab98a7740ca34fec72ed6e3b38760b2b1">llvm::AArch64ISD::ADCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a591c03cc284124ff624856ce485ebc17">llvm::ISD::ADDROFRETURNADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af7bfad446dfd85837fe7ff904ebb1aff">llvm::ISD::ADJUST_TRAMPOLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a905925a49cdc6b4a6017d215820dad30">llvm::ISD::ATOMIC_LOAD_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1db943abc1bf78a911daeb7b03d81de8">llvm::ISD::ATOMIC_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a55a4b1d94ca6176bcb5449196d67e798">llvm::ISD::AVGCEILS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8489c40b1b3f92b0c4fc98d06099c441">llvm::ISD::AVGCEILU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110acc5444f2e2933b551e3afbdd93a9bfc8">llvm::ISD::AVGFLOORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5096628a43b16ff34ace64193ded1c93">llvm::ISD::AVGFLOORU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeea401cc0b7fa5aa6f4d3a0612140e1d">llvm::ISD::BITREVERSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb">llvm::ISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716d19ebad1927a2e8dd5fe3f951f882">llvm::ISD::BR_JT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716765ad6ce5be71f987cd2097b1cdbf">llvm::ISD::BRIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a2ca380dca8a9dd681808096bfdd62695">llvm::AArch64ISD::BSWAP_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5">llvm::ISD::CONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c">llvm::ISD::CTLZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a7423f39e91075c53373cbc86362ddfb6">llvm::AArch64ISD::CTLZ_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a991d07d163bd4d9984cf1ef36e92c214">llvm::ISD::CTPOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6da41a113af0909470baea7486b3386b">llvm::ISD::CTTZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa71ac22470bf853868fe6b39a25bac72">llvm::ISD::DYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae243ce466d350b1aca774a6ae9aea81c">llvm::ISD::EXPERIMENTAL_VECTOR_HISTOGRAM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2b4d07600495a563319d6a3dda8dc44d">llvm::ISD::FABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a95126578449c59d8c182dcaec35c447c">llvm::AArch64ISD::FABS_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a79b964a205e8af1c7d40c1c7ea27cbeb">llvm::AArch64ISD::FADD_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad56e9199ae3993a09af36ff41d327a11">llvm::ISD::FCEIL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6683923954c2104dc5500772c896891f">llvm::AArch64ISD::FCEIL_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeffc3319657e213a530ce583603f7221">llvm::ISD::FCOPYSIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abc6c09c7af98236460f0b020eb3be94e">llvm::ISD::FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a236b6f5a3fa768b9338169585b94d31e">llvm::AArch64ISD::FDIV_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4336c27826676e1ef61383cafa999219">llvm::ISD::FFLOOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6e4af32448924c58cb4a748a07864bea">llvm::AArch64ISD::FFLOOR_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a455f49e18d470b97cd293acd7fbdf169">llvm::ISD::FLDEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a26eebef9ecd023d56a0d1f5659c6d56f">llvm::AArch64ISD::FMA_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae188e1a972d14cacb4b25aaa08c03fe7">llvm::AArch64ISD::FMAX_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3dfd1b187d121c0e214698eef1c20f53">llvm::ISD::FMAXIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a06e995899e91ad228e89b42a733a9fc8">llvm::AArch64ISD::FMAXNM_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a632dd4bb044d5cd11f671d176ef495f2">llvm::ISD::FMAXNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1280ffb064fa61a167776c1714f8c115">llvm::AArch64ISD::FMIN_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac27a43f98abb2d1ee2f2ce99a0b34b36">llvm::ISD::FMINIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a13039ac177cb3a515571da75980a41bc">llvm::AArch64ISD::FMINNM_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9f59cc264907eb86e29564d5f6a5b213">llvm::ISD::FMINNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178">llvm::ISD::FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a92132db91b6ec7e16a2d779bcc78385e">llvm::AArch64ISD::FMUL_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2dc876d6cc16ac04376483552292f9f4">llvm::ISD::FNEARBYINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a685ce754a67e5cb56d1ef4093e6bf4fe">llvm::AArch64ISD::FNEARBYINT_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d26c45c040d8f85d577a5f645261d1a">llvm::ISD::FNEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac13d816d2cb81731c25f88a756f78b75">llvm::AArch64ISD::FNEG_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae4a4e2126c6db34e2dfd71b6bd0408ee">llvm::ISD::FP_TO_SINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98661814400e72a77f5ed4e088c06937">llvm::ISD::FP_TO_UINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdb38c8daa8c1ab881007062d113cef3">llvm::ISD::FRAMEADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a68014623710f7a44c808cd412236d6a1">llvm::ISD::FRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a43d0d40d03e4d03b0512a74db902be45">llvm::AArch64ISD::FRINT_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a87b7dd3d6a9b68d1558fc6b4706708b0">llvm::ISD::FROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a7c0da9722d4fb6b68c096e15b50bdbac">llvm::AArch64ISD::FROUND_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab3cb85375f983765b93341d57a2f3838">llvm::ISD::FROUNDEVEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4ce802350a14f6dd022c1d2dd87ec7b6">llvm::AArch64ISD::FROUNDEVEN_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a822b0d02b601898e2d6db5b39e12cc8a">llvm::ISD::FSHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a874350de5b4f6b8f4db13940e17ed81b">llvm::ISD::FSHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6ba8fc92ee5081d3e533cb5322f74f29">llvm::ISD::FSINCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae1118ddac1ce0af8e9f7cc16c9e94fc0">llvm::ISD::FSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac51e55480048612eede3cb1b18513b22">llvm::AArch64ISD::FSQRT_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad">llvm::ISD::FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a05dd7344f5aef716731bf261a43f218c">llvm::AArch64ISD::FSUB_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1e92ea554489509b0ad970901bcc715b">llvm::ISD::FTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9fb341bd2a710ddf055b0545efc68fc0">llvm::AArch64ISD::FTRUNC_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8ba51b127e01a9e6412e7629c70ec4a1">llvm::ISD::GET_FPMODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89f3afc3fa907ff83759c6c76d97a973">llvm::ISD::GET_ROUNDING</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6ee732dc403611ea57c638c36abde989">llvm::AArch64ISD::HADDS_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a0a20600fa3b8b7576ef1e7a16f0c8351">llvm::AArch64ISD::HADDU_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4534a6db2862a28324932a8ea1cb54d6">llvm::ISD::INIT_TRAMPOLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">llvm::ISD::INSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0c70100db6ddc0b37b56feb242145cf4">llvm::ISD::JumpTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a25eed965b36ce43fc8b9daa2774dfad8">llvm::ISD::LLRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4e2fdf7d4dbc04469cf6a920262c82c8">llvm::ISD::LLROUND</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad02298a2723f65c6011512e29ea5bfc0">lowerADDSUBO_CARRY</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a39074c14f912395b71849863077d463d">LowerBRCOND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adc552041debc73d1122de01993523820">LowerFLDEXP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a908002fa0e62607096a6a564be8a4198">LowerFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9b284b652f676b448812e5ba2f1b9c70">LowerPREFETCH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa5a86623773ed13c55fc451727aa234f">LowerXALUO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a05f23e2cd900dc8f1dbf6702ab12423b">llvm::ISD::LRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adb1de74d602ef905e06785e0052b55bf">llvm::ISD::LROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab4685260a7e506fe51f17d9b600349c8">llvm::ISD::MGATHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a112324db3910fea5895514851c387442">llvm::ISD::MLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab179d7f42562bbb315a6b0589a25f733">llvm::ISD::MSCATTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a2486a390b5849a760c293a7aa8a569f8">llvm::AArch64ISD::MSRR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9add598de9e0a49cbb8fb19adf495051">llvm::ISD::MSTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa2a7c3eccf06b41e4275bbeadb46d22e">llvm::ISD::MULHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4b0056cc9bd2dd8caad14edf30f960a3">llvm::AArch64ISD::MULHS_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8a80d3b085af08f0dce1724207ef99b5">llvm::ISD::MULHU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ab1654eebeb0da72fb694cad7ccc65836">llvm::AArch64ISD::MULHU_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa47439d20ce0879ea68ca293e018b4f5">llvm::ISD::PARITY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a691a4c9004e9bd04d1c0bebc5df57443">llvm::ISD::PREFETCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8df1b84ea64ad5048f27873205c8ab89">llvm::ISD::PtrAuthGlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a386314479bc7963a544ed142866e7ece">llvm::ISD::RESET_FPMODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2dfacb29792dd59f2cfbe529206265bc">llvm::ISD::RETURNADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a06dadc5c6f83ab133efe7d629fa0ce54">llvm::AArch64ISD::RHADDS_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a472127f5c49ffe5d374d554b6fb69252">llvm::AArch64ISD::RHADDU_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a863ec6ebb75bf89cfea14da646d77e92">llvm::ISD::SADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af9eda6a77c3228cd36537469a7425133">llvm::ISD::SADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a3ce7d4f224730b380e96d3e674ef269c">llvm::AArch64ISD::SBCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a26b34eddab8969a79fd3cda432471809">llvm::ISD::SET_FPMODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4fe6c878350458de2c3182392f830988">llvm::ISD::SET_ROUNDING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6bb33e400f29724907dc27ced04e9038">llvm::ISD::SETCCCARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa560a9bc62116f8349176c8303745d0b">llvm::AArch64ISD::SIGN_EXTEND_INREG_MERGE_PASSTHRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af3b59179b6fcbc89463181015ace8e9b">llvm::ISD::SMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaac895215ecbb3c411c957c8beb39b70">llvm::ISD::SMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa35d0a58fdded3d225d512a60aea0951">llvm::ISD::SMULO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">llvm::ISD::SPLAT_VECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af587fdddecfd87186f09f4b1e9b4bc0a">llvm::SelectionDAG::SplitScalar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add9a41fa65a9675200d73710a82b880e">llvm::ISD::SPONENTRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6efe16ea597cfd8eeac26516fc992ee7">llvm::ISD::SSUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a139dc5419039d94496e69dbb264251b5">llvm::ISD::SSUBO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac47e026e409ff39f319cbb3b096863e6">llvm::ISD::STRICT_FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2273d9cd04ba6e4a7c1a4b28ab1aaba">llvm::ISD::STRICT_FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed">llvm::ISD::STRICT_FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf955b4b70f63865e022c329d1775579">llvm::ISD::STRICT_FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0466b21bfb4f3596e41380d8e2d1956f">llvm::ISD::STRICT_FSETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c8d07d668872f2176fb34724cd799c4">llvm::ISD::STRICT_FSETCCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad4892124e4817d9807dcf39808016bc4">llvm::ISD::STRICT_LLRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adef1eba7d8c2a0db4a94d7327d217c90">llvm::ISD::STRICT_LLROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa7fc883444df66de315a684ecf5f5e2d">llvm::ISD::STRICT_LRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6bd04c8da718875a071107ede0f362d6">llvm::ISD::STRICT_LROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab38d2af541b99492acf69c041c98bcb6">llvm::ISD::STRICT_SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a56735332b7dc26b4e164035831fb40ab">llvm::ISD::STRICT_UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1ddf36330110b4abea43fe390bea9ef9">llvm::ISD::UADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0f1e3ed26108fec69eb97209c0e39bf">llvm::ISD::UADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af675e759c0ffff8d48ea14a60fe3517b">llvm::ISD::UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a17126302da6199930e55e841ca1b082d">llvm::ISD::UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7800622851751b8ae318b41f4096830e">llvm::ISD::UMULO</a>, <a href="#afa8bfec034d066ec24d18d3fd76ac590">useSVEForFixedLengthVectorVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4ffc75d65231b55461c0ba4f36a3e500">llvm::ISD::USUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac81ebcd59d629d8680e50ffba9855255">llvm::ISD::USUBO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae77d03846b31c41c4860bcd96d780a78">llvm::ISD::VAARG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a804c1960ac64628cdd1f74d7de885284">llvm::ISD::VACOPY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adfe32beaa596a1512b17e66b46e773ed">llvm::ISD::VASTART</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89a8ec08f6908a989c2d0198ae8851f9">llvm::ISD::VECREDUCE_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa58fe501d4e4fa1b4d19e0ed6b8ee6bd">llvm::ISD::VECREDUCE_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5e28372b4a60bf792da88d9bc8a8d0bf">llvm::ISD::VECREDUCE_FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a323856d66e2d8b1f74e528e3f9fe804d">llvm::ISD::VECREDUCE_FMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a355892ae7349b089e0bd24b3087d9c75">llvm::ISD::VECREDUCE_FMAXIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6a8980cf09891ec57cbce010ba119f79">llvm::ISD::VECREDUCE_FMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae526df97bcbda2419acf8cf105c95e8e">llvm::ISD::VECREDUCE_FMINIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aafd45b465ac59a1a57b8b9862aef6bed">llvm::ISD::VECREDUCE_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0b3085a54414d7e8ae7c13f5aeadb9da">llvm::ISD::VECREDUCE_SEQ_FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c057571f4591494880ec0bba023e0c2">llvm::ISD::VECREDUCE_SMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a11825b59a52b4f5a73c0b877e1ba0e70">llvm::ISD::VECREDUCE_SMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7ce9f75eaf17256deb960b11d1930040">llvm::ISD::VECREDUCE_UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab67678c3310e505df1a3f7677b14cfb0">llvm::ISD::VECREDUCE_UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9b59fad28698a46c33285083818f6b87">llvm::ISD::VECREDUCE_XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adb06c311948bd9fb944ab3c433138181">llvm::ISD::VECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af5b978686fa3409a40ce3abe447db653">llvm::ISD::VECTOR_DEINTERLEAVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7314e9c42c2c93e3786adfd12aee39d7">llvm::ISD::VECTOR_INTERLEAVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad55a17543ef86f6d46aebb45028a9067">llvm::ISD::VECTOR_SPLICE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9b2378721f79f5b72a6398dce97b3a42">llvm::ISD::VSCALE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0b7d2c769fd0fbaab3c4a2fc8e7ea0c">llvm::ISD::VSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a61a1595d03afe86764ad7625d358608e">llvm::ISD::WRITE_REGISTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adf7f4fc30c272a1987e075d7470df84c">llvm::ISD::ZERO_EXTEND_VECTOR_INREG</a>.</p>

</div>
</div>

### mergeStoresAfterLegalization() {#aff2977da8eaad9875d1b5c9d3401e452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::mergeStoresAfterLegalization (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>SVE code generation for fixed length vectors does not custom lower BUILD_VECTOR.</p>


<p>This makes BUILD_VECTOR legalisation a source of stores to merge. However, merging them creates a BUILD_VECTOR that is just as illegal as the original, thus leading to an infinite legalisation loop. NOTE: Once BUILD_VECTOR is legal or can be custom lowered for all legal vector types this override can be removed.</p>


<p>Declaration at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 7661 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### needsFixedCatchObjects() {#ab85e6fcf7b8d3785c437808d101bd14f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::needsFixedCatchObjects ()</td>
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

<p>Used for exception handling on Win64.</p>

<p>Declaration at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### optimizeExtendOrTruncateConversion() {#a50016fb8102156a9c168cfd348b3509a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::optimizeExtendOrTruncateConversion (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI)</td>
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

<p>Try to optimize extending or truncating conversion instructions (like zext, trunc, fptoui, uitofp) for the target.</p>

<p>Declaration at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16879 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#adc6a2686b807c18e4a7f7fc58e68d423">llvm::IRBuilderBase::CreateAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4cac1c8f9a62a9d1079e4d0499bbb848">llvm::IRBuilderBase::CreateFPToUI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a2e19b7738daed96724457c786521e5e1">llvm::IRBuilderBase::CreateSIToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5aade91cf963bd6be461be24ff3a284c">createTblForTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae919aab2dcdca2fcb21214e33822c838">createTblShuffleForSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a93cdde383eeeb3fb45851d9660891a5f">createTblShuffleForZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5d0b7f11d28f823b8323344d84d63f03">llvm::IRBuilderBase::CreateUIToFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a696078388bd4281dc93c3bbcd74338d3">EnableExtToTBL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a096c8b641174dc0e486006926c5202cf">llvm::TargetTransformInfo::getCastContextHint</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a510fe1022b20cfb823cf9f1ee7f23a00">llvm::FixedVectorType::getInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a781c723920fb1d098c4d959f3218d9aa">llvm::VectorType::getInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">llvm::VectorType::getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af10813bee5ce9c7b412807aac434deef">llvm::PatternMatch::m_c_Mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae5cf2b09af0c75d08cf9e5e8f2818a66">llvm::PatternMatch::m_SExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca89f768b1267e3083b4eb05b4ab77e717">llvm::TargetTransformInfo::TCC_Free</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">llvm::TargetTransformInfo::TCK_SizeAndLatency</a>.</p>

</div>
</div>

### PerformDAGCombine() {#a960012b61a9977dc7c2d3af3943da953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::PerformDAGCombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
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


<p>Declaration at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 26418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a570a73eb4f12ab7c7db1e81f280b363c">llvm::AArch64ISD::ADC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ab98a7740ca34fec72ed6e3b38760b2b1">llvm::AArch64ISD::ADCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af36f36b0406330ead921ee1fb07de2cd">llvm::AArch64ISD::ANDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad6ab97e04848339b891365ffbcc1a0fc">llvm::AArch64ISD::BICi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1dd8fc0bc13596b74da85b07a1ee5dd2">llvm::AArch64ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a21d1b00201e7e4cb249066ba0da2dd0e">llvm::AArch64ISD::BSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a823e4af88c760486aecf7639ab3dc46e">combineSVEPrefetchVecBaseImmOff</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5">llvm::ISD::CONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aeaea22b21177ff390559a1314dbf6947">llvm::AArch64ISD::CSEL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4a963d58bfd84cd339df4a7c57f8764e">llvm::AArch64ISD::CSINC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c">llvm::ISD::CTLZ</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#acf37bd7e831bdb2a5c9da8d63f843101">llvm::TargetLowering::DAGCombinerInfo::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9e0955df410f281dcdb5272e0ab9ce3d">llvm::AArch64ISD::DUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a5dea2cc356e551e1a38be00f441d0aed">llvm::AArch64ISD::DUPLANE128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a63256211d7e9fcab596baa05d672db8d">llvm::AArch64ISD::DUPLANE16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a5d3f342d733ac020d495e08094c201bb">llvm::AArch64ISD::DUPLANE32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a626e899c69c3bfdbdbb094dd1c43bcc5">llvm::AArch64ISD::DUPLANE64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9e5cc09bf44571679cb7abc733bca21b">llvm::AArch64ISD::DUPLANE8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae243ce466d350b1aca774a6ae9aea81c">llvm::ISD::EXPERIMENTAL_VECTOR_HISTOGRAM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab43491efca0a534410c1dcece99f2949">foldADCToCINC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8648786e9af485e27d907ecd2f2a2a08">foldOverflowCheck</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae4a4e2126c6db34e2dfd71b6bd0408ee">llvm::ISD::FP_TO_SINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98661814400e72a77f5ed4e088c06937">llvm::ISD::FP_TO_UINT_SAT</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a193d4ea30b27a0c86550ae249eefaeaa">llvm::SelectionDAG::getMergeValues</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4c20c587f89ae2926f9e8a99093e8419">llvm::SelectionDAG::getTargetLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad0c6f059b29535f2c790d1c4f92b7a93">llvm::SelectionDAG::getZExtOrTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a7923f428f833cc997e1f5ecf0993f90e">llvm::AArch64ISD::GLD1_IMM_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a17e64b48fdac9928b6a0a092c5af7dc9">llvm::AArch64ISD::GLD1_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac8f6f034b1c865aa8e77ccaebda32218">llvm::AArch64ISD::GLD1_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a74b91234a131f53b9a68a9ca4cd26c87">llvm::AArch64ISD::GLD1_SXTW_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1e9d1eebf5bf9d4ff49ef45d7880e4ba">llvm::AArch64ISD::GLD1_SXTW_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19afa65635052abba7d2eb891eb24706af9">llvm::AArch64ISD::GLD1_UXTW_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad79b28d6740520761635d67c6c3c5dc9">llvm::AArch64ISD::GLD1_UXTW_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a3521337d037a29d43555c7ea1b96f75d">llvm::AArch64ISD::GLD1Q_INDEX_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a0bfe9e8819e5c1bfb6ab5515936a69ba">llvm::AArch64ISD::GLD1Q_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac11bd3bd817019b249d11d7f12aedd31">llvm::AArch64ISD::GLD1S_IMM_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a9be68046aad6ca20ef30d451f3ab9eb5">llvm::AArch64ISD::GLD1S_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac1b72bf6c7bc204136030e0ae144f3de">llvm::AArch64ISD::GLD1S_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a558ddabda114cddf991cf8052babf0da">llvm::AArch64ISD::GLD1S_SXTW_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af263284586304c99345ed0c663ea2e3c">llvm::AArch64ISD::GLD1S_SXTW_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19acc129ce1cfc16e162528c86841b10e32">llvm::AArch64ISD::GLD1S_UXTW_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a5ca98fbce7ddde8900dfd68b03a5b76f">llvm::AArch64ISD::GLD1S_UXTW_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a94f47573b2939ef71e656156bc5cd991">llvm::AArch64ISD::GLDFF1_IMM_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aec4b3e29e4c750748f6eec345d2ecfe7">llvm::AArch64ISD::GLDFF1_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a0d5ecaf42b919f021d7f90a1b17d3d4e">llvm::AArch64ISD::GLDFF1_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a637b9743c971911cbd50d1f7205db274">llvm::AArch64ISD::GLDFF1_SXTW_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a33060aa53377821ae236cdcdc6234f21">llvm::AArch64ISD::GLDFF1_SXTW_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa63ddb8204981576c188ecd594ec388a">llvm::AArch64ISD::GLDFF1_UXTW_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a68588f7134c66b9586fa7ad3d9720258">llvm::AArch64ISD::GLDFF1_UXTW_SCALED_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a658fff45ec5b54f450348d849379d5e7">llvm::AArch64ISD::GLDNT1_INDEX_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a148014182bdd341f262ef4d64969bb72">llvm::AArch64ISD::GLDNT1_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">llvm::ISD::INSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4e624e8cd76c2c489fc4a426687a5004">llvm::AArch64ISD::LD1_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a866e96767e66fab323aa11daa967334d">llvm::AArch64ISD::LDFF1_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac2a18bdf7917f763d050a81ab0762d91">llvm::AArch64ISD::LDNF1_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a77650539aaaa54572ee61d0cf97a3575">legalizeSVEGatherPrefetchOffsVec</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab4685260a7e506fe51f17d9b600349c8">llvm::ISD::MGATHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a0767ec4421b5ce84bb44f55969d6bea8">llvm::AArch64ISD::MRS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab179d7f42562bbb315a6b0589a25f733">llvm::ISD::MSCATTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9add598de9e0a49cbb8fb19adf495051">llvm::ISD::MSTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28a191e89dbc4939ebd0b572cae44aac05f">llvm::AArch64CC::NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a79512f79cb3d87ff14fd966207218ca5">llvm::AArch64ISD::NVCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afc2fb5809753e750c4245a785d06a754">performAddSubCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64b9ecc144bf0b95267b353d6ddf5b9b">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2a5ac33b69bb7d7687d12dc0dffe9f08">performBRCONDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab22a8cab92ee5978be7e541e30667c55">performBSPExpandForSVE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad6bb7ee72f79badd15b563bf112de6e5">performBuildVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4b8e4441770569e02f67db99773afff0">performCSELCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae26a970eb40a07c455b1bf8697cb9409">performCTLZCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08e1234497dd7fb39211e46523f02459">performDUPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a88130de22a0c1eefe0ff49acda2ca4fd">performDupLane128Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad4765786a8a3de00320df895defc3250">performExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aab253557e698e63e5f05d8d9dd1d91f5">performExtractSubvectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aefd957dcc1874b25b5b758324370d20d">performExtractVectorEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2f6ed7bfd084f49c2369eec4c74495a3">performFADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4a73ebacb24d087b199805b801f61507">performFlagSettingCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8b803a5cecda412b4f4984ad8db7201e">performFPExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa7054eb07a4962c7516115555800c017">performFpToIntCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a856202032515a6113c3de53d575f2d33">performGatherLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a20421c306f02a92c47eef00c2a1f02f8">performGLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a40c243011cdda005e97448378d575096">performGlobalAddressCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afa4334801ad99c95a1b5fd0f417e16af">performInsertSubvectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aecebd3286d7e5e48086b22673717d22c">performInsertVectorEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af95a8dd3a4e9b403d57b68b5cbda46e6">performIntrinsicCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a03b14e6aca1277bdee37639aec700ba7">performIntToFpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7b49e80a5c71aff0a4a6d6a637cafe3f">performLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aae814004d3aa90fb312b7ac62cedb284">performLD1ReplicateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed80d9ad70fe74f3136dd25a2eee1c47">performLDNT1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae60f4de0d1e0dac32141edcacb8d20c3">performLOADCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad50cb0376d697cd4ca4f6469bd6bd25c">performMaskedGatherScatterCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac1e566876b6ec934e149faae1a9b6f74">performMSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed1948f48d09629d7b5f3883119336b7">performMULLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2fbb20906245b5a07551c13da1409712">performNEONPostLDSTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a208e565c7a2bbd5703fcf565c790934e">performNVCASTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a33f99c1c02a48f20e7ec9d30d11d093c">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af121f09f2d04bed8fb532a82bceaa576">performReinterpretCastCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a596ebebe073bb9a8568f898a4c2a06f6">performScalarToVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad9d322dc7ec082cd00e94e7888b78a43">performScatterStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3580959284fc1395f017d102336eb695">performSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa26d28bee621b8087f1521482dc3b825">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abcaf1212adde88b8addaf1060c459819">performSetccMergeZeroCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a24edd3104fd2ecba03dd7ca79104295d">performSHLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a72895c7f66e26be35e106221a2ab26ae">performSignExtendInRegCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4b5bb7ddabde61f69fdb9785410078ac">performSpliceCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6d287a92051d679a9eb264a553c64ffd">performST1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a13534e47159f35c97e261aac72664214">performSTNT1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad19eb01bd287efda27e7bc5ba67cd144">performSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab5aa3058a584e6bc0e5b94db121422eb">performSunpkloCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af246e1e2988325698821d504157ed804">performTBZCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a48a325f68cd666c7ee8808c5e224192c">performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad657d5a1d3a2813dbd073c235119c7e8">performUADDVCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a47e64a2f9eb3ade81edd0d1e20034ec1">performUnpackCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8bdc70b2f7ce13fccad6913d54322dcf">performUzpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6d8fbde7afd8f90c51d6001d0144b1c8">performVecReduceAddCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a49ed4ed152a2f6e8533ccac1deb10ca0">performVecReduceBitwiseCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7e495837f173dea1e6919b589d315f67">performVectorShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac52bce44713165c831945178e1d5f696">performXorCombine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a52bd6aa1392a591e5727dfd0d0e880ba">llvm::AArch64ISD::PMULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a6ee026906ebb33819f0452450d5bc4ef">llvm::AArch64ISD::REINTERPRET_CAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a20a4c4ed442a366739eb8383950fa95e">llvm::AArch64ISD::RESTORE_ZT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a1748c672ccffe764a0bcc1fdfe16c9f6">llvm::AArch64ISD::SAVE_ZT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a3e0f0bc95b04d7de664c53bb98ec888b">llvm::AArch64ISD::SBC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a3ce7d4f224730b380e96d3e674ef269c">llvm::AArch64ISD::SBCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac148c71eaed20be4b9ea132008532d8d">llvm::AArch64ISD::SETCC_MERGE_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ab2fd70d9aeac9343fa8f00ccdeff7f0b">llvm::TargetLowering::SimplifyDemandedBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a088ad415e58a6fbb41ded8063e26bca6">llvm::AArch64ISD::SMULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a210b1c8a403932ae546ed0b54128cdda">llvm::AArch64ISD::SPLICE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a85ed05e5b6525f68f560aeec26360a9f">llvm::AArch64ISD::SST1_IMM_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a228badaf4ea8fc1855e346884210a40f">llvm::AArch64ISD::SST1_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4c18de870cd5cdb48d13c2554dbe975e">llvm::AArch64ISD::SST1_SCALED_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a63629e520272560bfaa91072ced436db">llvm::AArch64ISD::SST1_SXTW_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aee81f3a7f92882048ae759626cce52fc">llvm::AArch64ISD::SST1_SXTW_SCALED_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19adb25d74321dce9c4a69412fd849e6709">llvm::AArch64ISD::SST1_UXTW_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a31c76b6e0b307a491e2064bdaa55e16d">llvm::AArch64ISD::SST1_UXTW_SCALED_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad1c18847191322766d77b00a67708c9d">llvm::AArch64ISD::SST1Q_INDEX_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a58d30483f428219ebfd40e279db19942">llvm::AArch64ISD::SST1Q_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac59023c7b0b3c6f3fa7ff35406ebe37e">llvm::AArch64ISD::SSTNT1_INDEX_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ac790946c00d53a027bcd49843379fb21">llvm::AArch64ISD::SSTNT1_PRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aca0f8df53ae7a68829ef5100ee8e133a">llvm::AArch64ISD::SUNPKLO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a31e3eddf628ce0ce1ab1624e731ee92b">llvm::AArch64ISD::TBNZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa7d178f513996b738fea26d693c54e9a">llvm::AArch64ISD::TBZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a433c4e85025f39985b0e259cbf6f95ed">llvm::AArch64ISD::UADDV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae9765ad45095f8a38ed3c365c8b8039a">llvm::AArch64ISD::UMULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a001f62f9f1eca066cc571960f52dc564">llvm::AArch64ISD::UUNPKHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa5f5eaa830a51e606a1a5749dea7f297">llvm::AArch64ISD::UUNPKLO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4db23bc2ed0cc6a04a5c5d11bb45235f">llvm::AArch64ISD::UZP1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a8aec775bf28196c442cf229cd43db2e3">llvm::AArch64ISD::UZP2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a794f9f6bbb4013df844fce71137cb255">llvm::AArch64ISD::VASHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89a8ec08f6908a989c2d0198ae8851f9">llvm::ISD::VECREDUCE_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa58fe501d4e4fa1b4d19e0ed6b8ee6bd">llvm::ISD::VECREDUCE_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aafd45b465ac59a1a57b8b9862aef6bed">llvm::ISD::VECREDUCE_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9b59fad28698a46c33285083818f6b87">llvm::ISD::VECREDUCE_XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4318caf60a3c8fb3a95e336e55457763">llvm::AArch64ISD::VLSHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0b7d2c769fd0fbaab3c4a2fc8e7ea0c">llvm::ISD::VSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### preferIncOfAddToSubOfNot() {#a6249d1435318ffc44640d1b46f4ac294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::preferIncOfAddToSubOfNot (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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


<p>Declaration at line 906 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#ad958859a7af278dd5ea2b593c2b25050">llvm::EVT::isScalarInteger</a>.</p>

</div>
</div>

### preferredShiftLegalizationStrategy() {#a6667df004a39c249e82595e8c06841ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::ShiftLegalizationStrategy AArch64TargetLowering::preferredShiftLegalizationStrategy (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned ExpansionFactor)</td>
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



<p>Declaration at line 886 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28070 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a548cfb9440f36ba67fc5566b8e967fc6">llvm::Function::hasMinSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1cfe6f1187d7ab1a0ada9cc119c1b2b4a9774fd1a96085b8680d017dd42652bc1">llvm::TargetLoweringBase::LowerToLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa88eb4ddf2a7c4d5d5482c9fc0b9090a">llvm::TargetLoweringBase::preferredShiftLegalizationStrategy</a>.</p>

</div>
</div>

### ReconstructShuffle() {#a94825933fbeecbda802a1c22c46a524d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::ReconstructShuffle (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 12812 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3bf257bfbd279ecfad670be03b00210e">llvm::EVT::bitsLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5">llvm::ISD::CONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a68cdc2666693dffb9173a9dffee11ab8">llvm::SDValue::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a489b5bf6d9df2ae4dac6fce059b91bda">llvm::AArch64ISD::EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a64f6469ab95c4eec77e4ccf303619a81">llvm::SelectionDAG::getBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5d154312bef0ed1a6bacfcb52b7cf8eb">llvm::SelectionDAG::getBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae94d01adfba8b1a65f781ecd925111ea">getExtFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a7712dd4392b7eb944b709ac8442634d9">llvm::EVT::getFixedSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b0e59823444a55c295af279611a9d24">llvm::SelectionDAG::getUNDEF</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa7e233051b9ed8ebc0191f42698cb14">llvm::SelectionDAG::getVectorShuffle</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a210ba6b43ba451b698857dd9de71bd15">llvm::EVT::getVectorVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6db1f207286bd8bc6a978593a55955e9">llvm::EVT::is128BitVector</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#afa40b0ea2c1858e1e297227cc17d77db">llvm::EVT::is64BitVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a84c1d72001dd5f34d9a55b3a7bb8a474">llvm::DataLayout::isBigEndian</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab8967b7214f38cdea9c0158dbe2ffa31">llvm::EVT::isScalableVector</a>, <a href="#a1c7cb6b368ef7cba8da95f1f11ed4fc0">isShuffleMaskLegal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a79512f79cb3d87ff14fd966207218ca5">llvm::AArch64ISD::NVCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d812a2dd18aa186c164447e20e348e7">llvm::operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### shouldConsiderGEPOffsetSplit() {#ad3b9542cd71de589d049139d68ab6589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldConsiderGEPOffsetSplit ()</td>
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



<p>Declaration at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17869 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldConvertConstantLoadToIntImm() {#a3b40229ffa0ce512148acc985d56136c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldConvertConstantLoadToIntImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Declaration at line 784 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 18033 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a262431cccd14e6063eacc180130a5882">llvm::AArch64_AM::isLogicalImmediate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4f42ed6fd2569fa43f03814a17f9d94a">llvm::Log2_64</a>.</p>

</div>
</div>

### shouldConvertFpToSat() {#a406599321c7231224a41d58cbe973b15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldConvertFpToSat (unsigned Op, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> FPVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Declaration at line 908 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#affc37b88f2b4aa07bf2dedea934bb405">llvm::TargetLoweringBase::shouldConvertFpToSat</a>.</p>

</div>
</div>

### shouldExpandAtomicCmpXchgInIR() {#a70a83c8d008bb40c08c02d3238a992a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AtomicExpansionKind AArch64TargetLowering::shouldExpandAtomicCmpXchgInIR (<a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst">AtomicCmpXchgInst</a> * AI)</td>
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

<p>Declaration at line 821 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27821 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a39126826c171851bae4062b25b48e74e">llvm::AtomicCmpXchgInst::getCompareOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a2985b9c595be648a72a6dd08268c2218">llvm::TargetLoweringBase::LLSC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a6adf97f83acf6453d4a6a4b1070f3754">llvm::TargetLoweringBase::None</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### shouldExpandAtomicLoadInIR() {#a62ca2fe454c98ca30dd17d0b37ba3534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AtomicExpansionKind AArch64TargetLowering::shouldExpandAtomicLoadInIR (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI)</td>
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

<p>Declaration at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27722 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a369f472273bc816735055f13a6e6fd6c">llvm::TargetLoweringBase::CmpXChg</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#ace4241dfdb194e5c81c875b5be782213">isOpSuitableForLDPSTP</a>, <a href="#a9f1799dbf712799df049d22347e1362e">isOpSuitableForRCPC3</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a2985b9c595be648a72a6dd08268c2218">llvm::TargetLoweringBase::LLSC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a6adf97f83acf6453d4a6a4b1070f3754">llvm::TargetLoweringBase::None</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### shouldExpandAtomicRMWInIR() {#a7c188b2e9f8e7ab4da2a49c83acd299c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AtomicExpansionKind AArch64TargetLowering::shouldExpandAtomicRMWInIR (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * RMW)</td>
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


<p>Declaration at line 818 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27773 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a660a31179bfecd737a256372e5fd6122">llvm::AtomicRMWInst::And</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a369f472273bc816735055f13a6e6fd6c">llvm::TargetLoweringBase::CmpXChg</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a99fd4ef84981d6a2774c14c741b5ed65">llvm::AtomicRMWInst::getOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a667d327df48643f4d2111a0065b192f2">llvm::AtomicRMWInst::isFloatingPointOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a2985b9c595be648a72a6dd08268c2218">llvm::TargetLoweringBase::LLSC</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2">llvm::AtomicRMWInst::Max</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d">llvm::AtomicRMWInst::Min</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afdcdc631cf4fa6829fd7499cd06a306b">llvm::AtomicRMWInst::Nand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a6adf97f83acf6453d4a6a4b1070f3754">llvm::TargetLoweringBase::None</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5954f59053121b87ebe0c5fe79942c6e">llvm::AtomicRMWInst::Or</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a52cff5d33f36f7d74476e993b0118f58">rmwOpMayLowerToLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abe171d96ba8de66fb30e08c00211591e">llvm::AtomicRMWInst::UMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa53854e09143f57d2ff2ad6ac89dc55d">llvm::AtomicRMWInst::UMin</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77">llvm::AtomicRMWInst::Xchg</a>.</p>

</div>
</div>

### shouldExpandAtomicStoreInIR() {#ab5564f8fe97e73dd2f2cb8a76bbd3474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLoweringBase::AtomicExpansionKind AArch64TargetLowering::shouldExpandAtomicStoreInIR (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI)</td>
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


<p>Declaration at line 816 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27705 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a8098b34f582537833b36b58273c3545b">llvm::TargetLoweringBase::Expand</a>, <a href="#ace4241dfdb194e5c81c875b5be782213">isOpSuitableForLDPSTP</a>, <a href="#a6b0a106d77d380a71597433b5ac286ca">isOpSuitableForLSE128</a>, <a href="#a9f1799dbf712799df049d22347e1362e">isOpSuitableForRCPC3</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a6adf97f83acf6453d4a6a4b1070f3754">llvm::TargetLoweringBase::None</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### shouldExpandCmpUsingSelects() {#a3ce9ba59f8e02ebc4646f41ee4d57f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldExpandCmpUsingSelects (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Should we expand [US]CMP nodes using two selects and two compares, or by doing arithmetic on boolean types.</p>

<p>Declaration at line 910 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#a920f0719057d7352f9da10908859368d">llvm::EVT::isFixedLengthVector</a>.</p>

</div>
</div>

### shouldExpandCttzElements() {#a2b885204397a6fe1874c2c784015eb83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldExpandCttzElements (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if the @llvm.experimental.cttz.elts intrinsic should be expanded using generic code in <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a>.</p>

<p>Declaration at line 997 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2060 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldExpandGetActiveLaneMask() {#af86f6febc25487d02d7904252e2a107d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldExpandGetActiveLaneMask (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OpVT)</td>
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

<p>Return true if the @llvm.get.active.lane.mask intrinsic should be expanded using generic code in <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a>.</p>

<p>Declaration at line 992 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2025 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldExpandPartialReductionIntrinsic() {#a0c9502505ab5e9910350e241f20d976a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldExpandPartialReductionIntrinsic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * I)</td>
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

<p>Return true if the @llvm.experimental.vector.partial.reduce.</p>


<ul class="doxyList ">
<li>intrinsic should be expanded using generic code in <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a>.</li>
</ul>

<p>Declaration at line 995 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2045 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3d102abca1c9c95f36546dff2f39273b">llvm::EVT::getVectorElementCount</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### shouldExpandVectorMatch() {#ab04eee3cccc4fdfad42939e3b6a1378e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldExpandVectorMatch (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, unsigned SearchSize)</td>
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

<p>Return true if the @llvm.experimental.vector.match intrinsic should be expanded for vector type ‘VT` and search size ‘SearchSize` using generic code in <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a>.</p>

<p>Declaration at line 999 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2071 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldFoldConstantShiftPairToMask() {#acefcea723a8cd3136dae2d39a8dd7ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldFoldConstantShiftPairToMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7a">CombineLevel</a> Level)</td>
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

<p>Declaration at line 776 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 17989 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab57d04d7949ffdf008c6a2e222ebbe43">llvm::TargetLoweringBase::isIndexedLoadLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31ab5bb854fadd42503c849c4a48d7f3d90">llvm::ISD::PRE_INC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>.</p>

</div>
</div>

### shouldFoldSelectWithIdentityConstant() {#a06dd823fa615051cc96e1d7b9de7a2bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldFoldSelectWithIdentityConstant (unsigned BinOpcode, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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


<p>Declaration at line 779 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 18028 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#ab8967b7214f38cdea9c0158dbe2ffa31">llvm::EVT::isScalableVector</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>.</p>

</div>
</div>

### shouldFormOverflowOp() {#a7b9dee3428eaf04d856ffd6dab85b024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64TargetLowering::shouldFormOverflowOp (unsigned Opcode, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, bool MathUsed)</td>
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


<p>Definition at line 792 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1b6f74fbe8b15567434fa5d20a540c5c">llvm::TargetLoweringBase::shouldFormOverflowOp</a>.</p>

</div>
</div>

### shouldInsertFencesForAtomic() {#ab1d674bbe9aa52ee2ee2d2a3b6442e33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldInsertFencesForAtomic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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


<p>Declaration at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27666 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ace4241dfdb194e5c81c875b5be782213">isOpSuitableForLDPSTP</a>, <a href="#a6b0a106d77d380a71597433b5ac286ca">isOpSuitableForLSE128</a> and <a href="#a9f1799dbf712799df049d22347e1362e">isOpSuitableForRCPC3</a>.</p>

</div>
</div>

### shouldInsertTrailingFenceForAtomicStore() {#a29af3321cb077df4a9d6f4a981366fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldInsertTrailingFenceForAtomicStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Whether <a href="/web-llvm/docs/api/classes/llvm/atomicexpandpass">AtomicExpandPass</a> should automatically insert a trailing fence without reducing the ordering for this atomic.</p>


<p>Defaults to false.</p>


<p>Declaration at line 811 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27677 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a>.</p>

</div>
</div>

### shouldProduceAndByConstByHoistingConstFromShiftsLHSOfAnd() {#ab7ba1399d23ed2bdf2123d00db72cee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldProduceAndByConstByHoistingConstFromShiftsLHSOfAnd (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> X, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> * XC, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> * CC, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Y, unsigned OldShiftOpcode, unsigned NewShiftOpcode, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Given the pattern (X &amp; (C l&gt;&gt;/&lt;&lt; Y)) ==/!= 0 return true if it should be transformed into: ((X &lt;&lt;/l&gt;&gt; Y) &amp; C) ==/!= 0 WARNING: if 'X' is a constant, the fold may deadlock!</p>


<p>FIXME: we could avoid passing XC, but we can't use <a href="/web-llvm/docs/api/namespaces/llvm/#abb4484ddcdad2576d97870230db05ed8">isConstOrConstSplat()</a> here because it can end up being not linked in.</p>


<p>Declaration at line 880 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28057 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9bd4abfb6bf968505c7417e2b2532236">llvm::TargetLoweringBase::shouldProduceAndByConstByHoistingConstFromShiftsLHSOfAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### shouldReduceLoadWidth() {#aa03cec0d3e2e816167f41ac37995f274}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldReduceLoadWidth (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7">ISD::LoadExtType</a> ExtTy, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> NewVT)</td>
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

<p>Return true if it is profitable to reduce a load to a smaller type.</p>


<p>Example: (i16 (trunc (i32 (load x))) -&gt; i16 load x</p>


<p>Declaration at line 688 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16517 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aac2f0a84dd2aa5ee4c3f1385e9565f5e">llvm::ISD::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aa97617ded03926053f78ec06608f32bb">llvm::MemSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aee0e58997cd08983518f051e79b855d9">llvm::MemSDNode::getMemoryVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab8967b7214f38cdea9c0158dbe2ffa31">llvm::EVT::isScalableVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6aacde2c67988b43a261a7f7ceac4be3">llvm::ISD::NON_EXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9a0590fb25613550cffc505a2affc293">llvm::TargetLoweringBase::shouldReduceLoadWidth</a>.</p>

</div>
</div>

### shouldRemoveRedundantExtend() {#a4a6ec610f1626d7d5198a8d06e9eba18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldRemoveRedundantExtend (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
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

<p>Return true (the default) if it is profitable to remove a sext_inreg(x) where the sext is redundant, and use x directly.</p>

<p>Declaration at line 691 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16552 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a342c0d4e8e59b30daefe9a05bc2098bd">llvm::SDValue::hasOneUse</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a6163a1abbdce6098d64026e3393ecca7">llvm::SDNode::use_size</a>.</p>

</div>
</div>

### shouldTransformSignedTruncationCheck() {#ad3e6a84b6c78f3b26132a2f124749347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64TargetLowering::shouldTransformSignedTruncationCheck (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> XVT, unsigned KeptBits)</td>
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

<p>Should we tranform the IR-optimal check for whether given truncation down into KeptBits would be truncating or not: (add x, (1 &lt;&lt; (KeptBits-1))) srccond (1 &lt;&lt; KeptBits) Into it's more traditional form: ((x &lt;&lt; C) a&gt;&gt; C) dstcond x Return true if we should transform.</p>


<p>Return false if there is no preference.</p>


<p>Definition at line 889 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### supportKCFIBundles() {#af881f3ff352fcf2103ed1f1e8df2eea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64TargetLowering::supportKCFIBundles ()</td>
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

<p>Return true if the target supports kcfi operand bundles.</p>

<p>Definition at line 936 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>

</div>
</div>

### supportPtrAuthBundles() {#a4f303cd09f748c952cf97d194397bb7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64TargetLowering::supportPtrAuthBundles ()</td>
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

<p>Return true if the target supports ptrauth operand bundles.</p>

<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>

</div>
</div>

### supportSplitCSR() {#a049804b3fe8b5e8ddea9a1d2c15882b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64TargetLowering::supportSplitCSR (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Definition at line 921 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca75c7c151466ad7e041e9ed8aa4d5a4bf">llvm::CallingConv::CXX_FAST_TLS</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>.</p>

</div>
</div>

### supportSwiftError() {#aeed6ff19584b28f6a534e1aa8ed60037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64TargetLowering::supportSwiftError ()</td>
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


<p>Definition at line 930 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ac26dae5c257bfaab5aa15cab7255f107">llvm::AArch64RegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a2a4f0d74a9e54517b5009c2ac31503b5">llvm::AArch64RegisterInfo::getCallPreservedMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aaab57b42c1306819f384fbc8917e728b">llvm::AArch64RegisterInfo::getDarwinCalleeSavedRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ace1d2fbafd80bd71d27a949593da97f7">llvm::AArch64RegisterInfo::getDarwinCallPreservedMask</a>.</p>

</div>
</div>

### targetShrinkDemandedConstant() {#aca53f243b0008543a30a78356ac59010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::targetShrinkDemandedConstant (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO)</td>
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



<p>Declaration at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a36d7a38420699a48e96b1e3b390abf80">EnableOptimizeLogicalImm</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#aa945b77fd77cdc5cf80e7b7f6ae78a98">llvm::TargetLowering::TargetLoweringOpt::LegalOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a882ed852a717e7421c4dd8ede4908d92">optimizeLogicalImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>.</p>

</div>
</div>

### useLoadStackGuardNode() {#adc38e57cd913199ae05e57970421f100}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::useLoadStackGuardNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Declaration at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27587 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ad2b27b633b21a362571660ad09273d52">llvm::TargetLowering::useLoadStackGuardNode</a>.</p>

</div>
</div>

### useSVEForFixedLengthVectorVT() {#afa8bfec034d066ec24d18d3fd76ac590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::useSVEForFixedLengthVectorVT (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, bool OverrideNEON=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1014 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 7665 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a7712dd4392b7eb944b709ac8442634d9">llvm::EVT::getFixedSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6db1f207286bd8bc6a978593a55955e9">llvm::EVT::is128BitVector</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#afa40b0ea2c1858e1e297227cc17d77db">llvm::EVT::is64BitVector</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a920f0719057d7352f9da10908859368d">llvm::EVT::isFixedLengthVector</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a59eee3929b9155fd268e3e3f6c0efde9">llvm::EVT::isPow2VectorType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>


<p>Referenced by <a href="#acf8f1219dc8b656e8e11c4b08edc8979">AArch64TargetLowering</a>, <a href="#acaa0f01ce8216a0cc8704e2a086805c2">generateFMAsInMachineCombiner</a>, <a href="#a1c7cb6b368ef7cba8da95f1f11ed4fc0">isShuffleMaskLegal</a>, <a href="#a40581570b38300f3a21e2e8ec8c80839">LowerOperation</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adb90031fb3d067969f3951a7a65c3db9">tryCombineToBSL</a>.</p>

</div>
</div>

### verifyTargetSDNode() {#ab30bbf3bcf699a32f7113173b5cee991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::verifyTargetSDNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> the given <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>. Aborts if it is invalid.</p>

<p>Declaration at line 1032 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 30038 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3d102abca1c9c95f36546dff2f39273b">llvm::EVT::getVectorElementCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ae932a885fc5b27453c0530e88c4363b0">llvm::AArch64ISD::RSHRNB_I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a63c6337ab1a4098be3b02a65477f4c5c">llvm::AArch64ISD::SADDWB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19af8d0dfb8e455b848875a7c0c87cbf851">llvm::AArch64ISD::SADDWT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19ad97a96707d208382bc33f77bbe9f9edd">llvm::AArch64ISD::SUNPKHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aca0f8df53ae7a68829ef5100ee8e133a">llvm::AArch64ISD::SUNPKLO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a0ad2c68321ce87aa1ddfecd5db5620a8">llvm::AArch64ISD::TRN1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a568bdb1eb9c9d07c9baa011b76a97b06">llvm::AArch64ISD::TRN2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa0008165bc327e2a955dc5c33ebabe07">llvm::AArch64ISD::UADDWB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a83dc1c5f075d4e60118e4f1ca1bc2211">llvm::AArch64ISD::UADDWT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a001f62f9f1eca066cc571960f52dc564">llvm::AArch64ISD::UUNPKHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19aa5f5eaa830a51e606a1a5749dea7f297">llvm::AArch64ISD::UUNPKLO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a4db23bc2ed0cc6a04a5c5d11bb45235f">llvm::AArch64ISD::UZP1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a8aec775bf28196c442cf229cd43db2e3">llvm::AArch64ISD::UZP2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a574234144ef4f4e0115d0ef71a4efd80">llvm::AArch64ISD::ZIP1</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64isd/#a35ad1b8db0dfad0b69c9185c5fe24e19a58511b67177595581d8f94facb3565fe">llvm::AArch64ISD::ZIP2</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addDRType() {#a026c8ea412494113475433b9e65aba50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::addDRType (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1047 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### addQRType() {#ad510fa340d170f5bd6da1d024bc6f4fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::addQRType (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1048 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### addTokenForArgument() {#ababf41cb888755410b7d5c6539c41d0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::addTokenForArgument (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> &amp; MFI, int ClobberedFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finds the incoming stack arguments which overlap the given fixed stack object and incorporates their load into the current chain.</p>


<p>This prevents an upcoming store from clobbering the stack argument before it's used.</p>


<p>Declaration at line 1093 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 8706 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### addTypeForFixedLengthSVE() {#a85c14b1dd6d933addae9fbbfb9e70c5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::addTypeForFixedLengthSVE (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1046 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 2084 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### addTypeForNEON() {#a49e4e3535343601fee67d7c303e81478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::addTypeForNEON (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1045 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 1899 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### AdjustInstrPostInstrSelection() {#a7109c8327caf2c5922f32aba0681156f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::AdjustInstrPostInstrSelection (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
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


<p>Declaration at line 1058 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 8805 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### BuildSDIVPow2() {#a9ee57538321e485ddbf68a752ae8f6b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::BuildSDIVPow2 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Divisor, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; Created)</td>
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


<p>Declaration at line 1249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 18420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### BuildSREMPow2() {#a54ad1e460577077c916a65968f1fa4ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::BuildSREMPow2 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Divisor, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; Created)</td>
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

<p>Targets may override this function to provide custom SREM lowering for power-of-2 denominators.</p>


<p>If the target returns an empty <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, LLVM assumes SREM is expensive and replaces it with a series of other integer operations.</p>


<p>Declaration at line 1251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 18450 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### CanLowerReturn() {#a5ee1c2e421af7bccd71bfdf9809df927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::CanLowerReturn (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy)</td>
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


<p>Declaration at line 1101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 9707 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### combineRepeatedFPDivisors() {#a2a46a7d1d4b30c365a5b0c16faeb1a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64TargetLowering::combineRepeatedFPDivisors ()</td>
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


<p>Declaration at line 1262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27593 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### DoesCalleeRestoreStack() {#a08a3256c4a1cc109afc072ac00e9b590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::DoesCalleeRestoreStack (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallCC, bool TailCallOpt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1096 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 8737 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### finalizeLowering() {#a8e4061660a028461c831ee59526f05cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::finalizeLowering (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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


<p>Declaration at line 1326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getAddr() {#ab89b4ad91eeedf0fca3f22a969d43418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getAddr (NodeTy * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 9936 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getAddrLarge() {#a019eb50c151f7f279a1da60360116b47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getAddrLarge (NodeTy * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 9920 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getAddrTiny() {#a770378b0bf0d331f67c099ccc6bf6c0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getAddrTiny (NodeTy * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 9950 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getConstraintType() {#a8b0be789b677413965f96cbd82416342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64TargetLowering::ConstraintType AArch64TargetLowering::getConstraintType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint)</td>
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

<p>Declaration at line 1264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 12362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getGOT() {#a32a57dad3d930193e959438aa2082021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getGOT (NodeTy * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 9902 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getIndexedAddressParts() {#a566cba125e6bae4fa579e585a35d5b18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::getIndexedAddressParts (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 26827 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getInlineAsmMemConstraint() {#a1074d1b213893f53b6a37a9f2a53fedc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAsm::ConstraintCode llvm::AArch64TargetLowering::getInlineAsmMemConstraint (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ConstraintCode)</td>
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



<p>Definition at line 1285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>

</div>
</div>

### getMinimumJumpTableEntries() {#a5c8e6dd249e825f4b945f4d33621d2b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64TargetLowering::getMinimumJumpTableEntries ()</td>
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

<p>Return lower limit for number of blocks in a jump table.</p>

<p>Declaration at line 1359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29919 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getPostIndexedAddressParts() {#a90bc20a9bf01f9ce5548201a670867b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::getPostIndexedAddressParts (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31">ISD::MemIndexedMode</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
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

<p>Returns true by value, base pointer and offset pointer and addressing mode by reference if this node can be combined with a load / store to form a post-indexed load / store.</p>

<p>Declaration at line 1310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 26897 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getPreIndexedAddressParts() {#ab6968e1aa7f22c75ecd405bf5ba8c933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::getPreIndexedAddressParts (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31">ISD::MemIndexedMode</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
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

<p>Returns true by value, base pointer and offset pointer and addressing mode by reference if the node's address can be legally represented as pre-indexed load / store address.</p>

<p>Declaration at line 1307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 26876 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getRecipEstimate() {#aea9587751619171e83cce9d14fe5c7aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getRecipEstimate (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Operand, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, int Enabled, int &amp; RefinementSteps)</td>
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


<p>Declaration at line 1256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 12131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getRegForInlineAsmConstraint() {#a61c6ff5f4875a5a048462f94278f60ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, const TargetRegisterClass * &gt; AArch64TargetLowering::getRegForInlineAsmConstraint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
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


<p>Declaration at line 1275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 12434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getRegisterByName() {#a7a6ca5a86a7bb284087e0013b1529792}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register AArch64TargetLowering::getRegisterByName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RegName, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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


<p>Declaration at line 1265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11921 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getRuntimePStateSM() {#a7d758d2ef3debc9f9f885ad01fdb406e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getRuntimePStateSM (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 5770 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getSingleConstraintMatchWeight() {#a811f55416153ed06594f5d61f57d0d85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::ConstraintWeight AArch64TargetLowering::getSingleConstraintMatchWeight (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a> &amp; info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * constraint)</td>
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


<p>Declaration at line 1271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 12401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getSqrtEstimate() {#af46a036204c00ae8f16cf50790839095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getSqrtEstimate (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Operand, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, int Enabled, int &amp; RefinementSteps, bool &amp; UseOneConstNR, bool Reciprocal)</td>
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


<p>Declaration at line 1253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 12099 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getSqrtInputTest() {#ae1c70298f44453860125d2305651b48f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getSqrtInputTest (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Operand, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a> &amp; Mode)</td>
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


<p>Declaration at line 1258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 12084 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getSqrtResultForDenormInput() {#ad78e35d9a74a44c02751ca8041e10ec2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getSqrtResultForDenormInput (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Operand, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Declaration at line 1260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 12094 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getSVESafeBitCast() {#afe495b1e29519b957bc911f6bf505b20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getSVESafeBitCast (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29601 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getTargetNode() {#afe8de1d17ad89e06a8324e5a95e9bc88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getTargetNode (<a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 9868 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getTargetNode() {#a9ebf5412f732d157b98e17c53e98d56e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getTargetNode (<a href="/web-llvm/docs/api/classes/llvm/jumptablesdnode">JumpTableSDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 9875 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getTargetNode() {#a98ac0dd0c8badc55b17cd416dff219a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getTargetNode (<a href="/web-llvm/docs/api/classes/llvm/constantpoolsdnode">ConstantPoolSDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 9881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getTargetNode() {#a136723ae26be2eacd93d87174893ab07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getTargetNode (<a href="/web-llvm/docs/api/classes/llvm/blockaddresssdnode">BlockAddressSDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 9888 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### getTargetNode() {#a37b6df02da4d0da31a9597f2706faa8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::getTargetNode (<a href="/web-llvm/docs/api/classes/llvm/externalsymbolsdnode">ExternalSymbolSDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 9894 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### isEligibleForTailCallOptimization() {#abfd7276491ae7ad730c3e14362d247b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isEligibleForTailCallOptimization (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp; CLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1088 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 8549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### isExtFreeImpl() {#ad0523712fa8c0ccc2c1a13110303fe07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isExtFreeImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Return true if the extension represented by <span class="doxyComputerOutput">I</span> is free.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">I</span> is a sign, zero, or fp extension and is[Z|FP]ExtFree of the related types is not true.</p></dd>
</dl>


<p>Declaration at line 1043 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16642 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### isIndexingLegal() {#a424546d4a8647dc9f2c78befcf790fe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isIndexingLegal (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Base, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Offset, bool IsPre, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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

<p>Returns true if the specified base+offset is a legal indexed addressing mode for this target.</p>


<p><span class="doxyComputerOutput">MI</span> is the load or store instruction that is being considered for transformation.</p>


<p>Declaration at line 1313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 26814 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### isTargetCanonicalConstantNode() {#abd930cb28acdccb4c0251cb932cf190a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isTargetCanonicalConstantNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
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

<p>Returns true if the given Opc is considered a canonical constant for the target, which should not be transformed back into a BUILD_VECTOR.</p>

<p>Declaration at line 1338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29745 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### isUsedByReturnOnly() {#aaa769f5ac07ae2b4e287c71e8efcad7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isUsedByReturnOnly (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;)</td>
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


<p>Declaration at line 1303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 26773 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### isVectorLoadExtDesirable() {#adf44b880e2d3d4ae5b318181a0263b82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::isVectorLoadExtDesirable (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ExtVal)</td>
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

<p>Declaration at line 1302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 6572 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerAAPCS\_VASTART() {#a3e2c03794ff682ee5937754ed244ee16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerAAPCS_VASTART (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11702 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerABS() {#aa4024437327f3e76b575c1154cbfa5c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerABS (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1074 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 7153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerADDROFRETURNADDR() {#aac334b69492fdf29d91ceff0577c9098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerADDROFRETURNADDR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11936 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerADJUST\_TRAMPOLINE() {#a7fd0b04b195d11d0c224a7f1f4bc49c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerADJUST_TRAMPOLINE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 7255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerAsmOperandForConstraint() {#a653d460e1a9fa5b210e4336c52267b35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::LowerAsmOperandForConstraint (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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


<p>Declaration at line 1280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 12553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerAsmOutputForConstraint() {#a0cf448af1fb6a9c142d8806b8edd115a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerAsmOutputForConstraint (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Flag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a> &amp; Constraint, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Handle Lowering flag assembly outputs.</p>

<p>Declaration at line 1295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 12328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerATOMIC\_LOAD\_AND() {#a08f5c20380a3c53b28c66ff1b00de8b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerATOMIC_LOAD_AND (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerAVG() {#aed0b7409c8911010997242d8dbf42874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerAVG (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned NewOp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBITCAST() {#a9abbd30e6ddde662f7d58def93e17a1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerBITCAST (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 5270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBitreverse() {#a16a191948677bcfe69eccf0322e02b79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerBitreverse (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 10929 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBlockAddress() {#a8924310554d164a33cc2748170a48101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerBlockAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11622 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBR\_CC() {#a6e83939584f31a2ef02bc152784d92e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerBR_CC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 10517 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBR\_JT() {#ab981bc579cae5ddba558dac4a6caa2a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerBR_JT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11535 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBRIND() {#ad6e950c2e731ddec21609eb6929a7141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerBRIND (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11578 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBUILD\_VECTOR() {#abf06dc096fd1ed0fbd8ebdbd971611a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerBUILD_VECTOR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 14749 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCall() {#a930ea974499fcf244a3d5f696297de8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerCall (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp; CLI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals)</td>
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

<p>LowerCall - Lower a call to a callseq_start + CALL + callseq_end chain, and add input and output parameter nodes.</p>

<p>Declaration at line 1061 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 8939 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCallResult() {#afce14aea3bb1c7424d49561471be6637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerCallResult (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> InGlue, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &gt; &amp; RVLocs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals, bool isThisReturn, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ThisVal, bool RequiresSMChange)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LowerCallResult - Lower the result values of a call into the appropriate copies out of appropriate physical registers.</p>

<p>Declaration at line 1064 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 8400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCONCAT\_VECTORS() {#a01b14350d7abf282001bf0455db9f172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerCONCAT_VECTORS (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 15187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerConstantPool() {#a43ff6547eda6d335f89ca89f7cb48652}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerConstantPool (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11605 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCTPOP\_PARITY() {#a81a37fc038b29b804de7fcbb4f828408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerCTPOP_PARITY (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 10766 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCTTZ() {#ae356249a51754e3a82d988a27463fdbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerCTTZ (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 10871 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerDarwin\_VASTART() {#a42d19190ba08f80b14d4f32c618795d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerDarwin_VASTART (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11657 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerDarwinGlobalTLSAddress() {#a83b26d99127d678349cf67b58cf97230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerDarwinGlobalTLSAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert a TLS address reference into the correct sequence of loads and calls to compute the variable's address (for Darwin, currently) and return an <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> containing the final node.</p>


<p>Darwin only has one TLS scheme which must be capable of dealing with the fully general situation, in the worst case. This means:</p>


<ul class="doxyList ">
<li>"extern __thread" declaration.</li>
<li>Defined in a possibly unknown dynamic library.</li>
</ul>

<p>The general system is that each __thread variable has a [3 x i64] descriptor which contains information used by the runtime to calculate the address. The only part of this the compiler needs to know about is the first xword, which contains a function pointer that must be called with the address of the entire descriptor in "x0".</p>


<p>Since this descriptor may be in a different unit, in general even the descriptor must be accessed via an indirect load. The "ideal" code sequence is: adrp x0, _var@TLVPPAGE ldr x0, [x0, _var@TLVPPAGEOFF] ; x0 now contains address of descriptor ldr x1, [x0] ; x1 contains 1st entry of descriptor, ; the function pointer blr x1 ; Uses descriptor address in x0 ; Address of _var is now in x0.</p>


<p>If the address of _var's descriptor <em>is</em> known to the linker, then it can change the first "ldr" instruction to an appropriate "add x0, x0, #imm" for a slight efficiency gain.</p>


<p>Declaration at line 1132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 10021 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerDIV() {#aad18fa82a4be2a76552da11cfada2362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerDIV (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 15491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerDUPQLane() {#a68a1ef7b833350467f1e3f33321172a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerDUPQLane (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 14093 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerDYNAMIC\_STACKALLOC() {#a776d185a104a5d00ced5924ae68dac9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerDYNAMIC_STACKALLOC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerELFGlobalTLSAddress() {#a797a2e3922a5e091e6e5cfb01d0a7588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerELFGlobalTLSAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 10212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerELFTLSDescCallSeq() {#a4a74994b3cfdaedb1beffaccf3c2112d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerELFTLSDescCallSeq (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> SymAddr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When accessing thread-local variables under either the general-dynamic or local-dynamic system, we make a "TLS-descriptor" call.</p>


<p>The variable will have a descriptor, accessible via a PC-relative ADRP, and whose first entry is a function pointer to carry out the resolution.</p>


<p>The sequence is: adrp x0, :tlsdesc:var ldr x1, [x0, #:tlsdesc_lo12:var] add x0, x0, #:tlsdesc_lo12:var .tlsdesccall var blr x1 (TPIDR_EL0 offset now in x0)</p>


<p>The above sequence must be produced unscheduled, to enable the linker to optimize/relax this sequence. Therefore, a pseudo-instruction (TLSDESC_CALLSEQ) is used to represent the above sequence, and expanded really late in the compilation flow, to ensure the sequence is produced as per above.</p>


<p>Declaration at line 1136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 10193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerELFTLSLocalExec() {#a613aae161a403151b644b1297f3676b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerELFTLSLocalExec (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ThreadBase, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert a thread-local variable reference into a sequence of instructions to compute the variable's address for the local exec TLS model of <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets.</p>


<p>The sequence depends on the maximum TLS area size.</p>


<p>Declaration at line 1134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 10087 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerEXTRACT\_SUBVECTOR() {#aee74073dca2cbc912d08febd1f0ed336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerEXTRACT_SUBVECTOR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 15311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerEXTRACT\_VECTOR\_ELT() {#a30f3d867bec51d15847e56935d963c3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerEXTRACT_VECTOR_ELT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 15259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFCOPYSIGN() {#a93b1664b8bc1787f48713d3e88c8497b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFCOPYSIGN (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 10654 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthBitcastToSVE() {#a367dc2b505f8bb3fa3f83e20bb0aaab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthBitcastToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29049 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthBuildVectorToSVE() {#aa807450905c6c9d94044a677e37b5496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthBuildVectorToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 14690 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthConcatVectorsToSVE() {#a289bf418d32a00df50eb32678e54962e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthConcatVectorsToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29063 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthExtractVectorElt() {#a093052942180cfb1cbaafb2b20d7aa57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthExtractVectorElt (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28763 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthFPExtendToSVE() {#aee48f50853ef3b0875bcac7b1ff3373f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthFPExtendToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29098 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthFPRoundToSVE() {#a914a87e7efb93688ed68cb5a1ec45c1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthFPRoundToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthFPToIntToSVE() {#a9973c45ed11d90cece35cc62ac6d8699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthFPToIntToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthInsertVectorElt() {#a2c2b012d902848e5bc7dcf519e3ff69a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthInsertVectorElt (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28776 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthIntToFPToSVE() {#a2a611ab1c301b9eac417fbce54084a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthIntToFPToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthVECTOR\_SHUFFLEToSVE() {#a2700e981c7d14ac405513444afda913f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthVECTOR_SHUFFLEToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthVectorIntDivideToSVE() {#a8cb01dd42f233f24b1bda38edcecb39d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthVectorIntDivideToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28625 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthVectorIntExtendToSVE() {#ae8191643cae54feb576332888eb55109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthVectorIntExtendToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28691 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthVectorLoadToSVE() {#a2b0f39a3585e1d4e64c73860b9aada7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthVectorLoadToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthVectorMLoadToSVE() {#a4e3555b0572261374f4ad6cbf690ce64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthVectorMLoadToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28524 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthVectorMStoreToSVE() {#addd7e04e0d2fe74726ed2c19ca3443eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthVectorMStoreToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28608 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthVectorSelectToSVE() {#ade90770d4c77b5f495c08c4aec20c4ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthVectorSelectToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29000 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthVectorSetccToSVE() {#a2a7c7f2068b5a7e6e044bc7bf02f6f4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthVectorSetccToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29024 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthVectorStoreToSVE() {#a06bd58d45fac0086f21b03496c81d721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthVectorStoreToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28575 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFixedLengthVectorTruncateToSVE() {#afb99d5ab85ff8ad6bf8912d372b93455}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFixedLengthVectorTruncateToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28727 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFormalArguments() {#a91193d9e304f1486bfedfd84ec1fdbe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFormalArguments (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;)</td>
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


<p>Declaration at line 1052 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 7827 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_EXTEND() {#a9edd44b5410f2b0aa8b896efe6a0b6f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFP_EXTEND (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 4481 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_ROUND() {#a959d57b11b4e1d6141b73dc0c4758d53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFP_ROUND (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 4562 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_TO\_INT() {#a8d4fc21b2cc981172b0524587d689510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFP_TO_INT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 4789 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_TO\_INT\_SAT() {#a3fcace2b9b6eae23371eea1550fe2748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFP_TO_INT_SAT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 4926 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFRAMEADDR() {#a3e2683a403aef34e8626a00880d20c26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFRAMEADDR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11884 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFSINCOS() {#ab322431069592ccfd10d6aece55e68a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerFSINCOS (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 5234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGET\_FPMODE() {#a92bd218f47ba32a74d7ca85e18f2ad13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerGET_FPMODE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 5479 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGET\_ROUNDING() {#a25c07eae9a05b0fd519e28bde680af5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerGET_ROUNDING (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 5412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalAddress() {#a09748e380d9c85c0bb1a1470a45f212c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerGlobalAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 9959 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalTLSAddress() {#a81d984b4ee481099df27bca63a3c1f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerGlobalTLSAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 10359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINIT\_TRAMPOLINE() {#a9d5be73d60ed495dfe9f6216df0a3907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerINIT_TRAMPOLINE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 7265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerInlineDYNAMIC\_STACKALLOC() {#a06c98aca6c62d4ef3a3c0d9592e0946d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerInlineDYNAMIC_STACKALLOC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINSERT\_SUBVECTOR() {#af3832243cbcd2d1750ec80bd72e94b9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerINSERT_SUBVECTOR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 15364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINSERT\_VECTOR\_ELT() {#adfa7cc98beacefaa0f8ab14879c2657b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerINSERT_VECTOR_ELT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 15224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINT\_TO\_FP() {#aac219f9ce6262358e59cdf918d8b9b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerINT_TO_FP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 5093 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINTRINSIC\_VOID() {#a3e51235f2814ef7f947d835fe852d567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerINTRINSIC_VOID (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1085 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 5938 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINTRINSIC\_W\_CHAIN() {#ac16d4410fc3149f5f34e9e0821610c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerINTRINSIC_W_CHAIN (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1083 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 5980 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINTRINSIC\_WO\_CHAIN() {#adabca41e48b08718f47108e7464b772f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerINTRINSIC_WO_CHAIN (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1084 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 6013 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerJumpTable() {#a1b87094ab97a0cec1d6c5d3e8d8c8e39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerJumpTable (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11520 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerLOAD() {#aae74c22d7977560d651482ac8de85521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerLOAD (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1071 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 6997 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerMGATHER() {#aa91f332cb0f1985edd7125c2b3bcf5a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerMGATHER (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1076 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 6647 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerMinMax() {#a64e54884be7e33b543bdf8bcddbfbb2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerMinMax (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 10882 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerMLOAD() {#a958c3a9a1a65caf6b9f9e5110c989dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerMLOAD (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 6827 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerMSCATTER() {#a5ec1240ecf04168f0a1da569d7f9a729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerMSCATTER (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1077 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 6746 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerMUL() {#a8de86f3b070a451e5485db7af82e37dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerMUL (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 5594 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerPredReductionToSVE() {#a0c00923bade8cc4323f7d93e9652f7fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerPredReductionToSVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ScalarOp, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28909 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerPtrAuthGlobalAddress() {#a2dbaf43996da76acc3a908198e1e0b35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerPtrAuthGlobalAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 10428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerReductionToSVE() {#a48dac748ef81c9744d8da006bebcd86f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerReductionToSVE (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ScalarOp, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28952 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerRESET\_FPMODE() {#a72c0ded2bdf5343c0b481da714b74a84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerRESET_FPMODE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 5513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerReturn() {#a6b2c89d5e08d65a6bc259d07f3d46a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerReturn (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
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


<p>Declaration at line 1106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 9718 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerRETURNADDR() {#ac4faca15afd55e2c3e9e68d5c678ab24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerRETURNADDR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11950 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSELECT() {#a2f314f791d5497519c5dcd14ee1c068f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerSELECT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11440 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSELECT\_CC() {#a1141ffd30e0929e184698c3b5a8bc27d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerSELECT_CC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSELECT\_CC() {#aa811c7c8bf987f11de7cff51e650711a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerSELECT_CC (<a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> CC, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> TVal, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> FVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSET\_FPMODE() {#ad9154379c700e4c06c4d8992daa39778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerSET_FPMODE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 5498 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSET\_ROUNDING() {#ac6aa5c1c05559be441d4f9626fde1400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerSET_ROUNDING (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 5435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSETCC() {#aec7895d5365c75539c1390fce8d52c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerSETCC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11043 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSETCCCARRY() {#a6e7efeefc9e5acd96404abf803aa1425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerSETCCCARRY (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerShiftParts() {#a7874379fd6d6e266a0e0f71ec5cbdb4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerShiftParts (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LowerShiftParts - Lower SHL_PARTS/SRA_PARTS/SRL_PARTS, which returns two i32 values and take a 2 x i32 value to shift plus a shift amount.</p>

<p>Declaration at line 1188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11991 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSPLAT\_VECTOR() {#ae240072fae01c4881c43782447bee611}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerSPLAT_VECTOR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 14062 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSPONENTRY() {#a388b7fbe4a9bcf215cf6a23894ecae9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerSPONENTRY (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11905 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSTORE() {#a6c9b6194deb9ce89c72508ab7e137d3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerSTORE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1072 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 6888 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerStore128() {#a7bc8630b70dbb5b7acba30f36814ef61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerStore128 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower atomic or volatile 128-bit stores to a single STP instruction.</p>

<p>Declaration at line 1073 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 6966 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerToPredicatedOp() {#a80535ff2e20df287726ab1d9a2cd8185}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerToPredicatedOp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned NewOp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28795 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerToScalableOp() {#a2b98af07e953a8f928ff6033e82d05e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerToScalableOp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28852 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerTRUNCATE() {#ada0173c44fc0dee5e6d3e6e3186da8da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerTRUNCATE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 15630 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVAARG() {#a3ad11c5a92cf1f808046a60fb7f55be1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVAARG (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11814 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVACOPY() {#a381e5da7458f8babfae2ad446587d849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVACOPY (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11794 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVASTART() {#a028c754ec1043aae81cf9bc5f075be6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVASTART (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11781 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVECREDUCE() {#a5928136dca5d338b28355f94e66acb58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVECREDUCE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16093 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVECREDUCE\_SEQ\_FADD() {#aaadd336e2a5007e22f1cc743e44dfdbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVECREDUCE_SEQ_FADD (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ScalarOp, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVECTOR\_COMPRESS() {#a005e5eb0e954e153b8463195b636aa42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVECTOR_COMPRESS (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1081 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 7054 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVECTOR\_DEINTERLEAVE() {#a2f07d4d1f38c61b8b8f25cdfc1e8cb73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVECTOR_DEINTERLEAVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVECTOR\_HISTOGRAM() {#a9e84f5f3a3e1b308c281e9f137ce0308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVECTOR_HISTOGRAM (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVECTOR\_INTERLEAVE() {#a7e8c06c910f2e0725374a1876e0bac54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVECTOR_INTERLEAVE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVECTOR\_SHUFFLE() {#aed28aba46e00c555b6a3ab7eab351c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVECTOR_SHUFFLE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 13869 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVECTOR\_SPLICE() {#a007d794f5c57e9e3e28e99532ca850b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVECTOR_SPLICE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVectorFP\_TO\_INT() {#a3f8a2fd6639002107169b958acc35548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVectorFP_TO_INT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 4701 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVectorFP\_TO\_INT\_SAT() {#ac2aec72420b02edc0cb8a90513b44cfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVectorFP_TO_INT_SAT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 4822 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVectorINT\_TO\_FP() {#a8c1b63ae762fe1dfae053cdab5ade32d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVectorINT_TO_FP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 5003 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVectorOR() {#a075a7ab0c4d34a65598156869f68ec4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVectorOR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 14537 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVectorSRA\_SRL\_SHL() {#a61a805c5091de8b268d7ca7194b6a02c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVectorSRA_SRL_SHL (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 15699 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVectorXRINT() {#a422d5a82ecb9cbbb1bb50b1910afb426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVectorXRINT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 4983 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVSCALE() {#ab6f327f5b2f3791e4d4e59565ec614e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVSCALE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVSETCC() {#af6c686b83925d61ba52ed54d522b62e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerVSETCC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 15880 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerWin64\_VASTART() {#aebccf8543adbfef2fad2e7bd03e1dbe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerWin64_VASTART (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 11671 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerWindowsDYNAMIC\_STACKALLOC() {#aab27d9247786dc51e03654aff9d9c050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerWindowsDYNAMIC_STACKALLOC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 16188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerWindowsGlobalTLSAddress() {#a55f4b80584ad352b3d449f5a9b3deab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerWindowsGlobalTLSAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 10301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerXConstraint() {#ac894c9f07fd0c5af812818eac7839de1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * AArch64TargetLowering::LowerXConstraint (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ConstraintVT)</td>
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


<p>Declaration at line 1278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 12184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerXOR() {#ada5ae42dc1f07e304ce9417b794ee0d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerXOR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 4252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerZERO\_EXTEND\_VECTOR\_INREG() {#af5d6e174e4955f6320f22ad135585a98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue AArch64TargetLowering::LowerZERO_EXTEND_VECTOR_INREG (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 13852 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### mayBeEmittedAsTailCall() {#a43ba19c62a3955754bb400923b1bfab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::mayBeEmittedAsTailCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *)</td>
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


<p>Declaration at line 1304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 26810 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### preferScalarizeSplat() {#ae6f426df2cb3f8ca0a5d33617ffade81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::preferScalarizeSplat (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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



<p>Declaration at line 1357 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29909 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### ReplaceBITCASTResults() {#ab2fc37cebc11869e096bbcc810ca9961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::ReplaceBITCASTResults (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 26964 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### ReplaceExtractSubVectorResults() {#a53e1aa06384ce7ae8901856b77eca01a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::ReplaceExtractSubVectorResults (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27078 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### ReplaceNodeResults() {#a2996ad730f39f10d1f88157709a302af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::ReplaceNodeResults (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
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

<p>This callback is invoked when a node result type is illegal for the target, and the operation was registered to use 'custom' lowering for that result type.</p>


<p>The target places new result values for the node in Results (their number and types must exactly match those of the original return values of the node), or leaves Results empty, which indicates that the node is not to be custom lowered after all.</p>


<p>If the target has no operations that require custom lowering, it need not implement this. The default implementation aborts.</p>


<p>Declaration at line 1316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### saveVarArgRegisters() {#aaf295e86e6b556affb7ebbc204087e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64TargetLowering::saveVarArgRegisters (<a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; CCInfo, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1098 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 8302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldExpandBuildVectorWithShuffles() {#a7b0c22ee470e91ea51efea814d08583b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldExpandBuildVectorWithShuffles (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, unsigned DefinedValues)</td>
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



<p>Declaration at line 1050 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 15542 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldExtendGSIndex() {#a3bb63d9c10cea2e2af535f9d2b6b4e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldExtendGSIndex (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> &amp; EltTy)</td>
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

<p>Returns true if the index type for a masked gather/scatter requires extending.</p>

<p>Declaration at line 1300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 6547 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldLocalize() {#a656c4ad00931beff8c0c2d5e5ee91066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldLocalize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not <span class="doxyComputerOutput">MI</span> needs to be moved close to its uses.</p>

<p>Declaration at line 1328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 28244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldNormalizeToSelectSequence() {#a9a68789b0668c98f7088a6cb3f4c9614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldNormalizeToSelectSequence (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Returns true if we should normalize select(N0&amp;N1, X, Y) =&gt; select(N0, select(N1, X, Y), Y) and select(N0|N1, X, Y) =&gt; select(N0, select(N1, X, Y, Y)) if it is likely that it saves us from materializing N0 and N1 in an integer register.</p>


<p>Targets that are able to perform and/or on flags should return false here.</p>


<p>Declaration at line 1324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 27946 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldRemoveExtendFromGSIndex() {#a194a96b437faf888dcb1dd4bb3a31d85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::shouldRemoveExtendFromGSIndex (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Extend, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> DataVT)</td>
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



<p>Declaration at line 1301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 6556 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldScalarizeBinop() {#a5a704a52de47d9799d238e5ae1bcbf43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64TargetLowering::shouldScalarizeBinop (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> VecOp)</td>
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

<p>Try to convert an extract element of a vector binary operation into an extract element followed by a scalar operation.</p>

<p>Definition at line 1363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>

</div>
</div>

### SimplifyDemandedBitsForTargetNode() {#ac597a3f3ab29584848ef10f346aa75ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64TargetLowering::SimplifyDemandedBitsForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO, unsigned Depth)</td>
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


<p>Declaration at line 1331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>, definition at line 29667 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a>.</p>

</div>
</div>

### softPromoteHalfType() {#a56942071a0d88366724a8c7477728cf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64TargetLowering::softPromoteHalfType ()</td>
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



<p>Definition at line 1361 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BumpAlloc {#a64747852028af5890d0089b384f1429f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BumpPtrAllocator llvm::AArch64TargetLowering::BumpAlloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1040 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>

</div>
</div>

### Saver {#a0e3e0f0f1192eb7448df84112877020e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringSaver llvm::AArch64TargetLowering::Saver {BumpAlloc}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>

</div>
</div>

### Subtarget {#a5f48f162b567cbab885913376db0fac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64Subtarget* llvm::AArch64TargetLowering::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep a pointer to the <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> around so that we can make the right decision when generating code for different targets.</p>

<p>Definition at line 1038 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp">AArch64ISelLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
