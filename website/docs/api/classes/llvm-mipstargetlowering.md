---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mipstargetlowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MipsTargetLowering` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MipsTargetLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">Target/Mips/MipsISelLowering.h</a>"
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mips16targetlowering">Mips16TargetLowering</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mipssetargetlowering">MipsSETargetLowering</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4baae7363a2379cc1714f47c6f0404aa">MipsTargetLowering</a> (const MipsTargetMachine &amp;TM, const MipsSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40e9166415077d71f840a81b21a1313a">createFastISel</a> (FunctionLoweringInfo &amp;funcInfo, const TargetLibraryInfo *libInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createFastISel - This method returns a target specific <a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> object, or null if the target does not support "fast" ISel. <a href="#a40e9166415077d71f840a81b21a1313a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29a845eb11b29e4d97b09c3734ff0c27">getScalarShiftAmountTy</a> (const DataLayout &amp;, EVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type to use for a scalar shift opcode, given the shifted amount type. <a href="#a29a845eb11b29e4d97b09c3734ff0c27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a940aa5c3b3202d4d987e2a999450f240">getTypeForExtReturn</a> (LLVMContext &amp;Context, EVT VT, ISD::NodeType) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type that should be used to zero or sign extend a zeroext/signext integer return value. <a href="#a940aa5c3b3202d4d987e2a999450f240">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f401d091072000857a41ef619f1342a">isCheapToSpeculateCttz</a> (Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is cheap to speculate a call to intrinsic cttz. <a href="#a9f401d091072000857a41ef619f1342a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98315677ba77ffbfd8c7c6f13a05a890">isCheapToSpeculateCtlz</a> (Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is cheap to speculate a call to intrinsic ctlz. <a href="#a98315677ba77ffbfd8c7c6f13a05a890">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08fa631974fcb44a77c69f10fea8f089">hasBitTest</a> (SDValue X, SDValue Y) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target has a bit-test instruction: (X &amp; (1 &lt;&lt; Y)) ==/!= 0 This knowledge can be used to prevent breaking the pattern, or creating it if it could be recognized. <a href="#a08fa631974fcb44a77c69f10fea8f089">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3cf604f0da074af7ca64f80e5d753ea">shouldFoldConstantShiftPairToMask</a> (const SDNode *N, CombineLevel Level) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to fold a pair of shifts into a mask. <a href="#aa3cf604f0da074af7ca64f80e5d753ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04c394dca43220a262f8a67825cd4fb5">getRegisterTypeForCallingConv</a> (LLVMContext &amp;Context, CallingConv::ID CC, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register type for a given <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a>, ensuring vectors are treated as a series of gpr sized integers. <a href="#a04c394dca43220a262f8a67825cd4fb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d161cb9d6e4a3ef9c4af88bef2d3ab4">getNumRegistersForCallingConv</a> (LLVMContext &amp;Context, CallingConv::ID CC, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of registers for a given <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a>, ensuring vectors are treated as a series of gpr sized integers. <a href="#a7d161cb9d6e4a3ef9c4af88bef2d3ab4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21321ab7669a253fc0fe731602fe5695">getVectorTypeBreakdownForCallingConv</a> (LLVMContext &amp;Context, CallingConv::ID CC, EVT VT, EVT &amp;IntermediateVT, unsigned &amp;NumIntermediates, MVT &amp;RegisterVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Break down vectors to the correct number of gpr sized integers. <a href="#a21321ab7669a253fc0fe731602fe5695">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc893c905f006e49df4253ec300b3aee">getABIAlignmentForCallingConv</a> (Type *ArgTy, const DataLayout &amp;DL) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the correct alignment for the current calling convention. <a href="#afc893c905f006e49df4253ec300b3aee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaa188e6d5cd8a3dd6989c226a8ead63">getExtendForAtomicOps</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the platform's atomic operations are extended (ZERO_EXTEND, SIGN_EXTEND, or ANY_EXTEND). <a href="#acaa188e6d5cd8a3dd6989c226a8ead63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9935c00eaf6557ca6bfdb6ced9c377f6">LowerOperation</a> (SDValue Op, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerOperation - Provide custom lowering hooks for some operations. <a href="#a9935c00eaf6557ca6bfdb6ced9c377f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73afb942bbe9f13347f351f28ac2fe2c">ReplaceNodeResults</a> (SDNode *N, SmallVectorImpl&lt; SDValue &gt; &amp;Results, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReplaceNodeResults - Replace the results of node with an illegal result type with new values built out of custom code. <a href="#a73afb942bbe9f13347f351f28ac2fe2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a243d4ca8bf484d9d5ef47a9e8d2ad364">getTargetNodeName</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getTargetNodeName - This method returns the name of a target specific <a href="#a243d4ca8bf484d9d5ef47a9e8d2ad364">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38b88641f5f9abe6b18b921f0eaceb93">getSetCCResultType</a> (const DataLayout &amp;DL, LLVMContext &amp;Context, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSetCCResultType - get the <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">ISD::SETCC</a> result <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a> <a href="#a38b88641f5f9abe6b18b921f0eaceb93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b3ae019ac2faf4a810a9b8fa80b747d">PerformDAGCombine</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be invoked for all target nodes and for any target-independent nodes that the target has registered with invoke it for. <a href="#a6b3ae019ac2faf4a810a9b8fa80b747d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74ceed526d62127854c54efe9e7f6f06">EmitInstrWithCustomInserter</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'usesCustomInserter' flag. <a href="#a74ceed526d62127854c54efe9e7f6f06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c0a6f5ad327c20349f2a2e0a5845b3e">AdjustInstrPostInstrSelection</a> (MachineInstr &amp;MI, SDNode *Node) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'hasPostISelHook' flag. <a href="#a8c0a6f5ad327c20349f2a2e0a5845b3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad11c85a64a9aca0f5035553171364591">HandleByVal</a> (CCState *, unsigned &amp;, Align) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-specific cleanup for formal ByVal parameters. <a href="#ad11c85a64a9aca0f5035553171364591">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21a0e970e98d8f88cee991fe790e1fe9">getRegisterByName</a> (const char *RegName, LLT VT, const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the name passed in. <a href="#a21a0e970e98d8f88cee991fe790e1fe9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a190d897779db77a8f8d471364aeb2392">getExceptionPointerRegister</a> (const Constant *PersonalityFn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register, this returns the register that receives the exception address on entry to an EH pad. <a href="#a190d897779db77a8f8d471364aeb2392">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0317246747d495047ab935df5c027f1e">getExceptionSelectorRegister</a> (const Constant *PersonalityFn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register, this returns the register that receives the exception typeid on entry to a landing pad. <a href="#a0317246747d495047ab935df5c027f1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac2de0d3f585d618ab477a022e027da0">softPromoteHalfType</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2e5c3e98e51697955be49b39bb42c02">isJumpTableRelative</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ad01ac80ec7e6f5def1ebd899646e2e">CCAssignFnForCall</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c49004470ed8399a7c6362e580843bd">CCAssignFnForReturn</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeba37067209bf3e8f04114e8918b499">getGlobalReg</a> (SelectionDAG &amp;DAG, EVT Ty) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa5e1d1788ef2fee23b0f9542eda5c1b6">getAddrLocal</a> (NodeTy *N, const SDLoc &amp;DL, EVT Ty, SelectionDAG &amp;DAG, bool IsN32OrN64) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3f5a81ea3f95a4119d6c0a5b5b2f5c49">getAddrGlobal</a> (NodeTy *N, const SDLoc &amp;DL, EVT Ty, SelectionDAG &amp;DAG, unsigned Flag, SDValue Chain, const MachinePointerInfo &amp;PtrInfo) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5ccaa648716b2c4c8e0687f36e6c9fa2">getAddrGlobalLargeGOT</a> (NodeTy *N, const SDLoc &amp;DL, EVT Ty, SelectionDAG &amp;DAG, unsigned HiFlag, unsigned LoFlag, SDValue Chain, const MachinePointerInfo &amp;PtrInfo) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a80d7b6f8225e03c0e2b80249cca5bd85">getAddrNonPIC</a> (NodeTy *N, const SDLoc &amp;DL, EVT Ty, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a272d1bf276d97a177b681f465129fe56">getAddrNonPICSym64</a> (NodeTy *N, const SDLoc &amp;DL, EVT Ty, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c44aab19fd4cd86f04d2dcc45062b25">getAddrGPRel</a> (NodeTy *N, const SDLoc &amp;DL, EVT Ty, SelectionDAG &amp;DAG, bool IsN64) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a77a87423f2a96adea15f67141ced40bc">getDllimportSymbol</a> (NodeTy *N, const SDLoc &amp;DL, EVT Ty, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f41eccd0b382684fdb89443c0c54a99">getDllimportVariable</a> (NodeTy *N, const SDLoc &amp;DL, EVT Ty, SelectionDAG &amp;DAG, SDValue Chain, const MachinePointerInfo &amp;PtrInfo) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93bebb4498805f11e17d91d7cde35511">getOpndList</a> (SmallVectorImpl&lt; SDValue &gt; &amp;Ops, std::deque&lt; std::pair&lt; unsigned, SDValue &gt; &gt; &amp;RegsToPass, bool IsPICCall, bool GlobalOrExternal, bool InternalLinkage, bool IsCallReloc, CallLoweringInfo &amp;CLI, SDValue Callee, SDValue Chain) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function fills Ops, which is the list of operands that will later be used when a function call node is created. <a href="#a93bebb4498805f11e17d91d7cde35511">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8cb1a782bf62a812f68aac1af065a5e">lowerLOAD</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8308bacd5a1d10fdc7ac14c784f6ce0d">lowerSTORE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a190ff1c7002157e800c2d6d06ad01d4c">getTargetNode</a> (GlobalAddressSDNode *N, EVT Ty, SelectionDAG &amp;DAG, unsigned Flag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a008841a3e896bba955074eaa45aa1485">getTargetNode</a> (ExternalSymbolSDNode *N, EVT Ty, SelectionDAG &amp;DAG, unsigned Flag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a323b486561049b4496528b9787e62b09">getTargetNode</a> (BlockAddressSDNode *N, EVT Ty, SelectionDAG &amp;DAG, unsigned Flag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35654591798e4f52aef04e1b21c673d1">getTargetNode</a> (JumpTableSDNode *N, EVT Ty, SelectionDAG &amp;DAG, unsigned Flag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eb06af1b5c6083ad1c1ff88ec404fc3">getTargetNode</a> (ConstantPoolSDNode *N, EVT Ty, SelectionDAG &amp;DAG, unsigned Flag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a097af76c91a02317954db69ff85ac450">LowerCallResult</a> (SDValue Chain, SDValue InGlue, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals, TargetLowering::CallLoweringInfo &amp;CLI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerCallResult - Lower the result values of a call into the appropriate copies out of appropriate physical registers. <a href="#a097af76c91a02317954db69ff85ac450">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a101d3e63c145bb584f825a7f6e20bc7e">lowerBRCOND</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd0cdba0cf5c9a3edb3e1a42ae5a8f2b">lowerConstantPool</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacb67084205b084c1904b85407044c1b">lowerGlobalAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0568066176aeb7f626a9b6d595bfd4a">lowerBlockAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae989f979e281de2d1ce794a7db0f3574">lowerGlobalTLSAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80b20c2ac7dfb1f706d9e6350bc0c7c0">lowerJumpTable</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad51a9456de46adf2c041aabbee1e5abe">lowerSELECT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34631207e79bcf70618503b9e932e7a2">lowerSETCC</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af91e8e701813d016fc91fe339e0e2f8a">lowerVASTART</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88b70d75732ea507820187fc33d6ec0f">lowerVAARG</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a122b415151a9867baa764153030c1944">lowerFCOPYSIGN</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac43cebf6f25637fc02040ac94d2dcc9b">lowerFABS</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fc1eed215601a3aeb0c01ed73ed18bf">lowerFABS32</a> (SDValue Op, SelectionDAG &amp;DAG, bool HasExtractInsert) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc514bde3a19040254888a42c2adb689">lowerFABS64</a> (SDValue Op, SelectionDAG &amp;DAG, bool HasExtractInsert) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad85246c0e1ca80e3528cebf1b4ceef5d">lowerFCANONICALIZE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8fcbca915577e5fdccc5e3b2899b3f4">lowerFRAMEADDR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ccc12dd3fcad5abd17242fb919f04f">lowerRETURNADDR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82dabeb446695cceec86ded85489ef54">lowerEH_RETURN</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acda57021924c317b1230c247c8fdf838">lowerATOMIC_FENCE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2870362f089a6812c037ef8a0e93719d">lowerShiftLeftParts</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc4886ecf9039348b4477708119d42d6">lowerShiftRightParts</a> (SDValue Op, SelectionDAG &amp;DAG, bool IsSRA) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fa6398dd7c8e33caa425812d5086097">lowerEH_DWARF_CFA</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac96022972ee30e174b7b84d1ecb9fd6c">lowerFP_TO_SINT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8b8c4ecaae686698ad0dcae3eb89091">isEligibleForTailCallOptimization</a> (const CCState &amp;CCInfo, unsigned NextStackOffset, const MipsFunctionInfo &amp;FI) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isEligibleForTailCallOptimization - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the call is eligible for tail call optimization. <a href="#ac8b8c4ecaae686698ad0dcae3eb89091">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d35731f1755e8975d350b86cc55c82e">copyByValRegs</a> (SDValue Chain, const SDLoc &amp;DL, std::vector&lt; SDValue &gt; &amp;OutChains, SelectionDAG &amp;DAG, const ISD::ArgFlagsTy &amp;Flags, SmallVectorImpl&lt; SDValue &gt; &amp;InVals, const Argument *FuncArg, unsigned FirstReg, unsigned LastReg, const CCValAssign &amp;VA, MipsCCState &amp;State) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>copyByValArg - Copy argument registers which were used to pass a byval argument to the stack. <a href="#a7d35731f1755e8975d350b86cc55c82e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3e77fad6cc5836b531916bfa5499b2">passByValArg</a> (SDValue Chain, const SDLoc &amp;DL, std::deque&lt; std::pair&lt; unsigned, SDValue &gt; &gt; &amp;RegsToPass, SmallVectorImpl&lt; SDValue &gt; &amp;MemOpChains, SDValue StackPtr, MachineFrameInfo &amp;MFI, SelectionDAG &amp;DAG, SDValue Arg, unsigned FirstReg, unsigned LastReg, const ISD::ArgFlagsTy &amp;Flags, bool isLittle, const CCValAssign &amp;VA) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>passByValArg - <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> a byval argument in registers or on stack. <a href="#a0c3e77fad6cc5836b531916bfa5499b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2484562d148282c81ad548b53d66e008">writeVarArgRegs</a> (std::vector&lt; SDValue &gt; &amp;OutChains, SDValue Chain, const SDLoc &amp;DL, SelectionDAG &amp;DAG, CCState &amp;State) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>writeVarArgRegs - Write variable function arguments passed in registers to the stack. <a href="#a2484562d148282c81ad548b53d66e008">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad59f1fb8aea56b06c201bf22955e7b6f">LowerFormalArguments</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerFormalArguments - transform physical registers into virtual registers and generate load operations for arguments places on the stack. <a href="#ad59f1fb8aea56b06c201bf22955e7b6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52950e48327f2eb0db8be135eeaec503">passArgOnStack</a> (SDValue StackPtr, unsigned Offset, SDValue Chain, SDValue Arg, const SDLoc &amp;DL, bool IsTailCall, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee6422b18832dd0c56fe4ef182d9efc">LowerCall</a> (TargetLowering::CallLoweringInfo &amp;CLI, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerCall - functions arguments are copied from virtual regs to (physical regs)/(stack frame), CALLSEQ_START and CALLSEQ_END are emitted. <a href="#a7ee6422b18832dd0c56fe4ef182d9efc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64e7c917683a2ed19022a238137a3620">CanLowerReturn</a> (CallingConv::ID CallConv, MachineFunction &amp;MF, bool isVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, LLVMContext &amp;Context, const Type *RetTy) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook should be implemented to check whether the return values described by the Outs array can fit into the return registers. <a href="#a64e7c917683a2ed19022a238137a3620">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae12d5116aade84926053b4795e0c3e32">LowerReturn</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; SDValue &gt; &amp;OutVals, const SDLoc &amp;dl, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower outgoing return values, described by the Outs array, into the specified DAG. <a href="#ae12d5116aade84926053b4795e0c3e32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7cde7bfcf10fe6da23cbb3136452bf2">LowerInterruptReturn</a> (SmallVectorImpl&lt; SDValue &gt; &amp;RetOps, const SDLoc &amp;DL, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad40b4195a9ceb99a3d864a08233b0585">shouldSignExtendTypeInLibCall</a> (Type *Ty, bool IsSigned) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if arguments should be sign-extended in lib calls. <a href="#ad40b4195a9ceb99a3d864a08233b0585">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116">ConstraintType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a720b7bbf95d66b8862575f61399450b9">getConstraintType</a> (StringRef Constraint) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getConstraintType - Given a constraint letter, return the type of constraint it is for this target. <a href="#a720b7bbf95d66b8862575f61399450b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abc">ConstraintWeight</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a0e623707f01a9ceb5648f06867f714">getSingleConstraintMatchWeight</a> (AsmOperandInfo &amp;info, const char *constraint) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine constraint string and operand type and determine a weight value. <a href="#a4a0e623707f01a9ceb5648f06867f714">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1efdca10ae75ba22213e0d79fdf9691">parseRegForInlineAsmConstraint</a> (StringRef C, MVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function parses registers that appear in inline-asm constraints. <a href="#af1efdca10ae75ba22213e0d79fdf9691">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefef67c9936744e3f53f73d33499f4b0">getRegForInlineAsmConstraint</a> (const TargetRegisterInfo *TRI, StringRef Constraint, MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a register class constraint, like 'r', if this corresponds directly to an LLVM register class, return a register of 0 and the register class pointer. <a href="#aefef67c9936744e3f53f73d33499f4b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add0474e37f6a610d7f282a2c4bbedbb5">LowerAsmOperandForConstraint</a> (SDValue Op, StringRef Constraint, std::vector&lt; SDValue &gt; &amp;Ops, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerAsmOperandForConstraint - Lower the specified operand into the Ops vector. <a href="#add0474e37f6a610d7f282a2c4bbedbb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a225cb756d475ba1088031045a3f989f4">getInlineAsmMemConstraint</a> (StringRef ConstraintCode) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f9d40da643ffa6664be940bce42b5f3">isLegalAddressingMode</a> (const DataLayout &amp;DL, const AddrMode &amp;AM, Type *Ty, unsigned AS, Instruction *I=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the addressing mode represented by AM is legal for this target, for a load/store of the specified type. <a href="#a2f9d40da643ffa6664be940bce42b5f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeff62af9eec9dfce6aa927b02a2690df">isOffsetFoldingLegal</a> (const GlobalAddressSDNode *GA) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if folding a constant offset with the given GlobalAddress is legal. <a href="#aeff62af9eec9dfce6aa927b02a2690df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ab379de66d5f6e8890abd28ba8d055">getOptimalMemOpType</a> (const MemOp &amp;Op, const AttributeList &amp;FuncAttributes) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the target specific optimal type for load and store operations as a result of memset, memcpy, and memmove lowering. <a href="#ae4ab379de66d5f6e8890abd28ba8d055">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada8183a1d27062f3a53c2c433951795a">isFPImmLegal</a> (const APFloat &amp;Imm, EVT VT, bool ForCodeSize) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isFPImmLegal - Returns true if the target can instruction select the specified FP immediate natively. <a href="#ada8183a1d27062f3a53c2c433951795a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64e17fb5f0ae39d7eda4f807d3c2321">getJumpTableEncoding</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the entry encoding for a jump table in the current function. <a href="#ae64e17fb5f0ae39d7eda4f807d3c2321">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9e5d3c4fc647bb41428783017e1a26c">useSoftFloat</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ee9fc4da03c3bd29463accad6e4dad">shouldInsertFencesForAtomic</a> (const Instruction *I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether <a href="/web-llvm/docs/api/classes/llvm/atomicexpandpass">AtomicExpandPass</a> should automatically insert fences and reduce ordering for this atomic. <a href="#a26ee9fc4da03c3bd29463accad6e4dad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cc804986d4a1aa76a1e3a3106692cf5">emitSignExtendToI32InReg</a> (MachineInstr &amp;MI, MachineBasicBlock *BB, unsigned Size, unsigned DstReg, unsigned SrcRec) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a sign-extension using sll/sra, seb, or seh appropriately. <a href="#a4cc804986d4a1aa76a1e3a3106692cf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac490fb121a9b194dc482e4fc18fa2a66">emitAtomicBinary</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a870bcb23daa9a9b1abf406b257bc7a73">emitAtomicBinaryPartword</a> (MachineInstr &amp;MI, MachineBasicBlock *BB, unsigned Size) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a805c71896a605b8d8387fc9092f767da">emitAtomicCmpSwap</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4964c32f9b6a92d7bd0061b916a6148">emitAtomicCmpSwapPartword</a> (MachineInstr &amp;MI, MachineBasicBlock *BB, unsigned Size) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae06f2127bbee73ea75e0d413190378c5">emitSEL_D</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33b05f483472ba0342ec19e788bd7b58">emitPseudoSELECT</a> (MachineInstr &amp;MI, MachineBasicBlock *BB, bool isFPCmp, unsigned Opc) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae36fef866acebc5d2297f2d90fde30bc">emitPseudoD_SELECT</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52a234f0c67e0124704ce8b3d7a4e344">emitLDR_W</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8323f0a41966ef04ff3b6c540b7ff1ac">emitLDR_D</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbde5e9b5a74ed72bad4128ea4b3ce1a">emitSTR_W</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a735d0623658a25e346e75751ed431473">emitSTR_D</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget">MipsSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo">MipsABIInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a535e0e577653c46309de47d558fed337">ABI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd437d4d184e4fdf681b3afa41d18b22">isMicroMips</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering">MipsTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15f65769a3b8f609efbdc7eba633c1cc">create</a> (const MipsTargetMachine &amp;TM, const MipsSubtarget &amp;STI)</td>
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


<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MipsTargetLowering() {#a4baae7363a2379cc1714f47c6f0404aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsTargetLowering::MipsTargetLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine">MipsTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget">MipsSubtarget</a> &amp; STI)</td>
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



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="#a535e0e577653c46309de47d558fed337">ABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab8c490e0623b6a0e2c12c12e0d924abe">llvm::TargetLoweringBase::AddPromotedToType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af23301e60475124fd80a2cb51f6ba863">llvm::ISD::AssertZext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c">llvm::ISD::CTLZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a991d07d163bd4d9984cf1ef36e92c214">llvm::ISD::CTPOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6da41a113af0909470baea7486b3386b">llvm::ISD::CTTZ</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa3441acf8576e4bbf48e9bd73ca3c0d8c">llvm::TargetLoweringBase::Custom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abad932e63381a4671b5db19a3404c82e">llvm::ISD::EH_DWARF_CFA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4edf35e2383003ff20057e5a45012a55">llvm::ISD::EH_RETURN</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa4b85349547c5b6126817e10152007931">llvm::TargetLoweringBase::Expand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">llvm::ISD::EXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a74a787311d3ab9a17ee0acde7b6a6b14">llvm::ISD::FCANONICALIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeffc3319657e213a530ce583603f7221">llvm::ISD::FCOPYSIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#af5e14144ddcc0caf0b4c461f9bc687d1">llvm::MVT::fp_fixedlen_vector_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#adfa86eda5d29b10227c46b4d8f071148">llvm::MVT::fp_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdd7bbb76dac7962dda6e116e33699da">llvm::ISD::FREM</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7b339f69bc3995d23399a85f81af6018">llvm::MVT::integer_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a76b6d3008e806ea613323ff316ef72c3">llvm::ISD::IS_FPCLASS</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#adde2b3c4de4c4ded2b80ff32f1020b9b">llvm::MVT::isValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0c70100db6ddc0b37b56feb242145cf4">llvm::ISD::JumpTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aefbee33131c130f8f691c9a482f5fc40">llvm::TargetLoweringBase::MaxStoresPerMemcpy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aaba91ac521e4f01f57413216273fd7b7f">llvm::TargetLoweringBase::Promote</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715">llvm::ISD::ROTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a874f66e1efe5be79552bbe7ee3121a">llvm::ISD::SDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6b928e5a6718acab4fa0030ce9198e8a">llvm::TargetLoweringBase::setBooleanContents</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0662d63e058816bf77a5b8f35331bd9d">llvm::TargetLoweringBase::setBooleanVectorContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad1d4d71bf37fea6a3170f27438d41e6d">llvm::TargetLoweringBase::setLoadExtAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4df001a3c611cc8b423ca0e54560210f">llvm::TargetLoweringBase::setMaxAtomicSizeInBitsSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6566d8c65c03ad2f7b18ed08f0e7f208">llvm::TargetLoweringBase::setMinFunctionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a2544bef91bdf3e85c561e59a0e662292">llvm::TargetLoweringBase::setMinStackArgumentAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a07c0c67913bb543fc45ce9ef65ef260a">llvm::TargetLoweringBase::setOperationAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab8a44fb1f49bcfbed806fef69301a67a">llvm::TargetLoweringBase::setStackPointerRegisterToSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac87dc82fa9f824a797198e7b0e16141d">llvm::TargetLoweringBase::setTargetDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa243085e56636cc454143f916686c190">llvm::TargetLoweringBase::setTruncStoreAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aaa96f111a59a7a2e7f9c689b344543df">llvm::TargetLowering::TargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a257ffa49107e2db978e8a6e2688ada">llvm::ISD::UDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28">llvm::ISD::UREM</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a695a19c9c3ae14638be151add82755cb">llvm::TargetLoweringBase::ZeroOrNegativeOneBooleanContent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a0e2d72cfdcc49d2d189f440b3cc31dff">llvm::TargetLoweringBase::ZeroOrOneBooleanContent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mips16targetlowering/#a97b896b6b94b563138613746e46e053e">llvm::Mips16TargetLowering::Mips16TargetLowering</a> and <a href="/web-llvm/docs/api/classes/llvm/mipssetargetlowering/#ae4a45998b3e29ffba3a1281d59f5fd44">llvm::MipsSETargetLowering::MipsSETargetLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AdjustInstrPostInstrSelection() {#a8c0a6f5ad327c20349f2a2e0a5845b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetLowering::AdjustInstrPostInstrSelection (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 3188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a081ab7d53b85dfd7a2f8609689147393">llvm::MachineOperand::CreateMCSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a9578328a1d072a99ad4322f34e52fa12">EmitJalrReloc</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aa8ab0804ddb40450da6549e1943817a2">llvm::TargetLowering::isPositionIndependent</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771fa1ad85da6e7dae2e1d6b2e9878a76d56f">llvm::MipsII::MO_JALR</a> and <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a>.</p>

</div>
</div>

### CCAssignFnForCall() {#a7ad01ac80ec7e6f5def1ebd899646e2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCAssignFn * MipsTargetLowering::CCAssignFnForCall ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 3101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### CCAssignFnForReturn() {#a6c49004470ed8399a7c6362e580843bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCAssignFn * MipsTargetLowering::CCAssignFnForReturn ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 3105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### createFastISel() {#a40e9166415077d71f840a81b21a1313a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastISel * MipsTargetLowering::createFastISel (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; funcInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * libInfo)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a7236509cbb7aa08b2768ca2215c72d8a">llvm::Mips::createFastISel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#ab26d50483184808463759bea1da917f8">llvm::TargetOptions::EnableFastISel</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#ac9287d39f216ac61b351d95a4f7e3df3">llvm::FunctionLoweringInfo::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a> and <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a>.</p>

</div>
</div>

### EmitInstrWithCustomInserter() {#a74ceed526d62127854c54efe9e7f6f06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MipsTargetLowering::EmitInstrWithCustomInserter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 1361 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a75f3e392bd9cff57dcd444d521d7fd94">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mips16targetlowering/#a3de3b06df114ac07ac0f5e9c14fe77da">llvm::Mips16TargetLowering::EmitInstrWithCustomInserter</a> and <a href="/web-llvm/docs/api/classes/llvm/mipssetargetlowering/#a9c7cbca89501bcb4073c6f41f38afeeb">llvm::MipsSETargetLowering::EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### getABIAlignmentForCallingConv() {#afc893c905f006e49df4253ec300b3aee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MipsTargetLowering::getABIAlignmentForCallingConv (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ArgTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Return the correct alignment for the current calling convention.</p>

<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>.</p>

</div>
</div>

### getExceptionPointerRegister() {#a190d897779db77a8f8d471364aeb2392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::MipsTargetLowering::getExceptionPointerRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PersonalityFn)</td>
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

<p>If a physical register, this returns the register that receives the exception address on entry to an EH pad.</p>

<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>Reference <a href="#a535e0e577653c46309de47d558fed337">ABI</a>.</p>

</div>
</div>

### getExceptionSelectorRegister() {#a0317246747d495047ab935df5c027f1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::MipsTargetLowering::getExceptionSelectorRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PersonalityFn)</td>
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

<p>If a physical register, this returns the register that receives the exception typeid on entry to a landing pad.</p>

<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>Reference <a href="#a535e0e577653c46309de47d558fed337">ABI</a>.</p>

</div>
</div>

### getExtendForAtomicOps() {#acaa188e6d5cd8a3dd6989c226a8ead63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::NodeType llvm::MipsTargetLowering::getExtendForAtomicOps ()</td>
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

<p>Returns how the platform's atomic operations are extended (ZERO_EXTEND, SIGN_EXTEND, or ANY_EXTEND).</p>

<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>.</p>

</div>
</div>

### getNumRegistersForCallingConv() {#a7d161cb9d6e4a3ef9c4af88bef2d3ab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsTargetLowering::getNumRegistersForCallingConv (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of registers for a given <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a>, ensuring vectors are treated as a series of gpr sized integers.</p>

<p>Declaration at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a42bf7ed3daec395fe644414494888bc6">llvm::TargetLoweringBase::getNumRegisters</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a59eee3929b9155fd268e3e3f6c0efde9">llvm::EVT::isPow2VectorType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab41e50273c70287914ded0ae668bc507">llvm::EVT::isRound</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a> and <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a>.</p>


<p>Referenced by <a href="#a21321ab7669a253fc0fe731602fe5695">getVectorTypeBreakdownForCallingConv</a>.</p>

</div>
</div>

### getRegisterByName() {#a21a0e970e98d8f88cee991fe790e1fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register MipsTargetLowering::getRegisterByName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RegName, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4837 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a>.</p>

</div>
</div>

### getRegisterTypeForCallingConv() {#a04c394dca43220a262f8a67825cd4fb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT MipsTargetLowering::getRegisterTypeForCallingConv (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the register type for a given <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a>, ensuring vectors are treated as a series of gpr sized integers.</p>

<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af344c6bd2d070c999525df85be7688cf">llvm::TargetLoweringBase::getRegisterType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a59eee3929b9155fd268e3e3f6c0efde9">llvm::EVT::isPow2VectorType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab41e50273c70287914ded0ae668bc507">llvm::EVT::isRound</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a> and <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a>.</p>


<p>Referenced by <a href="#a21321ab7669a253fc0fe731602fe5695">getVectorTypeBreakdownForCallingConv</a>.</p>

</div>
</div>

### getScalarShiftAmountTy() {#a29a845eb11b29e4d97b09c3734ff0c27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::MipsTargetLowering::getScalarShiftAmountTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
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


<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a11579efb56ca3f28a43e11ddf6011a1d">performMULCombine</a>.</p>

</div>
</div>

### getSetCCResultType() {#a38b88641f5f9abe6b18b921f0eaceb93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT MipsTargetLowering::getSetCCResultType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getSetCCResultType - get the <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">ISD::SETCC</a> result <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a></p>

<p>Declaration at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a0351571482fea42a3b326147fb2ce9e2">llvm::EVT::changeVectorElementTypeToInteger</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### getTargetNodeName() {#a243d4ca8bf484d9d5ef47a9e8d2ad364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * MipsTargetLowering::getTargetNodeName (unsigned Opcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getTargetNodeName - This method returns the name of a target specific</p>

<p>Declaration at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba88ffa8113b6c4225bf003666059d414d">llvm::MipsISD::BuildPairF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba9e5ce4da69f90c2676e11b3f1571c808">llvm::MipsISD::CIns</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba3a6a21a2d276a42c197770044394d028">llvm::MipsISD::CMovFP_F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba828cbd76d0b9af6de505d186f3011b79">llvm::MipsISD::CMovFP_T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba78f756a9d54535a9d5c68a0566b59623">llvm::MipsISD::DivRem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba2de1b8d6037bc7e75328df25ee7ca7a2">llvm::MipsISD::DivRem16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba0631b78a3ec3f07b63c0813fc261f1f5">llvm::MipsISD::DivRemU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba6178329f87bb3b3fb8fd249cff4578b4">llvm::MipsISD::DivRemU16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bac9b0dd713fedef231f6934be939701f9">llvm::MipsISD::DOUBLE_SELECT_I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba3a1817f931bce782df97320107134c00">llvm::MipsISD::DOUBLE_SELECT_I64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba5012e99fb35a23c09158acee6c102aef">llvm::MipsISD::DPA_W_PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baf9bd57cd73be476056c3fa256791db13">llvm::MipsISD::DPAQ_S_W_PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba0a2ea41a49ec7e1c17c4761b99d264f6">llvm::MipsISD::DPAQ_SA_L_W</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69babc1c128d43a0149d14663608966c5e05">llvm::MipsISD::DPAQX_S_W_PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba3272b07f2ea401b4fd0f830266b8ddb5">llvm::MipsISD::DPAQX_SA_W_PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bae452b9b2a62c6666e17c1391a08b318d">llvm::MipsISD::DPAU_H_QBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba54dd2a2b5a29f17b022c436a563a6df1">llvm::MipsISD::DPAU_H_QBR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bac4dd4476003819ed217c5e0829b30c58">llvm::MipsISD::DPAX_W_PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba5e93986f8d0b530a4b0daa3c0063fa7a">llvm::MipsISD::DPS_W_PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba6fb87fbe4a280ff588b31530e8e1aed7">llvm::MipsISD::DPSQ_S_W_PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69babd56ae0a2e1453041b199a1ca7d6123a">llvm::MipsISD::DPSQ_SA_L_W</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba769886f6ebeb03d592f12792b84129cb">llvm::MipsISD::DPSQX_S_W_PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baf79474ce1a2019cdcf1ad68585f5c1d9">llvm::MipsISD::DPSQX_SA_W_PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bab2e20f4730b6dee393b525d5a73449f7">llvm::MipsISD::DPSU_H_QBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba304cd83316b5db1f958489ec4e3347e8">llvm::MipsISD::DPSU_H_QBR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba2d0562c15823fed62c781badcb3a11c3">llvm::MipsISD::DPSX_W_PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba01f63ea4f5784b419988cabeb1028e47">llvm::MipsISD::DynAlloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baac73ab8f8ec895ed89445f3e6a203921">llvm::MipsISD::EH_RETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baf71ae49db5c9512a30d897ef7dff5e1e">llvm::MipsISD::ERet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba88a797f57846adb2c382b3732b471913">llvm::MipsISD::Ext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba6ffafd27acd561721645cf9062649650">llvm::MipsISD::EXTP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba160d807a08cfa50f0fe067d7b507cd4f">llvm::MipsISD::EXTPDP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bab21c1416d9487cf068d978d1e33c8081">llvm::MipsISD::EXTR_R_W</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba9a915233797c186132f7f0be8e219d12">llvm::MipsISD::EXTR_RS_W</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bad3624e2c68f103c6a257d2ca46ea1150">llvm::MipsISD::EXTR_S_H</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baf2e111b735626a02f75856148ac05069">llvm::MipsISD::EXTR_W</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba1545eb8951c999495303a078459ca3e4">llvm::MipsISD::ExtractElementF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba4f09e5b9ab57b1d72349caeba37a0dc1">llvm::MipsISD::FAbs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba91597fd627e43769c09cc532f7178473">llvm::MipsISD::FIRST_NUMBER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba98f59986149fc5d24607be353a82c842">llvm::MipsISD::FMS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba92a649fd8568f6f1cffd11b0886e03cb">llvm::MipsISD::FPBrcond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba44b9c5d5769578c3a6689c52c3c9b1c1">llvm::MipsISD::FPCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bad16ee478dfa940adbd84aae36ce08eb6">llvm::MipsISD::FSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba47b57f516892e576e8800508d9991339">llvm::MipsISD::GotHi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba48209a7d98dfb59cfd87fcdfde836d0c">llvm::MipsISD::GPRel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba71e1753b225b38eb88e67626f6cfbff0">llvm::MipsISD::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba304da432eae1d8e75d89594afb3d6f18">llvm::MipsISD::Higher</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba230674684da59830e4af773e6393d1dd">llvm::MipsISD::Highest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba66d3e593d4b5d9355845418ce07b8093">llvm::MipsISD::ILVEV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba1559a6a52ea1b86e53852f0c4e11fe0b">llvm::MipsISD::ILVL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba7480b95bf7e21f17e79e3ef6f26b2090">llvm::MipsISD::ILVOD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba4ace0dc4a4017232cc502e6a7e238038">llvm::MipsISD::ILVR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bad5006873d15f9569d1cf09deef3c6363">llvm::MipsISD::Ins</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69badceba4e61f97a26798aac5824e2fcd4f">llvm::MipsISD::INSVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba6ffe3943947d5e215a842c92b923f785">llvm::MipsISD::JmpLink</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba7c9bd3f26365a95215ef02f178696ca1">llvm::MipsISD::LDL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baa0686bd3f7b2056b4fc76d2b4ec46e17">llvm::MipsISD::LDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bae687521fe85a8c2b4490bba6464f5be3">llvm::MipsISD::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bafe575bccaad054f296d74a527463714a">llvm::MipsISD::LWL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba00d989ef11bb6ca53e1669a0780109e8">llvm::MipsISD::LWR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bae4ae06d8231c915d3a38cdaa566f19e2">llvm::MipsISD::MAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba178be7a8cb8b7f4cefe8887e8b8ab0ce">llvm::MipsISD::MADD_DSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba024ac538f26dc815e5003dbfc7d0327b">llvm::MipsISD::MAddu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba89c071e5a8c88386c138c430b31a95ee">llvm::MipsISD::MADDU_DSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba1063fbee44d8aea14d4569b43ce16170">llvm::MipsISD::MAQ_S_W_PHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba56b7f3af4e2ee597ed9534143bf901ee">llvm::MipsISD::MAQ_S_W_PHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baee8772bc7c72109e060df72d0493f1f7">llvm::MipsISD::MAQ_SA_W_PHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba87e9e312ebaabf1a9c472bc9138120ac">llvm::MipsISD::MAQ_SA_W_PHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba2a748b4e6332ee6f1fcdef61e71112ce">llvm::MipsISD::MFHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bae4189aa234aa339a28c96ba4619b6127">llvm::MipsISD::MFLO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba5a3db6784c014740498303318623d822">llvm::MipsISD::MSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba70ad31600a42c92a4924e177020fc54d">llvm::MipsISD::MSUB_DSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bac72d871382f44009d2a1e136610dfb40">llvm::MipsISD::MSubu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba92ddaeff1e7d980c97e9ce423c230a44">llvm::MipsISD::MSUBU_DSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba32857b3b378b466787e3e75c6c09d770">llvm::MipsISD::MTC1_D64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba3bc20adbd2089ad5a30d82f50be7f7fe">llvm::MipsISD::MTHLIP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baaa3a89a99b8de6901fca06b0a8ef6fc7">llvm::MipsISD::MTLOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baefd22c0d0f61706ab6dbd97011972a82">llvm::MipsISD::MULSA_W_PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba27f29ec16a5aaa356f96ff1c1205002f">llvm::MipsISD::MULSAQ_S_W_PH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba2ba8e90b1a8dff465d899e33a6404a81">llvm::MipsISD::MULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba489c5c03b43333daa30af69d887fc1f2">llvm::MipsISD::Mult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baef631f9b0e1ee2e3c46a1a448d2d3efb">llvm::MipsISD::MULTU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baa9e622d1e702caa06bf51a57db994824">llvm::MipsISD::Multu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba721b30ace12bdac89b93684865ee6941">llvm::MipsISD::PCKEV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba059c603e586f238f5ec78c99c6dc1eaa">llvm::MipsISD::PCKOD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba366e1eac31eeb1a1892d62ccfc0c8cf8">llvm::MipsISD::Ret</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba802783759d8d5f51e58652e651a2f543">llvm::MipsISD::SDL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba98e5728321f3e1a33ebf7881011faf03">llvm::MipsISD::SDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba3115ebc375dd4e98b09907fee318dbd1">llvm::MipsISD::SELECT_CC_DSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba8ed1313249b5f0f1b44c728bf17ce2d4">llvm::MipsISD::SETCC_DSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baad35f47170b3dabe28b51462d40ba212">llvm::MipsISD::SHF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba27b6ac874e312b5f37fbc649f966c9c6">llvm::MipsISD::SHILO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba8ff274ae7e92745980a867ebc2695d0d">llvm::MipsISD::SHLL_DSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba99372f35f6f83b69470648eb845e07ac">llvm::MipsISD::SHRA_DSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba2b96b034c5babbcef2b044ccd4144eee">llvm::MipsISD::SHRL_DSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba606a3ada58afda41f8d8fa0dea24762b">llvm::MipsISD::SWL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba912bbd12a43c7565b673301ed0e0b92e">llvm::MipsISD::SWR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bab5291bce1e8881a9f3f1ee9981b422ed">llvm::MipsISD::Sync</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba84922260d1582a0d4f6f0925cef648d7">llvm::MipsISD::TailCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba6658af4b0a62ee48eb164fca20224aa5">llvm::MipsISD::ThreadPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba4a9abd1fa2b1eafc3e1cef7e2547a697">llvm::MipsISD::TlsHi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baabe596117d9a980304cfe3a090863974">llvm::MipsISD::TruncIntFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba94a8fbea394947cfd85ab7939f931378">llvm::MipsISD::VALL_NONZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba88698c97bacd6aef8d438a130203c69a">llvm::MipsISD::VALL_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baf1cbc3b8a8f6b83397cba66e989e8bd2">llvm::MipsISD::VANY_NONZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bac346b4950388fdb4201196c03533fd5d">llvm::MipsISD::VANY_ZERO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba5ac3089162d80f74ee295dfbf1cfcafb">llvm::MipsISD::VCEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba9e01e7638de924f0942d420c5ff4d604">llvm::MipsISD::VCLE_S</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bafc6b3d5974ca43368eb99e8558202394">llvm::MipsISD::VCLE_U</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba7533897bc18887557911e1c835948d5c">llvm::MipsISD::VCLT_S</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba74bc5737732b04f461f372dadf6ec16b">llvm::MipsISD::VCLT_U</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bae92303a8af654541359884ddfc76af00">llvm::MipsISD::VEXTRACT_SEXT_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba6f1d5020c110223d3bb85a6e82e3b618">llvm::MipsISD::VEXTRACT_ZEXT_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bae2495da6743e7ab111e7a6d58fc9260b">llvm::MipsISD::VNOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bafb6a806352c26482752f729ff5843752">llvm::MipsISD::VSHF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bab66c1ce49361a050c152c59394d0e394">llvm::MipsISD::Wrapper</a>.</p>

</div>
</div>

### getTypeForExtReturn() {#a940aa5c3b3202d4d987e2a999450f240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT MipsTargetLowering::getTypeForExtReturn (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a>)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a3bf257bfbd279ecfad670be03b00210e">llvm::EVT::bitsLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af344c6bd2d070c999525df85be7688cf">llvm::TargetLoweringBase::getRegisterType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a> and <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a>.</p>

</div>
</div>

### getVectorTypeBreakdownForCallingConv() {#a21321ab7669a253fc0fe731602fe5695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsTargetLowering::getVectorTypeBreakdownForCallingConv (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> &amp; IntermediateVT, unsigned &amp; NumIntermediates, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; RegisterVT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Break down vectors to the correct number of gpr sized integers.</p>

<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a42bf7ed3daec395fe644414494888bc6">llvm::TargetLoweringBase::getNumRegisters</a>, <a href="#a7d161cb9d6e4a3ef9c4af88bef2d3ab4">getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af344c6bd2d070c999525df85be7688cf">llvm::TargetLoweringBase::getRegisterType</a>, <a href="#a04c394dca43220a262f8a67825cd4fb5">getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a59eee3929b9155fd268e3e3f6c0efde9">llvm::EVT::isPow2VectorType</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#ab41e50273c70287914ded0ae668bc507">llvm::EVT::isRound</a>.</p>

</div>
</div>

### HandleByVal() {#ad11c85a64a9aca0f5035553171364591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetLowering::HandleByVal (<a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> *, unsigned &amp;, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target-specific cleanup for formal ByVal parameters.</p>

<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4635 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="#a535e0e577653c46309de47d558fed337">ABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a5549513e93067ffe684891d1fca79e4b">Mips64DPRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a>.</p>

</div>
</div>

### hasBitTest() {#a08fa631974fcb44a77c69f10fea8f089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsTargetLowering::hasBitTest (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> X, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Y)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 1251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### isCheapToSpeculateCtlz() {#a98315677ba77ffbfd8c7c6f13a05a890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsTargetLowering::isCheapToSpeculateCtlz (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 1247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>Reference <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a>.</p>

</div>
</div>

### isCheapToSpeculateCttz() {#a9f401d091072000857a41ef619f1342a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsTargetLowering::isCheapToSpeculateCttz (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 1243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>Reference <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a>.</p>

</div>
</div>

### isJumpTableRelative() {#ae2e5c3e98e51697955be49b39bb42c02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsTargetLowering::isJumpTableRelative ()</td>
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



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a0e5ffac7fd84af772a216629f8bd6da9">llvm::TargetMachine::isPositionIndependent</a>.</p>

</div>
</div>

### LowerOperation() {#a9935c00eaf6557ca6bfdb6ced9c377f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::LowerOperation (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 1282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abad932e63381a4671b5db19a3404c82e">llvm::ISD::EH_DWARF_CFA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4edf35e2383003ff20057e5a45012a55">llvm::ISD::EH_RETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a74a787311d3ab9a17ee0acde7b6a6b14">llvm::ISD::FCANONICALIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeffc3319657e213a530ce583603f7221">llvm::ISD::FCOPYSIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdb38c8daa8c1ab881007062d113cef3">llvm::ISD::FRAMEADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0c70100db6ddc0b37b56feb242145cf4">llvm::ISD::JumpTable</a>, <a href="#af8cb1a782bf62a812f68aac1af065a5e">lowerLOAD</a>, <a href="#a8308bacd5a1d10fdc7ac14c784f6ce0d">lowerSTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2dfacb29792dd59f2cfbe529206265bc">llvm::ISD::RETURNADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a51cb24bd3e700fcf2f93d1afbb555a16">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipssetargetlowering/#acd35968c6214497c6865b65b151a2e5b">llvm::MipsSETargetLowering::LowerOperation</a>.</p>

</div>
</div>

### PerformDAGCombine() {#a6b3ae019ac2faf4a810a9b8fa80b747d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::PerformDAGCombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 1213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba3a6a21a2d276a42c197770044394d028">llvm::MipsISD::CMovFP_F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba828cbd76d0b9af6de505d186f3011b79">llvm::MipsISD::CMovFP_T</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#acf37bd7e831bdb2a5c9da8d63f843101">llvm::TargetLowering::DAGCombinerInfo::DAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a830e51b63befaa067f822c088dd8833b">performADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64b9ecc144bf0b95267b353d6ddf5b9b">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#adf702ecb841f96bb48f48607543fe438">performCMovFPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a4855642780c43259ecd18ea1bce3f0d3">performDivRemCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a33f99c1c02a48f20e7ec9d30d11d093c">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#add39487738bda59bdf85c85cb21b7e9a">performSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a24edd3104fd2ecba03dd7ca79104295d">performSHLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a9a5205b95660638f4c7d889f588251e7">performSUBCombine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a874f66e1efe5be79552bbe7ee3121a">llvm::ISD::SDIVREM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a51cb24bd3e700fcf2f93d1afbb555a16">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a257ffa49107e2db978e8a6e2688ada">llvm::ISD::UDIVREM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipssetargetlowering/#a23c69653370af251e721680e01303967">llvm::MipsSETargetLowering::PerformDAGCombine</a>.</p>

</div>
</div>

### ReplaceNodeResults() {#a73afb942bbe9f13347f351f28ac2fe2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetLowering::ReplaceNodeResults (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 1275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a12431703c17466d24d4bf388ce467ea3">llvm::TargetLowering::LowerOperationWrapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>.</p>

</div>
</div>

### shouldFoldConstantShiftPairToMask() {#aa3cf604f0da074af7ca64f80e5d753ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsTargetLowering::shouldFoldConstantShiftPairToMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7a">CombineLevel</a> Level)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 1261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>.</p>

</div>
</div>

### softPromoteHalfType() {#aac2de0d3f585d618ab477a022e027da0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsTargetLowering::softPromoteHalfType ()</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getAddrGlobal() {#a3f5a81ea3f95a4119d6c0a5b5b2f5c49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::MipsTargetLowering::getAddrGlobal (NodeTy * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flag, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; PtrInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#aaeba37067209bf3e8f04114e8918b499">getGlobalReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bab66c1ce49361a050c152c59394d0e394">llvm::MipsISD::Wrapper</a>.</p>

</div>
</div>

### getAddrGlobalLargeGOT() {#a5ccaa648716b2c4c8e0687f36e6c9fa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::MipsTargetLowering::getAddrGlobalLargeGOT (NodeTy * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned HiFlag, unsigned LoFlag, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; PtrInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#aaeba37067209bf3e8f04114e8918b499">getGlobalReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba47b57f516892e576e8800508d9991339">llvm::MipsISD::GotHi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bab66c1ce49361a050c152c59394d0e394">llvm::MipsISD::Wrapper</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpualiasanalysis-cpp/#a63f565f28385a6f2c7a4756ff6f3fa16">Wrapper</a>.</p>

</div>
</div>

### getAddrGPRel() {#a1c44aab19fd4cd86f04d2dcc45062b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::MipsTargetLowering::getAddrGPRel (NodeTy * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool IsN64)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba48209a7d98dfb59cfd87fcdfde836d0c">llvm::MipsISD::GPRel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771facc686a80ae02879bbbe0426839c64b2a">llvm::MipsII::MO_GPREL</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getAddrLocal() {#aa5e1d1788ef2fee23b0f9542eda5c1b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::MipsTargetLowering::getAddrLocal (NodeTy * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool IsN32OrN64)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0f68c9c0e4a38aebd5773f80dd5b716">llvm::SelectionDAG::getEntryNode</a>, <a href="#aaeba37067209bf3e8f04114e8918b499">getGlobalReg</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#aa70144cee705b3f0db7f53ff3bf004e9">llvm::MachinePointerInfo::getGOT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bae687521fe85a8c2b4490bba6464f5be3">llvm::MipsISD::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771fa23c1a6183ec3becd204af9f074a6a10e">llvm::MipsII::MO_ABS_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771fa1a2e2730911aa3bb70313c56b63951e2">llvm::MipsII::MO_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771fafd34cc5a05cd588c7c54984311b3a0ba">llvm::MipsII::MO_GOT_OFST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771fac2b1d63e911d3f10faaff19adc5b175f">llvm::MipsII::MO_GOT_PAGE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bab66c1ce49361a050c152c59394d0e394">llvm::MipsISD::Wrapper</a>.</p>

</div>
</div>

### getAddrNonPIC() {#a80d7b6f8225e03c0e2b80249cca5bd85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::MipsTargetLowering::getAddrNonPIC (NodeTy * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba71e1753b225b38eb88e67626f6cfbff0">llvm::MipsISD::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bae687521fe85a8c2b4490bba6464f5be3">llvm::MipsISD::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771fa5fbdfe4fb09a0dac0b32cce2d9d68624">llvm::MipsII::MO_ABS_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771fa23c1a6183ec3becd204af9f074a6a10e">llvm::MipsII::MO_ABS_LO</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getAddrNonPICSym64() {#a272d1bf276d97a177b681f465129fe56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::MipsTargetLowering::getAddrNonPICSym64 (NodeTy * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba71e1753b225b38eb88e67626f6cfbff0">llvm::MipsISD::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba304da432eae1d8e75d89594afb3d6f18">llvm::MipsISD::Higher</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba230674684da59830e4af773e6393d1dd">llvm::MipsISD::Highest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bae687521fe85a8c2b4490bba6464f5be3">llvm::MipsISD::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771fa5fbdfe4fb09a0dac0b32cce2d9d68624">llvm::MipsII::MO_ABS_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771fa23c1a6183ec3becd204af9f074a6a10e">llvm::MipsII::MO_ABS_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771fae9a6bcb93bd478212b515dedbcf7d07b">llvm::MipsII::MO_HIGHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771fab607eb14b7755148dd000a00762e46a8">llvm::MipsII::MO_HIGHEST</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>.</p>

</div>
</div>

### getDllimportSymbol() {#a77a87423f2a96adea15f67141ced40bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::MipsTargetLowering::getDllimportSymbol (NodeTy * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba71e1753b225b38eb88e67626f6cfbff0">llvm::MipsISD::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bae687521fe85a8c2b4490bba6464f5be3">llvm::MipsISD::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771fa5fbdfe4fb09a0dac0b32cce2d9d68624">llvm::MipsII::MO_ABS_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771fa23c1a6183ec3becd204af9f074a6a10e">llvm::MipsII::MO_ABS_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#ab0cf5f5ed4db649fc89a1b41f8b5771fab985de2c979ebcdba6e5456b31a00222">llvm::MipsII::MO_DLLIMPORT</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a5f41eccd0b382684fdb89443c0c54a99">getDllimportVariable</a>.</p>

</div>
</div>

### getDllimportVariable() {#a5f41eccd0b382684fdb89443c0c54a99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::MipsTargetLowering::getDllimportVariable (NodeTy * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; PtrInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a77a87423f2a96adea15f67141ced40bc">getDllimportSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getGlobalReg() {#aaeba37067209bf3e8f04114e8918b499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::getGlobalReg (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty)</td>
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



<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#a4f8c7b0497e80fd8c5028d2b564c0c3f">llvm::MipsFunctionInfo::getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>.</p>


<p>Referenced by <a href="#a3f5a81ea3f95a4119d6c0a5b5b2f5c49">getAddrGlobal</a>, <a href="#a5ccaa648716b2c4c8e0687f36e6c9fa2">getAddrGlobalLargeGOT</a>, <a href="#aa5e1d1788ef2fee23b0f9542eda5c1b6">getAddrLocal</a> and <a href="#a93bebb4498805f11e17d91d7cde35511">getOpndList</a>.</p>

</div>
</div>

### getOpndList() {#a93bebb4498805f11e17d91d7cde35511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetLowering::getOpndList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, std::deque&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &gt; &amp; RegsToPass, bool IsPICCall, bool GlobalOrExternal, bool InternalLinkage, bool IsCallReloc, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp; CLI, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Callee, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain)</td>
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

<p>This function fills Ops, which is the list of operands that will later be used when a function call node is created.</p>


<p>It also generates copyToReg nodes to set up argument registers.</p>


<p>Declaration at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 3131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="#a535e0e577653c46309de47d558fed337">ABI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae47a430364102f6e179d49cb3411b955">llvm::TargetLowering::CallLoweringInfo::CallConv</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a31faa4803c937d756c28947a070c6c2e">llvm::TargetLowering::CallLoweringInfo::Callee</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae76ac9826f02f95aae34e845ac110244">llvm::TargetLowering::CallLoweringInfo::DAG</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a3b6fcbb7bdd8ae29e8af4cd38bce7a40">llvm::TargetLowering::CallLoweringInfo::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="#aaeba37067209bf3e8f04114e8918b499">getGlobalReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a649ab540187060d1b313dba37a54f3a6">llvm::MipsRegisterInfo::getMips16RetHelperMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acfe1250a2214797a59c6457dd2180df9">llvm::SelectionDAG::getRegisterMask</a>, <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### lowerLOAD() {#af8cb1a782bf62a812f68aac1af065a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerLOAD (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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



<p>Declaration at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2772 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a78bffbf32a21dc24a29ed24a8233481e">createLoadLR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">llvm::ISD::EXTLOAD</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a193d4ea30b27a0c86550ae249eefaeaa">llvm::SelectionDAG::getMergeValues</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b0e59823444a55c295af279611a9d24">llvm::SelectionDAG::getUNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba7c9bd3f26365a95215ef02f178696ca1">llvm::MipsISD::LDL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69baa0686bd3f7b2056b4fc76d2b4ec46e17">llvm::MipsISD::LDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69bafe575bccaad054f296d74a527463714a">llvm::MipsISD::LWL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba00d989ef11bb6ca53e1669a0780109e8">llvm::MipsISD::LWR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6aacde2c67988b43a261a7f7ceac4be3">llvm::ISD::NON_EXTLOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a51cb24bd3e700fcf2f93d1afbb555a16">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>


<p>Referenced by <a href="#a9935c00eaf6557ca6bfdb6ced9c377f6">LowerOperation</a>.</p>

</div>
</div>

### lowerSTORE() {#a8308bacd5a1d10fdc7ac14c784f6ce0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerSTORE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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



<p>Declaration at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2898 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#a5ba669acfce53f64119001f5d46e162f">llvm::MemSDNode::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aee0e58997cd08983518f051e79b855d9">llvm::MemSDNode::getMemoryVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a4394bc2d4e4e90b47c9876e546e1429d">lowerFP_TO_SINT_STORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a6d57cc28d7c1b1806029db8e12c6a926">lowerUnalignedIntStore</a>, <a href="#abd5bf0c117bc4ead7f73f5e51a39a160">Subtarget</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a9935c00eaf6557ca6bfdb6ced9c377f6">LowerOperation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### CanLowerReturn() {#a64e7c917683a2ed19022a238137a3620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsTargetLowering::CanLowerReturn (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 3879 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### copyByValRegs() {#a7d35731f1755e8975d350b86cc55c82e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetLowering::copyByValRegs (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutChains, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; Flags, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> * FuncArg, unsigned FirstReg, unsigned LastReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA, <a href="/web-llvm/docs/api/classes/llvm/mipsccstate">MipsCCState</a> &amp; State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>copyByValArg - Copy argument registers which were used to pass a byval argument to the stack.</p>


<p>Create a stack frame object for the byval argument.</p>


<p>Declaration at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### emitAtomicBinary() {#ac490fb121a9b194dc482e4fc18fa2a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MipsTargetLowering::emitAtomicBinary (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 1534 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### emitAtomicBinaryPartword() {#a870bcb23daa9a9b1abf406b257bc7a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MipsTargetLowering::emitAtomicBinaryPartword (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 723 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 1720 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### emitAtomicCmpSwap() {#a805c71896a605b8d8387fc9092f767da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MipsTargetLowering::emitAtomicCmpSwap (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 1912 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### emitAtomicCmpSwapPartword() {#ae4964c32f9b6a92d7bd0061b916a6148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MipsTargetLowering::emitAtomicCmpSwapPartword (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 1968 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### emitLDR\_D() {#a8323f0a41966ef04ff3b6c540b7ff1ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MipsTargetLowering::emitLDR_D (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 737 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4904 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### emitLDR\_W() {#a52a234f0c67e0124704ce8b3d7a4e344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MipsTargetLowering::emitLDR_W (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4858 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### emitPseudoD\_SELECT() {#ae36fef866acebc5d2297f2d90fde30bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MipsTargetLowering::emitPseudoD_SELECT (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4759 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### emitPseudoSELECT() {#a33b05f483472ba0342ec19e788bd7b58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MipsTargetLowering::emitPseudoSELECT (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, bool isFPCmp, unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 732 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4680 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### emitSEL\_D() {#ae06f2127bbee73ea75e0d413190378c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::MipsTargetLowering::emitSEL_D (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>

</div>
</div>

### emitSignExtendToI32InReg() {#a4cc804986d4a1aa76a1e3a3106692cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MipsTargetLowering::emitSignExtendToI32InReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, unsigned Size, unsigned DstReg, unsigned SrcRec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a sign-extension using sll/sra, seb, or seh appropriately.</p>

<p>Declaration at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 1690 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### emitSTR\_D() {#a735d0623658a25e346e75751ed431473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MipsTargetLowering::emitSTR_D (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 5038 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### emitSTR\_W() {#abbde5e9b5a74ed72bad4128ea4b3ce1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MipsTargetLowering::emitSTR_W (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 738 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4988 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### getConstraintType() {#a720b7bbf95d66b8862575f61399450b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsTargetLowering::ConstraintType MipsTargetLowering::getConstraintType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4018 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### getInlineAsmMemConstraint() {#a225cb756d475ba1088031045a3f989f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAsm::ConstraintCode llvm::MipsTargetLowering::getInlineAsmMemConstraint (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ConstraintCode)</td>
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



<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>

</div>
</div>

### getJumpTableEncoding() {#ae64e17fb5f0ae39d7eda4f807d3c2321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsTargetLowering::getJumpTableEncoding ()</td>
</tr>
</table>
</td>
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


<p>Declaration at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### getOptimalMemOpType() {#ae4ab379de66d5f6e8890abd28ba8d055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT MipsTargetLowering::getOptimalMemOpType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memop">MemOp</a> &amp; Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AttributeList &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 699 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### getRegForInlineAsmConstraint() {#aefef67c9936744e3f53f73d33499f4b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, const TargetRegisterClass * &gt; MipsTargetLowering::getRegForInlineAsmConstraint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a register class constraint, like 'r', if this corresponds directly to an LLVM register class, return a register of 0 and the register class pointer.</p>

<p>Declaration at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### getSingleConstraintMatchWeight() {#a4a0e623707f01a9ceb5648f06867f714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::ConstraintWeight MipsTargetLowering::getSingleConstraintMatchWeight (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a> &amp; info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * constraint)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 662 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4055 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### getTargetNode() {#a190ff1c7002157e800c2d6d06ad01d4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::getTargetNode (<a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### getTargetNode() {#a008841a3e896bba955074eaa45aa1485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::getTargetNode (<a href="/web-llvm/docs/api/classes/llvm/externalsymbolsdnode">ExternalSymbolSDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### getTargetNode() {#a323b486561049b4496528b9787e62b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::getTargetNode (<a href="/web-llvm/docs/api/classes/llvm/blockaddresssdnode">BlockAddressSDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### getTargetNode() {#a35654591798e4f52aef04e1b21c673d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::getTargetNode (<a href="/web-llvm/docs/api/classes/llvm/jumptablesdnode">JumpTableSDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### getTargetNode() {#a4eb06af1b5c6083ad1c1ff88ec404fc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::getTargetNode (<a href="/web-llvm/docs/api/classes/llvm/constantpoolsdnode">ConstantPoolSDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### isEligibleForTailCallOptimization() {#ac8b8c4ecaae686698ad0dcae3eb89091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MipsTargetLowering::isEligibleForTailCallOptimization (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; CCInfo, unsigned NextStackOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo">MipsFunctionInfo</a> &amp; FI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isEligibleForTailCallOptimization - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the call is eligible for tail call optimization.</p>

<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>

</div>
</div>

### isFPImmLegal() {#ada8183a1d27062f3a53c2c433951795a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsTargetLowering::isFPImmLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Imm, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, bool ForCodeSize)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### isLegalAddressingMode() {#a2f9d40da643ffa6664be940bce42b5f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsTargetLowering::isLegalAddressingMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode">AddrMode</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned AddrSpace, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### isOffsetFoldingLegal() {#aeff62af9eec9dfce6aa927b02a2690df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsTargetLowering::isOffsetFoldingLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * GA)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 697 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### LowerAsmOperandForConstraint() {#add0474e37f6a610d7f282a2c4bbedbb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetLowering::LowerAsmOperandForConstraint (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 678 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerATOMIC\_FENCE() {#acda57021924c317b1230c247c8fdf838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerATOMIC_FENCE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2660 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerBlockAddress() {#af0568066176aeb7f626a9b6d595bfd4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerBlockAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerBRCOND() {#a101d3e63c145bb584f825a7f6e20bc7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerBRCOND (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2092 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCall() {#a7ee6422b18832dd0c56fe4ef182d9efc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::LowerCall (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">TargetLowering::CallLoweringInfo</a> &amp; CLI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LowerCall - functions arguments are copied from virtual regs to (physical regs)/(stack frame), CALLSEQ_START and CALLSEQ_END are emitted.</p>

<p>Declaration at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 3248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### LowerCallResult() {#a097af76c91a02317954db69ff85ac450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::LowerCallResult (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> InGlue, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">TargetLowering::CallLoweringInfo</a> &amp; CLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LowerCallResult - Lower the result values of a call into the appropriate copies out of appropriate physical registers.</p>

<p>Declaration at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 3594 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerConstantPool() {#abd0cdba0cf5c9a3edb3e1a42ae5a8f2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerConstantPool (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerEH\_DWARF\_CFA() {#a3fa6398dd7c8e33caa425812d5086097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerEH_DWARF_CFA (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2911 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerEH\_RETURN() {#a82dabeb446695cceec86ded85489ef54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerEH_RETURN (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2636 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerFABS() {#ac43cebf6f25637fc02040ac94d2dcc9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerFABS (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2570 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerFABS32() {#a9fc1eed215601a3aeb0c01ed73ed18bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerFABS32 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool HasExtractInsert)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2506 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerFABS64() {#afc514bde3a19040254888a42c2adb689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerFABS64 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool HasExtractInsert)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2546 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerFCANONICALIZE() {#ad85246c0e1ca80e3528cebf1b4ceef5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerFCANONICALIZE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2577 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerFCOPYSIGN() {#a122b415151a9867baa764153030c1944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerFCOPYSIGN (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2499 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### LowerFormalArguments() {#ad59f1fb8aea56b06c201bf22955e7b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::LowerFormalArguments (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LowerFormalArguments - transform physical registers into virtual registers and generate load operations for arguments places on the stack.</p>

<p>Declaration at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 3721 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerFP\_TO\_SINT() {#ac96022972ee30e174b7b84d1ecb9fd6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerFP_TO_SINT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2922 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerFRAMEADDR() {#ad8fcbca915577e5fdccc5e3b2899b3f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerFRAMEADDR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2592 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerGlobalAddress() {#aacb67084205b084c1904b85407044c1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerGlobalAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerGlobalTLSAddress() {#ae989f979e281de2d1ce794a7db0f3574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerGlobalTLSAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### LowerInterruptReturn() {#af7cde7bfcf10fe6da23cbb3136452bf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::LowerInterruptReturn (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; RetOps, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 3897 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerJumpTable() {#a80b20c2ac7dfb1f706d9e6350bc0c7c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerJumpTable (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### LowerReturn() {#ae12d5116aade84926053b4795e0c3e32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::LowerReturn (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 3909 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerRETURNADDR() {#a80ccc12dd3fcad5abd17242fb919f04f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerRETURNADDR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2609 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerSELECT() {#ad51a9456de46adf2c041aabbee1e5abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerSELECT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerSETCC() {#a34631207e79bcf70618503b9e932e7a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerSETCC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerShiftLeftParts() {#a2870362f089a6812c037ef8a0e93719d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerShiftLeftParts (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2670 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerShiftRightParts() {#adc4886ecf9039348b4477708119d42d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerShiftRightParts (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool IsSRA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2702 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerVAARG() {#a88b70d75732ea507820187fc33d6ec0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerVAARG (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### lowerVASTART() {#af91e8e701813d016fc91fe339e0e2f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::lowerVASTART (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 2328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### parseRegForInlineAsmConstraint() {#af1efdca10ae75ba22213e0d79fdf9691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, const TargetRegisterClass * &gt; MipsTargetLowering::parseRegForInlineAsmConstraint (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> C, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function parses registers that appear in inline-asm constraints.</p>


<p>It returns pair (0, 0) on failure.</p>


<p>Declaration at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### passArgOnStack() {#a52950e48327f2eb0db8be135eeaec503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue MipsTargetLowering::passArgOnStack (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> StackPtr, unsigned Offset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Arg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, bool IsTailCall, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 3112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### passByValArg() {#a0c3e77fad6cc5836b531916bfa5499b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetLowering::passByValArg (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, std::deque&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &gt; &amp; RegsToPass, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; MemOpChains, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> StackPtr, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> &amp; MFI, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Arg, unsigned FirstReg, unsigned LastReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; Flags, bool isLittle, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>passByValArg - <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> a byval argument in registers or on stack.</p>

<p>Declaration at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4492 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### shouldInsertFencesForAtomic() {#a26ee9fc4da03c3bd29463accad6e4dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsTargetLowering::shouldInsertFencesForAtomic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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


<p>Definition at line 711 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>

</div>
</div>

### shouldSignExtendTypeInLibCall() {#ad40b4195a9ceb99a3d864a08233b0585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsTargetLowering::shouldSignExtendTypeInLibCall (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool IsSigned)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if arguments should be sign-extended in lib calls.</p>

<p>Declaration at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 3888 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### useSoftFloat() {#ad9e5d3c4fc647bb41428783017e1a26c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsTargetLowering::useSoftFloat ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

### writeVarArgRegs() {#a2484562d148282c81ad548b53d66e008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetLowering::writeVarArgRegs (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutChains, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>writeVarArgRegs - Write variable function arguments passed in registers to the stack.</p>


<p>Also create a stack frame object for the first variable argument.</p>


<p>Declaration at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 4588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ABI {#a535e0e577653c46309de47d558fed337}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsABIInfo&amp; llvm::MipsTargetLowering::ABI</td>
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



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>Referenced by <a href="#a190d897779db77a8f8d471364aeb2392">getExceptionPointerRegister</a>, <a href="#a0317246747d495047ab935df5c027f1e">getExceptionSelectorRegister</a>, <a href="#a93bebb4498805f11e17d91d7cde35511">getOpndList</a>, <a href="#ad11c85a64a9aca0f5035553171364591">HandleByVal</a> and <a href="#a4baae7363a2379cc1714f47c6f0404aa">MipsTargetLowering</a>.</p>

</div>
</div>

### Subtarget {#abd5bf0c117bc4ead7f73f5e51a39a160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsSubtarget&amp; llvm::MipsTargetLowering::Subtarget</td>
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



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>


<p>Referenced by <a href="#a8c0a6f5ad327c20349f2a2e0a5845b3e">AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssetargetlowering/#abe5fd0b5b59ac087ea3e1d91a4602766">llvm::MipsSETargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="#a40e9166415077d71f840a81b21a1313a">createFastISel</a>, <a href="#a74ceed526d62127854c54efe9e7f6f06">EmitInstrWithCustomInserter</a>, <a href="#a7d161cb9d6e4a3ef9c4af88bef2d3ab4">getNumRegistersForCallingConv</a>, <a href="#a93bebb4498805f11e17d91d7cde35511">getOpndList</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssetargetlowering/#a2768a2917e9623212c20ea1a2888b69d">llvm::MipsSETargetLowering::getPreferredVectorAction</a>, <a href="#a21a0e970e98d8f88cee991fe790e1fe9">getRegisterByName</a>, <a href="#a04c394dca43220a262f8a67825cd4fb5">getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssetargetlowering/#ab172c1a0e52cc32af5d786bcafa276b9">llvm::MipsSETargetLowering::getRepRegClassFor</a>, <a href="#a940aa5c3b3202d4d987e2a999450f240">getTypeForExtReturn</a>, <a href="#ad11c85a64a9aca0f5035553171364591">HandleByVal</a>, <a href="#a98315677ba77ffbfd8c7c6f13a05a890">isCheapToSpeculateCtlz</a>, <a href="#a9f401d091072000857a41ef619f1342a">isCheapToSpeculateCttz</a>, <a href="#af8cb1a782bf62a812f68aac1af065a5e">lowerLOAD</a>, <a href="#a8308bacd5a1d10fdc7ac14c784f6ce0d">lowerSTORE</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16targetlowering/#a97b896b6b94b563138613746e46e053e">llvm::Mips16TargetLowering::Mips16TargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssetargetlowering/#ae4a45998b3e29ffba3a1281d59f5fd44">llvm::MipsSETargetLowering::MipsSETargetLowering</a>, <a href="#a4baae7363a2379cc1714f47c6f0404aa">MipsTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssetargetlowering/#a23c69653370af251e721680e01303967">llvm::MipsSETargetLowering::PerformDAGCombine</a> and <a href="#a6b3ae019ac2faf4a810a9b8fa80b747d">PerformDAGCombine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### isMicroMips {#acd437d4d184e4fdf681b3afa41d18b22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsTargetLowering::isMicroMips</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a15f65769a3b8f609efbdc7eba633c1cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsTargetLowering * MipsTargetLowering::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine">MipsTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget">MipsSubtarget</a> &amp; STI)</td>
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



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>, definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa812deed71551ca69b7ce96cf3813d40">llvm::createMips16TargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc3a1332b12423275fdb422f5d7bd47d">llvm::createMipsSETargetLowering</a> and <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget/#a665e2ef3a476d2de4052b40756af0976">llvm::MipsSubtarget::inMips16Mode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp">MipsISelLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
