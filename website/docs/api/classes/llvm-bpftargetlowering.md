---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bpftargetlowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BPFTargetLowering` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::BPFTargetLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">Target/BPF/BPFISelLowering.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96722a41714a1c1b003e935c4e6c2133">BPFTargetLowering</a> (const TargetMachine &amp;TM, const BPFSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4ad980607ac7119421934b6c87a38c2">LowerOperation</a> (SDValue Op, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is invoked for operations that are unsupported by the target, which are registered to use 'custom' lowering, and whose defined values are all legal. <a href="#ab4ad980607ac7119421934b6c87a38c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c0506cb04fc518bb931dfdf1761ccc6">getTargetNodeName</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns the name of a target specific DAG node. <a href="#a2c0506cb04fc518bb931dfdf1761ccc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5deea162724d41bb06ae52a3a76cd90e">isOffsetFoldingLegal</a> (const GlobalAddressSDNode *GA) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if folding a constant offset with the given GlobalAddress is legal. <a href="#a5deea162724d41bb06ae52a3a76cd90e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116">BPFTargetLowering::ConstraintType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00fc80b3fa328fbe28fd9c3e7c336049">getConstraintType</a> (StringRef Constraint) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a constraint, return the type of constraint it is for this target. <a href="#a00fc80b3fa328fbe28fd9c3e7c336049">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb5e73aa86ef5c3747a4fa348274ad20">getRegForInlineAsmConstraint</a> (const TargetRegisterInfo *TRI, StringRef Constraint, MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a physical register constraint (e.g. <a href="#aeb5e73aa86ef5c3747a4fa348274ad20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac190f0cf5627568bd97cf1e5b24ce57d">EmitInstrWithCustomInserter</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'usesCustomInserter' flag. <a href="#ac190f0cf5627568bd97cf1e5b24ce57d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee32075f2d16275b1de47f684ef1ed3">getHasAlu32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e273735592f5be1f8b422294db8d272">getHasJmp32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fe1c1fe3a2ed9773b4af92b7f38e3c0">getHasJmpExt</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a6b7bbd00826a8ecf80a495060d1479">getSetCCResultType</a> (const DataLayout &amp;DL, LLVMContext &amp;Context, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a> of the result of SETCC operations. <a href="#a8a6b7bbd00826a8ecf80a495060d1479">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf3f0b8464b02185e2bef04cdba3ec25">getScalarShiftAmountTy</a> (const DataLayout &amp;, EVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type to use for a scalar shift opcode, given the shifted amount type. <a href="#acf3f0b8464b02185e2bef04cdba3ec25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a531f88e0075087122625fd97f1d3c676">LowerSDIVSREM</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adada9de02141b788e3b366a82a1527b6">LowerDYNAMIC_STACKALLOC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eea317e1ee1f23b81adaf1eb80e7a48">LowerBR_CC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9db88d2f72de5f15c6612eb22dbed8c4">LowerSELECT_CC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7d9754b677052ecd872bca057cccc85">LowerConstantPool</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd5222718471923217e52468aeae6f31">LowerGlobalAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aec090bdefc987721e19b9b1dc49be849">getAddr</a> (NodeTy *N, SelectionDAG &amp;DAG, unsigned Flags=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72c1cbafc2bd87495cfcd0a2195e9957">LowerCallResult</a> (SDValue Chain, SDValue InGlue, CallingConv::ID CallConv, bool IsVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;DL, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc61bb0f828ea8ee948c13c97eda5bd">LowerCall</a> (TargetLowering::CallLoweringInfo &amp;CLI, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower calls into the specified DAG. <a href="#a9bc61bb0f828ea8ee948c13c97eda5bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab90b927707f9a2b6f46ebe0485e389f9">LowerFormalArguments</a> (SDValue Chain, CallingConv::ID CallConv, bool IsVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;DL, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower the incoming (formal) arguments, described by the Ins array, into the specified DAG. <a href="#ab90b927707f9a2b6f46ebe0485e389f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0481d58bd6d44b22bc54368538fe9fab">LowerReturn</a> (SDValue Chain, CallingConv::ID CallConv, bool IsVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; SDValue &gt; &amp;OutVals, const SDLoc &amp;DL, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower outgoing return values, described by the Outs array, into the specified DAG. <a href="#a0481d58bd6d44b22bc54368538fe9fab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63980d715e481048ac912cde68f9d161">ReplaceNodeResults</a> (SDNode *N, SmallVectorImpl&lt; SDValue &gt; &amp;Results, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is invoked when a node result type is illegal for the target, and the operation was registered to use 'custom' lowering for that result type. <a href="#a63980d715e481048ac912cde68f9d161">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d6fb422adcc57ed0a4c2e83def23850">getOptimalMemOpType</a> (const MemOp &amp;Op, const AttributeList &amp;FuncAttributes) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the target specific optimal type for load and store operations as a result of memset, memcpy, and memmove lowering. <a href="#a7d6fb422adcc57ed0a4c2e83def23850">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a795d6adee7828fc1f1e17301ef24e6bc">isIntDivCheap</a> (EVT VT, AttributeList Attr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if integer divide is usually cheaper than a sequence of several shifts, adds, and multiplies for this target. <a href="#a795d6adee7828fc1f1e17301ef24e6bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f953ceddcd7b68326bc7f34a8402a32">shouldConvertConstantLoadToIntImm</a> (const APInt &amp;Imm, Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is beneficial to convert a load of a constant to just the constant itself. <a href="#a2f953ceddcd7b68326bc7f34a8402a32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cd7cce72d7ecd9ff8d97c1c95ea3e4c">shouldReduceLoadWidth</a> (SDNode *Load, ISD::LoadExtType ExtTy, EVT NewVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to reduce a load to a smaller type. <a href="#a6cd7cce72d7ecd9ff8d97c1c95ea3e4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a175fe0422d7b32a3340dcad8dc5870ca">isLegalAddressingMode</a> (const DataLayout &amp;DL, const AddrMode &amp;AM, Type *Ty, unsigned AS, Instruction *I=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the addressing mode represented by AM is legal for this target, for a load/store of the specified type. <a href="#a175fe0422d7b32a3340dcad8dc5870ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd26803c95ebf4660b4ba6284cadf7ac">isTruncateFree</a> (Type *Ty1, Type *Ty2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's free to truncate a value of type FromTy to type ToTy. <a href="#abd26803c95ebf4660b4ba6284cadf7ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ffdf7ba3bb3adb2b0442441bd82148e">isTruncateFree</a> (EVT VT1, EVT VT2) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51fba6c4da1335bd16c6c1bb286c5048">isZExtFree</a> (Type *Ty1, Type *Ty2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if any actual instruction that defines a value of type FromTy implicitly zero-extends the value to ToTy in the result register. <a href="#a51fba6c4da1335bd16c6c1bb286c5048">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26d5024f1cf0d7de62cc16a557bb23b1">isZExtFree</a> (EVT VT1, EVT VT2) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab49e6efb50ae1f647bbcc56ed81ed351">isZExtFree</a> (SDValue Val, EVT VT2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if zero-extending the specific node Val to type VT2 is free (either because it's implicitly zero-extended such as <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> ldrb / ldrh or because it's folded such as <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> zero-extending loads). <a href="#ab49e6efb50ae1f647bbcc56ed81ed351">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99abadce4b74a5165cf4826a314b58da">EmitSubregExt</a> (MachineInstr &amp;MI, MachineBasicBlock *BB, unsigned Reg, bool isSigned) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b4561aa6ad9df7c438381f202c76ac">EmitInstrWithCustomInserterMemcpy</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a7ac62d898d099a743f441f3d8ec00e">HasAlu32</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab6cb4ae04d708dc6d13300eb53b6dad">HasJmp32</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ab18726949a002cab23697b9812c9fa">HasJmpExt</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d244357c280145ed724bf5cc4d38647">HasMovsx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dbff34b4e197e7fb4ba9c71763283d7">MaxArgs</a> = 5</td>
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


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BPFTargetLowering() {#a96722a41714a1c1b003e935c4e6c2133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BPFTargetLowering::BPFTargetLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bpfsubtarget">BPFSubtarget</a> &amp; STI)</td>
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



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7c45a718f16057459d95d09d42ec6902">llvm::TargetLoweringBase::addRegisterClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30649569b517a279a32fb3b48cc154e0">llvm::ISD::ATOMIC_CMP_SWAP_WITH_SUCCESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf5f612de1a25451c9a0c33d77bf3e74">llvm::ISD::ATOMIC_LOAD_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a905925a49cdc6b4a6017d215820dad30">llvm::ISD::ATOMIC_LOAD_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4112a866197a97a70bdc78ef92c79b4c">llvm::ISD::ATOMIC_LOAD_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a428ec1341b34eafa63518914e7f5ddf0">llvm::ISD::ATOMIC_LOAD_XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad728a4b56d49f39375881511d8d3118d">llvm::ISD::ATOMIC_SWAP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp/#a4b8c087a490f10055c3401307a857fab">BPFExpandMemcpyInOrder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb">llvm::ISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716d19ebad1927a2e8dd5fe3f951f882">llvm::ISD::BR_JT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716765ad6ce5be71f987cd2097b1cdbf">llvm::ISD::BRIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6df03220bbe2ea3cfb905f36fb26822c">llvm::TargetLoweringBase::computeRegisterProperties</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c">llvm::ISD::CTLZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0340c8d57d1dcebc43a00412989583d3">llvm::ISD::CTLZ_ZERO_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a991d07d163bd4d9984cf1ef36e92c214">llvm::ISD::CTPOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6da41a113af0909470baea7486b3386b">llvm::ISD::CTTZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a601e66a26efd05520f7cb26aef3af340">llvm::ISD::CTTZ_ZERO_UNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa3441acf8576e4bbf48e9bd73ca3c0d8c">llvm::TargetLoweringBase::Custom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa71ac22470bf853868fe6b39a25bac72">llvm::ISD::DYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa4b85349547c5b6126817e10152007931">llvm::TargetLoweringBase::Expand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">llvm::ISD::EXTLOAD</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfselectiondaginfo/#adec191a7bf7eccb4439c3270d688e999">llvm::BPFSelectionDAGInfo::getCommonMaxStoresPerMemFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfsubtarget/#af9a921127a02db4e41f601c83ad2a7df">llvm::BPFSubtarget::getHasAlu32</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfsubtarget/#abed21af3c3ed410fbbde5a0ec67c79a6">llvm::BPFSubtarget::getHasJmp32</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfsubtarget/#a73f4afceaae849cc2444831fefb7045f">llvm::BPFSubtarget::getHasJmpExt</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfsubtarget/#ac8d35dad93874ab572c7754aacaf6fc9">llvm::BPFSubtarget::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfsubtarget/#a8cbb387a7582a2af736a8f71e8c61137">llvm::BPFSubtarget::getSelectionDAGInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfsubtarget/#aa5803e9679dc24980542992d1e36f48c">llvm::BPFSubtarget::hasLdsx</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfsubtarget/#ab651fa4ef89db6d242a46450767e21b5">llvm::BPFSubtarget::hasMovsx</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfsubtarget/#a2a8fa3f4b46451c535b1e5936e519a9b">llvm::BPFSubtarget::hasSdivSmod</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7b339f69bc3995d23399a85f81af6018">llvm::MVT::integer_valuetypes</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3111deca0523de0afcc110cf020ebaaf">llvm::TargetLoweringBase::MaxLoadsPerMemcmp</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aae9cf790eaa990b803a93058582d78e8">llvm::TargetLoweringBase::MaxLoadsPerMemcmpOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aefbee33131c130f8f691c9a482f5fc40">llvm::TargetLoweringBase::MaxStoresPerMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1695feb44cd6dd30c64697360f1e76d3">llvm::TargetLoweringBase::MaxStoresPerMemcpyOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6d0f43699563375800a45f45bc11ff49">llvm::TargetLoweringBase::MaxStoresPerMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7800cede44a09d00fcc61b9087c20d85">llvm::TargetLoweringBase::MaxStoresPerMemmoveOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9830bda9bf50bfdab4c10954cc6fb1ac">llvm::TargetLoweringBase::MaxStoresPerMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a67f472063b7db365d0b5da597871e03d">llvm::TargetLoweringBase::MaxStoresPerMemsetOptSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa2a7c3eccf06b41e4275bbeadb46d22e">llvm::ISD::MULHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8a80d3b085af08f0dce1724207ef99b5">llvm::ISD::MULHU</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aaba91ac521e4f01f57413216273fd7b7f">llvm::TargetLoweringBase::Promote</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715">llvm::ISD::ROTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a874f66e1efe5be79552bbe7ee3121a">llvm::ISD::SDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6b928e5a6718acab4fa0030ce9198e8a">llvm::TargetLoweringBase::setBooleanContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad1d4d71bf37fea6a3170f27438d41e6d">llvm::TargetLoweringBase::setLoadExtAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4df001a3c611cc8b423ca0e54560210f">llvm::TargetLoweringBase::setMaxAtomicSizeInBitsSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6566d8c65c03ad2f7b18ed08f0e7f208">llvm::TargetLoweringBase::setMinFunctionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a07c0c67913bb543fc45ce9ef65ef260a">llvm::TargetLoweringBase::setOperationAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8bb50938977c871d4dfa617d1b759a9a">llvm::TargetLoweringBase::setPrefFunctionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab8a44fb1f49bcfbed806fef69301a67a">llvm::TargetLoweringBase::setStackPointerRegisterToSaveRestore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1354c6f8508d6cd697dc89a5d9a52dfd">llvm::ISD::SMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a023a9de787026fe61b024476bf9c32cb">llvm::ISD::STACKRESTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a031ce694e40832d40a163d7254a8df14">llvm::ISD::STACKSAVE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aaa96f111a59a7a2e7f9c689b344543df">llvm::TargetLowering::TargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a257ffa49107e2db978e8a6e2688ada">llvm::ISD::UDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a79c959df09509d7ff66d9b04bc40d18d">llvm::ISD::UMUL_LOHI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a0e2d72cfdcc49d2d189f440b3cc31dff">llvm::TargetLoweringBase::ZeroOrOneBooleanContent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### EmitInstrWithCustomInserter() {#ac190f0cf5627568bd97cf1e5b24ce57d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * BPFTargetLowering::EmitInstrWithCustomInserter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 825 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4874816314c3308be0bf1e71de2078d8">llvm::MachineBasicBlock::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp/#aff7521dff7b86d6970cbfedfe2b25592">SET_NEWCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a7f47862de23f7210f88ccf98ae1efbe4">llvm::ISD::SETGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a5ad12b466e3a5900d0c307b301465d25">llvm::ISD::SETGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ab49f81c2ecbbff3d0fbe55dd46353774">llvm::ISD::SETLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a6f05a09edb671910f85f8665981cbde9">llvm::ISD::SETLT</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a>.</p>

</div>
</div>

### getConstraintType() {#a00fc80b3fa328fbe28fd9c3e7c336049}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BPFTargetLowering::ConstraintType BPFTargetLowering::getConstraintType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a constraint, return the type of constraint it is for this target.</p>

<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a1d7718fd43ac0a5c715686a76f9cfd89">llvm::TargetLowering::C_RegisterClass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a45b2deb637d370d68d3bd3786c21e415">llvm::TargetLowering::getConstraintType</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### getHasAlu32() {#a7ee32075f2d16275b1de47f684ef1ed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BPFTargetLowering::getHasAlu32 ()</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>.</p>


<p>Referenced by <a href="#acf3f0b8464b02185e2bef04cdba3ec25">getScalarShiftAmountTy</a> and <a href="#a8a6b7bbd00826a8ecf80a495060d1479">getSetCCResultType</a>.</p>

</div>
</div>

### getHasJmp32() {#a1e273735592f5be1f8b422294db8d272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BPFTargetLowering::getHasJmp32 ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>.</p>

</div>
</div>

### getHasJmpExt() {#a3fe1c1fe3a2ed9773b4af92b7f38e3c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BPFTargetLowering::getHasJmpExt ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>.</p>

</div>
</div>

### getRegForInlineAsmConstraint() {#aeb5e73aa86ef5c3747a4fa348274ad20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, const TargetRegisterClass * &gt; BPFTargetLowering::getRegForInlineAsmConstraint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#af09507c47dcb4cdb2a13064aaa6d5243">llvm::TargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getScalarShiftAmountTy() {#acf3f0b8464b02185e2bef04cdba3ec25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT BPFTargetLowering::getScalarShiftAmountTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="#a7ee32075f2d16275b1de47f684ef1ed3">getHasAlu32</a>.</p>

</div>
</div>

### getSetCCResultType() {#a8a6b7bbd00826a8ecf80a495060d1479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT BPFTargetLowering::getSetCCResultType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a> of the result of SETCC operations.</p>

<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 962 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>Reference <a href="#a7ee32075f2d16275b1de47f684ef1ed3">getHasAlu32</a>.</p>

</div>
</div>

### getTargetNodeName() {#a2c0506cb04fc518bb931dfdf1761ccc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * BPFTargetLowering::getTargetNodeName (unsigned Opcode)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bpfisd/#ad1b9f269787fa365335630c3d64db10ca75975f285edfc06ebf5a08a458ce7fd3">llvm::BPFISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bpfisd/#ad1b9f269787fa365335630c3d64db10caca42e2eb24aaf810e42e359c3480b407">llvm::BPFISD::CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bpfisd/#ad1b9f269787fa365335630c3d64db10ca658b923d6fa2a7d735fd11f1ccc0be67">llvm::BPFISD::FIRST_NUMBER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bpfisd/#ad1b9f269787fa365335630c3d64db10cabff0bc85d03f121e5ef54fca06dafe84">llvm::BPFISD::MEMCPY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bpfisd/#ad1b9f269787fa365335630c3d64db10cae41726bb5550367a07c5a671858be7b5">llvm::BPFISD::RET_GLUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bpfisd/#ad1b9f269787fa365335630c3d64db10ca505121606b82b45e459488d26838235a">llvm::BPFISD::SELECT_CC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bpfisd/#ad1b9f269787fa365335630c3d64db10ca8bed21105d5d2173d31b4f0c3611f183">llvm::BPFISD::Wrapper</a>.</p>

</div>
</div>

### isOffsetFoldingLegal() {#a5deea162724d41bb06ae52a3a76cd90e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFTargetLowering::isOffsetFoldingLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * GA)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### LowerOperation() {#ab4ad980607ac7119421934b6c87a38c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BPFTargetLowering::LowerOperation (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb">llvm::ISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa71ac22470bf853868fe6b39a25bac72">llvm::ISD::DYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### EmitInstrWithCustomInserterMemcpy() {#a31b4561aa6ad9df7c438381f202c76ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * BPFTargetLowering::EmitInstrWithCustomInserterMemcpy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 794 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### EmitSubregExt() {#a99abadce4b74a5165cf4826a314b58da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned BPFTargetLowering::EmitSubregExt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, unsigned Reg, bool isSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 762 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### getAddr() {#aec090bdefc987721e19b9b1dc49be849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BPFTargetLowering::getAddr (NodeTy * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### getOptimalMemOpType() {#a7d6fb422adcc57ed0a4c2e83def23850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::BPFTargetLowering::getOptimalMemOpType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memop">MemOp</a> &amp; Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &amp;)</td>
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

<p>Returns the target specific optimal type for load and store operations as a result of memset, memcpy, and memmove lowering.</p>


<p>It returns EVT::Other if the type should be determined using generic target-independent logic.</p>


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>.</p>

</div>
</div>

### isIntDivCheap() {#a795d6adee7828fc1f1e17301ef24e6bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BPFTargetLowering::isIntDivCheap (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> Attr)</td>
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

<p>Return true if integer divide is usually cheaper than a sequence of several shifts, adds, and multiplies for this target.</p>


<p>The definition of "cheaper" may depend on whether we're optimizing for speed or for size.</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>.</p>

</div>
</div>

### isLegalAddressingMode() {#a175fe0422d7b32a3340dcad8dc5870ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFTargetLowering::isLegalAddressingMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode">AddrMode</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned AddrSpace, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
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


<p>The type may be VoidTy, in which case only return true if the addressing mode is legal for a load/store of any legal type. TODO: Handle pre/postinc as well.</p>


<p>If the address space cannot be determined, it will be -1.</p>


<p>TODO: Remove default argument</p>


<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 972 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### isTruncateFree() {#abd26803c95ebf4660b4ba6284cadf7ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFTargetLowering::isTruncateFree (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * FromTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ToTy)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### isTruncateFree() {#a3ffdf7ba3bb3adb2b0442441bd82148e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFTargetLowering::isTruncateFree (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT1, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT2)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### isZExtFree() {#a51fba6c4da1335bd16c6c1bb286c5048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFTargetLowering::isZExtFree (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * FromTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ToTy)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### isZExtFree() {#a26d5024f1cf0d7de62cc16a557bb23b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFTargetLowering::isZExtFree (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT1, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT2)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### isZExtFree() {#ab49e6efb50ae1f647bbcc56ed81ed351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFTargetLowering::isZExtFree (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT2)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBR\_CC() {#a9eea317e1ee1f23b81adaf1eb80e7a48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BPFTargetLowering::LowerBR_CC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCall() {#a9bc61bb0f828ea8ee948c13c97eda5bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BPFTargetLowering::LowerCall (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">TargetLowering::CallLoweringInfo</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCallResult() {#a72c1cbafc2bd87495cfcd0a2195e9957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BPFTargetLowering::LowerCallResult (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> InGlue, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool IsVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### LowerConstantPool() {#ac7d9754b677052ecd872bca057cccc85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BPFTargetLowering::LowerConstantPool (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 754 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### LowerDYNAMIC\_STACKALLOC() {#adada9de02141b788e3b366a82a1527b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BPFTargetLowering::LowerDYNAMIC_STACKALLOC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFormalArguments() {#ab90b927707f9a2b6f46ebe0485e389f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BPFTargetLowering::LowerFormalArguments (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalAddress() {#acd5222718471923217e52468aeae6f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BPFTargetLowering::LowerGlobalAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### LowerReturn() {#a0481d58bd6d44b22bc54368538fe9fab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BPFTargetLowering::LowerReturn (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSDIVSREM() {#a531f88e0075087122625fd97f1d3c676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BPFTargetLowering::LowerSDIVSREM (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSELECT\_CC() {#a9db88d2f72de5f15c6612eb22dbed8c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BPFTargetLowering::LowerSELECT_CC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 687 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### ReplaceNodeResults() {#a63980d715e481048ac912cde68f9d161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFTargetLowering::ReplaceNodeResults (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>, definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### shouldConvertConstantLoadToIntImm() {#a2f953ceddcd7b68326bc7f34a8402a32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BPFTargetLowering::shouldConvertConstantLoadToIntImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Return true if it is beneficial to convert a load of a constant to just the constant itself.</p>


<p>On some targets it might be more efficient to use a combination of arithmetic instructions to materialize the constant instead of loading it from a constant pool.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>.</p>

</div>
</div>

### shouldReduceLoadWidth() {#a6cd7cce72d7ecd9ff8d97c1c95ea3e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BPFTargetLowering::shouldReduceLoadWidth (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7">ISD::LoadExtType</a> ExtTy, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> NewVT)</td>
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

<p>Return true if it is profitable to reduce a load to a smaller type.</p>


<p>Example: (i16 (trunc (i32 (load x))) -&gt; i16 load x</p>


<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HasAlu32 {#a7a7ac62d898d099a743f441f3d8ec00e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BPFTargetLowering::HasAlu32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>.</p>

</div>
</div>

### HasJmp32 {#aab6cb4ae04d708dc6d13300eb53b6dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BPFTargetLowering::HasJmp32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>.</p>

</div>
</div>

### HasJmpExt {#a0ab18726949a002cab23697b9812c9fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BPFTargetLowering::HasJmpExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>.</p>

</div>
</div>

### HasMovsx {#a3d244357c280145ed724bf5cc4d38647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BPFTargetLowering::HasMovsx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### MaxArgs {#a7dbff34b4e197e7fb4ba9c71763283d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const size_t BPFTargetLowering::MaxArgs = 5</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
