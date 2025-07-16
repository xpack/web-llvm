---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/x86targetlowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86TargetLowering` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::X86TargetLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">Target/X86/X86ISelLowering.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9e81fca4b22706c50ad62e3241b6286">X86TargetLowering</a> (const X86TargetMachine &amp;TM, const X86Subtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14ba729e50c70d2bff3f12c884209140">getJumpTableEncoding</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the entry encoding for a jump table in the current function. <a href="#a14ba729e50c70d2bff3f12c884209140">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a2c182f696ccea7f69622fb51c70a3f">useSoftFloat</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7fcaa7855f4688864e1315a38ab3694">markLibCallAttributes</a> (MachineFunction *MF, unsigned CC, ArgListTy &amp;Args) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c9434966be55f571aeedb8a356b5b1c">getScalarShiftAmountTy</a> (const DataLayout &amp;, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type to use for a scalar shift opcode, given the shifted amount type. <a href="#a4c9434966be55f571aeedb8a356b5b1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3e16079a117749c3a3ab03753982e0e">LowerCustomJumpTableEntry</a> (const MachineJumpTableInfo *MJTI, const MachineBasicBlock *MBB, unsigned uid, MCContext &amp;Ctx) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b5f9da7c8b5d244b67be30f07debf6c">getPICJumpTableRelocBase</a> (SDValue Table, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns relocation base for the given PIC jumptable. <a href="#a0b5f9da7c8b5d244b67be30f07debf6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a424abc19654b712885d63747e7f5b4db">getPICJumpTableRelocBaseExpr</a> (const MachineFunction *MF, unsigned JTI, MCContext &amp;Ctx) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This returns the relocation base for the given PIC jumptable, the same as getPICJumpTableRelocBase, but as an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a>. <a href="#a424abc19654b712885d63747e7f5b4db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fcc58c4d285835e0ac6fc644012b0be">getByValTypeAlignment</a> (Type *Ty, const DataLayout &amp;DL) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the desired alignment for ByVal aggregate function arguments in the caller parameter area. <a href="#a4fcc58c4d285835e0ac6fc644012b0be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53dee73973a09e035447943bb5bde29e">getOptimalMemOpType</a> (const MemOp &amp;Op, const AttributeList &amp;FuncAttributes) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>It returns EVT::Other if the type should be determined using generic target-independent logic. <a href="#a53dee73973a09e035447943bb5bde29e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4458afa9d4b40fe7c439f81cd5481366">isSafeMemOpType</a> (MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it's safe to use load / store of the specified type to expand memcpy / memset inline. <a href="#a4458afa9d4b40fe7c439f81cd5481366">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a78b1cfe835bfe405897b9b75cf17fb">isMemoryAccessFast</a> (EVT VT, Align Alignment) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fdb4a73925c17adcb4eaeafda02978d">allowsMisalignedMemoryAccesses</a> (EVT VT, unsigned AS, Align Alignment, MachineMemOperand::Flags Flags, unsigned *Fast) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target allows unaligned memory accesses of the specified type. <a href="#a7fdb4a73925c17adcb4eaeafda02978d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acca525d32f859c8c653921b5fff62ed3">allowsMemoryAccess</a> (LLVMContext &amp;Context, const DataLayout &amp;DL, EVT VT, unsigned AddrSpace, Align Alignment, MachineMemOperand::Flags Flags=MachineMemOperand::MONone, unsigned *Fast=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function returns true if the memory access is aligned or if the target allows this specific unaligned memory access. <a href="#acca525d32f859c8c653921b5fff62ed3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76385ca67c48554c408107c686ed0c68">allowsMemoryAccess</a> (LLVMContext &amp;Context, const DataLayout &amp;DL, EVT VT, const MachineMemOperand &amp;MMO, unsigned *Fast) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d437e0047c2e5a049151f46d9dd2d09">LowerOperation</a> (SDValue Op, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide custom lowering hooks for some operations. <a href="#a3d437e0047c2e5a049151f46d9dd2d09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af77fd362607d101a7080481254ee2fe3">ReplaceNodeResults</a> (SDNode *N, SmallVectorImpl&lt; SDValue &gt; &amp;Results, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the results of node with an illegal result type with new values built out of custom code. <a href="#af77fd362607d101a7080481254ee2fe3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a91c61d0657477fe6583b566dca7fb7">PerformDAGCombine</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be invoked for all target nodes and for any target-independent nodes that the target has registered with invoke it for. <a href="#a0a91c61d0657477fe6583b566dca7fb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cc0d655a91ab6eed7a5614e9482b2a6">preferABDSToABSWithNSW</a> (EVT VT) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a099d3d496bc5d6948101f22543d154b9">preferSextInRegOfTruncate</a> (EVT TruncVT, EVT VT, EVT ExtVT) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6601dcbc51d3043764e700c20db26e9c">isXAndYEqZeroPreferableToXAndYEqY</a> (ISD::CondCode Cond, EVT VT) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4217293101179a3839b8afb1fafb2e0d">isTypeDesirableForOp</a> (unsigned Opc, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target has native support for the specified value type and it is 'desirable' to use the type for the given node type. <a href="#a4217293101179a3839b8afb1fafb2e0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae344bf38282de26bb4d5783114a65eaf">IsDesirableToPromoteOp</a> (SDValue Op, EVT &amp;PVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target has native support for the specified value type and it is 'desirable' to use the type. <a href="#ae344bf38282de26bb4d5783114a65eaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac14a71b7c36f34100de107aadccc5578">TargetLowering::AndOrSETCCFoldKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad952c5828f21002a545e9de9f64cc4aa">isDesirableToCombineLogicOpOfSETCC</a> (const SDNode *LogicOp, const SDNode *SETCC0, const SDNode *SETCC1) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return prefered fold type, Abs if this is a vector, AddAnd if its an integer, None otherwise. <a href="#ad952c5828f21002a545e9de9f64cc4aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a402c372a2886c19770de2cc65b41a7e0">getNegatedExpression</a> (SDValue Op, SelectionDAG &amp;DAG, bool LegalOperations, bool ForCodeSize, NegatibleCost &amp;Cost, unsigned Depth) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the newly negated expression if the cost is not expensive and set the cost in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a></span> to indicate that if it is cheaper or neutral to do the negation. <a href="#a402c372a2886c19770de2cc65b41a7e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fd231b7f6dc1db67a2bb2f48bf5f342">EmitInstrWithCustomInserter</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'usesCustomInserter' flag. <a href="#a5fd231b7f6dc1db67a2bb2f48bf5f342">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3547e3af4263fb24bac33b211aa07fb">getTargetNodeName</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns the name of a target specific DAG node. <a href="#ab3547e3af4263fb24bac33b211aa07fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6940a3eec597c799eeee15cb0f7e808">mergeStoresAfterLegalization</a> (EVT MemVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do not merge vector stores after legalization because that may conflict with x86-specific store splitting optimizations. <a href="#ad6940a3eec597c799eeee15cb0f7e808">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66a0f33d36e31ddfbd254a77524f9192">canMergeStoresTo</a> (unsigned AddressSpace, EVT MemVT, const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns if it's reasonable to merge stores to MemVT size. <a href="#a66a0f33d36e31ddfbd254a77524f9192">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a504396336fa994725f3d8c3265e38ead">isCheapToSpeculateCttz</a> (Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is cheap to speculate a call to intrinsic cttz. <a href="#a504396336fa994725f3d8c3265e38ead">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10629e54ed902429f3c4c53e0073a198">isCheapToSpeculateCtlz</a> (Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is cheap to speculate a call to intrinsic ctlz. <a href="#a10629e54ed902429f3c4c53e0073a198">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4252a7b10bf920be7bc1da185d9c43b8">isCtlzFast</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if ctlz instruction is fast. <a href="#a4252a7b10bf920be7bc1da185d9c43b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1134e24a9f51b06d69b66aaede5eb422">isMultiStoresCheaperThanBitsMerge</a> (EVT LTy, EVT HTy) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is cheaper to split the store of a merged int val from a pair of smaller values into multiple stores. <a href="#a1134e24a9f51b06d69b66aaede5eb422">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af88464d58b1b70362b8ab991b0db2dbb">isMaskAndCmp0FoldingBeneficial</a> (const Instruction &amp;AndI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if the target supports combining a chain like: <a href="#af88464d58b1b70362b8ab991b0db2dbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e8d15fa57104d892b14366c39fafa77">hasAndNotCompare</a> (SDValue Y) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target should transform: (X &amp; Y) == Y ---&gt; (~X &amp; Y) == 0 (X &amp; Y) != Y ---&gt; (~X &amp; Y) != 0. <a href="#a8e8d15fa57104d892b14366c39fafa77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69fbe6a7969fadd37ebea537ba3041e3">hasAndNot</a> (SDValue Y) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target has a bitwise and-not operation: X = ~A &amp; B This can be used to simplify select or other instructions. <a href="#a69fbe6a7969fadd37ebea537ba3041e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97eec348be19ac2d04575b281d2456b7">hasBitTest</a> (SDValue X, SDValue Y) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target has a bit-test instruction: (X &amp; (1 &lt;&lt; Y)) ==/!= 0 This knowledge can be used to prevent breaking the pattern, or creating it if it could be recognized. <a href="#a97eec348be19ac2d04575b281d2456b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45b5bd9592a350b3994804b65f1eeaaf">shouldProduceAndByConstByHoistingConstFromShiftsLHSOfAnd</a> (SDValue X, ConstantSDNode *XC, ConstantSDNode *CC, SDValue Y, unsigned OldShiftOpcode, unsigned NewShiftOpcode, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given the pattern (X &amp; (C l&gt;&gt;/&lt;&lt; Y)) ==/!= 0 return true if it should be transformed into: ((X &lt;&lt;/l&gt;&gt; Y) &amp; C) ==/!= 0 WARNING: if 'X' is a constant, the fold may deadlock! <a href="#a45b5bd9592a350b3994804b65f1eeaaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a623fca6d1e6801438897a6335f1e4fb6">preferedOpcodeForCmpEqPiecesOfOperand</a> (EVT VT, unsigned ShiftOpc, bool MayTransformRotate, const APInt &amp;ShiftOrRotateAmt, const std::optional&lt; APInt &gt; &amp;AndMask) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79733c103f8a91ce6006567de49a6f40">preferScalarizeSplat</a> (SDNode *N) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/condmergingparams">CondMergingParams</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae825ce933018e12e8997a98923a1a4d8">getJumpConditionMergingParams</a> (Instruction::BinaryOps Opc, const Value *Lhs, const Value *Rhs) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85fb0d7e000c96b972014b0405aa9c88">shouldFoldConstantShiftPairToMask</a> (const SDNode *N, CombineLevel Level) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to fold a pair of shifts into a mask. <a href="#a85fb0d7e000c96b972014b0405aa9c88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaff89efc72db02240bc69c44c8f0691">shouldFoldMaskToVariableShiftPair</a> (SDValue Y) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>There are two ways to clear extreme bits (either low or high): Mask: x &amp; (-1 &lt;&lt; y) (the instcombine canonical form) Shifts: x &gt;&gt; y &lt;&lt; y Return true if the variant with 2 variable shifts is preferred. <a href="#adaff89efc72db02240bc69c44c8f0691">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a193b8c17079133af40829a1fef4adf6c">shouldTransformSignedTruncationCheck</a> (EVT XVT, unsigned KeptBits) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should we tranform the IR-optimal check for whether given truncation down into KeptBits would be truncating or not: (add x, (1 &lt;&lt; (KeptBits-1))) srccond (1 &lt;&lt; KeptBits) Into it's more traditional form: ((x &lt;&lt; C) a&gt;&gt; C) dstcond x Return true if we should transform. <a href="#a193b8c17079133af40829a1fef4adf6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1cfe6f1187d7ab1a0ada9cc119c1b2b4">ShiftLegalizationStrategy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bcf75579cf117a1b83a27dbe4d775d6">preferredShiftLegalizationStrategy</a> (SelectionDAG &amp;DAG, SDNode *N, unsigned ExpansionFactor) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51cb60d8c2758ff018c35468453c7eeb">shouldSplatInsEltVarIndex</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if inserting a scalar into a variable element of an undef vector is more efficiently handled by splatting the scalar instead. <a href="#a51cb60d8c2758ff018c35468453c7eeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a2c1154fe3e12011cb42fa9bfdc4387">shouldConvertFpToSat</a> (unsigned Op, EVT FPVT, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should we generate fp_to_si_sat and fp_to_ui_sat from type FPVT to type VT from min(max(fptoi)) saturation patterns. <a href="#a7a2c1154fe3e12011cb42fa9bfdc4387">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abba0e811da8d1436a96fda0e356a6d24">convertSetCCLogicToBitwiseLogic</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> bitwise logic to make pairs of compares more efficient. <a href="#abba0e811da8d1436a96fda0e356a6d24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52fdaa4464a4080f3b2883856462f6a7">hasFastEqualityCompare</a> (unsigned NumBits) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector-sized comparisons are fast using PCMPEQ + PMOVMSK or PTEST. <a href="#a52fdaa4464a4080f3b2883856462f6a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae93a1ba51c086441ec1b9ea4cdca853a">getSetCCResultType</a> (const DataLayout &amp;DL, LLVMContext &amp;Context, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value type to use for <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">ISD::SETCC</a>. <a href="#ae93a1ba51c086441ec1b9ea4cdca853a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc96b14a52d48d045a0a9d2cc9459a62">targetShrinkDemandedConstant</a> (SDValue Op, const APInt &amp;DemandedBits, const APInt &amp;DemandedElts, TargetLoweringOpt &amp;TLO) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0caaab3a18e77b9f48dc88b3b757dd6">computeKnownBitsForTargetNode</a> (const SDValue Op, KnownBits &amp;Known, const APInt &amp;DemandedElts, const SelectionDAG &amp;DAG, unsigned Depth=0) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine which of the bits specified in Mask are known to be either zero or one and return them in the KnownZero/KnownOne bitsets. <a href="#ae0caaab3a18e77b9f48dc88b3b757dd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa734719767b4f7faea1f7b40554f30be">ComputeNumSignBitsForTargetNode</a> (SDValue Op, const APInt &amp;DemandedElts, const SelectionDAG &amp;DAG, unsigned Depth) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the number of bits in the operation that are sign bits. <a href="#aa734719767b4f7faea1f7b40554f30be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a1dd27d36e829a2de3225991dac9c3e">SimplifyDemandedVectorEltsForTargetNode</a> (SDValue Op, const APInt &amp;DemandedElts, APInt &amp;KnownUndef, APInt &amp;KnownZero, TargetLoweringOpt &amp;TLO, unsigned Depth) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to simplify any target nodes based on the demanded vector elements, returning true on success. <a href="#a1a1dd27d36e829a2de3225991dac9c3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5681faab09fa140f67d47577193f2665">SimplifyDemandedVectorEltsForTargetShuffle</a> (SDValue Op, const APInt &amp;DemandedElts, unsigned MaskIndex, TargetLoweringOpt &amp;TLO, unsigned Depth) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fafb0a04f81d44e034566f1a758ea39">SimplifyDemandedBitsForTargetNode</a> (SDValue Op, const APInt &amp;DemandedBits, const APInt &amp;DemandedElts, KnownBits &amp;Known, TargetLoweringOpt &amp;TLO, unsigned Depth) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to simplify any target nodes based on the demanded bits/elts, returning true on success. <a href="#a6fafb0a04f81d44e034566f1a758ea39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30ea9932827054448251050d576b4874">SimplifyMultipleUseDemandedBitsForTargetNode</a> (SDValue Op, const APInt &amp;DemandedBits, const APInt &amp;DemandedElts, SelectionDAG &amp;DAG, unsigned Depth) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>More limited version of SimplifyDemandedBits that can be used to "look
through" ops that don't contribute to the DemandedBits/DemandedElts - bitwise ops etc. <a href="#a30ea9932827054448251050d576b4874">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2cb6bf0817b8dbe415405c7498b8ce7">isGuaranteedNotToBeUndefOrPoisonForTargetNode</a> (SDValue Op, const APInt &amp;DemandedElts, const SelectionDAG &amp;DAG, bool PoisonOnly, unsigned Depth) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this function can prove that <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> is never poison and, if <span class="doxyComputerOutput">PoisonOnly</span> is false, does not have undef bits. <a href="#ae2cb6bf0817b8dbe415405c7498b8ce7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2d807474cb0bf45eccd77f335159b8f">canCreateUndefOrPoisonForTargetNode</a> (SDValue Op, const APInt &amp;DemandedElts, const SelectionDAG &amp;DAG, bool PoisonOnly, bool ConsiderFlags, unsigned Depth) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> can create undef or poison from non-undef &amp; non-poison operands. <a href="#af2d807474cb0bf45eccd77f335159b8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34faa94759387be0a4881a7e227f6caf">isSplatValueForTargetNode</a> (SDValue Op, const APInt &amp;DemandedElts, APInt &amp;UndefElts, const SelectionDAG &amp;DAG, unsigned Depth) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if vector <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> has the same value across all <span class="doxyComputerOutput">DemandedElts</span>, indicating any elements which may be undef in the output <span class="doxyComputerOutput">UndefElts</span>. <a href="#a34faa94759387be0a4881a7e227f6caf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0914ba5d0ef25eca489b81cbf981517">isTargetCanonicalConstantNode</a> (SDValue Op) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given Opc is considered a canonical constant for the target, which should not be transformed back into a BUILD_VECTOR. <a href="#ad0914ba5d0ef25eca489b81cbf981517">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af23897e28e2e84966892e512317b6acc">getTargetConstantFromLoad</a> (LoadSDNode *LD) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns the constant pool value that will be loaded by LD. <a href="#af23897e28e2e84966892e512317b6acc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6da32121a396476129bc7577db0aad2">unwrapAddress</a> (SDValue N) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc0b03138cc7b455d625146b7091345d">getReturnAddressFrameIndex</a> (SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a687e754bf03f8d135bc899b49db74472">ExpandInlineAsm</a> (CallInst *CI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook allows the target to expand an inline asm call to be explicit llvm code if it wants to. <a href="#a687e754bf03f8d135bc899b49db74472">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116">ConstraintType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a370d811aff2e392f420421995d439701">getConstraintType</a> (StringRef Constraint) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a constraint letter, return the type of constraint for this target. <a href="#a370d811aff2e392f420421995d439701">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abc">ConstraintWeight</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac437e7230f2990fd60bf089f20ea2e78">getSingleConstraintMatchWeight</a> (AsmOperandInfo &amp;Info, const char *Constraint) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine constraint string and operand type and determine a weight value. <a href="#ac437e7230f2990fd60bf089f20ea2e78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa47f16031986718a30310f73c8c90c">LowerXConstraint</a> (EVT ConstraintVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to replace an X constraint, which matches anything, with another that has more specific requirements based on the type of the corresponding operand. <a href="#a2aa47f16031986718a30310f73c8c90c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8cc1f957026a793e58fec505e47a7c5">LowerAsmOperandForConstraint</a> (SDValue Op, StringRef Constraint, std::vector&lt; SDValue &gt; &amp;Ops, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower the specified operand into the Ops vector. <a href="#af8cc1f957026a793e58fec505e47a7c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ba8881f3b3a742488705f0d17bb2db5">getInlineAsmMemConstraint</a> (StringRef ConstraintCode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b67b537250936a616694b1bab0816dc">LowerAsmOutputForConstraint</a> (SDValue &amp;Chain, SDValue &amp;Flag, const SDLoc &amp;DL, const AsmOperandInfo &amp;Constraint, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle Lowering flag assembly outputs. <a href="#a1b67b537250936a616694b1bab0816dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a7237cd5cb35f9159b32a96f4b14541">getRegForInlineAsmConstraint</a> (const TargetRegisterInfo *TRI, StringRef Constraint, MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a physical register constraint (e.g. <a href="#a7a7237cd5cb35f9159b32a96f4b14541">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a79970217e7be886648d06d5fded3c">isLegalAddressingMode</a> (const DataLayout &amp;DL, const AddrMode &amp;AM, Type *Ty, unsigned AS, Instruction *I=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the addressing mode represented by AM is legal for this target, for a load/store of the specified type. <a href="#ad1a79970217e7be886648d06d5fded3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb85795e16fa504b6b2d37650c267b2b">addressingModeSupportsTLS</a> (const GlobalValue &amp;GV) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the targets addressing mode can target thread local storage (TLS). <a href="#adb85795e16fa504b6b2d37650c267b2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b29ba68187b5f5d44c6fc584b658d06">isLegalICmpImmediate</a> (int64_t Imm) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified immediate is legal icmp immediate, that is the target has icmp instructions which can compare a register against the immediate without having to materialize the immediate into a register. <a href="#a5b29ba68187b5f5d44c6fc584b658d06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a092cc6666d98dc58d90d67082beda499">isLegalAddImmediate</a> (int64_t Imm) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified immediate is legal add immediate, that is the target has add instructions which can add a register and the immediate without having to materialize the immediate into a register. <a href="#a092cc6666d98dc58d90d67082beda499">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e4a60b1f1249061764cf8d334c8e162">isLegalStoreImmediate</a> (int64_t Imm) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified immediate is legal for the value input of a store instruction. <a href="#a3e4a60b1f1249061764cf8d334c8e162">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae174548699928fd09f1b90077dfc2a48">isBinOp</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add x86-specific opcodes to the default list. <a href="#ae174548699928fd09f1b90077dfc2a48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0ee342efbe8b2fe6cf2b0bcfdf2619a">isCommutativeBinOp</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the opcode is a commutative binary operation. <a href="#ab0ee342efbe8b2fe6cf2b0bcfdf2619a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabf943e7fc68b0048d5278b5a35da3a9">isTruncateFree</a> (Type *Ty1, Type *Ty2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's free to truncate a value of type Ty1 to type Ty2. <a href="#aabf943e7fc68b0048d5278b5a35da3a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc2cb7b5433e21565a41f6154b7c816">isTruncateFree</a> (EVT VT1, EVT VT2) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c91bde4107b00ee5520f121253437ef">allowTruncateForTailCall</a> (Type *Ty1, Type *Ty2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a truncation from FromTy to ToTy is permitted when deciding whether a call is in tail position. <a href="#a9c91bde4107b00ee5520f121253437ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb13111bbf0c82193529692fd4017679">isZExtFree</a> (Type *Ty1, Type *Ty2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if any actual instruction that defines a value of type Ty1 implicit zero-extends the value to Ty2 in the result register. <a href="#acb13111bbf0c82193529692fd4017679">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd3f38eb5dc5b83e3a7aee22a0d501b7">isZExtFree</a> (EVT VT1, EVT VT2) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adda85bdff9375435866fa2bebaca4b27">isZExtFree</a> (SDValue Val, EVT VT2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if zero-extending the specific node Val to type VT2 is free (either because it's implicitly zero-extended such as <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> ldrb / ldrh or because it's folded such as <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> zero-extending loads). <a href="#adda85bdff9375435866fa2bebaca4b27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8605b738411a9018ae4e3ba5de54026">shouldConvertPhiType</a> (Type *From, Type *To) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a set in interconnected phis of type 'From' that are loaded/stored or bitcast to type 'To', return true if the set should be converted to 'To'. <a href="#ac8605b738411a9018ae4e3ba5de54026">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec5602ebffe4f185bb771a7ea328ad31">isVectorLoadExtDesirable</a> (SDValue) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if folding a vector load into ExtVal (a sign, zero, or any extend node) is profitable. <a href="#aec5602ebffe4f185bb771a7ea328ad31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5a3a214752cd4c83a68f99de65ad908">isFMAFasterThanFMulAndFAdd</a> (const MachineFunction &amp;MF, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if an FMA operation is faster than a pair of fmul and fadd instructions. <a href="#ab5a3a214752cd4c83a68f99de65ad908">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83185148c0d5d8353cc716271c560e66">isNarrowingProfitable</a> (SDNode *N, EVT SrcVT, EVT DestVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's profitable to narrow operations of type SrcVT to DestVT. <a href="#a83185148c0d5d8353cc716271c560e66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cd2ddff46dc5822bcc7666e336da52b">shouldFoldSelectWithIdentityConstant</a> (unsigned BinOpcode, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if pulling a binary operation into a select with an identity constant is profitable. <a href="#a5cd2ddff46dc5822bcc7666e336da52b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed6a89a13d6da0fb09c283664b86ccd0">getTgtMemIntrinsic</a> (IntrinsicInfo &amp;Info, const CallInst &amp;I, MachineFunction &amp;MF, unsigned Intrinsic) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an intrinsic, checks if on the target the intrinsic will need to map to a MemIntrinsicNode (touches memory). <a href="#aed6a89a13d6da0fb09c283664b86ccd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8394d225b325663032c0b724ce2e43bf">isFPImmLegal</a> (const APFloat &amp;Imm, EVT VT, bool ForCodeSize) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target can instruction select the specified FP immediate natively. <a href="#a8394d225b325663032c0b724ce2e43bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fdafe65d9378c70d936af1019040b0f">isShuffleMaskLegal</a> (ArrayRef&lt; int &gt; Mask, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets can use this to indicate that they only support <em>some</em> VECTOR_SHUFFLE operations, those with specific masks. <a href="#a9fdafe65d9378c70d936af1019040b0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf24a843e4c14485213d45230de71898">isVectorClearMaskLegal</a> (ArrayRef&lt; int &gt; Mask, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to isShuffleMaskLegal. <a href="#abf24a843e4c14485213d45230de71898">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf07f4afc0dc648abf4f548e2db2b7c8">areJTsAllowed</a> (const Function *Fn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if lowering to a jump table is allowed. <a href="#aaf07f4afc0dc648abf4f548e2db2b7c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab40e47d665eb61ef848654a1d6526f7d">getPreferredSwitchConditionType</a> (LLVMContext &amp;Context, EVT ConditionVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns preferred type for switch condition. <a href="#ab40e47d665eb61ef848654a1d6526f7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af67a690870634cfabaefd978dc3dd2e8">ShouldShrinkFPConstant</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true, then instruction selection should seek to shrink the FP constant of the specified type to a smaller type in order to save space and / or reduce runtime. <a href="#af67a690870634cfabaefd978dc3dd2e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ad23b58059ffd91df6a2dddf30c5d71">shouldReduceLoadWidth</a> (SDNode *Load, ISD::LoadExtType ExtTy, EVT NewVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we believe it is correct and profitable to reduce the load node to a smaller type. <a href="#a6ad23b58059ffd91df6a2dddf30c5d71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab32d538e8058be86b0efc0d970b35735">isScalarFPTypeInSSEReg</a> (EVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified scalar FP type is computed in an SSE register, not on the X87 floating point stack. <a href="#ab32d538e8058be86b0efc0d970b35735">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a711da9c348c7a96e4d79942afa0af105">shouldConvertConstantLoadToIntImm</a> (const APInt &amp;Imm, Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it is beneficial to convert a load of a constant to just the constant itself. <a href="#a711da9c348c7a96e4d79942afa0af105">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90cebf16a00cfcbf593595502bd34be9">reduceSelectOfFPConstantLoads</a> (EVT CmpOpVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to convert a select of FP constants into a constant pool load whose address depends on the select condition. <a href="#a90cebf16a00cfcbf593595502bd34be9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f30c99560e45f1031fe1855c73b02c">convertSelectOfConstantsToMath</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a select of constants (select Cond, C1, C2) should be transformed into simple math ops with the condition value. <a href="#a35f30c99560e45f1031fe1855c73b02c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaef16aaed0ce790c381e75d7c9253f1e">decomposeMulByConstant</a> (LLVMContext &amp;Context, EVT VT, SDValue C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to transform an integer multiplication-by-constant into simpler operations like shifts and adds. <a href="#aaef16aaed0ce790c381e75d7c9253f1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab75bfa0d750449f745ed10dba2f81e31">isExtractSubvectorCheap</a> (EVT ResVT, EVT SrcVT, unsigned Index) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if EXTRACT_SUBVECTOR is cheap for this result type with this index. <a href="#ab75bfa0d750449f745ed10dba2f81e31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa74ba35350fae122acd7284555740ba5">shouldScalarizeBinop</a> (SDValue) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scalar ops always have equal or better analysis/performance/power than the vector equivalent, so this always makes sense if the scalar op is supported. <a href="#aa74ba35350fae122acd7284555740ba5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afee5e52fd75b2906a16655fa264ee3d5">isExtractVecEltCheap</a> (EVT VT, unsigned Index) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract of a scalar FP value from index 0 of a vector is free. <a href="#afee5e52fd75b2906a16655fa264ee3d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0023312f4ffae5c8a127a8da0c812dba">shouldFormOverflowOp</a> (unsigned Opcode, EVT VT, bool MathUsed) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Overflow nodes should get combined/lowered to optimal instructions (they should allow eliminating explicit compares by getting flags from math ops). <a href="#a0023312f4ffae5c8a127a8da0c812dba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d9590a596760f98179ab0814b15318f">storeOfVectorConstantIsCheap</a> (bool IsZero, EVT MemVT, unsigned NumElem, unsigned AddrSpace) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is expected to be cheaper to do a store of vector constant with the given size and type for the address space than to store the individual scalar element constants. <a href="#a4d9590a596760f98179ab0814b15318f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ab3eaadf7f52ab7ca677e6c545e6508">isLoadBitCastBeneficial</a> (EVT LoadVT, EVT BitcastVT, const SelectionDAG &amp;DAG, const MachineMemOperand &amp;MMO) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the following transform is beneficial: fold (conv (load x)) -&gt; (load (conv*)x) On architectures that don't natively support some vector loads efficiently, casting the load to a smaller vector of larger types and loading is more efficient, however, this can be undone by optimizations in dag combiner. <a href="#a8ab3eaadf7f52ab7ca677e6c545e6508">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42f7160579c4a68a75447d21da859821">getRegisterByName</a> (const char *RegName, LLT VT, const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the name passed in. <a href="#a42f7160579c4a68a75447d21da859821">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcc17da43772e9fa8d8aeb458a8f2d98">getExceptionPointerRegister</a> (const Constant *PersonalityFn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register, this returns the register that receives the exception address on entry to an EH pad. <a href="#adcc17da43772e9fa8d8aeb458a8f2d98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3968afa27f1e806f9448f94527d61d53">getExceptionSelectorRegister</a> (const Constant *PersonalityFn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register, this returns the register that receives the exception typeid on entry to a landing pad. <a href="#a3968afa27f1e806f9448f94527d61d53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb9746b385314bc07403f471b1931a61">needsFixedCatchObjects</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0a481e8df0f6d0d536fa71fa5c5f3d9">createFastISel</a> (FunctionLoweringInfo &amp;funcInfo, const TargetLibraryInfo *libInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns a target specific <a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> object, or null if the target does not support "fast" ISel. <a href="#ae0a481e8df0f6d0d536fa71fa5c5f3d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cb54e7d62530f9e973ff35f6301de6a">getIRStackGuard</a> (IRBuilderBase &amp;IRB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the target has a standard location for the stack protector cookie, returns the address of that location. <a href="#a4cb54e7d62530f9e973ff35f6301de6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32acffd2f19c83d30c2955b094d7e96b">useLoadStackGuardNode</a> (const Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this function returns true, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> emits a LOAD_STACK_GUARD node when it is lowering Intrinsic::stackprotector. <a href="#a32acffd2f19c83d30c2955b094d7e96b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa25a7920eb37572630745203c9c50731">useStackGuardXorFP</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this function returns true, stack protection checks should XOR the frame pointer (or whichever pointer is used to address locals) into the stack guard value before checking it. <a href="#aa25a7920eb37572630745203c9c50731">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af30042e4c09138928b477e3834f0a13e">insertSSPDeclarations</a> (Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts necessary declarations for SSP (stack protection) purpose. <a href="#af30042e4c09138928b477e3834f0a13e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f631e7cc44c1035e858c667b345ec78">getSDagStackGuard</a> (const Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the variable that's previously inserted by insertSSPDeclarations, if any, otherwise return nullptr. <a href="#a8f631e7cc44c1035e858c667b345ec78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b927c27465f57caae75ac35b49409f">getSSPStackGuardCheck</a> (const Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the target has a standard stack protection check function that performs validation and error handling, returns the function. <a href="#a79b927c27465f57caae75ac35b49409f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4b65d0fe3e7a2dd0eed89a2c22d23bd">emitStackGuardXorFP</a> (SelectionDAG &amp;DAG, SDValue Val, const SDLoc &amp;DL) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae8b0683e3e2b366aaac8bca13553f42">getSafeStackPointerLocation</a> (IRBuilderBase &amp;IRB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target stores SafeStack pointer at a fixed offset in some non-standard address space, and populates the address space and offset as appropriate. <a href="#aae8b0683e3e2b366aaac8bca13553f42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168f3532cb1605bbc91fcc079892e357">BuildFILD</a> (EVT DstVT, EVT SrcVT, const SDLoc &amp;DL, SDValue Chain, SDValue Pointer, MachinePointerInfo PtrInfo, Align Alignment, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681">LegalizeTypeAction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac812947e59d1a47c994bc61bb372c743">getPreferredVectorAction</a> (MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Customize the preferred legalization strategy for certain types. <a href="#ac812947e59d1a47c994bc61bb372c743">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad34d40f5d0a64179484587b5012244b0">softPromoteHalfType</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c19f0fe8ae2a12ed0c5cf142a520522">getRegisterTypeForCallingConv</a> (LLVMContext &amp;Context, CallingConv::ID CC, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Certain combinations of ABIs, Targets and features require that types are legal for some operations and not for other operations. <a href="#a7c19f0fe8ae2a12ed0c5cf142a520522">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba30f84d7fd0dd3361ff92fe1e53d9ca">getNumRegistersForCallingConv</a> (LLVMContext &amp;Context, CallingConv::ID CC, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Certain targets require unusual breakdowns of certain types. <a href="#aba30f84d7fd0dd3361ff92fe1e53d9ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f81a81b890192ac2e40f2995080feaa">getVectorTypeBreakdownForCallingConv</a> (LLVMContext &amp;Context, CallingConv::ID CC, EVT VT, EVT &amp;IntermediateVT, unsigned &amp;NumIntermediates, MVT &amp;RegisterVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Certain targets such as MIPS require that some types such as vectors are always broken down into scalars in some contexts. <a href="#a9f81a81b890192ac2e40f2995080feaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48e8c06ef441f4292cca267972e02055">functionArgumentNeedsConsecutiveRegisters</a> (Type *Ty, CallingConv::ID CallConv, bool isVarArg, const DataLayout &amp;DL) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For some targets, an LLVM struct type must be broken down into multiple simple types, but the calling convention specifies that the entire struct must be passed in a block of consecutive registers. <a href="#a48e8c06ef441f4292cca267972e02055">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7a7243ff0d08f8e17239f3fab12a20f">isIntDivCheap</a> (EVT VT, AttributeList Attr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if integer divide is usually cheaper than a sequence of several shifts, adds, and multiplies for this target. <a href="#ac7a7243ff0d08f8e17239f3fab12a20f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d29a6154e85b01c7a17d09e23e71eca">supportSwiftError</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports swifterror attribute. <a href="#a4d29a6154e85b01c7a17d09e23e71eca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a212993bd851420cf4319ce3a0291578b">supportKCFIBundles</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports kcfi operand bundles. <a href="#a212993bd851420cf4319ce3a0291578b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89a6b95d310330e345c3aee6a07ffd96">EmitKCFICheck</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::instr_iterator &amp;MBBI, const TargetInstrInfo *TII) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9c3c65b113996cabc72bd6223410369">hasStackProbeSymbol</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if stack probing through a function call is requested. <a href="#ac9c3c65b113996cabc72bd6223410369">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cf46104ca48a9577dc4a61cf080003a">hasInlineStackProbe</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if stack probing through inline assembly is requested. <a href="#a5cf46104ca48a9577dc4a61cf080003a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e17e524fe1c82a26b5433b6e9715e3">getStackProbeSymbolName</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the name of the symbol used to emit stack probes or the empty string if not applicable. <a href="#a92e17e524fe1c82a26b5433b6e9715e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af64132885aa4151887699b689283e850">getStackProbeSize</a> (const MachineFunction &amp;MF) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37a095f9415bab8babe92997bd9bc863">hasVectorBlend</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target has a vector blend instruction. <a href="#a37a095f9415bab8babe92997bd9bc863">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b0b7687cd51e781f5b3851d9dcc10a6">getMaxSupportedInterleaveFactor</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the maximum supported factor for interleaved memory accesses. <a href="#a8b0b7687cd51e781f5b3851d9dcc10a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a528ccfe220ae477b22431f3328d0b90e">isInlineAsmTargetBranch</a> (const SmallVectorImpl&lt; StringRef &gt; &amp;AsmStrs, unsigned OpNo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>On x86, return true if the operand with index OpNo is a CALL or JUMP instruction, which can use either a memory constraint or an address constraint. <a href="#a528ccfe220ae477b22431f3328d0b90e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4a216c3f1033e64e9340aca44316ee4">visitMaskedLoad</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Chain, MachineMemOperand *MMO, SDValue &amp;NewLoad, SDValue Ptr, SDValue PassThru, SDValue Mask) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f2022425f9155911916a81841455566">visitMaskedStore</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Chain, MachineMemOperand *MMO, SDValue Ptr, SDValue Val, SDValue Mask) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9157e4aca11eca217c5c6d2c6a2eadbf">lowerInterleavedLoad</a> (LoadInst *LI, ArrayRef&lt; ShuffleVectorInst * &gt; Shuffles, ArrayRef&lt; unsigned &gt; Indices, unsigned Factor) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower interleaved <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumarklastscratchload-cpp/#a8a3fe89940744b94ffe5dacd6704c2be">load(s)</a> into target specific instructions/intrinsics. <a href="#a9157e4aca11eca217c5c6d2c6a2eadbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5881269962ffb5a6c2d4c5be45efbce">lowerInterleavedStore</a> (StoreInst *SI, ShuffleVectorInst *SVI, unsigned Factor) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower interleaved store(s) into target specific instructions/intrinsics. <a href="#ab5881269962ffb5a6c2d4c5be45efbce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfbecc9eaa3da520aafda5f3078baf3f">expandIndirectJTBranch</a> (const SDLoc &amp;dl, SDValue Value, SDValue Addr, int JTI, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expands target specific indirect branch for the case of <a href="/web-llvm/docs/api/namespaces/llvm/jumptable">JumpTable</a> expansion. <a href="#adfbecc9eaa3da520aafda5f3078baf3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a010c17359b18d005263da7a193fe2872">getPrefLoopAlignment</a> (MachineLoop *ML) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the preferred loop alignment. <a href="#a010c17359b18d005263da7a193fe2872">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af23e95d85be78026c607fa689dda4cd1">getTypeToTransformTo</a> (LLVMContext &amp;Context, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For types supported by the target, this is an identity function. <a href="#af23e95d85be78026c607fa689dda4cd1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08569892769aa5e49c2bf954082e9be5">findRepresentativeClass</a> (const TargetRegisterInfo *TRI, MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the largest legal super-reg register class of the register class for the specified type and its associated "cost". <a href="#a08569892769aa5e49c2bf954082e9be5">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44e5dc4cd7dcee99c44076c04a495b19">addLegalFPImmediate</a> (const APFloat &amp;Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that this x86 target can instruction select the specified FP immediate natively. <a href="#a44e5dc4cd7dcee99c44076c04a495b19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4d17c5d956c0b8d5187b420ac95e036">LowerCallResult</a> (SDValue Chain, SDValue InGlue, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals, uint32_t *RegMask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower the result values of a call into the appropriate copies out of appropriate physical registers. <a href="#aa4d17c5d956c0b8d5187b420ac95e036">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf70fe24896195cee150786395a12ac3">LowerMemArgument</a> (SDValue Chain, CallingConv::ID CallConv, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;ArgInfo, const SDLoc &amp;dl, SelectionDAG &amp;DAG, const CCValAssign &amp;VA, MachineFrameInfo &amp;MFI, unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c2a9aeb9cbe31170365402b5a1ed6ae">LowerMemOpCallTo</a> (SDValue Chain, SDValue StackPtr, SDValue Arg, const SDLoc &amp;dl, SelectionDAG &amp;DAG, const CCValAssign &amp;VA, ISD::ArgFlagsTy Flags, bool isByval) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09efcfe9c3e80e9ff5c0e21887c4a542">IsEligibleForTailCallOptimization</a> (TargetLowering::CallLoweringInfo &amp;CLI, CCState &amp;CCInfo, SmallVectorImpl&lt; CCValAssign &gt; &amp;ArgLocs, bool IsCalleePopSRet) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the call is eligible for tail call optimization. <a href="#a09efcfe9c3e80e9ff5c0e21887c4a542">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b5fdf09cbaa3744868bb160ad1fd33">EmitTailCallLoadRetAddr</a> (SelectionDAG &amp;DAG, SDValue &amp;OutRetAddr, SDValue Chain, bool IsTailCall, bool Is64Bit, int FPDiff, const SDLoc &amp;dl) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a load of return address if tail call optimization is performed and it is required. <a href="#a96b5fdf09cbaa3744868bb160ad1fd33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3017fbecf88f2aac84425a9886a11a3e">GetAlignedArgumentStackSize</a> (unsigned StackSize, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make the stack size align e.g 16n + 12 aligned for a 16-byte align requirement. <a href="#a3017fbecf88f2aac84425a9886a11a3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a603e81780090d28e4a691ef543bf5b0d">getAddressSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64ae0166ea0732e7d08610c6b11c9244">FP_TO_INTHelper</a> (SDValue Op, SelectionDAG &amp;DAG, bool IsSigned, SDValue &amp;Chain) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a385ab5f55d91b6d6c92a5d2ec8f737e3">LRINT_LLRINTHelper</a> (SDNode *N, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44257daf4209aa06b3933d8f2567ce27">LowerBUILD_VECTOR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b715117504cc9cf14e16cecf281e27b">LowerVSELECT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d1b727cab043cd79cb6ea3e8184bd29">LowerEXTRACT_VECTOR_ELT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fa248020f2f17136638e64bf8042dd5">LowerINSERT_VECTOR_ELT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7fa6d3e7e388a28aa972e7bd49593dc">getGlobalWrapperKind</a> (const GlobalValue *GV, const unsigned char OpFlags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe3e093d027081956ab9551460bd0be2">LowerConstantPool</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae28a3821944125ba0f7da1db935b96a6">LowerBlockAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a015553534b38343f00c8c096b90696cf">LowerGlobalAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a329864512ef9e9a1400cb96630207700">LowerGlobalTLSAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a707f6075019fa15f6d3e0e4de732a4">LowerExternalSymbol</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3635663c936a6745c4ea8315035c69ba">LowerGlobalOrExternal</a> (SDValue Op, SelectionDAG &amp;DAG, bool ForCall) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates target global address or external symbol nodes for calls or other uses. <a href="#a3635663c936a6745c4ea8315035c69ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1bbb7ab919ec0c381a0b89d12fa38f0">LowerSINT_TO_FP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d2b30b5592c53a9de885da5a90d154d">LowerUINT_TO_FP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40d2cf7f935e9873a736eb37132de88d">LowerTRUNCATE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09c8f29903cedf48e5d2b3007353450e">LowerFP_TO_INT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3468e59fc36fcb47df12edd22fd36955">LowerFP_TO_INT_SAT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90321e70801009eda27df4bfdf10f71c">LowerLRINT_LLRINT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23f125e48b475888d9580da2b3241eaa">LowerSETCC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0e4d87271f1745ef032aed83dabe510">LowerSETCCCARRY</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a406e66f77d02c54200c56d18ad7d4606">LowerSELECT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a402c2742dfd1e03caf54874fccb73a32">LowerBRCOND</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42dc222f2d796d56b8f6fb8073a97328">LowerJumpTable</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae55b190c2d96b5b2f76f685adec30a6a">LowerDYNAMIC_STACKALLOC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eb658067d017bafc5ad9b67e539ae8b">LowerVASTART</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6df5a54087b0164786c1b3f1a121cffd">LowerVAARG</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97f484a19478ba695318ca846352b6b7">LowerRETURNADDR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a232b0814c67b87d0a11dd4b5204c6fb2">LowerADDROFRETURNADDR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f0c9dd1c48cacdfa821f7ab49fa96a5">LowerFRAMEADDR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a341ce13c6b9f4243fa08921554258622">LowerFRAME_TO_ARGS_OFFSET</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59390fd04333fa49fabbf4be6b59bede">LowerEH_RETURN</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68e2568dd5d3fa88bd93886e0c3559da">lowerEH_SJLJ_SETJMP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81dd96f741e724d4719ce254aec6c361">lowerEH_SJLJ_LONGJMP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa628530d393e464070fe32d37a4ba3">lowerEH_SJLJ_SETUP_DISPATCH</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ace38cbafb4466803b4fa12a484c221">LowerINIT_TRAMPOLINE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a430ebeef6ceaa5a9d0a29253f14018e5">LowerGET_ROUNDING</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff19ec2b5ab688b726ee17e4d714138">LowerSET_ROUNDING</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1321d92ff60dd32f0671a9546e44c965">LowerGET_FPENV_MEM</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb7803ce3754aa9fddfd53405690e74d">LowerSET_FPENV_MEM</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0056dc4a32bf331ac24d9bcb1ed36bb0">LowerRESET_FPENV</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fe5dd0286a144930329f8b04833f7ec">LowerWin64_i128OP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addd8b8b94aa125905688044a6dd2d478">LowerWin64_FP_TO_INT128</a> (SDValue Op, SelectionDAG &amp;DAG, SDValue &amp;Chain) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c4bfd42d245eb41c76317518a497184">LowerWin64_INT128_TO_FP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33672ebdcfb03f655b2a4148f144df5b">LowerGC_TRANSITION</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a05cd9a29392791cee47ce7d448a6c2">LowerINTRINSIC_WO_CHAIN</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59bbfb435f70f941553758ad0774f2f3">lowerFaddFsub</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Depending on uarch and/or optimizing for size, we might prefer to use a vector operation in place of the typical scalar operation. <a href="#a59bbfb435f70f941553758ad0774f2f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa137c76efed16ed8728cbe97e30d97b3">LowerFP_EXTEND</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afff4d2f3a2973b8a8d5f1b60285dbe06">LowerFP_ROUND</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72125c02ec314b74c085a97cf61f3a52">LowerFP_TO_BF16</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4daa2ca582e132e3a08eca54c5353179">LowerFormalArguments</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower the incoming (formal) arguments, described by the Ins array, into the specified DAG. <a href="#a4daa2ca582e132e3a08eca54c5353179">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7daed1bc68b8961bb301f43ba08e617">LowerCall</a> (CallLoweringInfo &amp;CLI, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower calls into the specified DAG. <a href="#ab7daed1bc68b8961bb301f43ba08e617">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9af01afeebab7c828e2595aece7ce85">LowerReturn</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; SDValue &gt; &amp;OutVals, const SDLoc &amp;dl, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower outgoing return values, described by the Outs array, into the specified DAG. <a href="#ab9af01afeebab7c828e2595aece7ce85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e781d6b9f2dbd7f4d31edfa19ee795">supportSplitCSR</a> (MachineFunction *MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target supports that a subset of CSRs for the given machine function is handled explicitly via copies. <a href="#a32e781d6b9f2dbd7f4d31edfa19ee795">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac09bc33a0671e74f38c6c1f3654c0dd3">initializeSplitCSR</a> (MachineBasicBlock *Entry) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform necessary initialization to handle a subset of CSRs explicitly via copies. <a href="#ac09bc33a0671e74f38c6c1f3654c0dd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa60e5f2c24121347f67024637aa74405">insertCopiesSplitCSR</a> (MachineBasicBlock *Entry, const SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;Exits) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert explicit copies in entry and exit blocks. <a href="#aa60e5f2c24121347f67024637aa74405">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c52d2f566091bd09fa0971defd33b90">isUsedByReturnOnly</a> (SDNode *N, SDValue &amp;Chain) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if result of the specified node is used by a return node only. <a href="#a9c52d2f566091bd09fa0971defd33b90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab12e8b204f28c788c70b7d2c93521e09">mayBeEmittedAsTailCall</a> (const CallInst *CI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target may be able emit the call instruction as a tail call. <a href="#ab12e8b204f28c788c70b7d2c93521e09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdc2d795c628469393213a614542a610">getTypeForExtReturn</a> (LLVMContext &amp;Context, EVT VT, ISD::NodeType ExtendKind) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type that should be used to zero or sign extend a zeroext/signext integer return value. <a href="#acdc2d795c628469393213a614542a610">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a743a463663ba17b3d519e4098be6d710">CanLowerReturn</a> (CallingConv::ID CallConv, MachineFunction &amp;MF, bool isVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, LLVMContext &amp;Context, const Type *RetTy) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook should be implemented to check whether the return values described by the Outs array can fit into the return registers. <a href="#a743a463663ba17b3d519e4098be6d710">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92816ba1d0a0f3eb57fd758e67f5f1a3">getScratchRegisters</a> (CallingConv::ID CC) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a 0 terminated array of registers that can be safely used as scratch registers. <a href="#a92816ba1d0a0f3eb57fd758e67f5f1a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d12771a48cc8b16535eeb9ae4ce94fc">getRoundingControlRegisters</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a 0 terminated array of rounding control registers that can be attached into strict FP call. <a href="#a2d12771a48cc8b16535eeb9ae4ce94fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLoweringBase::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a553c0018101813c15a59063ce7f36bf3">shouldExpandAtomicLoadInIR</a> (LoadInst *LI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the given (atomic) load should be expanded by the IR-level AtomicExpand pass. <a href="#a553c0018101813c15a59063ce7f36bf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLoweringBase::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd31564b7faa43985a88235bb323eae3">shouldExpandAtomicStoreInIR</a> (StoreInst *SI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the given (atomic) store should be expanded by the IR-level AtomicExpand pass into. <a href="#abd31564b7faa43985a88235bb323eae3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLoweringBase::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac53bbecb27c9603445acf1e3965432f4">shouldExpandAtomicRMWInIR</a> (AtomicRMWInst *AI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the IR-level AtomicExpand pass should expand the given AtomicRMW, if at all. <a href="#ac53bbecb27c9603445acf1e3965432f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLoweringBase::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a382bb57dc50ee6687a4afeff9bf94278">shouldExpandLogicAtomicRMWInIR</a> (AtomicRMWInst *AI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765370db273adf54b86a60f3de558035">emitBitTestAtomicRMWIntrinsic</a> (AtomicRMWInst *AI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a bit test atomicrmw using a target-specific intrinsic. <a href="#a765370db273adf54b86a60f3de558035">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab6483478ea6cc26b7c4cdcac832ff3b">emitCmpArithAtomicRMWIntrinsic</a> (AtomicRMWInst *AI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a atomicrmw which the result is only used by comparison, using a target-specific intrinsic. <a href="#aab6483478ea6cc26b7c4cdcac832ff3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb51736698ae53a8d882e21925b81954">lowerIdempotentRMWIntoFencedLoad</a> (AtomicRMWInst *AI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>On some platforms, an AtomicRMW that never actually modifies the value (such as fetch_add of 0) can be turned into a fence followed by an atomic load. <a href="#acb51736698ae53a8d882e21925b81954">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02ba0fbeaccacb7a8887b62810e0f711">needsCmpXchgNb</a> (Type *MemType) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the operand type is exactly twice the native width, and the corresponding cmpxchg8b or cmpxchg16b instruction is available. <a href="#a02ba0fbeaccacb7a8887b62810e0f711">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36ac13a178bdda5a9a97633c6c853990">SetupEntryBlockForSjLj</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB, MachineBasicBlock *DispatchBB, int FI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6662e9bd609891f313d6afdd1e26c9db">EmitVAARGWithCustomInserter</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8991fbdd984cbb4f058dc0cc1fcd165">EmitLoweredCascadedSelect</a> (MachineInstr &amp;MI1, MachineInstr &amp;MI2, MachineBasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility function to emit the xmm reg save portion of va_start. <a href="#af8991fbdd984cbb4f058dc0cc1fcd165">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b779edd4c0f87ba42d323af71e6573">EmitLoweredSelect</a> (MachineInstr &amp;I, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae87c887710eb36bfc2fbdca9007078bf">EmitLoweredCatchRet</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b62e3102d65b55f6311fcec3e5269fa">EmitLoweredSegAlloca</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29723eb149349ce7b5f389fa7e413823">EmitLoweredProbedAlloca</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac03d685e08b4adada3631e2dfc6f8e34">EmitLoweredTLSCall</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f7962449e6f8a20ad62bf46c6b7973e">EmitLoweredIndirectThunk</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45b38fe5dfee48def2a08c82d2e3796e">emitEHSjLjSetJmp</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a89d8a9888958def220bb30277c66dd">emitSetJmpShadowStackFix</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SetJmp implies future control flow change upon calling the corresponding LongJmp. <a href="#a9a89d8a9888958def220bb30277c66dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad809ec9198a48ce7d3ea339cf3e37bf0">emitEHSjLjLongJmp</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2871933f02418c5f6d5ae1e8d81be085">emitLongJmpShadowStackFix</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fix the shadow stack using the previously saved SSP pointer. <a href="#a2871933f02418c5f6d5ae1e8d81be085">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb8fe1bc6925d9aaee73cf8ec3e4e8d2">EmitSjLjDispatchBlock</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91433c180ad2232456c3473327ffa71a">emitPatchableEventCall</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcc90943b4dd635e767a7a06bb10458e">emitFlagsForSetcc</a> (SDValue Op0, SDValue Op1, ISD::CondCode CC, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SDValue &amp;X86CC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit flags for the given setcc condition and operands. <a href="#afcc90943b4dd635e767a7a06bb10458e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b4d043dafc9dc7465f2f12700665848">optimizeFMulOrFDivAsShiftAddBitcast</a> (SDNode *N, SDValue FPConst, SDValue IntPow2) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20b0a79348cf4200832a334e418ae71f">isFsqrtCheap</a> (SDValue Op, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if replacement of SQRT with RSQRT should be disabled. <a href="#a20b0a79348cf4200832a334e418ae71f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dcc8a9a339f05f170eebe8a60c8a0f3">getSqrtEstimate</a> (SDValue Op, SelectionDAG &amp;DAG, int Enabled, int &amp;RefinementSteps, bool &amp;UseOneConstNR, bool Reciprocal) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> rsqrt* to speed up sqrt calculations. <a href="#a6dcc8a9a339f05f170eebe8a60c8a0f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e8fa8d0165f4b68bbe05487428ba6a5">getRecipEstimate</a> (SDValue Op, SelectionDAG &amp;DAG, int Enabled, int &amp;RefinementSteps) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> rcp* to speed up fdiv calculations. <a href="#a4e8fa8d0165f4b68bbe05487428ba6a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49756d103dc3cbe7cca1d98c07a767e5">combineRepeatedFPDivisors</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reassociate floating point divisions into multiply by reciprocal. <a href="#a49756d103dc3cbe7cca1d98c07a767e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57b1cb02c7064ffc62e7adf6333a6781">BuildSDIVPow2</a> (SDNode *N, const APInt &amp;Divisor, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDNode * &gt; &amp;Created) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets may override this function to provide custom SDIV lowering for power-of-2 denominators. <a href="#a57b1cb02c7064ffc62e7adf6333a6781">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a300d2d93bfdab2717786de60ee7dfcaa">getMOVL</a> (SelectionDAG &amp;DAG, const SDLoc &amp;dl, MVT VT, SDValue V1, SDValue V2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a vector_shuffle mask for an movs{s|d}, movd operation of specified width. <a href="#a300d2d93bfdab2717786de60ee7dfcaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcb67b471446e52c5d56aa87f08f28ce">Subtarget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep a reference to the <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> around so that we can make the right decision when generating code for different targets. <a href="#abcb67b471446e52c5d56aa87f08f28ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a628ac19a4ddc4a22d94fb57a6a18f700">LegalFPImmediates</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of legal FP immediates. <a href="#a628ac19a4ddc4a22d94fb57a6a18f700">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 1052 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86TargetLowering() {#ae9e81fca4b22706c50ad62e3241b6286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86TargetLowering::X86TargetLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine">X86TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp; STI)</td>
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



<p>Declaration at line 1054 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af798622367e75c5536666dbfec5d5ea3">llvm::ISD::ABDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff129f5ab4fbc8279e7aaacb45f840b1">llvm::ISD::ABDU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a35c1cf0dd553444732dba8e8b9be0f6b">llvm::ISD::ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3ebc673c7187aba992cc6925c27d47b5">llvm::TargetLoweringBase::addBypassSlowDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7c45a718f16057459d95d09d42ec6902">llvm::TargetLoweringBase::addRegisterClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae221016e72ad6632377ef55f9e0e4f61">llvm::ISD::ADDRSPACECAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af7bfad446dfd85837fe7ff904ebb1aff">llvm::ISD::ADJUST_TRAMPOLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa275bf149ab5df1067cfb721936ecbc">llvm::ISD::ANY_EXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30649569b517a279a32fb3b48cc154e0">llvm::ISD::ATOMIC_CMP_SWAP_WITH_SUCCESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a385d7f9c63f921a2b28e8426e4101de8">llvm::ISD::ATOMIC_FENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c47226f266248f4b8c155b83601b109">llvm::ISD::ATOMIC_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf5f612de1a25451c9a0c33d77bf3e74">llvm::ISD::ATOMIC_LOAD_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a905925a49cdc6b4a6017d215820dad30">llvm::ISD::ATOMIC_LOAD_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4112a866197a97a70bdc78ef92c79b4c">llvm::ISD::ATOMIC_LOAD_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3d12dbff6e50803982d0e92768a1479">llvm::ISD::ATOMIC_LOAD_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a428ec1341b34eafa63518914e7f5ddf0">llvm::ISD::ATOMIC_LOAD_XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1db943abc1bf78a911daeb7b03d81de8">llvm::ISD::ATOMIC_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a55a4b1d94ca6176bcb5449196d67e798">llvm::ISD::AVGCEILS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8489c40b1b3f92b0c4fc98d06099c441">llvm::ISD::AVGCEILU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110acc5444f2e2933b551e3afbdd93a9bfc8">llvm::ISD::AVGFLOORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5096628a43b16ff34ace64193ded1c93">llvm::ISD::AVGFLOORU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdae7178e801a788f47e55ad3db3ee6a">llvm::ISD::BF16_TO_FP</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ab46ff1a80ee89c9e22ca17c179a89ab1">llvm::APFloatBase::BFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeea401cc0b7fa5aa6f4d3a0612140e1d">llvm::ISD::BITREVERSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb">llvm::ISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716d19ebad1927a2e8dd5fe3f951f882">llvm::ISD::BR_JT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ae7fe7691e456e49addd866aa23896387">llvm::APFloat::changeSign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110addc63b0e91a7c2b397e7908052d8caf9">llvm::ISD::CLEAR_CACHE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6df03220bbe2ea3cfb905f36fb26822c">llvm::TargetLoweringBase::computeRegisterProperties</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5">llvm::ISD::CONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a257e3cb529defa79ad7a9f42072f339a">llvm::APFloat::convert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c">llvm::ISD::CTLZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0340c8d57d1dcebc43a00412989583d3">llvm::ISD::CTLZ_ZERO_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a991d07d163bd4d9984cf1ef36e92c214">llvm::ISD::CTPOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6da41a113af0909470baea7486b3386b">llvm::ISD::CTTZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a601e66a26efd05520f7cb26aef3af340">llvm::ISD::CTTZ_ZERO_UNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa3441acf8576e4bbf48e9bd73ca3c0d8c">llvm::TargetLoweringBase::Custom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a967fcb624e84458e135a763d1c11346a">llvm::ISD::DEBUGTRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa71ac22470bf853868fe6b39a25bac72">llvm::ISD::DYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4c1f7e0dc3af92b9cfd0d5d11231ddc1">llvm::ISD::EH_LABEL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4edf35e2383003ff20057e5a45012a55">llvm::ISD::EH_RETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a122a450e069003dc86859ef47ab6e278">llvm::ISD::EH_SJLJ_LONGJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae5a57fe9fd413df909ab121ca1a813c7">llvm::ISD::EH_SJLJ_SETJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2e0f3a93e85a46b2ebac7330c2a0c581">llvm::ISD::EH_SJLJ_SETUP_DISPATCH</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80ebe2acf36317f888422a345e90ba87">llvm::TargetLoweringBase::EnableExtLdPromotion</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa4b85349547c5b6126817e10152007931">llvm::TargetLoweringBase::Expand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad88f843bce966361c7fd2cd022e6528a">llvm::ISD::ExternalSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">llvm::ISD::EXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2b4d07600495a563319d6a3dda8dc44d">llvm::ISD::FABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3bd30fa450385ee74c9b275ba5f8d1c7">llvm::ISD::FACOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a62bcf7e98c551eddfe028e6ad6565215">llvm::ISD::FASIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3ec6f3b872819089911699ea156e6fc7">llvm::ISD::FATAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2a69cbb602c143642c1fe014bce6d44d">llvm::ISD::FATAN2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a74a787311d3ab9a17ee0acde7b6a6b14">llvm::ISD::FCANONICALIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad56e9199ae3993a09af36ff41d327a11">llvm::ISD::FCEIL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeffc3319657e213a530ce583603f7221">llvm::ISD::FCOPYSIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9133d7cfb6a66404ff7757b699bc3941">llvm::ISD::FCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30da9fef8027cdf8a719bdacb5300df8">llvm::ISD::FCOSH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abc6c09c7af98236460f0b020eb3be94e">llvm::ISD::FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad49a46d391f73aa96002adbdd0cf03f5">llvm::ISD::FEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a37c80ce3312d3fc5b925e326a16fff20">llvm::ISD::FEXP10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af3542a99501ffb93cee4aae9d1ec2d05">llvm::ISD::FEXP2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4336c27826676e1ef61383cafa999219">llvm::ISD::FFLOOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad9e6c8353bc9d023077590083cfce89c">llvm::ISD::FFREXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a130b6a6d409367c8a61dd14dfa39785c">llvm::ISD::FGETSIGN</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a850652b63276e9d79e6c1e05146c84c0">llvm::MVT::fixedlen_vector_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a455f49e18d470b97cd293acd7fbdf169">llvm::ISD::FLDEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac82d37f93ae4420659acdd03f79b15e0">llvm::ISD::FLOG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0d05d4a5cd10a46f69f9e62d49d275bb">llvm::ISD::FLOG10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a558dc710055f9d60cc3c0893bc29a72d">llvm::ISD::FLOG2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3dfd1b187d121c0e214698eef1c20f53">llvm::ISD::FMAXIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add34b1738b7bb2c298f92f1b7b62ce0c">llvm::ISD::FMAXIMUMNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a632dd4bb044d5cd11f671d176ef495f2">llvm::ISD::FMAXNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac27a43f98abb2d1ee2f2ce99a0b34b36">llvm::ISD::FMINIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af7691f41e448fefca844f687edabfb69">llvm::ISD::FMINIMUMNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9f59cc264907eb86e29564d5f6a5b213">llvm::ISD::FMINNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178">llvm::ISD::FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2dc876d6cc16ac04376483552292f9f4">llvm::ISD::FNEARBYINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d26c45c040d8f85d577a5f645261d1a">llvm::ISD::FNEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3e12fcc9960ef3bf0ae5876382d4c66f">llvm::ISD::FP16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0bb173b5a879225092abdeaba1394839">llvm::ISD::FP_TO_BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a38f379e4fddf750c36f1323a04d12171">llvm::ISD::FP_TO_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae4a4e2126c6db34e2dfd71b6bd0408ee">llvm::ISD::FP_TO_SINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98661814400e72a77f5ed4e088c06937">llvm::ISD::FP_TO_UINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1a6952b1572a4ce241cc3cf45a9ab071">llvm::ISD::FPOW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a66b7368b776f6aff492cf970db3df548">llvm::ISD::FPOWI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a228deacdfba1bd2d5a3663b19609f945">llvm::ISD::FRAME_TO_ARGS_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdd7bbb76dac7962dda6e116e33699da">llvm::ISD::FREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a68014623710f7a44c808cd412236d6a1">llvm::ISD::FRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a87b7dd3d6a9b68d1558fc6b4706708b0">llvm::ISD::FROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab3cb85375f983765b93341d57a2f3838">llvm::ISD::FROUNDEVEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a822b0d02b601898e2d6db5b39e12cc8a">llvm::ISD::FSHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a874350de5b4f6b8f4db13940e17ed81b">llvm::ISD::FSHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad46ae9fdfe20cd04f7fda7ccbb937543">llvm::ISD::FSIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6ba8fc92ee5081d3e533cb5322f74f29">llvm::ISD::FSINCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8c5012dcc326bb95fc45b1f2e80dbda">llvm::ISD::FSINH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae1118ddac1ce0af8e9f7cc16c9e94fc0">llvm::ISD::FSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad">llvm::ISD::FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9edaaccfce9ddf3113d737686f0a019e">llvm::ISD::FTAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7d675a8da9b3fa2ee3a15b3932eef38a">llvm::ISD::FTANH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1e92ea554489509b0ad970901bcc715b">llvm::ISD::FTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aee46c58568939eaeaa37ea6001bf432e">llvm::ISD::GC_TRANSITION_END</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71d133366c40437e06936626b32ba6d8">llvm::ISD::GC_TRANSITION_START</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac7e6de3a23c50c3f48e30e3a644a16aa">llvm::ISD::GET_FPENV_MEM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89f3afc3fa907ff83759c6c76d97a973">llvm::ISD::GET_ROUNDING</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae365cf8f9a6844685be3fd9f12956c33">llvm::TargetLoweringBase::getLibcallName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1a78b9f867cb5be3a052d6ad972484ca">llvm::TargetLoweringBase::getRegClassFor</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af591f8d18d0d9773192a0ffcca41796e">llvm::APFloat::getZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86415bb448a78ef1fed893f9eb0f5d06">llvm::APFloatBase::IEEEhalf</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a494661a175e7785032f9a05d963fc0e9">llvm::APFloatBase::IEEEquad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sched/#ab8d854a5ce2331586bcc6830cca52f0fac4801b47c85ae3044251c5ca7443b1df">llvm::Sched::ILP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4534a6db2862a28324932a8ea1cb54d6">llvm::ISD::INIT_TRAMPOLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">llvm::ISD::INSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7b339f69bc3995d23399a85f81af6018">llvm::MVT::integer_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a657b27286b37057f0fdf1af3e43bc890">llvm::TargetLoweringBase::isOperationCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0248ed29f933c5faa55cbdfebf3139bd">llvm::TargetLoweringBase::isOperationExpand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#adfe2696265f6b0a7cd08bb6159fb9db4">llvm::TargetLoweringBase::IsStrictFPEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0c70100db6ddc0b37b56feb242145cf4">llvm::ISD::JumpTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aafb9a152dd1ee4089f5fc96a33c5c90d2">llvm::TargetLoweringBase::LibCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a25eed965b36ce43fc8b9daa2774dfad8">llvm::ISD::LLRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4e2fdf7d4dbc04469cf6a920262c82c8">llvm::ISD::LLROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a05f23e2cd900dc8f1dbf6702ab12423b">llvm::ISD::LRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adb1de74d602ef905e06785e0052b55bf">llvm::ISD::LROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3111deca0523de0afcc110cf020ebaaf">llvm::TargetLoweringBase::MaxLoadsPerMemcmp</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aae9cf790eaa990b803a93058582d78e8">llvm::TargetLoweringBase::MaxLoadsPerMemcmpOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aefbee33131c130f8f691c9a482f5fc40">llvm::TargetLoweringBase::MaxStoresPerMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1695feb44cd6dd30c64697360f1e76d3">llvm::TargetLoweringBase::MaxStoresPerMemcpyOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6d0f43699563375800a45f45bc11ff49">llvm::TargetLoweringBase::MaxStoresPerMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7800cede44a09d00fcc61b9087c20d85">llvm::TargetLoweringBase::MaxStoresPerMemmoveOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9830bda9bf50bfdab4c10954cc6fb1ac">llvm::TargetLoweringBase::MaxStoresPerMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a67f472063b7db365d0b5da597871e03d">llvm::TargetLoweringBase::MaxStoresPerMemsetOptSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab4685260a7e506fe51f17d9b600349c8">llvm::ISD::MGATHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a112324db3910fea5895514851c387442">llvm::ISD::MLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab179d7f42562bbb315a6b0589a25f733">llvm::ISD::MSCATTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9add598de9e0a49cbb8fb19adf495051">llvm::ISD::MSTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa2a7c3eccf06b41e4275bbeadb46d22e">llvm::ISD::MULHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8a80d3b085af08f0dce1724207ef99b5">llvm::ISD::MULHU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa47439d20ce0879ea68ca293e018b4f5">llvm::ISD::PARITY</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cc366cf4e0b825191ca9babcf290286">llvm::TargetLoweringBase::PredictableSelectIsExpensive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a691a4c9004e9bd04d1c0bebc5df57443">llvm::ISD::PREFETCH</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aaba91ac521e4f01f57413216273fd7b7f">llvm::TargetLoweringBase::Promote</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac43f9bea13e29622bbf18c861b52144d">llvm::ISD::READCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sched/#ab8d854a5ce2331586bcc6830cca52f0fa5b5fba18a61456ef5858005d9f7b153e">llvm::Sched::RegPressure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a23914569caa5dbe0d340c3fbfc277efc">llvm::ISD::RESET_FPENV</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715">llvm::ISD::ROTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a863ec6ebb75bf89cfea14da646d77e92">llvm::ISD::SADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af9eda6a77c3228cd36537469a7425133">llvm::ISD::SADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af1b946afff631cee7aa6de570bef7785">llvm::ISD::SADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a874f66e1efe5be79552bbe7ee3121a">llvm::ISD::SDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af695708f70bdd710c8fda5c4570711d7">llvm::ISD::SET_FPENV_MEM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4fe6c878350458de2c3182392f830988">llvm::ISD::SET_ROUNDING</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6b928e5a6718acab4fa0030ce9198e8a">llvm::TargetLoweringBase::setBooleanContents</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0662d63e058816bf77a5b8f35331bd9d">llvm::TargetLoweringBase::setBooleanVectorContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6bb33e400f29724907dc27ced04e9038">llvm::ISD::SETCCCARRY</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#abbec47c0a3f39ed8fa200ccc9933318f">llvm::TargetLoweringBase::setCondCodeAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ab49f81c2ecbbff3d0fbe55dd46353774">llvm::ISD::SETLE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3b258bf80e376a39c623bf880461894b">llvm::TargetLoweringBase::setLibcallCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8b36797b46a42e7b489e47c2d009bc1d">llvm::TargetLoweringBase::setLibcallName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad1d4d71bf37fea6a3170f27438d41e6d">llvm::TargetLoweringBase::setLoadExtAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a6f05a09edb671910f85f8665981cbde9">llvm::ISD::SETLT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4df001a3c611cc8b423ca0e54560210f">llvm::TargetLoweringBase::setMaxAtomicSizeInBitsSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a09373cbbdb4326098156b8dfdad4e8b2">llvm::TargetLoweringBase::setMaxDivRemBitWidthSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a412198fc6d5387d22f6601f35e0ad254">llvm::TargetLoweringBase::setMaxLargeFPConvertBitWidthSupported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a08c31033acfb9d6f0bc4a8a82cc26862">llvm::ISD::SETOEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a07c0c67913bb543fc45ce9ef65ef260a">llvm::TargetLoweringBase::setOperationAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a357d8fa7fd274fd0fd281e19d468d92b">llvm::TargetLoweringBase::setOperationPromotedToType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8bb50938977c871d4dfa617d1b759a9a">llvm::TargetLoweringBase::setPrefFunctionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4aebe88e5c44bdb37513651bc72c2889">llvm::TargetLoweringBase::setPrefLoopAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af2a24aed2ba5d4f9c8db9904df6fa635">llvm::TargetLoweringBase::setSchedulingPreference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab8a44fb1f49bcfbed806fef69301a67a">llvm::TargetLoweringBase::setStackPointerRegisterToSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac87dc82fa9f824a797198e7b0e16141d">llvm::TargetLoweringBase::setTargetDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa243085e56636cc454143f916686c190">llvm::TargetLoweringBase::setTruncStoreAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a0d1546187d4d526fcbdd43183689075e">llvm::ISD::SETUNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3893859b5caa079593b9bf91b96e05fb">llvm::ISD::SIGN_EXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a0f60fd9b862dff366e18e32c6d98d96b">llvm::SjLj</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af3b59179b6fcbc89463181015ace8e9b">llvm::ISD::SMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaac895215ecbb3c411c957c8beb39b70">llvm::ISD::SMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1354c6f8508d6cd697dc89a5d9a52dfd">llvm::ISD::SMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa35d0a58fdded3d225d512a60aea0951">llvm::ISD::SMULO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6efe16ea597cfd8eeac26516fc992ee7">llvm::ISD::SSUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a139dc5419039d94496e69dbb264251b5">llvm::ISD::SSUBO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a77984d86d70df1f3229da7a5119652a9">llvm::ISD::SSUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a023a9de787026fe61b024476bf9c32cb">llvm::ISD::STACKRESTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a031ce694e40832d40a163d7254a8df14">llvm::ISD::STACKSAVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab60b57f9ecb68fa5f4445ec18e835a64">llvm::ISD::STRICT_BF16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc1699b53cce73a1a89fa9190db8f2f8">llvm::ISD::STRICT_FACOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad11fa7fd2a91d210ecbdf09d56cd9f42">llvm::ISD::STRICT_FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a548c5ee9bfffd516c18b0844d8916d98">llvm::ISD::STRICT_FASIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5fc35989024437e6878d228dce85b34d">llvm::ISD::STRICT_FATAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1c24a514835d74a2a0b441825a622cef">llvm::ISD::STRICT_FATAN2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1fb1e48394636004fd75f5916f0d730f">llvm::ISD::STRICT_FCEIL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae2047d551dd66943aa285b4c7eab0766">llvm::ISD::STRICT_FCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac9090021eb9a063125475a3d2f380af2">llvm::ISD::STRICT_FCOSH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4151e13f7626f6d790d58c0fa444f32e">llvm::ISD::STRICT_FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aba2dfbb2100ec6aee6e5b52bc713c26a">llvm::ISD::STRICT_FEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad5d3bf9997ecfea792abc058e7d39e72">llvm::ISD::STRICT_FEXP2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab74cbb3933c5f5d2cc90d299836c05cc">llvm::ISD::STRICT_FFLOOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110addd63c6d866c8a8020a0cc4de467b285">llvm::ISD::STRICT_FLDEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad795680a8d2d37bdede6696d72f41c35">llvm::ISD::STRICT_FLOG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad227f160898f13eeb05150f03de8d40b">llvm::ISD::STRICT_FLOG10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a409f18d3c3acb29ab844e9942441cc4b">llvm::ISD::STRICT_FLOG2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a26ff7f7547f66e1a4f6d5e7efe4b2f59">llvm::ISD::STRICT_FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a917038ef7ae3264e336457da0f75e95b">llvm::ISD::STRICT_FMAXIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92f7a0e4dfe860ff938d463d84270ba3">llvm::ISD::STRICT_FMAXNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3093a04e2918e155f32d435e2f974e88">llvm::ISD::STRICT_FMINIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98f18e85e4e6421f5c859680602a4c1f">llvm::ISD::STRICT_FMINNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4b912b6be299d30d75b876e939d16fd6">llvm::ISD::STRICT_FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae463c3e40819d6e9de30d7d858867ef4">llvm::ISD::STRICT_FNEARBYINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8be8417e323644ecd854ce67c362a850">llvm::ISD::STRICT_FP16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac47e026e409ff39f319cbb3b096863e6">llvm::ISD::STRICT_FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2273d9cd04ba6e4a7c1a4b28ab1aaba">llvm::ISD::STRICT_FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac98e3abb765d6786634ba0656ae83e17">llvm::ISD::STRICT_FP_TO_BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8a54f717e10fab9c9821196fc882cc11">llvm::ISD::STRICT_FP_TO_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed">llvm::ISD::STRICT_FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf955b4b70f63865e022c329d1775579">llvm::ISD::STRICT_FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a65a342694a17f4a1db771dbc36d31cc9">llvm::ISD::STRICT_FPOW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aacf4034f48b7e32a9e20bfedbb5502bd">llvm::ISD::STRICT_FREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af57a22f2843a1c3a79d17350945ede58">llvm::ISD::STRICT_FRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0953e80e4e94f6ded9680e64c5df5cc">llvm::ISD::STRICT_FROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab7d5c27c800b79a02a1492f1965af72f">llvm::ISD::STRICT_FROUNDEVEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0466b21bfb4f3596e41380d8e2d1956f">llvm::ISD::STRICT_FSETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c8d07d668872f2176fb34724cd799c4">llvm::ISD::STRICT_FSETCCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a06c721642eadaa31c37384b39fe11387">llvm::ISD::STRICT_FSIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9b07fb8cd5a1230b0f736489ddd9eebc">llvm::ISD::STRICT_FSINH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a476844aad24870fab3d132b5fe6b1f37">llvm::ISD::STRICT_FSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad6192a54cb1dfeca8173749cc735269a">llvm::ISD::STRICT_FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8ae8131038d9b94abd2880812bf5b0e">llvm::ISD::STRICT_FTAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a244401fe9aee94da72b7f0fb6b095a45">llvm::ISD::STRICT_FTANH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a883c1084962f12018ca0fe3e1222fa7d">llvm::ISD::STRICT_FTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab38d2af541b99492acf69c041c98bcb6">llvm::ISD::STRICT_SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a56735332b7dc26b4e164035831fb40ab">llvm::ISD::STRICT_UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aaa96f111a59a7a2e7f9c689b344543df">llvm::TargetLowering::TargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac5fb8808f3dcb9f0a83f1fc2e7747485">llvm::ISD::TRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1ddf36330110b4abea43fe390bea9ef9">llvm::ISD::UADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0f1e3ed26108fec69eb97209c0e39bf">llvm::ISD::UADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5e433873c201ad85c30e42da1ae05977">llvm::ISD::UADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa110c932d4027fe4043cceb7a579e5ee">llvm::ISD::UBSANTRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a257ffa49107e2db978e8a6e2688ada">llvm::ISD::UDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af675e759c0ffff8d48ea14a60fe3517b">llvm::ISD::UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a17126302da6199930e55e841ca1b082d">llvm::ISD::UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a79c959df09509d7ff66d9b04bc40d18d">llvm::ISD::UMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7800622851751b8ae318b41f4096830e">llvm::ISD::UMULO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c6d8f265e9e16e5debdb9a536b55d3d">llvm::ISD::UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28">llvm::ISD::UREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4ffc75d65231b55461c0ba4f36a3e500">llvm::ISD::USUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac81ebcd59d629d8680e50ffba9855255">llvm::ISD::USUBO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89166b38f12c0bd3e8a61d8f1a5a8bc8">llvm::ISD::USUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae77d03846b31c41c4860bcd96d780a78">llvm::ISD::VAARG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a804c1960ac64628cdd1f74d7de885284">llvm::ISD::VACOPY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1aadbb14ab26b74d841ac003363e3a5d">llvm::ISD::VAEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adfe32beaa596a1512b17e66b46e773ed">llvm::ISD::VASTART</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adb06c311948bd9fb944ab3c433138181">llvm::ISD::VECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b7cce6c4d601c0e40456c253d6c8e4e">llvm::verifyIntrinsicTables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0b7d2c769fd0fbaab3c4a2fc8e7ea0c">llvm::ISD::VSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caa88ccf4313b5bc700dec76fd9bc5d40e">llvm::CallingConv::X86_StdCall</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a4830aff0741b3cd7a3920826ae6c0ece">llvm::APFloatBase::x87DoubleExtended</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adf7f4fc30c272a1987e075d7470df84c">llvm::ISD::ZERO_EXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a695a19c9c3ae14638be151add82755cb">llvm::TargetLoweringBase::ZeroOrNegativeOneBooleanContent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a0e2d72cfdcc49d2d189f440b3cc31dff">llvm::TargetLoweringBase::ZeroOrOneBooleanContent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addressingModeSupportsTLS() {#adb85795e16fa504b6b2d37650c267b2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::addressingModeSupportsTLS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the targets addressing mode can target thread local storage (TLS).</p>

<p>Declaration at line 1395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 19364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120aa530fb2056fbb72e132893eba6ff4883">llvm::TLSModel::GeneralDynamic</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120a3cae4242c478d473bfa1af350f126545">llvm::TLSModel::InitialExec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120a110e377ad85dc311cb9bce1e32bea8aa">llvm::TLSModel::LocalDynamic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120ae13ef3bbe423ce80086f0a684fd25753">llvm::TLSModel::LocalExec</a>.</p>

</div>
</div>

### allowsMemoryAccess() {#acca525d32f859c8c653921b5fff62ed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::allowsMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, unsigned AddrSpace, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dd">MachineMemOperand::Flags</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">MachineMemOperand::MONone</a>, unsigned * Fast=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function returns true if the memory access is aligned or if the target allows this specific unaligned memory access.</p>


<p>If the access is allowed, the optional final parameter returns a relative speed of the access (as defined by the target).</p>


<p>Declaration at line 1108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="#a7fdb4a73925c17adcb4eaeafda02978d">allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#aec0a89ba2bd4f839f4509ff10117b85f">isBitAligned</a>, <a href="#a1a78b1cfe835bfe405897b9b75cf17fb">isMemoryAccessFast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda8d09c51969b0954512ed65ee26551081">llvm::MachineMemOperand::MONonTemporal</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>.</p>


<p>Referenced by <a href="#a76385ca67c48554c408107c686ed0c68">allowsMemoryAccess</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>.</p>

</div>
</div>

### allowsMemoryAccess() {#a76385ca67c48554c408107c686ed0c68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86TargetLowering::allowsMemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO, unsigned * Fast)</td>
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



<p>Definition at line 1114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>


<p>References <a href="#acca525d32f859c8c653921b5fff62ed3">allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a3f583e2bb417139560bde043214d064a">llvm::MachineMemOperand::getAddrSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#abc15369ab4cc583332950b913e2ef1dd">llvm::MachineMemOperand::getAlign</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#ab991bb1444579648a165d1b134a0854d">llvm::MachineMemOperand::getFlags</a>.</p>

</div>
</div>

### allowsMisalignedMemoryAccesses() {#a7fdb4a73925c17adcb4eaeafda02978d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::allowsMisalignedMemoryAccesses (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, unsigned AS, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dd">MachineMemOperand::Flags</a> Flags, unsigned * Fast)</td>
</tr>
</table>
</td>
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


<p>Returns whether it is "fast" in the last argument.</p>


<p>Declaration at line 1100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="#a1a78b1cfe835bfe405897b9b75cf17fb">isMemoryAccessFast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda8d09c51969b0954512ed65ee26551081">llvm::MachineMemOperand::MONonTemporal</a>.</p>


<p>Referenced by <a href="#acca525d32f859c8c653921b5fff62ed3">allowsMemoryAccess</a>.</p>

</div>
</div>

### allowTruncateForTailCall() {#a9c91bde4107b00ee5520f121253437ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::allowTruncateForTailCall (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * FromTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ToTy)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>.</p>

</div>
</div>

### areJTsAllowed() {#aaf07f4afc0dc648abf4f548e2db2b7c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::areJTsAllowed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Fn)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if lowering to a jump table is allowed.</p>

<p>Declaration at line 1483 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a392f6e72d46ff14ee31481e3452f6c31">llvm::TargetLoweringBase::areJTsAllowed</a>.</p>

</div>
</div>

### BuildFILD() {#a168f3532cb1605bbc91fcc079892e357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; X86TargetLowering::BuildFILD (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> DstVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SrcVT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Pointer, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> PtrInfo, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1585 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 19816 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1ae307f415a8989475e3f7ddd6eefc8b">llvm::MachineFrameInfo::CreateStackObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aadc5e8eb45f3fff639c5f0edefe64f641">llvm::X86ISD::FILD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa01d97a3473a8e41bf1dcc6ba3ea8c7eb">llvm::X86ISD::FST</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acb59cbd8f4a8c1cf820b2b540aebdac1">llvm::SelectionDAG::getFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6cc63109335eefe2c5727d1e12fc820">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a1572b31fadbd0d758314b8d35a050410">llvm::EVT::getStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="#ab32d538e8058be86b0efc0d970b35735">isScalarFPTypeInSSEReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>.</p>

</div>
</div>

### canCreateUndefOrPoisonForTargetNode() {#af2d807474cb0bf45eccd77f335159b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::canCreateUndefOrPoisonForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool PoisonOnly, bool ConsiderFlags, unsigned Depth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> can create undef or poison from non-undef &amp; non-poison operands.</p>


<p>The DemandedElts argument limits the check to the requested vector elements.</p>


<p>Declaration at line 1322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 44490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a690ecd418854c4f2bea36d278c8cb7a2">llvm::TargetLowering::canCreateUndefOrPoisonForTargetNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa0f4605a7e5bb3cda3e1e3f6b05c08c46">llvm::X86ISD::CMPP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a4346f62e0e1ee37b8c7877df168057f5aaa2fad9a8387f8d5f005f3e308ae676f">PoisonOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa182b063ab7dd0842ce968cef5f981e92">llvm::X86ISD::PSHUFD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa03a9611e6b354e10a8c3809f49b61eac">llvm::X86ISD::UNPCKH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa000697f31e57d54cd3ae43a2568c36ca">llvm::X86ISD::UNPCKL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aadbf48e1eda461f1db91b138d32c7e8d5">llvm::X86ISD::VPERMILPI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab63fa0a5c1888e275635edaaf3ffa3ed">llvm::X86ISD::VPERMV3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab02310456415907ec1be4ceae53d48a9">llvm::X86ISD::VPMADDUBSW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa90d5ada6e2cf83b82e077c35702f2fc3">llvm::X86ISD::VPMADDWD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf5db7ecddd15a88ac103ef566d0b2180">llvm::X86ISD::VSHLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa53a1bf88056b37006ab9ba3b83f1f6ae">llvm::X86ISD::VSRAI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa88145107ca3ab31b2e96b5e99bf5b517">llvm::X86ISD::VSRLI</a>.</p>

</div>
</div>

### canMergeStoresTo() {#a66a0f33d36e31ddfbd254a77524f9192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::canMergeStoresTo (unsigned AS, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> MemVT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>.</p>

</div>
</div>

### computeKnownBitsForTargetNode() {#ae0caaab3a18e77b9f48dc88b3b757dd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86TargetLowering::computeKnownBitsForTargetNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth=0)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 38187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8957fd90a0c765af6746fb0849ee1a8a">llvm::X86ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae1624a99d3ee1309539c25a7afe2a852">llvm::X86ISD::ANDNP</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a0c649ec21217b3feb2f2a28b4736b689">llvm::KnownBits::anyextOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a7e30b3aa214eba50eed018b5b19fc6aa">llvm::APInt::ashrInPlace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7ead8df5cf10d5f87e8c19b6f7d34ad6">llvm::X86ISD::BEXTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa0e30dfae5bfdf5db17847036581a181f">llvm::X86ISD::BEXTRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37c1fdede126353d80c3753dfe06f3c7">llvm::bit_width</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae5919ad05b126b2a4c57f822c6521d77">llvm::X86ISD::BSF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa3eb8cf555013535c83a18858c5c4d5e3">llvm::X86ISD::BSR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a477ef80c70c7359199eace0e5d3133b1">llvm::ISD::BUILTIN_OP_END</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a781bd5c20864a9c185018258af774ace">llvm::APInt::clearAllBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf413bba9e77d68afdc1afba084851728">llvm::X86ISD::CMOV</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aa730d6c2ddb52a05e3602c501e961629">computeKnownBitsForHorizontalOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa16bb473dbb4b04fd2b11ccb72660b0e">computeKnownBitsForPMADDUBSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3caf52501b70f5695183149e578fbd5a">computeKnownBitsForPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a36334a70d900ffeea3274a6078fce675">computeKnownBitsForPSADBW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a2ad6370e532a52014fe2e5a54bfbaddd">llvm::KnownBits::countMaxTrailingZeros</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a7f47812e8e75b0616a97d7004e5fb909">llvm::KnownBits::countMinLeadingZeros</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a1eeff70353694cb360b2893553c18e7d">llvm::KnownBits::countMinTrailingZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83c7c9008ba213687483b60a658b4a13">llvm::APInt::countr_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa3d9c4511648f4aeb6cdc39851c6b4759">llvm::X86ISD::CVTP2SI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa5af26ba107d346037ecbd751de03de5d">llvm::X86ISD::CVTP2UI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa1fec5162852502da5a2832321f9c1012">llvm::X86ISD::CVTPS2PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf64444ca786d0cddde2bc8628f324e3e">llvm::X86ISD::CVTSI2P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa873eda45cff31b9f5fe7af33ed2ec407">llvm::X86ISD::CVTTP2SI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac6c8013c7f060d7023eb23cb32fc14c8">llvm::X86ISD::CVTTP2UI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7821643340a91702a2540ac9a3e6ab53">llvm::X86ISD::CVTUI2P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a0aef6b7958c3eebec986bd226aca7325">llvm::KnownBits::eq</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a6f1c4a256c58844fb8dc8aa154f335a4">llvm::KnownBits::extractBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaabe3cfcecab0e3b2e2ab496a566c8d1c">llvm::X86ISD::FOR</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a4fdc09049a61f952b5d52788dbd2f69b">llvm::KnownBits::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adcb96bd09d7c75c7669fa5f9d1190899">llvm::APInt::getHighBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e33cb0aa9b4fbae99810b4d70d29f25">getPackDemandedElts</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0b31f77b61967dd90fbcc8174ea66e93">getTargetShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a126c61d55fb4d2e509537ce68e8b6400">llvm::TargetLoweringBase::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa0f4ce46b34ac79f389d475fa6745463e">llvm::X86ISD::HADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf02f5b8c1cc25ab0a8e6cd8e5364332f">llvm::X86ISD::HSUB</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a76e45a40f2f0b5b09132d1de119765e8">llvm::KnownBits::intersectWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a157efd68e8b4b838829cad165b1583f8">llvm::KnownBits::isNonNegative</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a5d774365f4d1120b030d026860193a02">llvm::KnownBits::isNonZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a91e9ffc69ac314ed0568b4dff93aa60f">isTargetShuffle</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a28cf355963391ab8781b2347d495553d">llvm::KnownBits::isUnknown</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af338e23a90c301183968435e80cd6a27">llvm::APInt::lshrInPlace</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a066220c7a472d8793de64a0ad23487d2">llvm::KnownBits::makeConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa9fc9cf61fd9db57b6e139ba9faa632ce">llvm::X86ISD::MCVTP2SI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa73d8b03b224b357896577a0b4df66be4">llvm::X86ISD::MCVTP2UI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa1bdf811a50ebc4ef297a426ff53509c2">llvm::X86ISD::MCVTPS2PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae2925d7ff6b5400012986018a81ecaa2">llvm::X86ISD::MCVTSI2P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa4e58653f8830ab73ca1b46538568aafc">llvm::X86ISD::MCVTTP2SI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa4608ef6812af0d3a623cf57df47178a1">llvm::X86ISD::MCVTTP2SIS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa5cffc707d7313cf293e1101acd35a609">llvm::X86ISD::MCVTTP2UI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa14cef8c252c1acfa276c0da5f1740743">llvm::X86ISD::MCVTTP2UIS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aafe9aa5f2f459e64cb14518d17481ad3f">llvm::X86ISD::MCVTUI2P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa5b943cbe99c34600de83e0c7c0046e18">llvm::X86ISD::MOVMSK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa126e28f14818b0b293da6aef89e11cbe">llvm::X86ISD::MOVQ2DQ</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#abd85d08f35600dd19615a1efe9cacb1d">llvm::KnownBits::mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab42a00cd9b29370e08759eeed0673c0a">llvm::X86ISD::MUL_IMM</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae3abaac16c2c7818508b6e93d170c6b3">llvm::X86ISD::PACKUS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8e6b692f93aee762231d7221e5730598">llvm::X86ISD::PCMPEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf1366c70ee0fa95a076fe683d900e9f9">llvm::X86ISD::PCMPGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa492e5211769c80814cb779b4ba995f23">llvm::X86ISD::PDEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa5e4a0e6bc60434430bf6a9da9071e894">llvm::X86ISD::PEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa71fe63f40efcc073f1a5dd6df6efc550">llvm::X86ISD::PEXTRB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8c57aafe37f470b4b146ea8307983228">llvm::X86ISD::PEXTRW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7f0c379fa7f4b37235504936c56ae486">llvm::X86ISD::PMULUDQ</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a27ad8ac0b3b15a21f86c5f89e0c9cdd0">llvm::APInt::popcount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaaa69270d771a472e5b86c11370dc0330">llvm::X86ISD::PSADBW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8a421b1832302b5097a94b81ed579170">llvm::X86ISD::PSHUFB</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a538f22b4ea2ff04a0b41403f26eaeb67">llvm::KnownBits::resetAll</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab6fff8a97bcb55e50e9be0ecf0c99b63">llvm::APInt::setAllBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ab0f473e7109b116f0337cbe78964e6af">llvm::KnownBits::setAllOnes</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a4816b869391aac5bbcce9c889c2ecd97">llvm::KnownBits::setAllZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a286d4fa2a50c9ac6ac3a8069cccfcd0c">llvm::APInt::setBitsFrom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa45f2ab1ba8d655b3fde883df17385b54">llvm::X86ISD::SETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a2780c5606880394d3f07cd2079a27697">llvm::APInt::setHighBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ade8e20ecea1091e835395746448e262e">llvm::APInt::setLowBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ad20d9f61ec3c5c2a0bd9163cb6c15335">llvm::KnownBits::sgt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaddf811d44f58e7d0e16ca3266b8689a3f112d168d45b1ab58a80c2b9f7e6cb4">llvm::SM_SentinelUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaddf811d44f58e7d0e16ca3266b8689ac131901c70cd3380fd61a47415b58740">llvm::SM_SentinelZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aafa37e128cf1dbc7b4b4825400f999e83">llvm::X86ISD::STRICT_CVTPS2PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa73a98d37d002eedda0f99b15e04462a3">llvm::X86ISD::STRICT_CVTSI2P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa64a6fc099c65248a3deba44a57f1d99f">llvm::X86ISD::STRICT_CVTTP2SI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa40f22ea742439c6dddbfe08b02d48331">llvm::X86ISD::STRICT_CVTTP2UI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa6b06c0682b59b924440540643e5c3262">llvm::X86ISD::STRICT_CVTUI2P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab12f350653f681354125c5f9a97c6bab">llvm::X86ISD::STRICT_VFPROUND</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a40a666d8a3b58f5eca5d7f9f26796bc7">llvm::KnownBits::trunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac3bc043916fd84786c2ac451e0a3cd24">llvm::X86ISD::VBROADCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa78f74c46439b34ecc3b826e4bb5f1fc2">llvm::X86ISD::VBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa931754702331756731a26916aebb794c">llvm::X86ISD::VFPROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa4d1e3a8e02ddc590b8c60205884b32d4">llvm::X86ISD::VMFPROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab02310456415907ec1be4ceae53d48a9">llvm::X86ISD::VPMADDUBSW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa90d5ada6e2cf83b82e077c35702f2fc3">llvm::X86ISD::VPMADDWD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf5db7ecddd15a88ac103ef566d0b2180">llvm::X86ISD::VSHLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa53a1bf88056b37006ab9ba3b83f1f6ae">llvm::X86ISD::VSRAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa88145107ca3ab31b2e96b5e99bf5b517">llvm::X86ISD::VSRLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aabb0879a5b12d023b74697191612bddaa">llvm::X86ISD::VTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa192681cddd79867e5a6924bbcf453965">llvm::X86ISD::VTRUNCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa3b2fdb13adfdfd71f723a38073cb43f0">llvm::X86ISD::VTRUNCUS</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a51c3c203b80468b8761416d14e6f5b7f">llvm::KnownBits::zext</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a7ddb13bdf305b1d4eee7bf1a9ac9d35e">llvm::KnownBits::zextOrTrunc</a>.</p>

</div>
</div>

### ComputeNumSignBitsForTargetNode() {#aa734719767b4f7faea1f7b40554f30be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86TargetLowering::ComputeNumSignBitsForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the number of bits in the operation that are sign bits.</p>

<p>Declaration at line 1289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 38650 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae1624a99d3ee1309539c25a7afe2a852">llvm::X86ISD::ANDNP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf413bba9e77d68afdc1afba084851728">llvm::X86ISD::CMOV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa0f4605a7e5bb3cda3e1e3f6b05c08c46">llvm::X86ISD::CMPP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac01c66c983bfbac05a0cf903f08417df">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7b0a95242bc129e654632fbc83ecc472">llvm::X86ISD::FSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e33cb0aa9b4fbae99810b4d70d29f25">getPackDemandedElts</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#abd46b9ca1d156bc7e3dd9150cc106a28">llvm::SDValue::getScalarValueSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0b31f77b61967dd90fbcc8174ea66e93">getTargetShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a126c61d55fb4d2e509537ce68e8b6400">llvm::TargetLoweringBase::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a91e9ffc69ac314ed0568b4dff93aa60f">isTargetShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa0e447f5393ad6797e4af00c9401ca6d3">llvm::X86ISD::PACKSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8e6b692f93aee762231d7221e5730598">llvm::X86ISD::PCMPEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf1366c70ee0fa95a076fe683d900e9f9">llvm::X86ISD::PCMPGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1f4429b3a6cbf22cea042b77cf055f40">llvm::peekThroughBitcasts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aadd6a532536216924183465a65e0585b7">llvm::X86ISD::SETCC_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaddf811d44f58e7d0e16ca3266b8689a3f112d168d45b1ab58a80c2b9f7e6cb4">llvm::SM_SentinelUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaddf811d44f58e7d0e16ca3266b8689ac131901c70cd3380fd61a47415b58740">llvm::SM_SentinelZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac3bc043916fd84786c2ac451e0a3cd24">llvm::X86ISD::VBROADCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aadcca882e85abfd81e17c1dba55d05e1a">llvm::X86ISD::VPCOM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa3be4201d9ac120bd22b241cb6062f558">llvm::X86ISD::VPCOMU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf5db7ecddd15a88ac103ef566d0b2180">llvm::X86ISD::VSHLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa53a1bf88056b37006ab9ba3b83f1f6ae">llvm::X86ISD::VSRAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aabb0879a5b12d023b74697191612bddaa">llvm::X86ISD::VTRUNC</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a2ed912a28808268e35bd58e8f11251aa">llvm::APInt::zextOrTrunc</a>.</p>

</div>
</div>

### convertSelectOfConstantsToMath() {#a35f30c99560e45f1031fe1855c73b02c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::convertSelectOfConstantsToMath (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if a select of constants (select Cond, C1, C2) should be transformed into simple math ops with the condition value.</p>


<p>For example: select Cond, C1, C1-1 --&gt; add (zext Cond), C1-1</p>


<p>Declaration at line 1509 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### convertSetCCLogicToBitwiseLogic() {#abba0e811da8d1436a96fda0e356a6d24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86TargetLowering::convertSetCCLogicToBitwiseLogic (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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


<p>Definition at line 1265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#ad958859a7af278dd5ea2b593c2b25050">llvm::EVT::isScalarInteger</a>.</p>

</div>
</div>

### createFastISel() {#ae0a481e8df0f6d0d536fa71fa5c5f3d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastISel * X86TargetLowering::createFastISel (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; funcInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * libInfo)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1564 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2771 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ac370a59c2440ede047ceeea4ac9e9f77">llvm::X86::createFastISel</a>.</p>

</div>
</div>

### decomposeMulByConstant() {#aaef16aaed0ce790c381e75d7c9253f1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::decomposeMulByConstant (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> C)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1511 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad859786d7e54bdc5c568ac20c69816e0">llvm::TargetLoweringBase::getTypeAction</a>, <a href="#af23e95d85be78026c607fa689dda4cd1">getTypeToTransformTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#aafb64237a88493be2c913b0a51630a0f">llvm::ISD::isConstantSplatVector</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9245ed740fe76aaad3e5b0650da21c98">llvm::TargetLoweringBase::isOperationLegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681af54ec6880362512f9fec982cd4ce39fb">llvm::TargetLoweringBase::TypeLegal</a>.</p>

</div>
</div>

### EmitInstrWithCustomInserter() {#a5fd231b7f6dc1db67a2bb2f48bf5f342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * X86TargetLowering::EmitInstrWithCustomInserter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 37349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e8b1da7820b3f19cfb702d4312410ce">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41229d95ec1712486d97ae6c27a0ba8a">llvm::addFullAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acce9c12cc977a88dc7bc51493ce7681c">llvm::MachineBasicBlock::addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a752b9dfb94f917a9e494fc4ed8cb6208">llvm::addRegOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a5aec578e2e391e99e1705012752d84ac4169d78e1c6de9b189f31b90f1c2691">llvm::X86::AddrNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1ae307f415a8989475e3f7ddd6eefc8b">llvm::MachineFrameInfo::CreateStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a5c77792a06583e0fe7a0379ad94a2809">llvm::MachineRegisterInfo::createVirtualRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a24c2247bd546fc56e2de6cfd04a3d7aecaade218a8405db0eae7cab82109c40">llvm::DirectReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13a9214d6e92afcb3e956a5891522bed">emitXBegin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp/#a23ffb844d0a50f112dc26ac2d0e41910">GET_EGPR_IF_ENABLED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a3c38584ad91b3e408fa867373ca63225">llvm::X86MachineFunctionInfo::getPreallocatedArgOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a98635a734a316564e14c3d8026dfd579">llvm::X86MachineFunctionInfo::getPreallocatedStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1a78b9f867cb5be3a052d6ad972484ca">llvm::TargetLoweringBase::getRegClassFor</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode/#af1965b0188d8595d0aaf002d0eb6d009">llvm::X86AddressMode::IndexReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#af9745f59d6647bd43f9f7959ca1a9971">llvm::MachineBasicBlock::isLiveIn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a24c2247bd546fc56e2de6cfd04a3d7aa92628f81845096d30f91faafc41c043">llvm::ManagedRA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a2a25c462b91ac5da41f4ab7edc32b650">llvm::MachineBasicBlock::rend</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a0ac98011f3ccfe7d6bcde125908df7e4">llvm::X86MachineFunctionInfo::setAMXProgModel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a306fafb1bafe9d3071420d3795dcfef2">llvm::setDirectAddressInInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a902babe97cb0fab51ae380bc8acec4a3">llvm::X86MachineFunctionInfo::setHasPreallocatedCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806">llvm::RegState::Undef</a>.</p>

</div>
</div>

### EmitKCFICheck() {#a89a6b95d310330e345c3aee6a07ffd96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * X86TargetLowering::EmitKCFICheck (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a> &amp; MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1617 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 60925 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aca439bf65258d9d8d057812938b617c5">llvm::StringRef::ends_with</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af066b2b6a1013299bfca84fe8b798a0b">llvm::MachineInstrBuilder::getInstr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a1edf23fab2b9c28661068c487aeeb401">llvm::MachineFunction::moveAdditionalCallInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### emitStackGuardXorFP() {#ad4b65d0fe3e7a2dd0eed89a2c22d23bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::emitStackGuardXorFP (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1576 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2745 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c04c72abd24de2572a03ef686a36dd6">llvm::SelectionDAG::getMachineNode</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>.</p>

</div>
</div>

### expandIndirectJTBranch() {#adfbecc9eaa3da520aafda5f3078baf3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::expandIndirectJTBranch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Value, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, int JTI, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expands target specific indirect branch for the case of <a href="/web-llvm/docs/api/namespaces/llvm/jumptable">JumpTable</a> expansion.</p>

<p>Declaration at line 1654 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 59598 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ad19715a9c62a6c91102ac12bbe18b63a">llvm::TargetLowering::expandIndirectJTBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2bc00c7622192e2c657119cf002b0f1d">llvm::SelectionDAG::getJumpTableDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa99670b16fe6d370e306896cd91b6fa6">llvm::SelectionDAG::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a33fe94054a904130a7c774f78423c8b7">llvm::TargetMachine::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a6300d761fd69580d711fad99b934950a">llvm::Triple::isOSBinFormatCOFF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa5913fb8adc3c04ec97f2069e6df3ffa1">llvm::X86ISD::NT_BRIND</a>.</p>

</div>
</div>

### ExpandInlineAsm() {#a687e754bf03f8d135bc899b49db74472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::ExpandInlineAsm (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 59778 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#add1eb5637dd671428b6f138ed3db6428">llvm::array_pod_sort</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a98f2e06ea0575c5920f76e241e4cc65f">clobbersFlagRegisters</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a8d13199cbf4d080d3b5dcf330dad5d2c">llvm::CallBase::getCalledOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a1e07c1aec365d4862fe2edef28aeec38">llvm::IntrinsicLowering::LowerToByteSwap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6ded20d42a05e6478238dcfd3caceede">matchAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>

</div>
</div>

### functionArgumentNeedsConsecutiveRegisters() {#a48e8c06ef441f4292cca267972e02055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::functionArgumentNeedsConsecutiveRegisters (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1607 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### getByValTypeAlignment() {#a4fcc58c4d285835e0ac6fc644012b0be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align X86TargetLowering::getByValTypeAlignment (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the desired alignment for ByVal aggregate function arguments in the caller parameter area.</p>


<p>For <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a>, aggregates that contains are placed at 16-byte boundaries while the rest are at 4-byte boundaries.</p>


<p>For <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a>, aggregates that contain SSE vectors are placed at 16-byte boundaries while the rest are at 4-byte boundaries.</p>


<p>Declaration at line 1083 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/align/#ac7699332a966bc646e928f780142c43a">llvm::Align::Constant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a8baa555a40ec02c58a1e0455237f65f9">getMaxByValAlign</a>.</p>

</div>
</div>

### getConstraintType() {#a370d811aff2e392f420421995d439701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86TargetLowering::ConstraintType X86TargetLowering::getConstraintType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a constraint letter, return the type of constraint for this target.</p>

<p>Declaration at line 1351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 59890 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a7bc0fe0fa6be5eaabb77e46c8d9ab2c8">llvm::TargetLowering::C_Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116abc9c279d343d2f957ab51b37ff39e88e">llvm::TargetLowering::C_Other</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a85f9b8131f0608c03c58e4e23d875dfc">llvm::TargetLowering::C_Register</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a1d7718fd43ac0a5c715686a76f9cfd89">llvm::TargetLowering::C_RegisterClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2eab1840bfcd789713b29a40d9d55cb41e3">llvm::X86::COND_INVALID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a45b2deb637d370d68d3bd3786c21e415">llvm::TargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5d8593bb34f2d8b9e8b81d36a3a72e54">parseConstraintCode</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### getExceptionPointerRegister() {#adcc17da43772e9fa8d8aeb458a8f2d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register X86TargetLowering::getExceptionPointerRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PersonalityFn)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 27985 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aa05b0e25c98ba4300ca28989a35dab72a">llvm::CoreCLR</a>.</p>

</div>
</div>

### getExceptionSelectorRegister() {#a3968afa27f1e806f9448f94527d61d53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register X86TargetLowering::getExceptionSelectorRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PersonalityFn)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 27993 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa014490a40c9286ee7e026a2f579eea9">llvm::isFuncletEHPersonality</a>.</p>

</div>
</div>

### getInlineAsmMemConstraint() {#a3ba8881f3b3a742488705f0d17bb2db5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAsm::ConstraintCode llvm::X86TargetLowering::getInlineAsmMemConstraint (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ConstraintCode)</td>
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



<p>Definition at line 1369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a3acbc2d34d9a6d35b63a04f0ae20136c">llvm::TargetLowering::getInlineAsmMemConstraint</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a9e3669d19b675bd57058fd4664205d2a">llvm::InlineAsm::v</a>.</p>

</div>
</div>

### getIRStackGuard() {#a4cb54e7d62530f9e973ff35f6301de6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * X86TargetLowering::getIRStackGuard (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; IRB)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1569 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86as/#a58acad10b11edf7fe9b4465d6e02e9bda5b3a782ccae295a254e2794ad30ad07f">llvm::X86AS::FS</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a784589f886057bdb03273b8bb07deb2b">llvm::TargetLoweringBase::getIRStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86as/#a58acad10b11edf7fe9b4465d6e02e9bdae6c7f069a983c84ea52c71b384ad2730">llvm::X86AS::GS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#aaf395b1362beab9f5199bd2094f3d19c">hasStackGuardSlotTLS</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#abdf7cd534c311883094a5534590f3bc1">SegmentOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a78c4d0538c7dbffa955486abae2b61bb">llvm::GlobalValue::setDSOLocal</a>.</p>

</div>
</div>

### getJumpConditionMergingParams() {#ae825ce933018e12e8997a98923a1a4d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLoweringBase::CondMergingParams X86TargetLowering::getJumpConditionMergingParams (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Rhs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fab51db30fb085ff7ef8fa9ecb4c58a">BrMergingBaseCostThresh</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a16ee7c0f765b7e0985af597bc9d90a5b">BrMergingCcmpBias</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a98ab07fc7f0a56bf5aa394094f9899c5">BrMergingLikelyBias</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af6c78a3fb72a1151565c4cd517a0859b">BrMergingUnlikelyBias</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6924ab881778c340b66e1e693154b1a8">llvm::PatternMatch::m_SpecificICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>

</div>
</div>

### getJumpTableEncoding() {#a14ba729e50c70d2bff3f12c884209140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86TargetLowering::getJumpTableEncoding ()</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#aaa21facdbb167f7c33d21907b8e5b9d3a9e655fb625d744f96e03aed78ca85707">llvm::MachineJumpTableInfo::EK_Custom32</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#aaa21facdbb167f7c33d21907b8e5b9d3a9f3683fb3f6e9f802d817742cf08a1a5">llvm::MachineJumpTableInfo::EK_LabelDifference64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#aa85a26f5f6b24110a2388e4726cdd282">getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aded686370215fda472fa7b38ccbba458">llvm::TargetLowering::getJumpTableEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aa8ab0804ddb40450da6549e1943817a2">llvm::TargetLowering::isPositionIndependent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>.</p>

</div>
</div>

### getMaxSupportedInterleaveFactor() {#a8b0b7687cd51e781f5b3851d9dcc10a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86TargetLowering::getMaxSupportedInterleaveFactor ()</td>
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


<p>Definition at line 1629 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>


<p>Referenced by <a href="#a9157e4aca11eca217c5c6d2c6a2eadbf">lowerInterleavedLoad</a> and <a href="#ab5881269962ffb5a6c2d4c5be45efbce">lowerInterleavedStore</a>.</p>

</div>
</div>

### getNegatedExpression() {#a402c372a2886c19770de2cc65b41a7e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::getNegatedExpression (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool LegalOperations, bool ForCodeSize, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad717707a2df4226d0388460e87c8cd84">NegatibleCost</a> &amp; Cost, unsigned Depth)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 54116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad717707a2df4226d0388460e87c8cd84a4691542279fb918ac8c43619d77aefdf">llvm::TargetLoweringBase::Cheaper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae5c55557d6753435f3b5b6d9678dfacc">llvm::X86ISD::FMADD_RND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa9d8ad87414cdc8a0416b4c94957c1775">llvm::X86ISD::FMSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa865d34b939542df305710438eb9a8d2f">llvm::X86ISD::FMSUB_RND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa367039352ad0788f23a2ce9bcd493f2a">llvm::X86ISD::FNMADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa60f697da41de26a8822eeea8b508404c">llvm::X86ISD::FNMADD_RND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa5366e83be28759f315637517f6d3f369">llvm::X86ISD::FNMSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa6adc5233cdab66da1ea6f13370a00570">llvm::X86ISD::FNMSUB_RND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aacd28a0d5248d37cbf2d4449434a70a98">llvm::X86ISD::FRCP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a64f6469ab95c4eec77e4ccf303619a81">llvm::SelectionDAG::getBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a48fe15bdf777438d3ff912a613650642">llvm::TargetLowering::getCheaperNegatedExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aea3e575b3cff4eb444567d50959b929c">llvm::TargetLowering::getNegatedExpression</a>, <a href="#a402c372a2886c19770de2cc65b41a7e0">getNegatedExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a37f06b796addd745c44af4546b84fe76">isFNEG</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9245ed740fe76aaad3e5b0650da21c98">llvm::TargetLoweringBase::isOperationLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab25016fec23cd9163b31c97f1e90f5a4">negateFMAOpcode</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad717707a2df4226d0388460e87c8cd84ae9bb5320b3890b6747c91b5a71ae5a01">llvm::TargetLoweringBase::Neutral</a>.</p>


<p>Referenced by <a href="#a402c372a2886c19770de2cc65b41a7e0">getNegatedExpression</a>.</p>

</div>
</div>

### getNumRegistersForCallingConv() {#aba30f84d7fd0dd3361ff92fe1e53d9ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86TargetLowering::getNumRegistersForCallingConv (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1599 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ad9d00ad929ec93255787f7f80c4659d9">llvm::EVT::changeVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a315b23c0819f55fa9e7473c21992fc12">llvm::TargetLoweringBase::getNumRegistersForCallingConv</a>, <a href="#aba30f84d7fd0dd3361ff92fe1e53d9ca">getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a6bee4eedbbc7bcd5f3b37572c9bf2a67">handleMaskRegisterForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64daf4f312520aaba4506b874a3f83fe2464">llvm::MVT::INVALID_SIMPLE_VALUE_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>


<p>Referenced by <a href="#aba30f84d7fd0dd3361ff92fe1e53d9ca">getNumRegistersForCallingConv</a>.</p>

</div>
</div>

### getOptimalMemOpType() {#a53dee73973a09e035447943bb5bde29e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT X86TargetLowering::getOptimalMemOpType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memop">MemOp</a> &amp; Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &amp; FuncAttributes)</td>
</tr>
</table>
</td>
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


<p>For vector ops we check that the overall size isn't larger than our preferred vector width.</p>


<p>Declaration at line 1085 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a61054ea97168f709c1e46345f80c16a3">llvm::AttributeList::hasFnAttr</a>.</p>

</div>
</div>

### getPICJumpTableRelocBase() {#a0b5f9da7c8b5d244b67be30f07debf6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::getPICJumpTableRelocBase (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Table, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1073 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa9f2e4e1e83010173fe9361ecfa60faef">llvm::X86ISD::GlobalBaseReg</a>.</p>

</div>
</div>

### getPICJumpTableRelocBaseExpr() {#a424abc19654b712885d63747e7f5b4db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * X86TargetLowering::getPICJumpTableRelocBaseExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, unsigned JTI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1076 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#aa85a26f5f6b24110a2388e4726cdd282">getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a28b6761f167a2c40e54f5291ac35051d">llvm::MachineFunction::getPICBaseSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a993d38cd5b37a6ee0c9c3cb24ada5392">llvm::TargetLowering::getPICJumpTableRelocBaseExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>.</p>

</div>
</div>

### getPreferredSwitchConditionType() {#ab40e47d665eb61ef848654a1d6526f7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT X86TargetLowering::getPreferredSwitchConditionType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ConditionVT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns preferred type for switch condition.</p>

<p>Declaration at line 1485 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a79ca0cc68830eccfb4d7e2f4bdfd9857">llvm::TargetLoweringBase::getPreferredSwitchConditionType</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>.</p>

</div>
</div>

### getPreferredVectorAction() {#ac812947e59d1a47c994bc61bb372c743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLoweringBase::LegalizeTypeAction X86TargetLowering::getPreferredVectorAction (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Customize the preferred legalization strategy for certain types.</p>

<p>Declaration at line 1592 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2754 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a59ae7f93fccb0ae431e82f8d74ba443c">llvm::TargetLoweringBase::getPreferredVectorAction</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a447ebcc5de7a1d9bc163862bf2c78e41">llvm::MVT::isScalableVector</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681a40cd81ebfaf97cef327ad65d37b816da">llvm::TargetLoweringBase::TypeSplitVector</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681a5290057031a9bc71850f61e757cb940e">llvm::TargetLoweringBase::TypeWidenVector</a>.</p>

</div>
</div>

### getPrefLoopAlignment() {#a010c17359b18d005263da7a193fe2872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align X86TargetLowering::getPrefLoopAlignment (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * ML)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1657 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 61043 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4748c1336e7a78a7ca86402d788f39cb">ExperimentalPrefInnermostLoopAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6d826603b43f8d54445e71d004a79f36">llvm::TargetLoweringBase::getPrefLoopAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3ad01fd9b01e9dde8bd3dc247afbfb7218">ML</a>.</p>

</div>
</div>

### getRegForInlineAsmConstraint() {#a7a7237cd5cb35f9159b32a96f4b14541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, const TargetRegisterClass * &gt; X86TargetLowering::getRegForInlineAsmConstraint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
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


<p>{edx}), return the register number and the register class for the register. This should only be used for C_Register constraints. On error, this returns a register number of 0.</p>


<p>Declaration at line 1386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 60355 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2eab1840bfcd789713b29a40d9d55cb41e3">llvm::X86::COND_INVALID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a60b6974966381f08079722f2258a0039">llvm::TargetRegisterClass::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#af09507c47dcb4cdb2a13064aaa6d5243">llvm::TargetLowering::getRegForInlineAsmConstraint</a>, <a href="#a7a7237cd5cb35f9159b32a96f4b14541">getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27b344a283e0620f484144889fe32064">llvm::getX86SubSuperRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a811049dc54f4a8053c0b34c8fa470a99">isFRClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0ae9685e0bfae51cfb048c3a2da8a06f">isGRClass</a>, <a href="#ab32d538e8058be86b0efc0d970b35735">isScalarFPTypeInSSEReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67e06f2d863f883613cc60086eb26493">isVKClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5d8593bb34f2d8b9e8b81d36a3a72e54">parseConstraintCode</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0983bc6900904613d5fc6f7108333d88">useEGPRInlineAsm</a>.</p>


<p>Referenced by <a href="#a7a7237cd5cb35f9159b32a96f4b14541">getRegForInlineAsmConstraint</a>.</p>

</div>
</div>

### getRegisterByName() {#a42f7160579c4a68a75447d21da859821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register X86TargetLowering::getRegisterByName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RegName, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1547 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 27946 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### getRegisterTypeForCallingConv() {#a7c19f0fe8ae2a12ed0c5cf142a520522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT X86TargetLowering::getRegisterTypeForCallingConv (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1596 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ad9d00ad929ec93255787f7f80c4659d9">llvm::EVT::changeVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a347d293012b5070f6833926f3d2e50d7">llvm::TargetLoweringBase::getRegisterTypeForCallingConv</a>, <a href="#a7c19f0fe8ae2a12ed0c5cf142a520522">getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a6bee4eedbbc7bcd5f3b37572c9bf2a67">handleMaskRegisterForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64daf4f312520aaba4506b874a3f83fe2464">llvm::MVT::INVALID_SIMPLE_VALUE_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>


<p>Referenced by <a href="#a7c19f0fe8ae2a12ed0c5cf142a520522">getRegisterTypeForCallingConv</a>.</p>

</div>
</div>

### getReturnAddressFrameIndex() {#adc0b03138cc7b455d625146b7091345d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::getReturnAddressFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2899 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a03cf34252938b54f7e86c736f9fd7dc1">llvm::MachineFrameInfo::CreateFixedObject</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acb59cbd8f4a8c1cf820b2b540aebdac1">llvm::SelectionDAG::getFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>.</p>

</div>
</div>

### getSafeStackPointerLocation() {#aae8b0683e3e2b366aaac8bca13553f42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * X86TargetLowering::getSafeStackPointerLocation (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; IRB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target stores SafeStack pointer at a fixed offset in some non-standard address space, and populates the address space and offset as appropriate.</p>

<p>Declaration at line 1583 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1b127c37d77da045cea07e787e2d1e48">llvm::TargetLoweringBase::getSafeStackPointerLocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#abdf7cd534c311883094a5534590f3bc1">SegmentOffset</a>.</p>

</div>
</div>

### getScalarShiftAmountTy() {#a4c9434966be55f571aeedb8a356b5b1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::X86TargetLowering::getScalarShiftAmountTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
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


<p>Definition at line 1063 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>

</div>
</div>

### getSDagStackGuard() {#a8f631e7cc44c1035e858c667b345ec78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * X86TargetLowering::getSDagStackGuard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1574 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a40e9675119de3bcd2fd05b549994a17d">llvm::TargetLoweringBase::getSDagStackGuard</a>.</p>

</div>
</div>

### getSetCCResultType() {#ae93a1ba51c086441ec1b9ea4cdca853a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT X86TargetLowering::getSetCCResultType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the value type to use for <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">ISD::SETCC</a>.</p>

<p>Declaration at line 1273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a0351571482fea42a3b326147fb2ce9e2">llvm::EVT::changeVectorElementTypeToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad859786d7e54bdc5c568ac20c69816e0">llvm::TargetLoweringBase::getTypeAction</a>, <a href="#af23e95d85be78026c607fa689dda4cd1">getTypeToTransformTo</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a3d102abca1c9c95f36546dff2f39273b">llvm::EVT::getVectorElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a210ba6b43ba451b698857dd9de71bd15">llvm::EVT::getVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a776c0f4551869d18e571ae4e87583d86">llvm::MVT::is512BitVector</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681af54ec6880362512f9fec982cd4ce39fb">llvm::TargetLoweringBase::TypeLegal</a>.</p>

</div>
</div>

### getSingleConstraintMatchWeight() {#ac437e7230f2990fd60bf089f20ea2e78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::ConstraintWeight X86TargetLowering::getSingleConstraintMatchWeight (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a> &amp; Info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Constraint)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 59969 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abca632c68154579a54426d0841e490ddb40">llvm::TargetLowering::CW_Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abcad4df0dd48c58dea43776a5a77e74ba76">llvm::TargetLowering::CW_Default</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abca2a03cc05a305d0cd861ff2d070da40ca">llvm::TargetLowering::CW_Invalid</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abcaa36ab38b266c612487d9ff61df7475af">llvm::TargetLowering::CW_Register</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abca8f769b6cac1ebb4de9412ecfe92fe20d">llvm::TargetLowering::CW_SpecificReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#afaa66a325b7b8c5c79eb2c8e9822ffd2">llvm::TargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### getSSPStackGuardCheck() {#a79b927c27465f57caae75ac35b49409f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * X86TargetLowering::getSSPStackGuardCheck (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1575 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a5cc7ede2e4ce0498c628270ca97ed75c">llvm::TargetLoweringBase::getSSPStackGuardCheck</a>.</p>

</div>
</div>

### getStackProbeSize() {#af64132885aa4151887699b689283e850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86TargetLowering::getStackProbeSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1625 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 61036 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a4c866d3504a1e0717c8152a590bd6203">llvm::Function::getFnAttributeAsParsedInteger</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>.</p>

</div>
</div>

### getStackProbeSymbolName() {#a92e17e524fe1c82a26b5433b6e9715e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef X86TargetLowering::getStackProbeSymbolName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the name of the symbol used to emit stack probes or the empty string if not applicable.</p>

<p>Declaration at line 1623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 61013 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a4c319db4fe05c27cfe55bd133a87414d">llvm::Function::getFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a968930aea9d9efa8d46dd890fce75643">llvm::Attribute::getValueAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a> and <a href="#a5cf46104ca48a9577dc4a61cf080003a">hasInlineStackProbe</a>.</p>


<p>Referenced by <a href="#ac9c3c65b113996cabc72bd6223410369">hasStackProbeSymbol</a>.</p>

</div>
</div>

### getTargetConstantFromLoad() {#af23897e28e2e84966892e512317b6acc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Constant * X86TargetLowering::getTargetConstantFromLoad (<a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> * LD)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method returns the constant pool value that will be loaded by LD.</p>


<p>NOTE: You must check for implicit extensions of the constant by LD.</p>


<p>Declaration at line 1343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 4890 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab0bb270c4647dee5b3ba4ff11bf30016">getTargetConstantFromNode</a>.</p>

</div>
</div>

### getTargetNodeName() {#ab3547e3af4263fb24bac33b211aa07fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * X86TargetLowering::getTargetNodeName (unsigned Opcode)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 34539 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad98783229b874cc80970a2f3aa495caaaa4b5c24d7f76fc72f5ef6d74ce18928b">llvm::BEXTRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad98783229b874cc80970a2f3aa495caaa9c1cecb11f8397a1372ea42882d80570">llvm::BLENDV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad98783229b874cc80970a2f3aa495caaa27853e9371524f9c0078f0489b2475b5">llvm::COMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp/#a05bf4b164c71aa8d0faf7b8cc33c47d5">EXPAND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa21644bb1fecd89fe8aef108bd866cb59">llvm::X86ISD::FIRST_NUMBER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02a3765a3e5b572f57e131a5eb88c0d4722">llvm::FMSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a788ace9bfafe2db73b33d1f4301ce081a3fa37ac5f5d303429c55b37d11a86190">llvm::FNMADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02a837b9b047b8d6dc7148a6a8882fb3e48">llvm::FNMSUB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#a5a3237f2dd913ef611a858ffc74366bc">NODE_NAME_CASE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad98783229b874cc80970a2f3aa495caaaaeaf5d7687a9049fe3bc3af6053fab81">llvm::RDRAND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad98783229b874cc80970a2f3aa495caaaa557b7fffdc064cde7929ab2c88747cf">llvm::RDSEED</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpualiasanalysis-cpp/#a63f565f28385a6f2c7a4756ff6f3fa16">Wrapper</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad98783229b874cc80970a2f3aa495caaa30b4eb5f7edad51c053b49114a37013d">llvm::XTEST</a>.</p>

</div>
</div>

### getTgtMemIntrinsic() {#aed6a89a13d6da0fb09c283664b86ccd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::getTgtMemIntrinsic (<a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/intrinsicinfo">IntrinsicInfo</a> &amp; Info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned Intrinsic)</td>
</tr>
</table>
</td>
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


<p>If this is the case, it returns true and stores the intrinsic information into the <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/intrinsicinfo">IntrinsicInfo</a> that was passed to the function.</p>


<p>Declaration at line 1461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3091 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad98783229b874cc80970a2f3aa495caaaae7890e198f938a5cfe2ac4c528c4ac7">llvm::GATHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad98783229b874cc80970a2f3aa495caaa369fe22b04d92017ce27c83273ba71e8">llvm::GATHER_AVX2</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a752372e170e4e7c595bf8810bb52adf2">llvm::EVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1f121f8dbe88b69e7f23fdb32f5fcc3c">llvm::getIntrinsicWithChain</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a56bb53e2d0b01c78c8c538f903fd45b8">llvm::MVT::getVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64daf4f312520aaba4506b874a3f83fe2464">llvm::MVT::INVALID_SIMPLE_VALUE_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">llvm::MachineMemOperand::MONone</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda796891d6ca349b671fce24b6d01d77a8">llvm::MachineMemOperand::MOVolatile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad98783229b874cc80970a2f3aa495caaa635984b0013f45af313b83be0011e523">llvm::SCATTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad98783229b874cc80970a2f3aa495caaa0709afeb5cefcf0434cb57684b576b4b">llvm::TRUNCATE_TO_MEM_VI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad98783229b874cc80970a2f3aa495caaa166a0110f020be69358071227b8cfe62">llvm::TRUNCATE_TO_MEM_VI32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad98783229b874cc80970a2f3aa495caaa5657bda6a489e5df169eaa9e9d517613">llvm::TRUNCATE_TO_MEM_VI8</a> and <a href="/web-llvm/docs/api/structs/llvm/intrinsicdata/#a8e168ff10e52c801f9792bdcab770613">llvm::IntrinsicData::Type</a>.</p>

</div>
</div>

### getTypeToTransformTo() {#af23e95d85be78026c607fa689dda4cd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::X86TargetLowering::getTypeToTransformTo (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>For types supported by the target, this is an identity function.</p>


<p>For types that must be promoted to larger types, this returns the larger type to promote to. For integer types that are larger than the largest integer register, this contains one step in the expansion to get to the smaller register. For illegal floating point types, this returns the integer type to transform to.</p>


<p>Definition at line 1659 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a752372e170e4e7c595bf8810bb52adf2">llvm::EVT::getIntegerVT</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a77f7add8733417370a56154e8b560617">llvm::TargetLoweringBase::getTypeToTransformTo</a>.</p>


<p>Referenced by <a href="#aaef16aaed0ce790c381e75d7c9253f1e">decomposeMulByConstant</a>, <a href="#ae93a1ba51c086441ec1b9ea4cdca853a">getSetCCResultType</a> and <a href="#af77fd362607d101a7080481254ee2fe3">ReplaceNodeResults</a>.</p>

</div>
</div>

### getVectorTypeBreakdownForCallingConv() {#a9f81a81b890192ac2e40f2995080feaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86TargetLowering::getVectorTypeBreakdownForCallingConv (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> &amp; IntermediateVT, unsigned &amp; NumIntermediates, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; RegisterVT)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ad9d00ad929ec93255787f7f80c4659d9">llvm::EVT::changeVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a5b806e2538d0e91175d970c8232a3099">llvm::TargetLoweringBase::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafab01b07b85e043c71ad4e2715d22073">llvm::CallingConv::X86_RegCall</a>.</p>

</div>
</div>

### hasAndNot() {#a69fbe6a7969fadd37ebea537ba3041e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::hasAndNot (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> X)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target has a bitwise and-not operation: X = ~A &amp; B This can be used to simplify select or other instructions.</p>

<p>Declaration at line 1210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3476 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="#a8e8d15fa57104d892b14366c39fafa77">hasAndNotCompare</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### hasAndNotCompare() {#a8e8d15fa57104d892b14366c39fafa77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::hasAndNotCompare (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Y)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
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


<p>Declaration at line 1208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3460 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="#a69fbe6a7969fadd37ebea537ba3041e3">hasAndNot</a>.</p>

</div>
</div>

### hasBitTest() {#a97eec348be19ac2d04575b281d2456b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::hasBitTest (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> X, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Y)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target has a bit-test instruction: (X &amp; (1 &lt;&lt; Y)) ==/!= 0 This knowledge can be used to prevent breaking the pattern, or creating it if it could be recognized.</p>

<p>Declaration at line 1212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3493 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### hasFastEqualityCompare() {#a52fdaa4464a4080f3b2883856462f6a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT X86TargetLowering::hasFastEqualityCompare (unsigned NumBits)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector-sized comparisons are fast using PCMPEQ + PMOVMSK or PTEST.</p>

<p>Declaration at line 1270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3658 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64daf4f312520aaba4506b874a3f83fe2464">llvm::MVT::INVALID_SIMPLE_VALUE_TYPE</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>.</p>

</div>
</div>

### hasInlineStackProbe() {#a5cf46104ca48a9577dc4a61cf080003a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::hasInlineStackProbe (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if stack probing through inline assembly is requested.</p>

<p>Declaration at line 1622 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 60995 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a4c319db4fe05c27cfe55bd133a87414d">llvm::Function::getFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a968930aea9d9efa8d46dd890fce75643">llvm::Attribute::getValueAsString</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>.</p>


<p>Referenced by <a href="#a92e17e524fe1c82a26b5433b6e9715e3">getStackProbeSymbolName</a>.</p>

</div>
</div>

### hasStackProbeSymbol() {#ac9c3c65b113996cabc72bd6223410369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::hasStackProbeSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if stack probing through a function call is requested.</p>

<p>Declaration at line 1621 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 60990 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="#a92e17e524fe1c82a26b5433b6e9715e3">getStackProbeSymbolName</a>.</p>

</div>
</div>

### hasVectorBlend() {#a37a095f9415bab8babe92997bd9bc863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86TargetLowering::hasVectorBlend ()</td>
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

<p>Return true if the target has a vector blend instruction.</p>

<p>Definition at line 1627 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>

</div>
</div>

### insertSSPDeclarations() {#af30042e4c09138928b477e3834f0a13e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86TargetLowering::insertSSPDeclarations (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1573 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncallee/#ac5d8da677233fa2e1e7039508ed56e0e">llvm::FunctionCallee::getCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#aaf395b1362beab9f5199bd2094f3d19c">hasStackGuardSlotTLS</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af3e31a71f6d0e55d41956d5b20ed7989">llvm::TargetLoweringBase::insertSSPDeclarations</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafde87569738f9e23963e8735f71c33eb">llvm::CallingConv::X86_FastCall</a>.</p>

</div>
</div>

### isBinOp() {#ae174548699928fd09f1b90077dfc2a48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isBinOp (unsigned Opcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add x86-specific opcodes to the default list.</p>

<p>Declaration at line 1412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35063 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae1624a99d3ee1309539c25a7afe2a852">llvm::X86ISD::ANDNP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa97670c93c4c4e70151c63e534993e04a">llvm::X86ISD::FANDN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa080313447e98432d4b62801bf2ad761f">llvm::X86ISD::FMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aabad10e5691f05a78824d6bad0300e529">llvm::X86ISD::FMIN</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab3598cfe4665dac7e694fb4be22158b8">llvm::TargetLoweringBase::isBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf1366c70ee0fa95a076fe683d900e9f9">llvm::X86ISD::PCMPGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaece0f87e173b1f5b36990e9ac4aa5ae5">llvm::X86ISD::VPSHA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaab0d78bdd53f75f09beb712341df5660">llvm::X86ISD::VPSHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8a2fc33ce2fe41ef2d20854eda49a4f6">llvm::X86ISD::VSHLV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7b2c246cb3a5d3513041dab6a32b2901">llvm::X86ISD::VSRAV</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa1e837f978c72eafaf138c1b0a7b6cddf">llvm::X86ISD::VSRLV</a>.</p>


<p>Referenced by <a href="#aa74ba35350fae122acd7284555740ba5">shouldScalarizeBinop</a>.</p>

</div>
</div>

### isCheapToSpeculateCtlz() {#a10629e54ed902429f3c4c53e0073a198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isCheapToSpeculateCtlz (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### isCheapToSpeculateCttz() {#a504396336fa994725f3d8c3265e38ead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isCheapToSpeculateCttz (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### isCommutativeBinOp() {#ab0ee342efbe8b2fe6cf2b0bcfdf2619a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isCommutativeBinOp (unsigned Opcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the opcode is a commutative binary operation.</p>

<p>Declaration at line 1415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35083 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaed927d0ca1203766de671e7437d658b2">llvm::X86ISD::FAND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaa24b80a5be93b9ddfa62446ced71b68e">llvm::X86ISD::FMAXC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aafb454d19747fe081325da96a69373f82">llvm::X86ISD::FMINC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaabe3cfcecab0e3b2e2ab496a566c8d1c">llvm::X86ISD::FOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa72b53026518573189b8a49ae5f5c2c2d">llvm::X86ISD::FXOR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4c3a10f878938b827a268d6ab66dbb77">llvm::TargetLoweringBase::isCommutativeBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8e6b692f93aee762231d7221e5730598">llvm::X86ISD::PCMPEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac42bb75fe0307f14264032e6db521de2">llvm::X86ISD::PMULDQ</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7f0c379fa7f4b37235504936c56ae486">llvm::X86ISD::PMULUDQ</a>.</p>

</div>
</div>

### isCtlzFast() {#a4252a7b10bf920be7bc1da185d9c43b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isCtlzFast ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if ctlz instruction is fast.</p>

<p>Declaration at line 1188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3451 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a027102ec674270eecc2a1a6ec8588e44">combineOrCmpEqZeroToCtlzSrl</a>.</p>

</div>
</div>

### isDesirableToCombineLogicOpOfSETCC() {#ad952c5828f21002a545e9de9f64cc4aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AndOrSETCCFoldKind X86TargetLowering::isDesirableToCombineLogicOpOfSETCC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * LogicOp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * SETCC0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * SETCC1)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return prefered fold type, Abs if this is a vector, AddAnd if its an integer, None otherwise.</p>

<p>Declaration at line 1156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 59620 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a35c1cf0dd553444732dba8e8b9be0f6b">llvm::ISD::ABS</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac14a71b7c36f34100de107aadccc5578a539cbb800fb9210997c38aa8bb5e88cb">llvm::TargetLoweringBase::ABS</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac14a71b7c36f34100de107aadccc5578ace95e127af7e6b27d9b2168d504ee3e1">llvm::TargetLoweringBase::AddAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac0a534d63ac5c5b87f36acdade953fbe">llvm::SDNode::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9245ed740fe76aaad3e5b0650da21c98">llvm::TargetLoweringBase::isOperationLegal</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac14a71b7c36f34100de107aadccc5578af13d639dc869a95fce88b087dc66856e">llvm::TargetLoweringBase::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac14a71b7c36f34100de107aadccc5578a01086c40411a099b30c4a119c95ef262">llvm::TargetLoweringBase::NotAnd</a>.</p>

</div>
</div>

### IsDesirableToPromoteOp() {#ae344bf38282de26bb4d5783114a65eaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::IsDesirableToPromoteOp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> &amp; PVT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target has native support for the specified value type and it is 'desirable' to use the type.</p>


<p>e.g. On x86 i16 is legal, but undesirable since i16 instruction encodings are longer and some i16 instructions are slow.</p>


<p>Declaration at line 1151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 59642 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c47226f266248f4b8c155b83601b109">llvm::ISD::ATOMIC_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1db943abc1bf78a911daeb7b03d81de8">llvm::ISD::ATOMIC_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a308088c2d65f8f3955f5fb0f6aca7ccc">llvm::ISD::isNormalStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#aafd16108bb2bfb19eed47e23dcbee3dd">llvm::X86::mayFoldLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### isExtractSubvectorCheap() {#ab75bfa0d750449f745ed10dba2f81e31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isExtractSubvectorCheap (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ResVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SrcVT, unsigned Index)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1516 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa93fbbc66d52a51d178af8ac4398ec05">llvm::TargetLoweringBase::isOperationLegalOrCustom</a>.</p>

</div>
</div>

### isExtractVecEltCheap() {#afee5e52fd75b2906a16655fa264ee3d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86TargetLowering::isExtractVecEltCheap (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, unsigned Index)</td>
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

<p>Extract of a scalar FP value from index 0 of a vector is free.</p>

<p>Definition at line 1525 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>.</p>

</div>
</div>

### isFMAFasterThanFMulAndFAdd() {#ab5a3a214752cd4c83a68f99de65ad908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isFMAFasterThanFMulAndFAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1446 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>

</div>
</div>

### isFPImmLegal() {#a8394d225b325663032c0b724ce2e43bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isFPImmLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Imm, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, bool ForCodeSize)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1468 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### isGuaranteedNotToBeUndefOrPoisonForTargetNode() {#ae2cb6bf0817b8dbe415405c7498b8ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isGuaranteedNotToBeUndefOrPoisonForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool PoisonOnly, unsigned Depth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this function can prove that <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> is never poison and, if <span class="doxyComputerOutput">PoisonOnly</span> is false, does not have undef bits.</p>


<p>The DemandedElts argument limits the check to the requested vector elements.</p>


<p>Declaration at line 1318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 44453 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0b31f77b61967dd90fbcc8174ea66e93">getTargetShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8947affefbaa5e1099d7ba6bd401f05a">llvm::SelectionDAG::isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#abb1ad8b21c9956ffb90121e24f8bc116">llvm::TargetLowering::isGuaranteedNotToBeUndefOrPoisonForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a4346f62e0e1ee37b8c7877df168057f5aaa2fad9a8387f8d5f005f3e308ae676f">PoisonOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa182b063ab7dd0842ce968cef5f981e92">llvm::X86ISD::PSHUFD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaddf811d44f58e7d0e16ca3266b8689a3f112d168d45b1ab58a80c2b9f7e6cb4">llvm::SM_SentinelUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaddf811d44f58e7d0e16ca3266b8689ac131901c70cd3380fd61a47415b58740">llvm::SM_SentinelZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aadbf48e1eda461f1db91b138d32c7e8d5">llvm::X86ISD::VPERMILPI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab63fa0a5c1888e275635edaaf3ffa3ed">llvm::X86ISD::VPERMV3</a>.</p>

</div>
</div>

### isInlineAsmTargetBranch() {#a528ccfe220ae477b22431f3328d0b90e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isInlineAsmTargetBranch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; AsmStrs, unsigned OpNo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>On x86, return true if the operand with index OpNo is a CALL or JUMP instruction, which can use either a memory constraint or an address constraint.</p>


<p>-fasm-blocks "__asm call foo" lowers to call void asm sideeffect inteldialect "call ${0:P}", "*m..."</p>


<p>This function is used by a hack to choose the address constraint, lowering to a direct call.</p>


<p>Declaration at line 1631 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 33138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae46058c90a3c703357331a6501b32f1c">llvm::StringRef::equals_insensitive</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad583c842b8bb943986245cd3dca82e46">getInstrStrFromOpNo</a>.</p>

</div>
</div>

### isIntDivCheap() {#ac7a7243ff0d08f8e17239f3fab12a20f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isIntDivCheap (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> Attr)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1611 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 60859 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a61054ea97168f709c1e46345f80c16a3">llvm::AttributeList::hasFnAttr</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### isLegalAddImmediate() {#a092cc6666d98dc58d90d67082beda499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isLegalAddImmediate (int64_t Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified immediate is legal add immediate, that is the target has add instructions which can add a register and the immediate without having to materialize the immediate into a register.</p>

<p>Declaration at line 1407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>.</p>

</div>
</div>

### isLegalAddressingMode() {#ad1a79970217e7be886648d06d5fded3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isLegalAddressingMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode">AddrMode</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned AS, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35011 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a2d775e3fd8ebcd0941d1e12cbfccda3d">llvm::TargetLoweringBase::AddrMode::BaseGV</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a115ffe6d615735fbe8b1bf31877565ba">llvm::TargetLoweringBase::AddrMode::BaseOffs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ae106f6c6362377b3016f0d174227e193">llvm::TargetMachine::getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8868c35de6c36dc0d57e84f256c4ffde">llvm::TargetLoweringBase::AddrMode::HasBaseReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a17fba293567ee7ac6bb0ff0843d9e4">llvm::isGlobalRelativeToPICBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a029305779c4671cfa47263aae5ed18cc">llvm::isGlobalStubReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ac5d9870049dd4eaa5938dd4e920d354a">llvm::X86::isOffsetSuitableForCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aa8ab0804ddb40450da6549e1943817a2">llvm::TargetLowering::isPositionIndependent</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8ea7d02f0e4b0c1d37d6986ec9f7f5c0">llvm::TargetLoweringBase::AddrMode::Scale</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a>.</p>

</div>
</div>

### isLegalICmpImmediate() {#a5b29ba68187b5f5d44c6fc584b658d06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isLegalICmpImmediate (int64_t Imm)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>.</p>

</div>
</div>

### isLegalStoreImmediate() {#a3e4a60b1f1249061764cf8d334c8e162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isLegalStoreImmediate (int64_t Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified immediate is legal for the value input of a store instruction.</p>

<p>Declaration at line 1409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>.</p>

</div>
</div>

### isLoadBitCastBeneficial() {#a8ab3eaadf7f52ab7ca677e6c545e6508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isLoadBitCastBeneficial (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> LoadVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> BitcastVT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; MMO)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the following transform is beneficial: fold (conv (load x)) -&gt; (load (conv*)x) On architectures that don't natively support some vector loads efficiently, casting the load to a smaller vector of larger types and loading is more efficient, however, this can be undone by optimizations in dag combiner.</p>

<p>Declaration at line 1543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a460fe5aea074c37615e0106c2a13a1e4">llvm::TargetLoweringBase::isLoadBitCastBeneficial</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### isMaskAndCmp0FoldingBeneficial() {#af88464d58b1b70362b8ab991b0db2dbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isMaskAndCmp0FoldingBeneficial (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; AndI)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3455 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### isMemoryAccessFast() {#a1a78b1cfe835bfe405897b9b75cf17fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isMemoryAccessFast (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1096 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#aec0a89ba2bd4f839f4509ff10117b85f">isBitAligned</a>.</p>


<p>Referenced by <a href="#acca525d32f859c8c653921b5fff62ed3">allowsMemoryAccess</a> and <a href="#a7fdb4a73925c17adcb4eaeafda02978d">allowsMisalignedMemoryAccesses</a>.</p>

</div>
</div>

### isMultiStoresCheaperThanBitsMerge() {#a1134e24a9f51b06d69b66aaede5eb422}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86TargetLowering::isMultiStoresCheaperThanBitsMerge (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> LTy, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> HTy)</td>
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

<p>Return true if it is cheaper to split the store of a merged int val from a pair of smaller values into multiple stores.</p>

<p>Definition at line 1190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a3cb888a2ce8e95e0d9769687a5e2f7d8">llvm::EVT::isFloatingPoint</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a>.</p>

</div>
</div>

### isNarrowingProfitable() {#a83185148c0d5d8353cc716271c560e66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isNarrowingProfitable (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SrcVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> DestVT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it's profitable to narrow operations of type SrcVT to DestVT.</p>


<p>e.g. on x86, it's profitable to narrow from i32 to i8 but not from i32 to i16.</p>


<p>Declaration at line 1452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isSafeMemOpType() {#a4458afa9d4b40fe7c439f81cd5481366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isSafeMemOpType (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if it's safe to use load / store of the specified type to expand memcpy / memset inline.</p>


<p>This is mostly true for all types except for some special cases. For example, on <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> targets without SSE2 f64 load / store are done with fldl / fstpl which also does type conversion. Note the specified type doesn't have to be legal as the hook is used before type legalization.</p>


<p>Declaration at line 1094 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### isScalarFPTypeInSSEReg() {#ab32d538e8058be86b0efc0d970b35735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isScalarFPTypeInSSEReg (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified scalar FP type is computed in an SSE register, not on the X87 floating point stack.</p>

<p>Declaration at line 1500 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#a168f3532cb1605bbc91fcc079892e357">BuildFILD</a>, <a href="#a7a7237cd5cb35f9159b32a96f4b14541">getRegForInlineAsmConstraint</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel/#a621eb8645a9f80882b80ac3c6d4e0091">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::PreprocessISelDAG</a>.</p>

</div>
</div>

### isShuffleMaskLegal() {#a9fdafe65d9378c70d936af1019040b0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isShuffleMaskLegal (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Targets can use this to indicate that they only support <em>some</em> VECTOR_SHUFFLE operations, those with specific masks.</p>


<p>By default, if a target supports the VECTOR_SHUFFLE node, all mask values are assumed to be legal.</p>


<p>Declaration at line 1475 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mvt/#aea8bc2b59cb3fa833eb7895a3a216abd">llvm::MVT::getScalarType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>.</p>


<p>Referenced by <a href="#abf24a843e4c14485213d45230de71898">isVectorClearMaskLegal</a>.</p>

</div>
</div>

### isSplatValueForTargetNode() {#a34faa94759387be0a4881a7e227f6caf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isSplatValueForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; UndefElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if vector <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> has the same value across all <span class="doxyComputerOutput">DemandedElts</span>, indicating any elements which may be undef in the output <span class="doxyComputerOutput">UndefElts</span>.</p>

<p>Declaration at line 1326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 44528 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aa31fb5c8038b82f00b3a1d19144c0516">llvm::TargetLowering::isSplatValueForTargetNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac3bc043916fd84786c2ac451e0a3cd24">llvm::X86ISD::VBROADCAST</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa78f74c46439b34ecc3b826e4bb5f1fc2">llvm::X86ISD::VBROADCAST_LOAD</a>.</p>

</div>
</div>

### isTargetCanonicalConstantNode() {#ad0914ba5d0ef25eca489b81cbf981517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86TargetLowering::isTargetCanonicalConstantNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
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

<p>Returns true if the given Opc is considered a canonical constant for the target, which should not be transformed back into a BUILD_VECTOR.</p>

<p>Definition at line 1330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">llvm::ISD::INSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a4568c6fee399b92f6971aa10266a89b0">llvm::TargetLowering::isTargetCanonicalConstantNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa78f74c46439b34ecc3b826e4bb5f1fc2">llvm::X86ISD::VBROADCAST_LOAD</a>.</p>

</div>
</div>

### isTruncateFree() {#aabf943e7fc68b0048d5278b5a35da3a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isTruncateFree (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty1, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty2)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it's free to truncate a value of type Ty1 to type Ty2.</p>


<p>e.g. On x86 it's free to truncate a i32 value in register EAX to i16 by referencing its sub-register AX.</p>


<p>Declaration at line 1420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>.</p>

</div>
</div>

### isTruncateFree() {#a6cc2cb7b5433e21565a41f6154b7c816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isTruncateFree (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT1, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT2)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#ad958859a7af278dd5ea2b593c2b25050">llvm::EVT::isScalarInteger</a>.</p>

</div>
</div>

### isTypeDesirableForOp() {#a4217293101179a3839b8afb1fafb2e0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isTypeDesirableForOp (unsigned Opc, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
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


<p>e.g. On x86 i16 is legal, but undesirable since i16 instruction encodings are longer and some i16 instructions are slow.</p>


<p>Declaration at line 1145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 59548 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### isVectorClearMaskLegal() {#abf24a843e4c14485213d45230de71898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isVectorClearMaskLegal (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
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


<p>Targets can use this to indicate if there is a suitable VECTOR_SHUFFLE that can be used to replace a VAND with a constant pool entry.</p>


<p>Declaration at line 1480 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="#a9fdafe65d9378c70d936af1019040b0f">isShuffleMaskLegal</a>.</p>

</div>
</div>

### isVectorLoadExtDesirable() {#aec5602ebffe4f185bb771a7ea328ad31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isVectorLoadExtDesirable (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ExtVal)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### isXAndYEqZeroPreferableToXAndYEqY() {#a6601dcbc51d3043764e700c20db26e9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isXAndYEqZeroPreferableToXAndYEqY (<a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> Cond, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 23166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a>.</p>

</div>
</div>

### isZExtFree() {#acb13111bbf0c82193529692fd4017679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isZExtFree (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty1, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty2)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if any actual instruction that defines a value of type Ty1 implicit zero-extends the value to Ty2 in the result register.</p>


<p>This does not necessarily include registers defined in unknown ways, such as incoming arguments, or copies from unknown virtual registers. Also, if isTruncateFree(Ty2, Ty1) is true, this does not necessarily apply to truncate instructions. e.g. on x86-64, all instructions that define 32-bit values implicit zero-extend the result out to 64 bits.</p>


<p>Declaration at line 1433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>.</p>


<p>Referenced by <a href="#adda85bdff9375435866fa2bebaca4b27">isZExtFree</a>.</p>

</div>
</div>

### isZExtFree() {#afd3f38eb5dc5b83e3a7aee22a0d501b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isZExtFree (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT1, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT2)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### isZExtFree() {#adda85bdff9375435866fa2bebaca4b27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isZExtFree (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT2)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>, <a href="#acb13111bbf0c82193529692fd4017679">isZExtFree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>

</div>
</div>

### LowerAsmOperandForConstraint() {#af8cc1f957026a793e58fec505e47a7c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86TargetLowering::LowerAsmOperandForConstraint (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower the specified operand into the Ops vector.</p>


<p>If it is invalid, don't add anything to Ops. If hasMemory is true it means one of the asm constraint of the inline asm instruction being processed is 'm'.</p>


<p>If it is invalid, don't add anything to Ops.</p>


<p>Declaration at line 1364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 60158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a79adbcc34e24b86ef8a216a34ccf5af8">llvm::TargetLoweringBase::getBooleanContents</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#affa111c5fcedf4f9c7eaf11be9977f32">llvm::TargetLoweringBase::getExtendForContent</a>, <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode/#aac749351927cd1732994a39d40fdd4f2">llvm::GlobalAddressSDNode::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac28c549afb9f9751d45c37dc9a9b9a7d">llvm::SelectionDAG::getTargetBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a05c0ae3eb411a8c53a6ce48b66c0d3f8">llvm::SelectionDAG::getTargetGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac0a534d63ac5c5b87f36acdade953fbe">llvm::SDNode::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a029305779c4671cfa47263aae5ed18cc">llvm::isGlobalStubReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a5b75b94b0d81c2ae458192b4a6544e18">llvm::ConstantInt::isValueValidForType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ad3f2eb78e627fd0d785fd4119d299558">llvm::TargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### LowerAsmOutputForConstraint() {#a1b67b537250936a616694b1bab0816dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerAsmOutputForConstraint (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Flag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a> &amp; Constraint, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 60131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2eab1840bfcd789713b29a40d9d55cb41e3">llvm::X86::COND_INVALID</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo/#acaa17aeb01534f4ef06085783d0cd065">llvm::TargetLowering::AsmOperandInfo::ConstraintCode</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo/#a7cd6f0fbc0aebaac2019af30a06c7b18">llvm::TargetLowering::AsmOperandInfo::ConstraintVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6551350658729b36c93362fcff19abab">llvm::SelectionDAG::getCopyFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a99a8ef36a45a120663b4f16707a5ee42">getSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a437cf7bc875369cbe0ea62f949626f0b">llvm::MVT::isInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5d8593bb34f2d8b9e8b81d36a3a72e54">parseConstraintCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### LowerCustomJumpTableEntry() {#af3e16079a117749c3a3ab03753982e0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * X86TargetLowering::LowerCustomJumpTableEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo">MachineJumpTableInfo</a> * MJTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, unsigned uid, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1068 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aa8ab0804ddb40450da6549e1943817a2">llvm::TargetLowering::isPositionIndependent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a4396d69feb19b053f335f9baa4fb9b62">llvm::MCSymbolRefExpr::VK_GOTOFF</a>.</p>

</div>
</div>

### lowerInterleavedLoad() {#a9157e4aca11eca217c5c6d2c6a2eadbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::lowerInterleavedLoad (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> * &gt; Shuffles, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Indices, unsigned Factor)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower interleaved <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumarklastscratchload-cpp/#a8a3fe89940744b94ffe5dacd6704c2be">load(s)</a> into target specific instructions/intrinsics.</p>

<p>Declaration at line 1644 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 803 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="#a8b0b7687cd51e781f5b3851d9dcc10a6">getMaxSupportedInterleaveFactor</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### lowerInterleavedStore() {#ab5881269962ffb5a6c2d4c5be45efbce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::lowerInterleavedStore (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> * SVI, unsigned Factor)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower interleaved store(s) into target specific instructions/intrinsics.</p>

<p>Declaration at line 1651 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 820 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a8b0b7687cd51e781f5b3851d9dcc10a6">getMaxSupportedInterleaveFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a6eaff12d0d3ead952f2a2a2781df56ac">llvm::ShuffleVectorInst::getShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a59c34209e9206120edf7ce3c5da4f872">llvm::ShuffleVectorInst::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### LowerOperation() {#a3d437e0047c2e5a049151f46d9dd2d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerOperation (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 33198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af798622367e75c5536666dbfec5d5ea3">llvm::ISD::ABDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff129f5ab4fbc8279e7aaacb45f840b1">llvm::ISD::ABDU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a35c1cf0dd553444732dba8e8b9be0f6b">llvm::ISD::ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a591c03cc284124ff624856ce485ebc17">llvm::ISD::ADDROFRETURNADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae221016e72ad6632377ef55f9e0e4f61">llvm::ISD::ADDRSPACECAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af7bfad446dfd85837fe7ff904ebb1aff">llvm::ISD::ADJUST_TRAMPOLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30649569b517a279a32fb3b48cc154e0">llvm::ISD::ATOMIC_CMP_SWAP_WITH_SUCCESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a385d7f9c63f921a2b28e8426e4101de8">llvm::ISD::ATOMIC_FENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf5f612de1a25451c9a0c33d77bf3e74">llvm::ISD::ATOMIC_LOAD_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a905925a49cdc6b4a6017d215820dad30">llvm::ISD::ATOMIC_LOAD_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4112a866197a97a70bdc78ef92c79b4c">llvm::ISD::ATOMIC_LOAD_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3d12dbff6e50803982d0e92768a1479">llvm::ISD::ATOMIC_LOAD_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a428ec1341b34eafa63518914e7f5ddf0">llvm::ISD::ATOMIC_LOAD_XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1db943abc1bf78a911daeb7b03d81de8">llvm::ISD::ATOMIC_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8489c40b1b3f92b0c4fc98d06099c441">llvm::ISD::AVGCEILU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeea401cc0b7fa5aa6f4d3a0612140e1d">llvm::ISD::BITREVERSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5">llvm::ISD::CONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c">llvm::ISD::CTLZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0340c8d57d1dcebc43a00412989583d3">llvm::ISD::CTLZ_ZERO_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a991d07d163bd4d9984cf1ef36e92c214">llvm::ISD::CTPOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6da41a113af0909470baea7486b3386b">llvm::ISD::CTTZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a601e66a26efd05520f7cb26aef3af340">llvm::ISD::CTTZ_ZERO_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa1fec5162852502da5a2832321f9c1012">llvm::X86ISD::CVTPS2PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa71ac22470bf853868fe6b39a25bac72">llvm::ISD::DYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4edf35e2383003ff20057e5a45012a55">llvm::ISD::EH_RETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a122a450e069003dc86859ef47ab6e278">llvm::ISD::EH_SJLJ_LONGJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae5a57fe9fd413df909ab121ca1a813c7">llvm::ISD::EH_SJLJ_SETJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2e0f3a93e85a46b2ebac7330c2a0c581">llvm::ISD::EH_SJLJ_SETUP_DISPATCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad88f843bce966361c7fd2cd022e6528a">llvm::ISD::ExternalSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2b4d07600495a563319d6a3dda8dc44d">llvm::ISD::FABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a74a787311d3ab9a17ee0acde7b6a6b14">llvm::ISD::FCANONICALIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeffc3319657e213a530ce583603f7221">llvm::ISD::FCOPYSIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a130b6a6d409367c8a61dd14dfa39785c">llvm::ISD::FGETSIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3dfd1b187d121c0e214698eef1c20f53">llvm::ISD::FMAXIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add34b1738b7bb2c298f92f1b7b62ce0c">llvm::ISD::FMAXIMUMNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac27a43f98abb2d1ee2f2ce99a0b34b36">llvm::ISD::FMINIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af7691f41e448fefca844f687edabfb69">llvm::ISD::FMINIMUMNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d26c45c040d8f85d577a5f645261d1a">llvm::ISD::FNEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3e12fcc9960ef3bf0ae5876382d4c66f">llvm::ISD::FP16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0bb173b5a879225092abdeaba1394839">llvm::ISD::FP_TO_BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a38f379e4fddf750c36f1323a04d12171">llvm::ISD::FP_TO_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae4a4e2126c6db34e2dfd71b6bd0408ee">llvm::ISD::FP_TO_SINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98661814400e72a77f5ed4e088c06937">llvm::ISD::FP_TO_UINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a228deacdfba1bd2d5a3663b19609f945">llvm::ISD::FRAME_TO_ARGS_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdb38c8daa8c1ab881007062d113cef3">llvm::ISD::FRAMEADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a87b7dd3d6a9b68d1558fc6b4706708b0">llvm::ISD::FROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a822b0d02b601898e2d6db5b39e12cc8a">llvm::ISD::FSHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a874350de5b4f6b8f4db13940e17ed81b">llvm::ISD::FSHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6ba8fc92ee5081d3e533cb5322f74f29">llvm::ISD::FSINCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad">llvm::ISD::FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aee46c58568939eaeaa37ea6001bf432e">llvm::ISD::GC_TRANSITION_END</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71d133366c40437e06936626b32ba6d8">llvm::ISD::GC_TRANSITION_START</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac7e6de3a23c50c3f48e30e3a644a16aa">llvm::ISD::GET_FPENV_MEM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89f3afc3fa907ff83759c6c76d97a973">llvm::ISD::GET_ROUNDING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4534a6db2862a28324932a8ea1cb54d6">llvm::ISD::INIT_TRAMPOLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">llvm::ISD::INSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0c70100db6ddc0b37b56feb242145cf4">llvm::ISD::JumpTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a25eed965b36ce43fc8b9daa2774dfad8">llvm::ISD::LLRINT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1ad42ca57c3c3ab00dd66ca5870e7bb8">LowerABD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af9488f8e3a8bd2dafa658fc48419f3b2">LowerABS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8d3d665855cae4e412e40108809ea91d">LowerADDRSPACECAST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad9601b4bf1ad70c2fe4534ecf69c165f">LowerADDSAT_SUBSAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a285bb9e7e94d9755aadf7680ebf4af97">lowerAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a72ab512faa829e90b3bac50641315497">LowerADDSUBO_CARRY</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a187168567f5f0395fd0a59b85c35342b">LowerADJUST_TRAMPOLINE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a14c1da0d6397508803e61b56652580f6">LowerANY_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a44afdb77dfc5779686a8da6ffda6abab">LowerATOMIC_FENCE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a62712c499928ed783ba6329269bbc8f9">LowerATOMIC_STORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3b7d14ce641064b70c1b921dd97afd3e">lowerAtomicArith</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a66df6e2d29622075c45fb05c03727127">LowerAVG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3ce8ae9aaa34fdd7062856c126e18f43">LowerBITCAST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab2689b832f03d85c8c3f2a096b653f75">LowerBITREVERSE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af9f436f6b3196efa8801aadaaf8dd52e">LowerCMP_SWAP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a25018debfdb73e1591f2fef057c92fc2">LowerCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a3eb735150a3d034d431651b14209c867">LowerCTLZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#ade8fbcac63ba4f738ae2de92a195becc">LowerCTPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6fd620f229a9cde3e60fc77ab234cd1e">LowerCTTZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9238cf9b77cdeb78b65281c229d2dfd0">LowerCVTPS2PH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad1a2f745da12a487f957812160298aa7">LowerEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a36623d79590f271aff0f88734e356708">LowerEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac05773b4901540ea7eaeb572cce9b00d">LowerFABSorFNEG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a785699ec362428cc2e9f5ec9993a8d3f">LowerFCanonicalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abc7ab426f010b3402a1e9e6a9fef1327">LowerFCOPYSIGN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa1203a47f70c03c0125b4333f900452d">LowerFGETSIGN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abe8a849f2fea1988803555cc45d24721">LowerFMINIMUM_FMAXIMUM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5eb575c2fb66cdcd28cdb35faaf88621">LowerFP16_TO_FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1dd78cdbc9a4862c30576152d2412277">LowerFP_TO_FP16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab2731249115c18b6fbd58ad75ce431f9">LowerFROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a51e11fac59331e5e9704295214a2d5ee">LowerFSINCOS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a908002fa0e62607096a6a564be8a4198">LowerFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ebfb235de18f6e17d6d5de0a8b90b55">LowerINSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25a5e94166cf78354826b46e402ebcd9">LowerINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a47413709ef916baf36607da462d93ccc">LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8245c7a15b6042f1346d528db83476a9">LowerMGATHER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaffb1afd23a1f6c79ce9d84b3c380a4b">LowerMINMAX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab8bc9452845ce93765def17a42addaed">LowerMLOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a42f26c84bb612e3bd4acb003a3cdbdc7">LowerMSCATTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8cbf01443deb8406807eaf5afe109f56">LowerMSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab254961e69630f8f3d82f83429dd4be4">LowerMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4b50dba6968ef240c092133600946ef9">LowerMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5d48bc80fa2c6e61a0ad0dfedac1553a">LowerMULO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaf26b08c5135c5ae2bc71189dff29b79">LowerPARITY</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9b284b652f676b448812e5ba2f1b9c70">LowerPREFETCH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1b7e327f795df40244e9d4588012967e">LowerREADCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4871d6290298d9eaae5b5da0160e5a21">LowerRotate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae1e26c281236fd29f5a93e58a4397601">LowerSCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a07bef52d3581440af08be07591f29990">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a63812eb1fe4e44df46b0b789597a8b5f">LowerShiftParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8b19574b3ca4ba61aec3275548e416e4">LowerSIGN_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a05914158f39e230548b1b743eee2e5f6">LowerStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a84269093cb913d8f68ea84f72d75dee1">LowerVACOPY</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab1f71843f178d1cbe0f1bd95af528c46">lowerVECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04b59de220180462277a0d8d7f146b0e">lowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa5a86623773ed13c55fc451727aa234f">LowerXALUO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a37beb02a4ace10bc841524083344c448">LowerZERO_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a05f23e2cd900dc8f1dbf6702ab12423b">llvm::ISD::LRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab4685260a7e506fe51f17d9b600349c8">llvm::ISD::MGATHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a112324db3910fea5895514851c387442">llvm::ISD::MLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab179d7f42562bbb315a6b0589a25f733">llvm::ISD::MSCATTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9add598de9e0a49cbb8fb19adf495051">llvm::ISD::MSTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa2a7c3eccf06b41e4275bbeadb46d22e">llvm::ISD::MULHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8a80d3b085af08f0dce1724207ef99b5">llvm::ISD::MULHU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa47439d20ce0879ea68ca293e018b4f5">llvm::ISD::PARITY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a691a4c9004e9bd04d1c0bebc5df57443">llvm::ISD::PREFETCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac43f9bea13e29622bbf18c861b52144d">llvm::ISD::READCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a23914569caa5dbe0d340c3fbfc277efc">llvm::ISD::RESET_FPENV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2dfacb29792dd59f2cfbe529206265bc">llvm::ISD::RETURNADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715">llvm::ISD::ROTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a863ec6ebb75bf89cfea14da646d77e92">llvm::ISD::SADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af9eda6a77c3228cd36537469a7425133">llvm::ISD::SADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af1b946afff631cee7aa6de570bef7785">llvm::ISD::SADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af695708f70bdd710c8fda5c4570711d7">llvm::ISD::SET_FPENV_MEM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4fe6c878350458de2c3182392f830988">llvm::ISD::SET_ROUNDING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6bb33e400f29724907dc27ced04e9038">llvm::ISD::SETCCCARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3893859b5caa079593b9bf91b96e05fb">llvm::ISD::SIGN_EXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af3b59179b6fcbc89463181015ace8e9b">llvm::ISD::SMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaac895215ecbb3c411c957c8beb39b70">llvm::ISD::SMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa35d0a58fdded3d225d512a60aea0951">llvm::ISD::SMULO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6efe16ea597cfd8eeac26516fc992ee7">llvm::ISD::SSUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a139dc5419039d94496e69dbb264251b5">llvm::ISD::SSUBO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a77984d86d70df1f3229da7a5119652a9">llvm::ISD::SSUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8be8417e323644ecd854ce67c362a850">llvm::ISD::STRICT_FP16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac47e026e409ff39f319cbb3b096863e6">llvm::ISD::STRICT_FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2273d9cd04ba6e4a7c1a4b28ab1aaba">llvm::ISD::STRICT_FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8a54f717e10fab9c9821196fc882cc11">llvm::ISD::STRICT_FP_TO_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed">llvm::ISD::STRICT_FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf955b4b70f63865e022c329d1775579">llvm::ISD::STRICT_FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0466b21bfb4f3596e41380d8e2d1956f">llvm::ISD::STRICT_FSETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c8d07d668872f2176fb34724cd799c4">llvm::ISD::STRICT_FSETCCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab38d2af541b99492acf69c041c98bcb6">llvm::ISD::STRICT_SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a56735332b7dc26b4e164035831fb40ab">llvm::ISD::STRICT_UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1ddf36330110b4abea43fe390bea9ef9">llvm::ISD::UADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0f1e3ed26108fec69eb97209c0e39bf">llvm::ISD::UADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5e433873c201ad85c30e42da1ae05977">llvm::ISD::UADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af675e759c0ffff8d48ea14a60fe3517b">llvm::ISD::UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a17126302da6199930e55e841ca1b082d">llvm::ISD::UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7800622851751b8ae318b41f4096830e">llvm::ISD::UMULO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4ffc75d65231b55461c0ba4f36a3e500">llvm::ISD::USUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac81ebcd59d629d8680e50ffba9855255">llvm::ISD::USUBO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89166b38f12c0bd3e8a61d8f1a5a8bc8">llvm::ISD::USUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae77d03846b31c41c4860bcd96d780a78">llvm::ISD::VAARG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a804c1960ac64628cdd1f74d7de885284">llvm::ISD::VACOPY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adfe32beaa596a1512b17e66b46e773ed">llvm::ISD::VASTART</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adb06c311948bd9fb944ab3c433138181">llvm::ISD::VECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0b7d2c769fd0fbaab3c4a2fc8e7ea0c">llvm::ISD::VSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adf7f4fc30c272a1987e075d7470df84c">llvm::ISD::ZERO_EXTEND_VECTOR_INREG</a>.</p>

</div>
</div>

### LowerXConstraint() {#a2aa47f16031986718a30310f73c8c90c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * X86TargetLowering::LowerXConstraint (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ConstraintVT)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 60119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a3cb888a2ce8e95e0d9769687a5e2f7d8">llvm::EVT::isFloatingPoint</a> and <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aeca75f6b346035626e8849863671e02d">llvm::TargetLowering::LowerXConstraint</a>.</p>

</div>
</div>

### markLibCallAttributes() {#aa7fcaa7855f4688864e1315a38ab3694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86TargetLowering::markLibCallAttributes (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, unsigned CC, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae4ac6bc14db22dbd7b94a3b1bd276796">ArgListTy</a> &amp; Args)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1060 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#aa48b3b7e554b44f4e513d5dd8d9f9343">llvm::DataLayout::getTypeAllocSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caa88ccf4313b5bc700dec76fd9bc5d40e">llvm::CallingConv::X86_StdCall</a>.</p>

</div>
</div>

### mergeStoresAfterLegalization() {#ad6940a3eec597c799eeee15cb0f7e808}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86TargetLowering::mergeStoresAfterLegalization (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> MemVT)</td>
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

<p>Do not merge vector stores after legalization because that may conflict with x86-specific store splitting optimizations.</p>

<p>Definition at line 1177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### needsFixedCatchObjects() {#afb9746b385314bc07403f471b1931a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::needsFixedCatchObjects ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1560 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 28001 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### PerformDAGCombine() {#a0a91c61d0657477fe6583b566dca7fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::PerformDAGCombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 59337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa72deaddfd41882e7ddf09409d9528bc8">llvm::X86ISD::ADC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aacf42ecbf82f3dcbf52c109ee0e3f5838">llvm::X86ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae1624a99d3ee1309539c25a7afe2a852">llvm::X86ISD::ANDNP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa275bf149ab5df1067cfb721936ecbc">llvm::ISD::ANY_EXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a55a4b1d94ca6176bcb5449196d67e798">llvm::ISD::AVGCEILS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8489c40b1b3f92b0c4fc98d06099c441">llvm::ISD::AVGCEILU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110acc5444f2e2933b551e3afbdd93a9bfc8">llvm::ISD::AVGFLOORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5096628a43b16ff34ace64193ded1c93">llvm::ISD::AVGFLOORU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7ead8df5cf10d5f87e8c19b6f7d34ad6">llvm::X86ISD::BEXTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa0e30dfae5bfdf5db17847036581a181f">llvm::X86ISD::BEXTRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeea401cc0b7fa5aa6f4d3a0612140e1d">llvm::ISD::BITREVERSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa134343dc9302925cf314b9b891880380">llvm::X86ISD::BLENDI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa249e11d47119ca5c2666008857b3b534">llvm::X86ISD::BLENDV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa788e2bf6afec57a73a4118be1cc7af3e">llvm::X86ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa081ba89905b8c040bee9e6944233a6e1">llvm::X86ISD::BT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8a8c8f74a281b988a0641dd7f909e20a">llvm::X86ISD::CLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf413bba9e77d68afdc1afba084851728">llvm::X86ISD::CMOV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa23260aedef0a54d543d227e57955c652">llvm::X86ISD::CMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2ef9bba3be5001d1d80c474dd335dff7">combineADC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4585b76cee25b89a8706715217a1c743">combineAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0285b9eb9c4a75abb42c7cf0ef0154f1">combineAndnp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af59e4da255e65a90b6c4710be399b9e6">combineAVG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0e0d5fc4a01d9f412064a5448052330">combineBEXTR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acb27133587f777e5b89572d1c62aeac9">combineBITREVERSE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afd512b724e2c19c51591ff52531f8659">combineBrCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba1b64f17c84bc615a735f48746a0740">combineBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afab7e380356e4b22d23f87fa2f45daf9">combineBT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0fb4a30e359345f1f6c967488cd37ab">combineCMov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba289468402d03624610fd1f5fb042d0">combineCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae2e4d6043b5ce023daf9d1d905eb2110">combineCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a69c29dade9c2c83e9928f92e0e6452f0">combineCVTP2I_CVTTP2I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a24cdc31f225e6b17b30c139085b064">combineCVTPH2PS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acfa813720f554bb68a6e8c5fdb870f4e">combineEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a767fefc1593899bc23f0b03007b0bd76">combineExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae7dca9dde4468bf201a9020ffb66e8b7">combineFaddFsub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae1ff7bc42bf5767e31a54339e89ce713">combineFAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6fea2dc458fb3a17821239b8383d26ad">combineFAndn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8dae5a29dc37de048a59e5bab5e30af2">combineFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0f13d1cf96cb32fba6d7ed4bd50ba5f">combineFMADDSUB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81efb38c390b38633dbdb3e877a15a84">combineFMinFMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba1e500fbed9b5849bfd76724ccf3825">combineFMinNumFMaxNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a63a699ff4d2df76812431793394bf85a">combineFMulcFCMulc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7a388b8e71542c8223c73a0d99691c71">combineFneg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7e81e46aed86f26e5183c666e5dd1b06">combineFOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1d28003b370fb2c0860ad25f3ef57c5f">combineFP16_TO_FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2b9e3b2b4b0c1d77472815e6d770a4fb">combineFP_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4106aa1194d1a3ddfe03bbbc600913cf">combineFP_ROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaa9fb1f6b90b41c70933803cefa8661a">combineFP_TO_xINT_SAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a250b1e0899d6d01c60cb7af31cd2a2fd">combineGatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ace3516d005e59a05c7b3ff975d063f23">combineINSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ed3d44a545e6f543e76cf58245d1f19">combineINTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac13cf93d084e804ad88b2b1dbef0c618">combineINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a84473a3a9dca82077491c2b25bc82837">combineINTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a886d3292e22e113b2f04c1c35811bd0c">combineKSHIFT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab723e84f5e5bacce2d3e9a9bacf2c707">combineLRINT_LLRINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a6a2af7640ee8f9e66287e024d0f6b8">combineMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a44f727169247a0359f485216a83265ac">combineMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4d6ae8095a6353874359d5f5e886410c">combineMOVDQ2Q</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab6a2c45af55afc1bf183cbafc577fd03">combineMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adc36484c228b0ce9652f549d04ae4e6e">combineMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad27c58fe609558af3d02f6eb59c0d075">combinePDEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a92cb7f91737deedc3c70fb0ec0b70807">combinePMULDQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa13d4cd47426dbe430d65df73fbab44b">combineSBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2d9fefea85a815cc1227bbd3eee1fab3">combineSCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad7c52d56e60df127f4f9a429a5455590">combineSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7324b1333eec1b04ee358d58c42834ef">combineShiftLeft</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a925ab60e01665e8956b384fb79d7491c">combineShiftRightArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0b92776e41d73c3b5d4f1c5712f212c7">combineShiftRightLogical</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae9b4450314b8e4acb9f937389b349fce">combineShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0cccf679aa7f34055f858474bf8bdcdf">combineSignExtendInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0a830cdb7a7691a1d390be839ff5859f">combineSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a619d32c3e94bf8ee0348f9611590dd90">combineTESTP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae1e707b863a71852badbab7870597d8f">combineTruncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e17548b90a1c18c6199a8f99c544dfc">combineUIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aca03795fe4ea383d28dcf4433f994485">combineVectorCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae65b165a9908b7b67d1bb6d3b93e8fd4">combineVectorHADDSUB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a611e5eca9f470030689ec3f7d71c8e20">combineVectorInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a66295c004fc51403028ea1933b66642a">combineVectorShiftVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9ac1db32c7172ebb71d45a6ece209b53">combineVEXTRACT_STORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5c6a560bbaa7931f6375fd838fcfbaa8">combineVPMADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a45f59ac6b0a55fb1b92f4b3bfd5ce327">combineVTRUNC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abb2988152a6f0b53e8da73bd75915365">combineX86AddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6038cc86e3b86730ea40b4ee63200f40">combineX86CloadCstore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae6535f37686895d8ab294ce06ffe2f15">combineX86GatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0185d63d243a248f5bc69dfc943c88a">combineX86INT_TO_FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af29aa650f73d0ffdd74d33e6d4fef173">combineX86SetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a321df2422ee45cfd96e738928fb178f7">combineXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a108b26123f976ad2ab078287e4be83ef">combineZext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5">llvm::ISD::CONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa99e2bb0ac23ed780f3929d5024cbc088">llvm::X86ISD::CSTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa3d9c4511648f4aeb6cdc39851c6b4759">llvm::X86ISD::CVTP2SI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa5af26ba107d346037ecbd751de03de5d">llvm::X86ISD::CVTP2UI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa94c00be07b5a7475ca1ae4b1e1676fff">llvm::X86ISD::CVTPH2PS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf64444ca786d0cddde2bc8628f324e3e">llvm::X86ISD::CVTSI2P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa873eda45cff31b9f5fe7af33ed2ec407">llvm::X86ISD::CVTTP2SI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac6c8013c7f060d7023eb23cb32fc14c8">llvm::X86ISD::CVTTP2UI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7821643340a91702a2540ac9a3e6ab53">llvm::X86ISD::CVTUI2P</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#acf37bd7e831bdb2a5c9da8d63f843101">llvm::TargetLowering::DAGCombinerInfo::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaa39d334524059c9dfadbdc28394139b2">llvm::X86ISD::EXTRQI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaed927d0ca1203766de671e7437d658b2">llvm::X86ISD::FAND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa97670c93c4c4e70151c63e534993e04a">llvm::X86ISD::FANDN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa3a702f9706acfd0711a2ef618e764eb9">llvm::X86ISD::FHADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaab2f2aa57f37dc2b9c616ce720e6b8ea">llvm::X86ISD::FHSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae5c55557d6753435f3b5b6d9678dfacc">llvm::X86ISD::FMADD_RND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa58f003a627b6506ad2893c67204325e0">llvm::X86ISD::FMADDSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa2877f0d6e51388d3a93a7b407289ae70">llvm::X86ISD::FMADDSUB_RND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa080313447e98432d4b62801bf2ad761f">llvm::X86ISD::FMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a632dd4bb044d5cd11f671d176ef495f2">llvm::ISD::FMAXNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aabad10e5691f05a78824d6bad0300e529">llvm::X86ISD::FMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9f59cc264907eb86e29564d5f6a5b213">llvm::ISD::FMINNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa9d8ad87414cdc8a0416b4c94957c1775">llvm::X86ISD::FMSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa865d34b939542df305710438eb9a8d2f">llvm::X86ISD::FMSUB_RND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aabeccad22b28fc7542e683776e90454d6">llvm::X86ISD::FMSUBADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa255d13dedbd0510f453bd5927ed80c31">llvm::X86ISD::FMSUBADD_RND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d26c45c040d8f85d577a5f645261d1a">llvm::ISD::FNEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa367039352ad0788f23a2ce9bcd493f2a">llvm::X86ISD::FNMADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa60f697da41de26a8822eeea8b508404c">llvm::X86ISD::FNMADD_RND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa5366e83be28759f315637517f6d3f369">llvm::X86ISD::FNMSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa6adc5233cdab66da1ea6f13370a00570">llvm::X86ISD::FNMSUB_RND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaabe3cfcecab0e3b2e2ab496a566c8d1c">llvm::X86ISD::FOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3e12fcc9960ef3bf0ae5876382d4c66f">llvm::ISD::FP16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae4a4e2126c6db34e2dfd71b6bd0408ee">llvm::ISD::FP_TO_SINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98661814400e72a77f5ed4e088c06937">llvm::ISD::FP_TO_UINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad">llvm::ISD::FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa72b53026518573189b8a49ae5f5c2c2d">llvm::X86ISD::FXOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa0f4ce46b34ac79f389d475fa6745463e">llvm::X86ISD::HADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf02f5b8c1cc25ab0a8e6cd8e5364332f">llvm::X86ISD::HSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">llvm::ISD::INSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa87f757077dbefa56b1172c1d7c05da53">llvm::X86ISD::INSERTPS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aace7867675de7ee0798a8fec222fe3a7b">llvm::X86ISD::INSERTQI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa00eeeadc9b5bc4170585af2c864b0080">llvm::X86ISD::KSHIFTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa990193ae17623553503589ce732d6d9d">llvm::X86ISD::KSHIFTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a25eed965b36ce43fc8b9daa2774dfad8">llvm::ISD::LLRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a05f23e2cd900dc8f1dbf6702ab12423b">llvm::ISD::LRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab4685260a7e506fe51f17d9b600349c8">llvm::ISD::MGATHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab87f23ed71e4bfc2234328ede40dccd2">llvm::X86ISD::MGATHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a112324db3910fea5895514851c387442">llvm::ISD::MLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa6ce5ecc4640f78a2ecbe9acb4e3908de">llvm::X86ISD::MOVDDUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aadd5701bb43afc4c3b3c13bf989a03cd1">llvm::X86ISD::MOVDQ2Q</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa607fe97a2d1c7d13eec1b620df6ab05a">llvm::X86ISD::MOVHLPS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa1c741c364406fb0b9958fdbba2c7be66">llvm::X86ISD::MOVLHPS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa5b943cbe99c34600de83e0c7c0046e18">llvm::X86ISD::MOVMSK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac1ce5c2b00e728bf0dd6b84f67f418ea">llvm::X86ISD::MOVSD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa341f5831cc328c89d5082a91b9c6b1e5">llvm::X86ISD::MOVSH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaccebcd9a853dde6b119f0ce7ba968c50">llvm::X86ISD::MOVSHDUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aabedb442ee692bfea01853044734e5ae1">llvm::X86ISD::MOVSLDUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf6eab04fa10f5f7e89800dacfbe2dd2c">llvm::X86ISD::MOVSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab179d7f42562bbb315a6b0589a25f733">llvm::ISD::MSCATTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac94a1f22824051f250590a7fa31e442c">llvm::X86ISD::MSCATTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9add598de9e0a49cbb8fb19adf495051">llvm::ISD::MSTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa0e447f5393ad6797e4af00c9401ca6d3">llvm::X86ISD::PACKSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae3abaac16c2c7818508b6e93d170c6b3">llvm::X86ISD::PACKUS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aadbc8832d51cd514c75c2be6b65f0ac82">llvm::X86ISD::PALIGNR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8e6b692f93aee762231d7221e5730598">llvm::X86ISD::PCMPEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf1366c70ee0fa95a076fe683d900e9f9">llvm::X86ISD::PCMPGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa492e5211769c80814cb779b4ba995f23">llvm::X86ISD::PDEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa71fe63f40efcc073f1a5dd6df6efc550">llvm::X86ISD::PEXTRB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8c57aafe37f470b4b146ea8307983228">llvm::X86ISD::PEXTRW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7d9a2bb887ffdd3c85b7eb7215b891db">llvm::X86ISD::PINSRB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac851454bb8c0c576e53b3d993d9c2acf">llvm::X86ISD::PINSRW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac42bb75fe0307f14264032e6db521de2">llvm::X86ISD::PMULDQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7f0c379fa7f4b37235504936c56ae486">llvm::X86ISD::PMULUDQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8a421b1832302b5097a94b81ed579170">llvm::X86ISD::PSHUFB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa182b063ab7dd0842ce968cef5f981e92">llvm::X86ISD::PSHUFD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aafce56cb4ce3db03407437c4ae07d4103">llvm::X86ISD::PSHUFHW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa6c444c7b1be0ea32c7e2c92fbc40388a">llvm::X86ISD::PSHUFLW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa5d99076d052295315dc1e2dd067d2ad7">llvm::X86ISD::SBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa45f2ab1ba8d655b3fde883df17385b54">llvm::X86ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa79877458fe9ec4fc94c68f40e2b54fe0">llvm::X86ISD::SHUF128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa24d6477bb4120ec6b6517ca5e272da9c">llvm::X86ISD::SHUFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3893859b5caa079593b9bf91b96e05fb">llvm::ISD::SIGN_EXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa711d4a7af7fc515982a14698747aa12f">llvm::X86ISD::STRICT_CVTPH2PS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa64a6fc099c65248a3deba44a57f1d99f">llvm::X86ISD::STRICT_CVTTP2SI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa40f22ea742439c6dddbfe08b02d48331">llvm::X86ISD::STRICT_CVTTP2UI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a26ff7f7547f66e1a4f6d5e7efe4b2f59">llvm::ISD::STRICT_FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa74732dc3358e5cf49d56f725cc9b1946">llvm::X86ISD::STRICT_FMSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8d273a921f347c6711b85b0da9bbae43">llvm::X86ISD::STRICT_FNMADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf58da512c0b7a4f83134b838525d4340">llvm::X86ISD::STRICT_FNMSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac47e026e409ff39f319cbb3b096863e6">llvm::ISD::STRICT_FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2273d9cd04ba6e4a7c1a4b28ab1aaba">llvm::ISD::STRICT_FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab38d2af541b99492acf69c041c98bcb6">llvm::ISD::STRICT_SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a56735332b7dc26b4e164035831fb40ab">llvm::ISD::STRICT_UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa4affb47abdfdd54079d5a2f8c1d3e628">llvm::X86ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa17d58dbb94911cf1630e9c523cfe1911">llvm::X86ISD::SUBV_BROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa71996007c100b1c370ffc2444bc680a3">llvm::X86ISD::TESTP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa03a9611e6b354e10a8c3809f49b61eac">llvm::X86ISD::UNPCKH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa000697f31e57d54cd3ae43a2568c36ca">llvm::X86ISD::UNPCKL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aadc975c428af9c770fddc2a81ddbce015">llvm::X86ISD::VALIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac3bc043916fd84786c2ac451e0a3cd24">llvm::X86ISD::VBROADCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa78f74c46439b34ecc3b826e4bb5f1fc2">llvm::X86ISD::VBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaeb84460d683f07195940fd88ff366cf2">llvm::X86ISD::VEXTRACT_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaa0b3bd02ac22b665f1abc59f4966d465">llvm::X86ISD::VFCMULC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa5f29e5c0f677a84a777ab70e00bcb637">llvm::X86ISD::VFMULC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aad57ffc99b9cbbf690e9ac199fc06573d">llvm::X86ISD::VPERM2X128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8bc7868b5b5c49adff7e1b701e2f6daf">llvm::X86ISD::VPERMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaa359935c9a800c36fd9429fa8691c98f">llvm::X86ISD::VPERMIL2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aadbf48e1eda461f1db91b138d32c7e8d5">llvm::X86ISD::VPERMILPI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac98989ae74d479c77e8ac37cf95f3f22">llvm::X86ISD::VPERMILPV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab250ea084b009cb311b1617f5f527c35">llvm::X86ISD::VPERMV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab63fa0a5c1888e275635edaaf3ffa3ed">llvm::X86ISD::VPERMV3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab02310456415907ec1be4ceae53d48a9">llvm::X86ISD::VPMADDUBSW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa90d5ada6e2cf83b82e077c35702f2fc3">llvm::X86ISD::VPMADDWD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa223d75974bc37f644ce46f5a8684ab9e">llvm::X86ISD::VPPERM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0b7d2c769fd0fbaab3c4a2fc8e7ea0c">llvm::ISD::VSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa4c0d35627a076e5424b6de3804613ec6">llvm::X86ISD::VSHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7e968cfe56e1cef0e04fc1537d5a5219">llvm::X86ISD::VSHLDQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf5db7ecddd15a88ac103ef566d0b2180">llvm::X86ISD::VSHLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa751ccb36d27604bba1151ef84cd98510">llvm::X86ISD::VSRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa53a1bf88056b37006ab9ba3b83f1f6ae">llvm::X86ISD::VSRAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa0f740b2d7ea674677c7e8073453f8814">llvm::X86ISD::VSRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa671bbc2a9353cf20bbfb8af47aa237ab">llvm::X86ISD::VSRLDQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa88145107ca3ab31b2e96b5e99bf5b517">llvm::X86ISD::VSRLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aabb0879a5b12d023b74697191612bddaa">llvm::X86ISD::VTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa1356801ab44d90ec9c7643ac8ff0770c">llvm::X86ISD::VZEXT_MOVL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adf7f4fc30c272a1987e075d7470df84c">llvm::ISD::ZERO_EXTEND_VECTOR_INREG</a>.</p>

</div>
</div>

### preferABDSToABSWithNSW() {#a0cc0d655a91ab6eed7a5614e9482b2a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::preferABDSToABSWithNSW (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 59538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### preferedOpcodeForCmpEqPiecesOfOperand() {#a623fca6d1e6801438897a6335f1e4fb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86TargetLowering::preferedOpcodeForCmpEqPiecesOfOperand (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, unsigned ShiftOpc, bool MayTransformRotate, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; ShiftOrRotateAmt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt; &amp; AndMask)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3520 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a>.</p>

</div>
</div>

### preferredShiftLegalizationStrategy() {#a3bcf75579cf117a1b83a27dbe4d775d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::ShiftLegalizationStrategy X86TargetLowering::preferredShiftLegalizationStrategy (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned ExpansionFactor)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3643 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a548cfb9440f36ba67fc5566b8e967fc6">llvm::Function::hasMinSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1cfe6f1187d7ab1a0ada9cc119c1b2b4a9774fd1a96085b8680d017dd42652bc1">llvm::TargetLoweringBase::LowerToLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa88eb4ddf2a7c4d5d5482c9fc0b9090a">llvm::TargetLoweringBase::preferredShiftLegalizationStrategy</a>.</p>

</div>
</div>

### preferScalarizeSplat() {#a79733c103f8a91ce6006567de49a6f40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::preferScalarizeSplat (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3605 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### preferSextInRegOfTruncate() {#a099d3d496bc5d6948101f22543d154b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::preferSextInRegOfTruncate (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> TruncVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ExtVT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 59543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### reduceSelectOfFPConstantLoads() {#a90cebf16a00cfcbf593595502bd34be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::reduceSelectOfFPConstantLoads (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> CmpOpVT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it is profitable to convert a select of FP constants into a constant pool load whose address depends on the select condition.</p>


<p>The parameter may be used to differentiate a select with FP compare from integer compare.</p>


<p>Declaration at line 1507 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#a3cb888a2ce8e95e0d9769687a5e2f7d8">llvm::EVT::isFloatingPoint</a>.</p>

</div>
</div>

### ReplaceNodeResults() {#af77fd362607d101a7080481254ee2fe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86TargetLowering::ReplaceNodeResults (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace the results of node with an illegal result type with new values built out of custom code.</p>


<p>Replace a node with an illegal result type with a new node built out of custom code.</p>


<p>Declaration at line 1128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 33362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae221016e72ad6632377ef55f9e0e4f61">llvm::ISD::ADDRSPACECAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aee4f13218bdbb5c5697f7e786618ecb2">llvm::ISD::AssertSext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af23301e60475124fd80a2cb51f6ba863">llvm::ISD::AssertZext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30649569b517a279a32fb3b48cc154e0">llvm::ISD::ATOMIC_CMP_SWAP_WITH_SUCCESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c47226f266248f4b8c155b83601b109">llvm::ISD::ATOMIC_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf5f612de1a25451c9a0c33d77bf3e74">llvm::ISD::ATOMIC_LOAD_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a905925a49cdc6b4a6017d215820dad30">llvm::ISD::ATOMIC_LOAD_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1cf8547d612d954d34aab1d4f78e7fa1">llvm::ISD::ATOMIC_LOAD_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7049708cb0e0703a467b95a506293aec">llvm::ISD::ATOMIC_LOAD_MIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a13a3e6402abf972278c6a7d5ee509f9d">llvm::ISD::ATOMIC_LOAD_NAND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4112a866197a97a70bdc78ef92c79b4c">llvm::ISD::ATOMIC_LOAD_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3d12dbff6e50803982d0e92768a1479">llvm::ISD::ATOMIC_LOAD_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ca44a643714809ef384e7494604db14">llvm::ISD::ATOMIC_LOAD_UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1ff6f20a9255f7a333f4c9d25393674c">llvm::ISD::ATOMIC_LOAD_UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a428ec1341b34eafa63518914e7f5ddf0">llvm::ISD::ATOMIC_LOAD_XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad728a4b56d49f39375881511d8d3118d">llvm::ISD::ATOMIC_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeea401cc0b7fa5aa6f4d3a0612140e1d">llvm::ISD::BITREVERSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a41bd84b853e2c03fb1af1f4ca9ebdcaf">llvm::ISD::BUILD_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ad9d00ad929ec93255787f7f80c4659d9">llvm::EVT::changeVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a0351571482fea42a3b326147fb2ce9e2">llvm::EVT::changeVectorElementTypeToInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5">llvm::ISD::CONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2ea80da60ed5c7b20653afe0b4b21a91ec1">llvm::X86::COND_E</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a7f47812e8e75b0616a97d7004e5fb909">llvm::KnownBits::countMinLeadingZeros</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a1eeff70353694cb360b2893553c18e7d">llvm::KnownBits::countMinTrailingZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae83b3d8e9a944b5d818e80524a5003e2">llvm::SelectionDAG::CreateStackTemporary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a991d07d163bd4d9984cf1ef36e92c214">llvm::ISD::CTPOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa94c00be07b5a7475ca1ae4b1e1676fff">llvm::X86ISD::CVTPH2PS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa1fec5162852502da5a2832321f9c1012">llvm::X86ISD::CVTPS2PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf64444ca786d0cddde2bc8628f324e3e">llvm::X86ISD::CVTSI2P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa873eda45cff31b9f5fe7af33ed2ec407">llvm::X86ISD::CVTTP2SI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac6c8013c7f060d7023eb23cb32fc14c8">llvm::X86ISD::CVTTP2UI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7821643340a91702a2540ac9a3e6ab53">llvm::X86ISD::CVTUI2P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afac0f876f49fae503633b0dac2a3c812">expandFP_TO_UINT_SSE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a53402f6e918f527e92ecdc700d88c472">expandIntrinsicWChainHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aadc5e8eb45f3fff639c5f0edefe64f641">llvm::X86ISD::FILD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab76ad9f323bc617cfce12a9df044441f">llvm::X86ISD::FIST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa080313447e98432d4b62801bf2ad761f">llvm::X86ISD::FMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaa24b80a5be93b9ddfa62446ced71b68e">llvm::X86ISD::FMAXC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aabad10e5691f05a78824d6bad0300e529">llvm::X86ISD::FMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aafb454d19747fe081325da96a69373f82">llvm::X86ISD::FMINC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae4a4e2126c6db34e2dfd71b6bd0408ee">llvm::ISD::FP_TO_SINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaa254fe3775f6769e9b0a07402db7e153">llvm::X86ISD::FP_TO_SINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98661814400e72a77f5ed4e088c06937">llvm::ISD::FP_TO_UINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa037ef8dd52f75e9f1f9a9706ba4d8f42">llvm::X86ISD::FP_TO_UINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad">llvm::ISD::FSUB</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a64f6469ab95c4eec77e4ccf303619a81">llvm::SelectionDAG::getBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5d154312bef0ed1a6bacfcb52b7cf8eb">llvm::SelectionDAG::getBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a354aae224911d4dab66e34bfa10cf5d6">llvm::SelectionDAG::getConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6551350658729b36c93362fcff19abab">llvm::SelectionDAG::getCopyFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6d7162a570369a85f2a5238452e196e3">getEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a5023bb0687db0b35d3b2d19327217ce5">llvm::SDNode::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6cc63109335eefe2c5727d1e12fc820">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae020054e3ff6b34b048afacab677d69b">getReadTimeStampCounter</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a65bbaa0a9f04a6e217da15b3e8402c14">llvm::SelectionDAG::getSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a99a8ef36a45a120663b4f16707a5ee42">getSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2c237b0f007548cb6bc021d00ffee87f">llvm::SelectionDAG::getSetCC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1a45c74ebe73ebaf0bd8463164e0b764">llvm::SelectionDAG::getShiftAmountConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a576060235339ed4cc1615a55ed869bf0">llvm::SelectionDAG::GetSplitDestVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad859786d7e54bdc5c568ac20c69816e0">llvm::TargetLoweringBase::getTypeAction</a>, <a href="#af23e95d85be78026c607fa689dda4cd1">getTypeToTransformTo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b0e59823444a55c295af279611a9d24">llvm::SelectionDAG::getUNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac597f2b1601a3acbac07347251e588f8">llvm::SelectionDAG::getVectorIdxConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa7e233051b9ed8ebc0191f42698cb14">llvm::SelectionDAG::getVectorShuffle</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a210ba6b43ba451b698857dd9de71bd15">llvm::EVT::getVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad0c6f059b29535f2c790d1c4f92b7a93">llvm::SelectionDAG::getZExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6db1f207286bd8bc6a978593a55955e9">llvm::EVT::is128BitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a0c1ae89f2c2765a979f999ecdc11304c">llvm::MVT::is128BitVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#aafb64237a88493be2c913b0a51630a0f">llvm::ISD::isConstantSplatVector</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a437cf7bc875369cbe0ea62f949626f0b">llvm::MVT::isInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a15623094a1ed0cd7163dc786e44c87c9">llvm::ISD::isNON_EXTLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a762f04a671b75c7b2465da246456e183">isSoftF16</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaeb1887e4cd15e006f28a5f75a691a620">llvm::X86ISD::LCMPXCHG16_DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa4d2a298fcfba10ab50983efa354ebcb6">llvm::X86ISD::LCMPXCHG8_DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a25eed965b36ce43fc8b9daa2774dfad8">llvm::ISD::LLRINT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8d3d665855cae4e412e40108809ea91d">LowerADDRSPACECAST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab2689b832f03d85c8c3f2a096b653f75">LowerBITREVERSE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9238cf9b77cdeb78b65281c229d2dfd0">LowerCVTPS2PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a05f23e2cd900dc8f1dbf6702ab12423b">llvm::ISD::LRINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac76473b9005e8953bfde5975fc7d2eca">matchTruncateWithPACK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab4685260a7e506fe51f17d9b600349c8">llvm::ISD::MGATHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab87f23ed71e4bfc2234328ede40dccd2">llvm::X86ISD::MGATHER</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa126e28f14818b0b293da6aef89e11cbe">llvm::X86ISD::MOVQ2DQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac43f9bea13e29622bbf18c861b52144d">llvm::ISD::READCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a5ad12b466e3a5900d0c307b301465d25">llvm::ISD::SETGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a6f05a09edb671910f85f8665981cbde9">llvm::ISD::SETLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaddf811d44f58e7d0e16ca3266b8689a3f112d168d45b1ab58a80c2b9f7e6cb4">llvm::SM_SentinelUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa35d0a58fdded3d225d512a60aea0951">llvm::ISD::SMULO</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af587fdddecfd87186f09f4b1e9b4bc0a">llvm::SelectionDAG::SplitScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8695950995820e5f6c0407c68f91f44f">llvm::SelectionDAG::SplitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a483aff639a45188ff0f10ae1ae79da16">llvm::SelectionDAG::SplitVectorOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa711d4a7af7fc515982a14698747aa12f">llvm::X86ISD::STRICT_CVTPH2PS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aafa37e128cf1dbc7b4b4825400f999e83">llvm::X86ISD::STRICT_CVTPS2PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa73a98d37d002eedda0f99b15e04462a3">llvm::X86ISD::STRICT_CVTSI2P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa64a6fc099c65248a3deba44a57f1d99f">llvm::X86ISD::STRICT_CVTTP2SI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa40f22ea742439c6dddbfe08b02d48331">llvm::X86ISD::STRICT_CVTTP2UI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa6b06c0682b59b924440540643e5c3262">llvm::X86ISD::STRICT_CVTUI2P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad11fa7fd2a91d210ecbdf09d56cd9f42">llvm::ISD::STRICT_FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa2f49fc0a41551736df3850240384a0ab">llvm::X86ISD::STRICT_FMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7cdfcd3101cf1f5168d138368cf6f636">llvm::X86ISD::STRICT_FMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac47e026e409ff39f319cbb3b096863e6">llvm::ISD::STRICT_FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2273d9cd04ba6e4a7c1a4b28ab1aaba">llvm::ISD::STRICT_FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed">llvm::ISD::STRICT_FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf955b4b70f63865e022c329d1775579">llvm::ISD::STRICT_FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad6192a54cb1dfeca8173749cc735269a">llvm::ISD::STRICT_FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab38d2af541b99492acf69c041c98bcb6">llvm::ISD::STRICT_SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a56735332b7dc26b4e164035831fb40ab">llvm::ISD::STRICT_UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab12f350653f681354125c5f9a97c6bab">llvm::X86ISD::STRICT_VFPROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa038574a2252340dd1eb6885856717ce">truncateVectorWithPACK</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681a26f35604723482a1aee6514940c2987d">llvm::TargetLoweringBase::TypePromoteInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681a40cd81ebfaf97cef327ad65d37b816da">llvm::TargetLoweringBase::TypeSplitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681a5290057031a9bc71850f61e757cb940e">llvm::TargetLoweringBase::TypeWidenVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7800622851751b8ae318b41f4096830e">llvm::ISD::UMULO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28">llvm::ISD::UREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa931754702331756731a26916aebb794c">llvm::X86ISD::VFPROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa90d5ada6e2cf83b82e077c35702f2fc3">llvm::X86ISD::VPMADDWD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aabb0879a5b12d023b74697191612bddaa">llvm::X86ISD::VTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa41663b0542b9ae893f5c9122a7b1ce4c">llvm::X86ISD::VZEXT_LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6edfdb2ee22d183ae51d57796e56f8e3">widenSubVector</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### shouldConvertConstantLoadToIntImm() {#a711da9c348c7a96e4d79942afa0af105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::shouldConvertConstantLoadToIntImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1504 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### shouldConvertFpToSat() {#a7a2c1154fe3e12011cb42fa9bfdc4387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86TargetLowering::shouldConvertFpToSat (unsigned Op, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> FPVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Should we generate fp_to_si_sat and fp_to_ui_sat from type FPVT to type VT from min(max(fptoi)) saturation patterns.</p>

<p>Definition at line 1259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98661814400e72a77f5ed4e088c06937">llvm::ISD::FP_TO_UINT_SAT</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa93fbbc66d52a51d178af8ac4398ec05">llvm::TargetLoweringBase::isOperationLegalOrCustom</a>.</p>

</div>
</div>

### shouldConvertPhiType() {#ac8605b738411a9018ae4e3ba5de54026}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::shouldConvertPhiType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * From, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * To)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a set in interconnected phis of type 'From' that are loaded/stored or bitcast to type 'To', return true if the set should be converted to 'To'.</p>

<p>Declaration at line 1437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af40372fc6c2f0c6fea698d32c6730166">llvm::TargetLoweringBase::shouldConvertPhiType</a>.</p>

</div>
</div>

### shouldFoldConstantShiftPairToMask() {#a85fb0d7e000c96b972014b0405aa9c88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::shouldFoldConstantShiftPairToMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7a">CombineLevel</a> Level)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3609 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6ea263078f271d4d5e25764ef77d2878">llvm::TargetLoweringBase::shouldFoldConstantShiftPairToMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>.</p>

</div>
</div>

### shouldFoldMaskToVariableShiftPair() {#adaff89efc72db02240bc69c44c8f0691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::shouldFoldMaskToVariableShiftPair (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> X)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>There are two ways to clear extreme bits (either low or high): Mask: x &amp; (-1 &lt;&lt; y) (the instcombine canonical form) Shifts: x &gt;&gt; y &lt;&lt; y Return true if the variant with 2 variable shifts is preferred.</p>


<p>Return false if there is no preference.</p>


<p>Declaration at line 1233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3628 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### shouldFoldSelectWithIdentityConstant() {#a5cd2ddff46dc5822bcc7666e336da52b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::shouldFoldSelectWithIdentityConstant (unsigned BinOpcode, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a8eed7940698816c772ded7b098f2e1a1">llvm::EVT::is512BitVector</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### shouldFormOverflowOp() {#a0023312f4ffae5c8a127a8da0c812dba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::shouldFormOverflowOp (unsigned Opcode, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, bool MathUsed)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Overflow nodes should get combined/lowered to optimal instructions (they should allow eliminating explicit compares by getting flags from math ops).</p>

<p>Declaration at line 1533 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0248ed29f933c5faa55cbdfebf3139bd">llvm::TargetLoweringBase::isOperationExpand</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### shouldProduceAndByConstByHoistingConstFromShiftsLHSOfAnd() {#a45b5bd9592a350b3994804b65f1eeaaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::shouldProduceAndByConstByHoistingConstFromShiftsLHSOfAnd (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> X, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> * XC, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> * CC, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Y, unsigned OldShiftOpcode, unsigned NewShiftOpcode, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3498 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9bd4abfb6bf968505c7417e2b2532236">llvm::TargetLoweringBase::shouldProduceAndByConstByHoistingConstFromShiftsLHSOfAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### shouldReduceLoadWidth() {#a6ad23b58059ffd91df6a2dddf30c5d71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::shouldReduceLoadWidth (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Load, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7">ISD::LoadExtType</a> ExtTy, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> NewVT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if we believe it is correct and profitable to reduce the load node to a smaller type.</p>

<p>Declaration at line 1495 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/use/#a53a48d67682705c5f7f06ffc850fd622">llvm::Use::getUser</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aacd05b71fb3b325dcc53a7df09d37edb">llvm::EVT::is256BitVector</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a8eed7940698816c772ded7b098f2e1a1">llvm::EVT::is512BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a3ca9742688618517cc4690fb947fb609">isSimple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ac7ab3243c491b3b6ff673eaf87335fe5">llvm::X86II::MO_GOTTPOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a158da2b6d3d938aaa15b6acd00150e2c">llvm::Value::user_begin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf9b840077b4580ddbfd3bf992fe359eb">llvm::X86ISD::WrapperRIP</a>.</p>

</div>
</div>

### shouldScalarizeBinop() {#aa74ba35350fae122acd7284555740ba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::shouldScalarizeBinop (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> VecOp)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scalar ops always have equal or better analysis/performance/power than the vector equivalent, so this always makes sense if the scalar op is supported.</p>

<p>Declaration at line 1522 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a477ef80c70c7359199eace0e5d3133b1">llvm::ISD::BUILTIN_OP_END</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="#ae174548699928fd09f1b90077dfc2a48">isBinOp</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afd2a90bd679de6f5964ce9b6f9931541">llvm::TargetLoweringBase::isOperationLegalOrCustomOrPromote</a>.</p>

</div>
</div>

### ShouldShrinkFPConstant() {#af67a690870634cfabaefd978dc3dd2e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::ShouldShrinkFPConstant (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If true, then instruction selection should seek to shrink the FP constant of the specified type to a smaller type in order to save space and / or reduce runtime.</p>

<p>Declaration at line 1491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldSplatInsEltVarIndex() {#a51cb60d8c2758ff018c35468453c7eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::shouldSplatInsEltVarIndex (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if inserting a scalar into a variable element of an undef vector is more efficiently handled by splatting the scalar instead.</p>

<p>Declaration at line 1257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3652 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>.</p>

</div>
</div>

### shouldTransformSignedTruncationCheck() {#a193b8c17079133af40829a1fef4adf6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86TargetLowering::shouldTransformSignedTruncationCheck (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> XVT, unsigned KeptBits)</td>
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


<p>Definition at line 1236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### SimplifyDemandedBitsForTargetNode() {#a6fafb0a04f81d44e034566f1a758ea39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::SimplifyDemandedBitsForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO, unsigned Depth)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 43786 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae1624a99d3ee1309539c25a7afe2a852">llvm::X86ISD::ANDNP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7ead8df5cf10d5f87e8c19b6f7d34ad6">llvm::X86ISD::BEXTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa0e30dfae5bfdf5db17847036581a181f">llvm::X86ISD::BEXTRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa249e11d47119ca5c2666008857b3b534">llvm::X86ISD::BLENDV</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a781bd5c20864a9c185018258af774ace">llvm::APInt::clearAllBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a155466c9ea0a2bd00e09c62fdce2c052">llvm::APInt::clearBit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf413bba9e77d68afdc1afba084851728">llvm::X86ISD::CMOV</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#a75c3b728d0f9ba68b58c71a4940aedab">llvm::TargetLowering::TargetLoweringOpt::CombineTo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac01c66c983bfbac05a0cf903f08417df">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8bad27827f46bca6baf814cbd2b64e84">llvm::APInt::countl_zero</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a1eeff70353694cb360b2893553c18e7d">llvm::KnownBits::countMinTrailingZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83c7c9008ba213687483b60a658b4a13">llvm::APInt::countr_zero</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#a15f606b1ca13c24d23039809f667daeb">llvm::TargetLowering::TargetLoweringOpt::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af1235e2e2ca58b93e3b22bc6c8b3d9ab">extract128BitVector</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a6f1c4a256c58844fb8dc8aa154f335a4">llvm::KnownBits::extractBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3015474e70e59c0a3ed4f9f0e8644b75">llvm::APInt::getActiveBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6e64fef2ad2ba4052cd8365e97e8d2">llvm::SDNode::getAsZExtVal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a64f6469ab95c4eec77e4ccf303619a81">llvm::SelectionDAG::getBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a46ceedee591f92727b85641794a96061">llvm::APInt::getBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#afd1c330d00d17bd267450ab43d5f0eec">llvm::KnownBits::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ac969b6c833cfa44c1b4fcd5790268340">llvm::SDValue::getConstantOperandVal</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e33cb0aa9b4fbae99810b4d70d29f25">getPackDemandedElts</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#abd46b9ca1d156bc7e3dd9150cc106a28">llvm::SDValue::getScalarValueSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1e6f0d8dfed0ab631b488a3e6317718e">llvm::APInt::getSignMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#acbcc973a299b6f8733774668210b5227">llvm::SDValue::getSimpleValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a76e45a40f2f0b5b09132d1de119765e8">llvm::KnownBits::intersectWith</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a9e3e2c5a531a6ff555d5302ba1745357">llvm::MVT::is256BitVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#aaac3e239cbdfe15a8e9bad4f8e1e3a95">llvm::ISD::isBuildVectorAllZeros</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a5274c29c7da2473d342adfa98f34a025">llvm::KnownBits::isConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aea5f26deda5ef97e02f6afc57c0c3920">llvm::APInt::isOne</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abdeb0e345d1884804b99c02dafb2eb08">llvm::MVT::isScalarInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a4aa7e7ca8ab4093fd0dbadb223b998c0">llvm::APInt::isSignMask</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acfae9bdee6027ffa8ffe244cc22e3a76">llvm::APInt::isSubsetOf</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a1620c017d995c7ccbcb59e0212618017">llvm::KnownBits::isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af34549c39d6f741fbdaf9a795aa306e9">llvm::APInt::lshr</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af338e23a90c301183968435e80cd6a27">llvm::APInt::lshrInPlace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa5b943cbe99c34600de83e0c7c0046e18">llvm::X86ISD::MOVMSK</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa0e447f5393ad6797e4af00c9401ca6d3">llvm::X86ISD::PACKSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf1366c70ee0fa95a076fe683d900e9f9">llvm::X86ISD::PCMPGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa492e5211769c80814cb779b4ba995f23">llvm::X86ISD::PDEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa71fe63f40efcc073f1a5dd6df6efc550">llvm::X86ISD::PEXTRB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8c57aafe37f470b4b146ea8307983228">llvm::X86ISD::PEXTRW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7d9a2bb887ffdd3c85b7eb7215b891db">llvm::X86ISD::PINSRB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac851454bb8c0c576e53b3d993d9c2acf">llvm::X86ISD::PINSRW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac42bb75fe0307f14264032e6db521de2">llvm::X86ISD::PMULDQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7f0c379fa7f4b37235504936c56ae486">llvm::X86ISD::PMULUDQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a4816b869391aac5bbcce9c889c2ecd97">llvm::KnownBits::setAllZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a2780c5606880394d3f07cd2079a27697">llvm::APInt::setHighBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ade8e20ecea1091e835395746448e262e">llvm::APInt::setLowBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a4f1e1a4449b58958c5884c689e7f4861">llvm::APInt::setSignBit</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ac6a3aaac8faabe7dc09114d716a93eba">llvm::TargetLowering::ShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ab2fd70d9aeac9343fa8f00ccdeff7f0b">llvm::TargetLowering::SimplifyDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a1bb3f6ea028996773613a5f135b4d083">llvm::TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a45a058376b4d2b008f7ea5ca16cecf55">llvm::TargetLowering::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0338302ee706a6cd16534e768210b0b2">llvm::TargetLowering::SimplifyMultipleUseDemandedBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa71996007c100b1c370ffc2444bc680a3">llvm::X86ISD::TESTP</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a40a666d8a3b58f5eca5d7f9f26796bc7">llvm::KnownBits::trunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac3bc043916fd84786c2ac451e0a3cd24">llvm::X86ISD::VBROADCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf5db7ecddd15a88ac103ef566d0b2180">llvm::X86ISD::VSHLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa53a1bf88056b37006ab9ba3b83f1f6ae">llvm::X86ISD::VSRAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa88145107ca3ab31b2e96b5e99bf5b517">llvm::X86ISD::VSRLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aabb0879a5b12d023b74697191612bddaa">llvm::X86ISD::VTRUNC</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a51c3c203b80468b8761416d14e6f5b7f">llvm::KnownBits::zext</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a2ed912a28808268e35bd58e8f11251aa">llvm::APInt::zextOrTrunc</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a7ddb13bdf305b1d4eee7bf1a9ac9d35e">llvm::KnownBits::zextOrTrunc</a>.</p>

</div>
</div>

### SimplifyDemandedVectorEltsForTargetNode() {#a1a1dd27d36e829a2de3225991dac9c3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; KnownUndef, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; KnownZero, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO, unsigned Depth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to simplify any target nodes based on the demanded vector elements, returning true on success.</p>


<p>Otherwise, analyze the expression and return a mask of KnownUndef and KnownZero elements for the expression (used to simplify the caller). The KnownUndef/Zero elements may only be accurate for those bits in the DemandedMask.</p>


<p>Declaration at line 1294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 42993 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae1624a99d3ee1309539c25a7afe2a852">llvm::X86ISD::ANDNP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa134343dc9302925cf314b9b891880380">llvm::X86ISD::BLENDI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa249e11d47119ca5c2666008857b3b534">llvm::X86ISD::BLENDV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a781bd5c20864a9c185018258af774ace">llvm::APInt::clearAllBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aac76bff09195240a482b319136ab6144">llvm::APInt::clearLowBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad00ef9b94ff672e7a3ef2a0cae24b757">combineBlendOfPermutes</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#a75c3b728d0f9ba68b58c71a4940aedab">llvm::TargetLowering::TargetLoweringOpt::CombineTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa94c00be07b5a7475ca1ae4b1e1676fff">llvm::X86ISD::CVTPH2PS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa1fec5162852502da5a2832321f9c1012">llvm::X86ISD::CVTPS2PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf64444ca786d0cddde2bc8628f324e3e">llvm::X86ISD::CVTSI2P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa873eda45cff31b9f5fe7af33ed2ec407">llvm::X86ISD::CVTTP2SI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac6c8013c7f060d7023eb23cb32fc14c8">llvm::X86ISD::CVTTP2UI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7821643340a91702a2540ac9a3e6ab53">llvm::X86ISD::CVTUI2P</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#a15f606b1ca13c24d23039809f667daeb">llvm::TargetLowering::TargetLoweringOpt::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d97ec8d51a9f56c4a2cff1f7a567b4e">llvm::DecodeBLENDMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e3f786bc082e1485e1a863aab736513">llvm::DecodeVPERMMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aecabf0b51b7f3a579c05fc08e06c265a">extractSubVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa3a702f9706acfd0711a2ef618e764eb9">llvm::X86ISD::FHADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaab2f2aa57f37dc2b9c616ce720e6b8ea">llvm::X86ISD::FHSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa080313447e98432d4b62801bf2ad761f">llvm::X86ISD::FMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaa24b80a5be93b9ddfa62446ced71b68e">llvm::X86ISD::FMAXC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aabad10e5691f05a78824d6bad0300e529">llvm::X86ISD::FMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aafb454d19747fe081325da96a69373f82">llvm::X86ISD::FMINC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aacd28a0d5248d37cbf2d4449434a70a98">llvm::X86ISD::FRCP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaff7f55bae98701a821d0529a64932088">llvm::X86ISD::FRSQRT</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a64f6469ab95c4eec77e4ccf303619a81">llvm::SelectionDAG::getBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61f23ea50bb7d5e61ca17b8d73bc7f7e">getBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adcb96bd09d7c75c7669fa5f9d1190899">llvm::APInt::getHighBitsSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8c620fc470731fdb2a41678c294a1e6c">getHorizDemandedElts</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6cc63109335eefe2c5727d1e12fc820">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e33cb0aa9b4fbae99810b4d70d29f25">getPackDemandedElts</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aea8bc2b59cb3fa833eb7895a3a216abd">llvm::MVT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#acbcc973a299b6f8733774668210b5227">llvm::SDValue::getSimpleValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a5f64c589a5312630fe76a37f62a39707">llvm::EVT::getStoreSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a27d46d110a0572a24271e707cbeebb79">getTargetShuffleInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b0e59823444a55c295af279611a9d24">llvm::SelectionDAG::getUNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a126c61d55fb4d2e509537ce68e8b6400">llvm::TargetLoweringBase::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a210ba6b43ba451b698857dd9de71bd15">llvm::EVT::getVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9130245943505c30b0ba979c8a77d723">getZeroVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa0f4ce46b34ac79f389d475fa6745463e">llvm::X86ISD::HADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf02f5b8c1cc25ab0a8e6cd8e5364332f">llvm::X86ISD::HSUB</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7cb0f27acb965339dde328392c1adaf7">insertSubVector</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a6da514c588b2668280a861a59bfc9fa5">llvm::APInt::intersects</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a0c1ae89f2c2765a979f999ecdc11304c">llvm::MVT::is128BitVector</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aacd05b71fb3b325dcc53a7df09d37edb">llvm::EVT::is256BitVector</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a8eed7940698816c772ded7b098f2e1a1">llvm::EVT::is512BitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a423e2c491de1408d54e35f0b47d076be">llvm::APInt::isAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aea5f26deda5ef97e02f6afc57c0c3920">llvm::APInt::isOne</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af62c6be38ef70e3cb785ca99e3642a52">isSequentialOrUndefInRange</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acfae9bdee6027ffa8ffe244cc22e3a76">llvm::APInt::isSubsetOf</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6f70409be6aadf7e5967d643c821d44f">isUndefInRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a90ffe79bb38686b4c283e3959fdf8b31">isUndefOrEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a206d09d378fc9700fa93cd72adba2257">isUndefOrZeroInRange</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa00eeeadc9b5bc4170585af2c864b0080">llvm::X86ISD::KSHIFTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa990193ae17623553503589ce732d6d9d">llvm::X86ISD::KSHIFTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af34549c39d6f741fbdaf9a795aa306e9">llvm::APInt::lshr</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af338e23a90c301183968435e80cd6a27">llvm::APInt::lshrInPlace</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a25c0550227f31c7368fcefb62d72fcf1">llvm::SelectionDAG::makeEquivalentMemoryOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac25d8581d098d4c817c5602c5907967f">llvm::SelectionDAG::MaskedVectorIsZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2ede8334e026220fc2f2884ba0aba7b6af20ba120fee712e351cd784e6142a6e6">llvm::X86::MaxShuffleCombineDepth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa0e447f5393ad6797e4af00c9401ca6d3">llvm::X86ISD::PACKSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae3abaac16c2c7818508b6e93d170c6b3">llvm::X86ISD::PACKUS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8e6b692f93aee762231d7221e5730598">llvm::X86ISD::PCMPEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf1366c70ee0fa95a076fe683d900e9f9">llvm::X86ISD::PCMPGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac42bb75fe0307f14264032e6db521de2">llvm::X86ISD::PMULDQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7f0c379fa7f4b37235504936c56ae486">llvm::X86ISD::PMULUDQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaaa69270d771a472e5b86c11370dc0330">llvm::X86ISD::PSADBW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8a421b1832302b5097a94b81ed579170">llvm::X86ISD::PSHUFB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa182b063ab7dd0842ce968cef5f981e92">llvm::X86ISD::PSHUFD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aafce56cb4ce3db03407437c4ae07d4103">llvm::X86ISD::PSHUFHW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa6c444c7b1be0ea32c7e2c92fbc40388a">llvm::X86ISD::PSHUFLW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ab455b98d2cc1e2a8ff7a9486ec4c2982">llvm::APIntOps::ScaleBitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab6fff8a97bcb55e50e9be0ecf0c99b63">llvm::APInt::setAllBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a33f9f862dca8ee0f23bff5941bf433d8">llvm::APInt::setBit</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a2780c5606880394d3f07cd2079a27697">llvm::APInt::setHighBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ade8e20ecea1091e835395746448e262e">llvm::APInt::setLowBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acb9c55b6986369948507ca5241b4e411">llvm::APInt::shl</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a45a058376b4d2b008f7ea5ca16cecf55">llvm::TargetLowering::SimplifyDemandedVectorElts</a>, <a href="#a5681faab09fa140f67d47577193f2665">SimplifyDemandedVectorEltsForTargetShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0338302ee706a6cd16534e768210b0b2">llvm::TargetLowering::SimplifyMultipleUseDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a480a8e3181c852945f597bad4fd0d9c3">llvm::TargetLowering::SimplifyMultipleUseDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaddf811d44f58e7d0e16ca3266b8689a3f112d168d45b1ab58a80c2b9f7e6cb4">llvm::SM_SentinelUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa17d58dbb94911cf1630e9c523cfe1911">llvm::X86ISD::SUBV_BROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa03a9611e6b354e10a8c3809f49b61eac">llvm::X86ISD::UNPCKH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa000697f31e57d54cd3ae43a2568c36ca">llvm::X86ISD::UNPCKL</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ad5596cf1822f4cc9e37fb75b6dff630f">llvm::SDNode::users</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac3bc043916fd84786c2ac451e0a3cd24">llvm::X86ISD::VBROADCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa78f74c46439b34ecc3b826e4bb5f1fc2">llvm::X86ISD::VBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aad57ffc99b9cbbf690e9ac199fc06573d">llvm::X86ISD::VPERM2X128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8bc7868b5b5c49adff7e1b701e2f6daf">llvm::X86ISD::VPERMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaa359935c9a800c36fd9429fa8691c98f">llvm::X86ISD::VPERMIL2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aadbf48e1eda461f1db91b138d32c7e8d5">llvm::X86ISD::VPERMILPI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac98989ae74d479c77e8ac37cf95f3f22">llvm::X86ISD::VPERMILPV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab250ea084b009cb311b1617f5f527c35">llvm::X86ISD::VPERMV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab63fa0a5c1888e275635edaaf3ffa3ed">llvm::X86ISD::VPERMV3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab02310456415907ec1be4ceae53d48a9">llvm::X86ISD::VPMADDUBSW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa90d5ada6e2cf83b82e077c35702f2fc3">llvm::X86ISD::VPMADDWD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa223d75974bc37f644ce46f5a8684ab9e">llvm::X86ISD::VPPERM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaece0f87e173b1f5b36990e9ac4aa5ae5">llvm::X86ISD::VPSHA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaab0d78bdd53f75f09beb712341df5660">llvm::X86ISD::VPSHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa4c0d35627a076e5424b6de3804613ec6">llvm::X86ISD::VSHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7e968cfe56e1cef0e04fc1537d5a5219">llvm::X86ISD::VSHLDQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf5db7ecddd15a88ac103ef566d0b2180">llvm::X86ISD::VSHLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8a2fc33ce2fe41ef2d20854eda49a4f6">llvm::X86ISD::VSHLV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa751ccb36d27604bba1151ef84cd98510">llvm::X86ISD::VSRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa53a1bf88056b37006ab9ba3b83f1f6ae">llvm::X86ISD::VSRAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7b2c246cb3a5d3513041dab6a32b2901">llvm::X86ISD::VSRAV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa0f740b2d7ea674677c7e8073453f8814">llvm::X86ISD::VSRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa671bbc2a9353cf20bbfb8af47aa237ab">llvm::X86ISD::VSRLDQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa88145107ca3ab31b2e96b5e99bf5b517">llvm::X86ISD::VSRLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa1e837f978c72eafaf138c1b0a7b6cddf">llvm::X86ISD::VSRLV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aabb0879a5b12d023b74697191612bddaa">llvm::X86ISD::VTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa192681cddd79867e5a6924bbcf453965">llvm::X86ISD::VTRUNCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa3b2fdb13adfdfd71f723a38073cb43f0">llvm::X86ISD::VTRUNCUS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa41663b0542b9ae893f5c9122a7b1ce4c">llvm::X86ISD::VZEXT_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa1356801ab44d90ec9c7643ac8ff0770c">llvm::X86ISD::VZEXT_MOVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6edfdb2ee22d183ae51d57796e56f8e3">widenSubVector</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a2ed912a28808268e35bd58e8f11251aa">llvm::APInt::zextOrTrunc</a>.</p>

</div>
</div>

### SimplifyDemandedVectorEltsForTargetShuffle() {#a5681faab09fa140f67d47577193f2665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::SimplifyDemandedVectorEltsForTargetShuffle (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, unsigned MaskIndex, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 42926 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#a75c3b728d0f9ba68b58c71a4940aedab">llvm::TargetLowering::TargetLoweringOpt::CombineTo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#a15f606b1ca13c24d23039809f667daeb">llvm::TargetLowering::TargetLoweringOpt::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#ade9fa017ca3aa82f7694a47090547bc1">llvm::ConstantVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a64f6469ab95c4eec77e4ccf303619a81">llvm::SelectionDAG::getBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a8b1a64bd0c1be7a99998055c78d1312b">llvm::MachinePointerInfo::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a22c327ddfcb98f911f3197180981f41e">llvm::SelectionDAG::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0f68c9c0e4a38aebd5773f80dd5b716">llvm::SelectionDAG::getEntryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab0bb270c4647dee5b3ba4ff11bf30016">getTargetConstantFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a423e2c491de1408d54e35f0b47d076be">llvm::APInt::isAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8816fa735915778273088b9d0d10adc9">llvm::peekThroughOneUseBitcasts</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a45a058376b4d2b008f7ea5ca16cecf55">llvm::TargetLowering::SimplifyDemandedVectorElts</a>.</p>


<p>Referenced by <a href="#a1a1dd27d36e829a2de3225991dac9c3e">SimplifyDemandedVectorEltsForTargetNode</a>.</p>

</div>
</div>

### SimplifyMultipleUseDemandedBitsForTargetNode() {#a30ea9932827054448251050d576b4874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>More limited version of SimplifyDemandedBits that can be used to "look
through" ops that don't contribute to the DemandedBits/DemandedElts - bitwise ops etc.</p>

<p>Declaration at line 1314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 44333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae1624a99d3ee1309539c25a7afe2a852">llvm::X86ISD::ANDNP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa249e11d47119ca5c2666008857b3b534">llvm::X86ISD::BLENDV</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a781bd5c20864a9c185018258af774ace">llvm::APInt::clearAllBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac01c66c983bfbac05a0cf903f08417df">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83c7c9008ba213687483b60a658b4a13">llvm::APInt::countr_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a64f6469ab95c4eec77e4ccf303619a81">llvm::SelectionDAG::getBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#acbcc973a299b6f8733774668210b5227">llvm::SDValue::getSimpleValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a27d46d110a0572a24271e707cbeebb79">getTargetShuffleInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b0e59823444a55c295af279611a9d24">llvm::SelectionDAG::getUNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a3a371e99982e3168caf644d82298fcac">llvm::MVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9130245943505c30b0ba979c8a77d723">getZeroVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#aaac3e239cbdfe15a8e9bad4f8e1e3a95">llvm::ISD::isBuildVectorAllZeros</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aabc0af41b4437080b27002ed7a1ed656">llvm::KnownBits::isNegative</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a157efd68e8b4b838829cad165b1583f8">llvm::KnownBits::isNonNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acfae9bdee6027ffa8ffe244cc22e3a76">llvm::APInt::isSubsetOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf1366c70ee0fa95a076fe683d900e9f9">llvm::X86ISD::PCMPGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7d9a2bb887ffdd3c85b7eb7215b891db">llvm::X86ISD::PINSRB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac851454bb8c0c576e53b3d993d9c2acf">llvm::X86ISD::PINSRW</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a27ad8ac0b3b15a21f86c5f89e0c9cdd0">llvm::APInt::popcount</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a03f40e066df2407ab1e901ca999d717e">llvm::TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf5db7ecddd15a88ac103ef566d0b2180">llvm::X86ISD::VSHLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa53a1bf88056b37006ab9ba3b83f1f6ae">llvm::X86ISD::VSRAI</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>

</div>
</div>

### softPromoteHalfType() {#ad34d40f5d0a64179484587b5012244b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86TargetLowering::softPromoteHalfType ()</td>
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



<p>Definition at line 1594 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>

</div>
</div>

### storeOfVectorConstantIsCheap() {#a4d9590a596760f98179ab0814b15318f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86TargetLowering::storeOfVectorConstantIsCheap (bool IsZero, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> MemVT, unsigned NumElem, unsigned AddrSpace)</td>
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

<p>Return true if it is expected to be cheaper to do a store of vector constant with the given size and type for the address space than to store the individual scalar element constants.</p>

<p>Definition at line 1536 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>

</div>
</div>

### supportKCFIBundles() {#a212993bd851420cf4319ce3a0291578b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86TargetLowering::supportKCFIBundles ()</td>
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

<p>Definition at line 1615 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>

</div>
</div>

### supportSwiftError() {#a4d29a6154e85b01c7a17d09e23e71eca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::supportSwiftError ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target supports swifterror attribute.</p>


<p>It optimizes loads and stores to reading and writing a specific register.</p>


<p>Declaration at line 1613 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 60920 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#af9d07c5d74dcf9baf1693e4c7a98074b">llvm::X86RegisterInfo::getCalleeSavedRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a6afff15818a5fb74943eccad1ff4f786">llvm::X86RegisterInfo::getCallPreservedMask</a>.</p>

</div>
</div>

### targetShrinkDemandedConstant() {#adc96b14a52d48d045a0a9d2cc9459a62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::targetShrinkDemandedConstant (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 38008 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae1624a99d3ee1309539c25a7afe2a852">llvm::X86ISD::ANDNP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4cc11b26432f9343b3c532f06171ad04">llvm::bit_ceil</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#a75c3b728d0f9ba68b58c71a4940aedab">llvm::TargetLowering::TargetLoweringOpt::CombineTo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#a15f606b1ca13c24d23039809f667daeb">llvm::TargetLowering::TargetLoweringOpt::DAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3015474e70e59c0a3ed4f9f0e8644b75">llvm::APInt::getActiveBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a752372e170e4e7c595bf8810bb52adf2">llvm::EVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8924f4d542442eecf3aac41a0bd61fa3">llvm::APInt::getNumSignBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a210ba6b43ba451b698857dd9de71bd15">llvm::EVT::getVectorVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a2f37af786c5ba90887c1b4ec137a066c">llvm::ISD::isBuildVectorOfConstantSDNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acfae9bdee6027ffa8ffe244cc22e3a76">llvm::APInt::isSubsetOf</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>.</p>

</div>
</div>

### unwrapAddress() {#ae6da32121a396476129bc7577db0aad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::unwrapAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 38819 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac52ade4e38c09090c08d423e886cb4b2">llvm::X86ISD::Wrapper</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf9b840077b4580ddbfd3bf992fe359eb">llvm::X86ISD::WrapperRIP</a>.</p>

</div>
</div>

### useLoadStackGuardNode() {#a32acffd2f19c83d30c2955b094d7e96b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::useLoadStackGuardNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2736 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### useSoftFloat() {#a3a2c182f696ccea7f69622fb51c70a3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::useSoftFloat ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1058 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### useStackGuardXorFP() {#aa25a7920eb37572630745203c9c50731}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::useStackGuardXorFP ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this function returns true, stack protection checks should XOR the frame pointer (or whichever pointer is used to address locals) into the stack guard value before checking it.</p>


<p>getIRStackGuard must return nullptr if this returns true.</p>


<p>Declaration at line 1572 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2740 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### visitMaskedLoad() {#ab4a216c3f1033e64e9340aca44316ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::visitMaskedLoad (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MMO, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; NewLoad, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Ptr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> PassThru, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Mask)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1634 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 33160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8a8c8f74a281b988a0641dd7f909e20a">llvm::X86ISD::CLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2eacb2f86eaebe8b719f743d17a2d5a5f3d">llvm::X86::COND_NE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a64f6469ab95c4eec77e4ccf303619a81">llvm::SelectionDAG::getBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab41ff97ee5adf16c2a50b890a000d79f">getFlagsOfCmpZeroFori1</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6cc63109335eefe2c5727d1e12fc820">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a1c861a21f795c3108ab690f3a45c881a">llvm::SDValue::isUndef</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### visitMaskedStore() {#a3f2022425f9155911916a81841455566}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::visitMaskedStore (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MMO, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Ptr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Mask)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1638 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 33180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2eacb2f86eaebe8b719f743d17a2d5a5f3d">llvm::X86::COND_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa99e2bb0ac23ed780f3929d5024cbc088">llvm::X86ISD::CSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a64f6469ab95c4eec77e4ccf303619a81">llvm::SelectionDAG::getBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab41ff97ee5adf16c2a50b890a000d79f">getFlagsOfCmpZeroFori1</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6cc63109335eefe2c5727d1e12fc820">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### findRepresentativeClass() {#a08569892769aa5e49c2bf954082e9be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const TargetRegisterClass *, uint8_t &gt; X86TargetLowering::findRepresentativeClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
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


<p>Declaration at line 1667 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac1cbaebc2a18476b73105d6916a56664">llvm::TargetLoweringBase::findRepresentativeClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addLegalFPImmediate() {#a44e5dc4cd7dcee99c44076c04a495b19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86TargetLowering::addLegalFPImmediate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Imm)</td>
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

<p>Indicate that this x86 target can instruction select the specified FP immediate natively.</p>

<p>Definition at line 1680 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>

</div>
</div>

### BuildSDIVPow2() {#a57b1cb02c7064ffc62e7adf6333a6781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::BuildSDIVPow2 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Divisor, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; Created)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1904 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 23322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### CanLowerReturn() {#a743a463663ba17b3d519e4098be6d710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::CanLowerReturn (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1807 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### combineRepeatedFPDivisors() {#a49756d103dc3cbe7cca1d98c07a767e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86TargetLowering::combineRepeatedFPDivisors ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reassociate floating point divisions into multiply by reciprocal.</p>


<p>If we have at least two divisions that use the same divisor, convert to multiplication by a reciprocal.</p>


<p>This may need to be adjusted for a given CPU if a division's cost is not at least twice the cost of a multiplication. This is because we still need one division to calculate the reciprocal and then we need two multiplies by that reciprocal as replacements for the original divisions.</p>


<p>Declaration at line 1902 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 23317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### emitBitTestAtomicRMWIntrinsic() {#a765370db273adf54b86a60f3de558035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86TargetLowering::emitBitTestAtomicRMWIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * AI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a bit test atomicrmw using a target-specific intrinsic.</p>


<p>This represents the combined bit test intrinsic which will be lowered at a late stage by the backend.</p>


<p>Declaration at line 1824 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 31495 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### emitCmpArithAtomicRMWIntrinsic() {#aab6483478ea6cc26b7c4cdcac832ff3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86TargetLowering::emitCmpArithAtomicRMWIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * AI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a atomicrmw which the result is only used by comparison, using a target-specific intrinsic.</p>


<p>This represents the combined atomic and compare intrinsic which will be lowered at a late stage by the backend.</p>


<p>Declaration at line 1825 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 31638 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### emitEHSjLjLongJmp() {#ad809ec9198a48ce7d3ea339cf3e37bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * X86TargetLowering::emitEHSjLjLongJmp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1868 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 36959 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### emitEHSjLjSetJmp() {#a45b38fe5dfee48def2a08c82d2e3796e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * X86TargetLowering::emitEHSjLjSetJmp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1862 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 36610 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### emitFlagsForSetcc() {#afcc90943b4dd635e767a7a06bb10458e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::emitFlagsForSetcc (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op1, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> CC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; X86CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit flags for the given setcc condition and operands.</p>


<p>Also returns the corresponding <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> condition code constant in X86CC.</p>


<p>Declaration at line 1882 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 24156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### emitLongJmpShadowStackFix() {#a2871933f02418c5f6d5ae1e8d81be085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * X86TargetLowering::emitLongJmpShadowStackFix (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fix the shadow stack using the previously saved SSP pointer.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>emitSetJmpShadowStackFix</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] MI</td>
<td class="doxyParamItemDescription"><p>The temporary Machine <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> for the builtin.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] MBB</td>
<td class="doxyParamItemDescription"><p>The Machine Basic Block that will be modified.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The sink MBB that will perform the future indirect branch.</p></dd>
</dl>


<p>Declaration at line 1871 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 36770 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### EmitLoweredCascadedSelect() {#af8991fbdd984cbb4f058dc0cc1fcd165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * X86TargetLowering::EmitLoweredCascadedSelect (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI1, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI2, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Utility function to emit the xmm reg save portion of va_start.</p>

<p>Declaration at line 1840 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35797 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### EmitLoweredCatchRet() {#ae87c887710eb36bfc2fbdca9007078bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * X86TargetLowering::EmitLoweredCatchRet (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1847 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 36328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### EmitLoweredIndirectThunk() {#a3f7962449e6f8a20ad62bf46c6b7973e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * X86TargetLowering::EmitLoweredIndirectThunk (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1859 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 36506 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### EmitLoweredProbedAlloca() {#a29723eb149349ce7b5f389fa7e413823}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * X86TargetLowering::EmitLoweredProbedAlloca (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1853 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 36100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### EmitLoweredSegAlloca() {#a8b62e3102d65b55f6311fcec3e5269fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * X86TargetLowering::EmitLoweredSegAlloca (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1850 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 36194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### EmitLoweredSelect() {#a44b779edd4c0f87ba42d323af71e6573}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * X86TargetLowering::EmitLoweredSelect (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1844 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35950 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### EmitLoweredTLSCall() {#ac03d685e08b4adada3631e2dfc6f8e34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * X86TargetLowering::EmitLoweredTLSCall (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1856 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 36363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### emitPatchableEventCall() {#a91433c180ad2232456c3473327ffa71a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * X86TargetLowering::emitPatchableEventCall (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1877 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 37324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### emitSetJmpShadowStackFix() {#a9a89d8a9888958def220bb30277c66dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86TargetLowering::emitSetJmpShadowStackFix (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SetJmp implies future control flow change upon calling the corresponding LongJmp.</p>


<p>Instead of using the 'return' instruction, the long jump fixes the stack and performs an indirect branch. To do so it uses the registers that were stored in the jump buffer (when calling SetJmp). In case the shadow stack is enabled we need to fix it as well, because some return addresses will be skipped. The function will save the SSP for future fixing in the function emitLongJmpShadowStackFix.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>emitLongJmpShadowStackFix</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] MI</td>
<td class="doxyParamItemDescription"><p>The temporary Machine <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> for the builtin.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] MBB</td>
<td class="doxyParamItemDescription"><p>The Machine Basic Block that will be modified.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1865 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 36568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### EmitSjLjDispatchBlock() {#adb8fe1bc6925d9aaee73cf8ec3e4e8d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * X86TargetLowering::EmitSjLjDispatchBlock (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1874 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 37093 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### EmitTailCallLoadRetAddr() {#a96b5fdf09cbaa3744868bb160ad1fd33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::EmitTailCallLoadRetAddr (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; OutRetAddr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, bool IsTailCall, bool Is64Bit, int FPDiff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a load of return address if tail call optimization is performed and it is required.</p>

<p>Declaration at line 1707 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 1956 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### EmitVAARGWithCustomInserter() {#a6662e9bd609891f313d6afdd1e26c9db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * X86TargetLowering::EmitVAARGWithCustomInserter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1837 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 35403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### FP\_TO\_INTHelper() {#a64ae0166ea0732e7d08610c6b11c9244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::FP_TO_INTHelper (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool IsSigned, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1717 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 20377 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### getAddressSpace() {#a603e81780090d28e4a691ef543bf5b0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86TargetLowering::getAddressSpace ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1715 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### GetAlignedArgumentStackSize() {#a3017fbecf88f2aac84425a9886a11a3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86TargetLowering::GetAlignedArgumentStackSize (unsigned StackSize, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make the stack size align e.g 16n + 12 aligned for a 16-byte align requirement.</p>

<p>Declaration at line 1712 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2639 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### getGlobalWrapperKind() {#ae7fa6d3e7e388a28aa972e7bd49593dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86TargetLowering::getGlobalWrapperKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char OpFlags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1726 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 18852 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### getMOVL() {#a300d2d93bfdab2717786de60ee7dfcaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::getMOVL (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> V1, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> V2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a vector_shuffle mask for an movs{s|d}, movd operation of specified width.</p>

<p>Declaration at line 1907 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 1989 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### getRecipEstimate() {#a4e8fa8d0165f4b68bbe05487428ba6a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::getRecipEstimate (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, int Enabled, int &amp; RefinementSteps)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> rcp* to speed up fdiv calculations.</p>


<p>The minimum architected relative accuracy is 2^-12.</p>


<p>We need one Newton-Raphson step to have a good float result (24 bits of precision).</p>


<p>Declaration at line 1898 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 23262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### getRoundingControlRegisters() {#a2d12771a48cc8b16535eeb9ae4ce94fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; X86TargetLowering::getRoundingControlRegisters ()</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1814 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 682 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### getScratchRegisters() {#a92816ba1d0a0f3eb57fd758e67f5f1a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg * X86TargetLowering::getScratchRegisters (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1813 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### getSqrtEstimate() {#a6dcc8a9a339f05f170eebe8a60c8a0f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::getSqrtEstimate (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, int Enabled, int &amp; RefinementSteps, bool &amp; UseOneConstNR, bool Reciprocal)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> rsqrt* to speed up sqrt calculations.</p>


<p>The minimum architected relative accuracy is 2^-12.</p>


<p>We need one Newton-Raphson step to have a good float result (24 bits of precision).</p>


<p>Declaration at line 1893 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 23208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### getTypeForExtReturn() {#acdc2d795c628469393213a614542a610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT X86TargetLowering::getTypeForExtReturn (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the type that should be used to zero or sign extend a zeroext/signext integer return value.</p>


<p>FIXME: Some C calling conventions require the return type to be promoted, but this is not true all the time, e.g. i1/i8/i16 on x86/x86_64. It is also not necessary for non-C calling conventions. The frontend should handle this and include all of the necessary information.</p>


<p>Declaration at line 1804 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 987 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### initializeSplitCSR() {#ac09bc33a0671e74f38c6c1f3654c0dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86TargetLowering::initializeSplitCSR (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Entry)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1795 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 60871 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### insertCopiesSplitCSR() {#aa60e5f2c24121347f67024637aa74405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86TargetLowering::insertCopiesSplitCSR (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Entry, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; Exits)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1796 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 60881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### IsEligibleForTailCallOptimization() {#a09efcfe9c3e80e9ff5c0e21887c4a542}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::IsEligibleForTailCallOptimization (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">TargetLowering::CallLoweringInfo</a> &amp; CLI, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; CCInfo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &gt; &amp; ArgLocs, bool IsCalleePopSRet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the call is eligible for tail call optimization.</p>


<p>Targets that want to do tail call optimization should implement this function.</p>


<p>Targets that want to do tail call optimization should implement this function. Note that the x86 backend does not check musttail calls for eligibility! The rest of x86 tail call lowering must be prepared to forward arguments of any type.</p>


<p>Declaration at line 1704 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2749 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### isFsqrtCheap() {#a20b0a79348cf4200832a334e418ae71f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isFsqrtCheap (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if replacement of SQRT with RSQRT should be disabled.</p>

<p>Declaration at line 1890 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 23190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### isUsedByReturnOnly() {#a9c52d2f566091bd09fa0971defd33b90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::isUsedByReturnOnly (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1800 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 951 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### LowerADDROFRETURNADDR() {#a232b0814c67b87d0a11dd4b5204c6fb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerADDROFRETURNADDR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1754 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 27900 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBlockAddress() {#ae28a3821944125ba0f7da1db935b96a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerBlockAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1729 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 18929 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBRCOND() {#a402c2742dfd1e03caf54874fccb73a32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerBRCOND (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1748 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 25298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerBUILD\_VECTOR() {#a44257daf4209aa06b3933d8f2567ce27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerBUILD_VECTOR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1721 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 8997 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCall() {#ab7daed1bc68b8961bb301f43ba08e617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerCall (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1783 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2000 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### LowerCallResult() {#aa4d17c5d956c0b8d5187b420ac95e036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerCallResult (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> InGlue, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals, uint32_t * RegMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower the result values of a call into the appropriate copies out of appropriate physical registers.</p>

<p>Declaration at line 1684 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 1101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### LowerConstantPool() {#abe3e093d027081956ab9551460bd0be2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerConstantPool (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1728 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 18878 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerDYNAMIC\_STACKALLOC() {#ae55b190c2d96b5b2f76f685adec30a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerDYNAMIC_STACKALLOC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1750 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 25423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerEH\_RETURN() {#a59390fd04333fa49fabbf4be6b59bede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerEH_RETURN (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1757 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 28005 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### lowerEH\_SJLJ\_LONGJMP() {#a81dd96f741e724d4719ce254aec6c361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::lowerEH_SJLJ_LONGJMP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1759 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 28049 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### lowerEH\_SJLJ\_SETJMP() {#a68e2568dd5d3fa88bd93886e0c3559da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::lowerEH_SJLJ_SETJMP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1758 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 28031 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### lowerEH\_SJLJ\_SETUP\_DISPATCH() {#a5fa628530d393e464070fe32d37a4ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::lowerEH_SJLJ_SETUP_DISPATCH (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1760 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 28056 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerExternalSymbol() {#a3a707f6075019fa15f6d3e0e4de732a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerExternalSymbol (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1732 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 18923 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerEXTRACT\_VECTOR\_ELT() {#a3d1b727cab043cd79cb6ea3e8184bd29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerEXTRACT_VECTOR_ELT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1723 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 18390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### lowerFaddFsub() {#a59bbfb435f70f941553758ad0774f2f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::lowerFaddFsub (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Depending on uarch and/or optimizing for size, we might prefer to use a vector operation in place of the typical scalar operation.</p>

<p>Declaration at line 1773 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 22181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFormalArguments() {#a4daa2ca582e132e3a08eca54c5353179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerFormalArguments (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1779 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 1678 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### LowerFP\_EXTEND() {#aa137c76efed16ed8728cbe97e30d97b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerFP_EXTEND (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1774 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 21812 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_ROUND() {#afff4d2f3a2973b8a8d5f1b60285dbe06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerFP_ROUND (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1775 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 21930 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_TO\_BF16() {#a72125c02ec314b74c085a97cf61f3a52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerFP_TO_BF16 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1776 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 22083 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_TO\_INT() {#a09c8f29903cedf48e5d2b3007353450e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerFP_TO_INT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1742 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 21237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFP\_TO\_INT\_SAT() {#a3468e59fc36fcb47df12edd22fd36955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerFP_TO_INT_SAT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1743 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 21662 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFRAME\_TO\_ARGS\_OFFSET() {#a341ce13c6b9f4243fa08921554258622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerFRAME_TO_ARGS_OFFSET (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1756 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 27979 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFRAMEADDR() {#a1f0c9dd1c48cacdfa821f7ab49fa96a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerFRAMEADDR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1755 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 27906 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGC\_TRANSITION() {#a33672ebdcfb03f655b2a4148f144df5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerGC_TRANSITION (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1771 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 33034 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGET\_FPENV\_MEM() {#a1321d92ff60dd32f0671a9546e44c965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerGET_FPENV_MEM (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1764 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 28394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGET\_ROUNDING() {#a430ebeef6ceaa5a9d0a29253f14018e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerGET_ROUNDING (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1762 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 28212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalAddress() {#a015553534b38343f00c8c096b90696cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerGlobalAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1730 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 19027 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalOrExternal() {#a3635663c936a6745c4ea8315035c69ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerGlobalOrExternal (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool ForCall)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates target global address or external symbol nodes for calls or other uses.</p>

<p>Declaration at line 1736 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 18952 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerGlobalTLSAddress() {#a329864512ef9e9a1400cb96630207700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerGlobalTLSAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1731 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 19219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### lowerIdempotentRMWIntoFencedLoad() {#acb51736698ae53a8d882e21925b81954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadInst * X86TargetLowering::lowerIdempotentRMWIntoFencedLoad (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * RMWI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>On some platforms, an AtomicRMW that never actually modifies the value (such as fetch_add of 0) can be turned into a fence followed by an atomic load.</p>


<p>This may sound useless, but it makes it possible for the processor to keep the cacheline shared, dramatically improving performance. And such idempotent RMWs are useful for implementing some kinds of locks, see for example (justification + benchmarks): <a href="http://www.hpl.hp.com/techreports/2012/HPL-2012-68.pdf">http://www.hpl.hp.com/techreports/2012/HPL-2012-68.pdf</a> This method tries doing that transformation, returning the atomic load if it succeeds, and nullptr otherwise. If shouldExpandAtomicLoadInIR returns true on that load, it will undergo another round of expansion.</p>


<p>Declaration at line 1828 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 31750 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINIT\_TRAMPOLINE() {#a6ace38cbafb4466803b4fa12a484c221}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerINIT_TRAMPOLINE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1761 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 28067 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINSERT\_VECTOR\_ELT() {#a7fa248020f2f17136638e64bf8042dd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerINSERT_VECTOR_ELT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 18571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerINTRINSIC\_WO\_CHAIN() {#a1a05cd9a29392791cee47ce7d448a6c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerINTRINSIC_WO_CHAIN (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1772 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 25965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerJumpTable() {#a42dc222f2d796d56b8f6fb8073a97328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerJumpTable (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1749 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 18901 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerLRINT\_LLRINT() {#a90321e70801009eda27df4bfdf10f71c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerLRINT_LLRINT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1744 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 21597 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerMemArgument() {#adf70fe24896195cee150786395a12ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerMemArgument (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; ArgInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> &amp; MFI, unsigned i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1690 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 1301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### LowerMemOpCallTo() {#a7c2a9aeb9cbe31170365402b5a1ed6ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerMemOpCallTo (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> StackPtr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Arg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags, bool isByval)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1695 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 1931 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### LowerRESET\_FPENV() {#a0056dc4a32bf331ac24d9bcb1ed36bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerRESET_FPENV (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1766 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 28473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerReturn() {#ab9af01afeebab7c828e2595aece7ce85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerReturn (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1786 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### LowerRETURNADDR() {#a97f484a19478ba695318ca846352b6b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerRETURNADDR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1753 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 27873 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSELECT() {#a406e66f77d02c54200c56d18ad7d4606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerSELECT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1747 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 24587 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSET\_FPENV\_MEM() {#abb7803ce3754aa9fddfd53405690e74d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerSET_FPENV_MEM (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1765 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 28461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSET\_ROUNDING() {#adff19ec2b5ab688b726ee17e4d714138}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerSET_ROUNDING (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1763 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 28276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSETCC() {#a23f125e48b475888d9580da2b3241eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerSETCC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1745 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 24245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSETCCCARRY() {#ab0e4d87271f1745ef032aed83dabe510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerSETCCCARRY (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1746 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 24344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerSINT\_TO\_FP() {#ae1bbb7ab919ec0c381a0b89d12fa38f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerSINT_TO_FP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1739 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 19718 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerTRUNCATE() {#a40d2cf7f935e9873a736eb37132de88d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerTRUNCATE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1741 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 21077 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerUINT\_TO\_FP() {#a6d2b30b5592c53a9de885da5a90d154d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerUINT_TO_FP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1740 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 20217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVAARG() {#a6df5a54087b0164786c1b3f1a121cffd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerVAARG (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1752 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 25567 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVASTART() {#a9eb658067d017bafc5ad9b67e539ae8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerVASTART (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1751 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 25510 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerVSELECT() {#a5b715117504cc9cf14e16cecf281e27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerVSELECT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1722 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 18146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerWin64\_FP\_TO\_INT128() {#addd8b8b94aa125905688044a6dd2d478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerWin64_FP_TO_INT128 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1768 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 29687 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerWin64\_i128OP() {#a8fe5dd0286a144930329f8b04833f7ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerWin64_i128OP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1767 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 29623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LowerWin64\_INT128\_TO\_FP() {#a7c4bfd42d245eb41c76317518a497184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LowerWin64_INT128_TO_FP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1770 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 29721 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### LRINT\_LLRINTHelper() {#a385ab5f55d91b6d6c92a5d2ec8f737e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86TargetLowering::LRINT_LLRINTHelper (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1719 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 21616 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### mayBeEmittedAsTailCall() {#ab12e8b204f28c788c70b7d2c93521e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::mayBeEmittedAsTailCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1802 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 1289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### needsCmpXchgNb() {#a02ba0fbeaccacb7a8887b62810e0f711}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::needsCmpXchgNb (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * MemType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the operand type is exactly twice the native width, and the corresponding cmpxchg8b or cmpxchg16b instruction is available.</p>


<p>Used to know whether to use cmpxchg8/16b when expanding atomic operations (otherwise we leave them alone to become __sync_fetch_and_... calls).</p>


<p>Declaration at line 1830 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 31295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### optimizeFMulOrFDivAsShiftAddBitcast() {#a6b4d043dafc9dc7465f2f12700665848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86TargetLowering::optimizeFMulOrFDivAsShiftAddBitcast (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> FPConst, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> IntPow2)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1886 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 23171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### SetupEntryBlockForSjLj() {#a36ac13a178bdda5a9a97633c6c853990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86TargetLowering::SetupEntryBlockForSjLj (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DispatchBB, int FI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1832 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 37042 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldExpandAtomicLoadInIR() {#a553c0018101813c15a59063ce7f36bf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AtomicExpansionKind X86TargetLowering::shouldExpandAtomicLoadInIR (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 1817 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 31327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldExpandAtomicRMWInIR() {#ac53bbecb27c9603445acf1e3965432f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AtomicExpansionKind X86TargetLowering::shouldExpandAtomicRMWInIR (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * RMW)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1821 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 31702 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldExpandAtomicStoreInIR() {#abd31564b7faa43985a88235bb323eae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLoweringBase::AtomicExpansionKind X86TargetLowering::shouldExpandAtomicStoreInIR (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 1819 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 31307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### shouldExpandLogicAtomicRMWInIR() {#a382bb57dc50ee6687a4afeff9bf94278}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AtomicExpansionKind X86TargetLowering::shouldExpandLogicAtomicRMWInIR (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * AI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1823 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 31420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### supportSplitCSR() {#a32e781d6b9f2dbd7f4d31edfa19ee795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86TargetLowering::supportSplitCSR (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Definition at line 1791 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LegalFPImmediates {#a628ac19a4ddc4a22d94fb57a6a18f700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;APFloat&gt; llvm::X86TargetLowering::LegalFPImmediates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of legal FP immediates.</p>

<p>Definition at line 1676 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>

</div>
</div>

### Subtarget {#abcb67b471446e52c5d56aa87f08f28ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86Subtarget&amp; llvm::X86TargetLowering::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep a reference to the <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> around so that we can make the right decision when generating code for different targets.</p>

<p>Definition at line 1673 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp">X86InterleavedAccess.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
