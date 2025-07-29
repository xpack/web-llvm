---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sparctargetlowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SparcTargetLowering` Class



## Declaration

<div class="doxyDeclaration">
class llvm::SparcTargetLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">Target/Sparc/SparcISelLowering.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecea65c9daf59dcfdbeff434056d8a0c">SparcTargetLowering</a> (const TargetMachine &amp;TM, const SparcSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64cc4af32654deb89d3073cc5ef4290">LowerOperation</a> (SDValue Op, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is invoked for operations that are unsupported by the target, which are registered to use 'custom' lowering, and whose defined values are all legal. <a href="#ae64cc4af32654deb89d3073cc5ef4290">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f0b79c7c0f89f0a0309f622ff4f8310">useSoftFloat</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71ac95c34a6f80744df3010b673fc9e6">computeKnownBitsForTargetNode</a> (const SDValue Op, KnownBits &amp;Known, const APInt &amp;DemandedElts, const SelectionDAG &amp;DAG, unsigned Depth=0) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>computeKnownBitsForTargetNode - Determine which of the bits specified in Mask are known to be either zero or one and return them in the KnownZero/KnownOne bitsets. <a href="#a71ac95c34a6f80744df3010b673fc9e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f7e9408933821a2800b763af49074ea">EmitInstrWithCustomInserter</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'usesCustomInserter' flag. <a href="#a8f7e9408933821a2800b763af49074ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef588454306eb754b24d6d78cb818c9b">getTargetNodeName</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns the name of a target specific DAG node. <a href="#aef588454306eb754b24d6d78cb818c9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116">ConstraintType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c5a958743bc5a86564032ba9a3aaa58">getConstraintType</a> (StringRef Constraint) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getConstraintType - Given a constraint letter, return the type of constraint it is for this target. <a href="#a2c5a958743bc5a86564032ba9a3aaa58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abc">ConstraintWeight</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a237a27aeef06752d11d7ab1dc1560239">getSingleConstraintMatchWeight</a> (AsmOperandInfo &amp;info, const char *constraint) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine constraint string and operand type and determine a weight value. <a href="#a237a27aeef06752d11d7ab1dc1560239">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4eec9eb2d2c80156afb3788f2361f14">LowerAsmOperandForConstraint</a> (SDValue Op, StringRef Constraint, std::vector&lt; SDValue &gt; &amp;Ops, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerAsmOperandForConstraint - Lower the specified operand into the Ops vector. <a href="#af4eec9eb2d2c80156afb3788f2361f14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299e5debf3d108b71fc6642ecd31e5e7">getRegForInlineAsmConstraint</a> (const TargetRegisterInfo *TRI, StringRef Constraint, MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a physical register constraint (e.g. <a href="#a299e5debf3d108b71fc6642ecd31e5e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d18817015c8dbbcc039cf4b6f2007e8">isOffsetFoldingLegal</a> (const GlobalAddressSDNode *GA) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if folding a constant offset with the given GlobalAddress is legal. <a href="#a4d18817015c8dbbcc039cf4b6f2007e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e2bda06b567e2d0535b19e4de0f63b0">getScalarShiftAmountTy</a> (const DataLayout &amp;, EVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type to use for a scalar shift opcode, given the shifted amount type. <a href="#a9e2bda06b567e2d0535b19e4de0f63b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f13984fe50ba9df4f0345922c76639">getRegisterByName</a> (const char *RegName, LLT VT, const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the name passed in. <a href="#af4f13984fe50ba9df4f0345922c76639">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a630502f67375e993b814de858f6c2090">getExceptionPointerRegister</a> (const Constant *PersonalityFn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register, this returns the register that receives the exception address on entry to an EH pad. <a href="#a630502f67375e993b814de858f6c2090">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a923f53075d535b24c0fdb2dd41fa3e93">getExceptionSelectorRegister</a> (const Constant *PersonalityFn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register, this returns the register that receives the exception typeid on entry to a landing pad. <a href="#a923f53075d535b24c0fdb2dd41fa3e93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbada954ccf57e9f3a90869f740419b2">useLoadStackGuardNode</a> (const Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override to support customized stack guard loading. <a href="#adbada954ccf57e9f3a90869f740419b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92024824569c276179f28c519ed0fec2">insertSSPDeclarations</a> (Module &amp;M) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts necessary declarations for SSP (stack protection) purpose. <a href="#a92024824569c276179f28c519ed0fec2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6fdf85d994da1352162850ae53f7020">getSetCCResultType</a> (const DataLayout &amp;DL, LLVMContext &amp;Context, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSetCCResultType - Return the <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">ISD::SETCC</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a> <a href="#ab6fdf85d994da1352162850ae53f7020">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b83fd7e57877c0eb7870a661b533f23">LowerFormalArguments</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower the incoming (formal) arguments, described by the Ins array, into the specified DAG. <a href="#a2b83fd7e57877c0eb7870a661b533f23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a405578f0decf5610edec9f350a54e81f">LowerFormalArguments_32</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerFormalArguments32 - V8 uses a very simple ABI, where all values are passed in either one or two GPRs, including FP values. <a href="#a405578f0decf5610edec9f350a54e81f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae87be78c50d3026c58e203aa8f0b9164">LowerFormalArguments_64</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a466c698ef1cf9d946c2a69ef5ef3698e">LowerCall</a> (TargetLowering::CallLoweringInfo &amp;CLI, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower calls into the specified DAG. <a href="#a466c698ef1cf9d946c2a69ef5ef3698e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad97db5ef296bd1bc041ace70b1224812">LowerCall_32</a> (TargetLowering::CallLoweringInfo &amp;CLI, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a796fb7765de0aab1aa00f7a13f5796f9">LowerCall_64</a> (TargetLowering::CallLoweringInfo &amp;CLI, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b2038e4369982b749a467ad47226ac9">CanLowerReturn</a> (CallingConv::ID CallConv, MachineFunction &amp;MF, bool isVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, LLVMContext &amp;Context, const Type *RetTy) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook should be implemented to check whether the return values described by the Outs array can fit into the return registers. <a href="#a1b2038e4369982b749a467ad47226ac9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7deb9a2cf7eca6e363907cf09b677a03">LowerReturn</a> (SDValue Chain, CallingConv::ID CallConv, bool isVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; SDValue &gt; &amp;OutVals, const SDLoc &amp;dl, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower outgoing return values, described by the Outs array, into the specified DAG. <a href="#a7deb9a2cf7eca6e363907cf09b677a03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97357df4054a9551eb9a07b609cea109">LowerReturn_32</a> (SDValue Chain, CallingConv::ID CallConv, bool IsVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; SDValue &gt; &amp;OutVals, const SDLoc &amp;DL, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa76596666bd4af3c0104b7a8fd514db0">LowerReturn_64</a> (SDValue Chain, CallingConv::ID CallConv, bool IsVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; SDValue &gt; &amp;OutVals, const SDLoc &amp;DL, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62e3c214132d2e3b30de28f2d99d4122">LowerGlobalAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab44a5ddbc927f9b63731bf050dee8048">LowerGlobalTLSAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae827a181342834e756f5baeb36360a67">LowerConstantPool</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58d1040bc9ca646c704f74ba3a076098">LowerBlockAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a6633d479bd7811ef8c96ebb8372ee7">withTargetFlags</a> (SDValue Op, unsigned TF, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54b7a062e4a4b0e09e407970da1e18ec">makeHiLoPair</a> (SDValue Op, unsigned HiTF, unsigned LoTF, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c1423d81607a5548a57bf11a3ab447c">makeAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a525e9355bccd735cf648afbde45acfc5">LowerF128_LibCallArg</a> (SDValue Chain, ArgListTy &amp;Args, SDValue Arg, const SDLoc &amp;DL, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85b82d7c69a744603ea8eccd2c40d52e">LowerF128Op</a> (SDValue Op, SelectionDAG &amp;DAG, const char *LibFuncName, unsigned numArgs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af92646d30b3f15471c866cd83fadfb62">LowerF128Compare</a> (SDValue LHS, SDValue RHS, unsigned &amp;SPCC, const SDLoc &amp;DL, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9049c6bff42f918ef0156327330b026c">LowerINTRINSIC_WO_CHAIN</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f32b61ceb023325bed9e826ade5d6e4">PerformBITCASTCombine</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2107ac6ce763ed1ad3e60ba0e473139b">bitcastConstantFPToInt</a> (ConstantFPSDNode *C, const SDLoc &amp;DL, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a975d8653451eccbb54e12c11b39f1990">PerformDAGCombine</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be invoked for all target nodes and for any target-independent nodes that the target has registered with invoke it for. <a href="#a975d8653451eccbb54e12c11b39f1990">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ae582227faa40eda6e7066409e56596">IsEligibleForTailCallOptimization</a> (CCState &amp;CCInfo, CallLoweringInfo &amp;CLI, MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsEligibleForTailCallOptimization - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the call is eligible for tail call optimization. <a href="#a4ae582227faa40eda6e7066409e56596">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea64b94dec6ae1dd7d09aee6d3879991">ShouldShrinkFPConstant</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true, then instruction selection should seek to shrink the FP constant of the specified type to a smaller type in order to save space and / or reduce runtime. <a href="#aea64b94dec6ae1dd7d09aee6d3879991">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a045327926fd1d9568e3c573b3a57f099">shouldInsertFencesForAtomic</a> (const Instruction *I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether <a href="/web-llvm/docs/api/classes/llvm/atomicexpandpass">AtomicExpandPass</a> should automatically insert fences and reduce ordering for this atomic. <a href="#a045327926fd1d9568e3c573b3a57f099">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29137845e271a0520a8f1c3c397faf50">shouldExpandAtomicRMWInIR</a> (AtomicRMWInst *AI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the IR-level AtomicExpand pass should expand the given AtomicRMW, if at all. <a href="#a29137845e271a0520a8f1c3c397faf50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16e6c862a36871c4f388c826ad65b07c">ReplaceNodeResults</a> (SDNode *N, SmallVectorImpl&lt; SDValue &gt; &amp;Results, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is invoked when a node result type is illegal for the target, and the operation was registered to use 'custom' lowering for that result type. <a href="#a16e6c862a36871c4f388c826ad65b07c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a216c0fdb0cdd991dcf320bd42ff4c39e">expandSelectCC</a> (MachineInstr &amp;MI, MachineBasicBlock *BB, unsigned BROpcode) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a717a4e5061be3b123f336f0b78b525a9">AdjustInstrPostInstrSelection</a> (MachineInstr &amp;MI, SDNode *Node) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'hasPostISelHook' flag. <a href="#a717a4e5061be3b123f336f0b78b525a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sparcsubtarget">SparcSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdc824653365e8bf338f35c33e76779a">Subtarget</a></td>
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


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SparcTargetLowering() {#aecea65c9daf59dcfdbeff434056d8a0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparcTargetLowering::SparcTargetLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sparcsubtarget">SparcSubtarget</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 1583 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a20084f62caecb0db80ad71bdabda73c2">llvm::ISD::ADDC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad116e32876f2275acf60ffb1651c9256">llvm::ISD::ADDE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7c45a718f16057459d95d09d42ec6902">llvm::TargetLoweringBase::addRegisterClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9c91befeca2a25c8050d4c3dff8b6d67">llvm::ISD::ATOMIC_CMP_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a385d7f9c63f921a2b28e8426e4101de8">llvm::ISD::ATOMIC_FENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c47226f266248f4b8c155b83601b109">llvm::ISD::ATOMIC_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1db943abc1bf78a911daeb7b03d81de8">llvm::ISD::ATOMIC_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad728a4b56d49f39375881511d8d3118d">llvm::ISD::ATOMIC_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb">llvm::ISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716d19ebad1927a2e8dd5fe3f951f882">llvm::ISD::BR_JT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782">llvm::ISD::BRCOND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716765ad6ce5be71f987cd2097b1cdbf">llvm::ISD::BRIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a477ef80c70c7359199eace0e5d3133b1">llvm::ISD::BUILTIN_OP_END</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6df03220bbe2ea3cfb905f36fb26822c">llvm::TargetLoweringBase::computeRegisterProperties</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c">llvm::ISD::CTLZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a991d07d163bd4d9984cf1ef36e92c214">llvm::ISD::CTPOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6da41a113af0909470baea7486b3386b">llvm::ISD::CTTZ</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa3441acf8576e4bbf48e9bd73ca3c0d8c">llvm::TargetLoweringBase::Custom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a967fcb624e84458e135a763d1c11346a">llvm::ISD::DEBUGTRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa71ac22470bf853868fe6b39a25bac72">llvm::ISD::DYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa4b85349547c5b6126817e10152007931">llvm::TargetLoweringBase::Expand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">llvm::ISD::EXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2b4d07600495a563319d6a3dda8dc44d">llvm::ISD::FABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeffc3319657e213a530ce583603f7221">llvm::ISD::FCOPYSIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9133d7cfb6a66404ff7757b699bc3941">llvm::ISD::FCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abc6c09c7af98236460f0b020eb3be94e">llvm::ISD::FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178">llvm::ISD::FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d26c45c040d8f85d577a5f645261d1a">llvm::ISD::FNEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3e12fcc9960ef3bf0ae5876382d4c66f">llvm::ISD::FP16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a38f379e4fddf750c36f1323a04d12171">llvm::ISD::FP_TO_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#adfa86eda5d29b10227c46b4d8f071148">llvm::MVT::fp_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1a6952b1572a4ce241cc3cf45a9ab071">llvm::ISD::FPOW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdd7bbb76dac7962dda6e116e33699da">llvm::ISD::FREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad46ae9fdfe20cd04f7fda7ccbb937543">llvm::ISD::FSIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6ba8fc92ee5081d3e533cb5322f74f29">llvm::ISD::FSINCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae1118ddac1ce0af8e9f7cc16c9e94fc0">llvm::ISD::FSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad">llvm::ISD::FSUB</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a19cb5cb13066089592de60118998d9f8">llvm::MVT::integer_fixedlen_vector_valuetypes</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7b339f69bc3995d23399a85f81af6018">llvm::MVT::integer_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa2a7c3eccf06b41e4275bbeadb46d22e">llvm::ISD::MULHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8a80d3b085af08f0dce1724207ef99b5">llvm::ISD::MULHU</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aaba91ac521e4f01f57413216273fd7b7f">llvm::TargetLoweringBase::Promote</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac43f9bea13e29622bbf18c861b52144d">llvm::ISD::READCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715">llvm::ISD::ROTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a874f66e1efe5be79552bbe7ee3121a">llvm::ISD::SDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6b928e5a6718acab4fa0030ce9198e8a">llvm::TargetLoweringBase::setBooleanContents</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0662d63e058816bf77a5b8f35331bd9d">llvm::TargetLoweringBase::setBooleanVectorContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8b36797b46a42e7b489e47c2d009bc1d">llvm::TargetLoweringBase::setLibcallName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad1d4d71bf37fea6a3170f27438d41e6d">llvm::TargetLoweringBase::setLoadExtAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4df001a3c611cc8b423ca0e54560210f">llvm::TargetLoweringBase::setMaxAtomicSizeInBitsSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab6a8a4a9115087b5dd7aa1dbff26a193">llvm::TargetLoweringBase::setMinCmpXchgSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6566d8c65c03ad2f7b18ed08f0e7f208">llvm::TargetLoweringBase::setMinFunctionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a07c0c67913bb543fc45ce9ef65ef260a">llvm::TargetLoweringBase::setOperationAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab8a44fb1f49bcfbed806fef69301a67a">llvm::TargetLoweringBase::setStackPointerRegisterToSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac87dc82fa9f824a797198e7b0e16141d">llvm::TargetLoweringBase::setTargetDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa243085e56636cc454143f916686c190">llvm::TargetLoweringBase::setTruncStoreAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1354c6f8508d6cd697dc89a5d9a52dfd">llvm::ISD::SMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a023a9de787026fe61b024476bf9c32cb">llvm::ISD::STACKRESTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a031ce694e40832d40a163d7254a8df14">llvm::ISD::STACKSAVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2ab6db512a611d1ef4ff8069e2bbfd0d">llvm::ISD::SUBC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac9246c101c0cc9232e37b3941194bb13">llvm::ISD::SUBE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aaa96f111a59a7a2e7f9c689b344543df">llvm::TargetLowering::TargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac5fb8808f3dcb9f0a83f1fc2e7747485">llvm::ISD::TRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a257ffa49107e2db978e8a6e2688ada">llvm::ISD::UDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a79c959df09509d7ff66d9b04bc40d18d">llvm::ISD::UMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28">llvm::ISD::UREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae77d03846b31c41c4860bcd96d780a78">llvm::ISD::VAARG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a804c1960ac64628cdd1f74d7de885284">llvm::ISD::VACOPY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1aadbb14ab26b74d841ac003363e3a5d">llvm::ISD::VAEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adfe32beaa596a1512b17e66b46e773ed">llvm::ISD::VASTART</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a0e2d72cfdcc49d2d189f440b3cc31dff">llvm::TargetLoweringBase::ZeroOrOneBooleanContent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AdjustInstrPostInstrSelection() {#a717a4e5061be3b123f336f0b78b525a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SparcTargetLowering::AdjustInstrPostInstrSelection (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### bitcastConstantFPToInt() {#a2107ac6ce763ed1ad3e60ba0e473139b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::bitcastConstantFPToInt (<a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode">ConstantFPSDNode</a> * C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5d154312bef0ed1a6bacfcb52b7cf8eb">llvm::SelectionDAG::getBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a377365b0288a4d06a07e09252d7d583f">llvm::DataLayout::isLittleEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#ad97db5ef296bd1bc041ace70b1224812">LowerCall_32</a> and <a href="#a9f32b61ceb023325bed9e826ade5d6e4">PerformBITCASTCombine</a>.</p>

</div>
</div>

### CanLowerReturn() {#a1b2038e4369982b749a467ad47226ac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SparcTargetLowering::CanLowerReturn (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a687c88d4217651cc56a5a4aed7c8364f">llvm::CCState::CheckReturn</a>.</p>

</div>
</div>

### computeKnownBitsForTargetNode() {#a71ac95c34a6f80744df3010b673fc9e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SparcTargetLowering::computeKnownBitsForTargetNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Depth=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>computeKnownBitsForTargetNode - Determine which of the bits specified in Mask are known to be either zero or one and return them in the KnownZero/KnownOne bitsets.</p>


<p>isMaskedValueZeroForTargetNode - Return true if '<a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> &amp; Mask' is known to be zero.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is expected to be a target specific node. Used by DAG combiner.</p>


<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 2047 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a76e45a40f2f0b5b09132d1de119765e8">llvm::KnownBits::intersectWith</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a538f22b4ea2ff04a0b41403f26eaeb67">llvm::KnownBits::resetAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35abda9c95ee3b4c99e97ebb1ad56d50e2f">llvm::SPISD::SELECT_FCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a52206dee1158f69604c50a230c255c01">llvm::SPISD::SELECT_ICC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a210eedf63f9f1b7ca903a027cc1b4458">llvm::SPISD::SELECT_XCC</a>.</p>

</div>
</div>

### EmitInstrWithCustomInserter() {#a8f7e9408933821a2800b763af49074ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * SparcTargetLowering::EmitInstrWithCustomInserter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="#a216c0fdb0cdd991dcf320bd42ff4c39e">expandSelectCC</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### expandSelectCC() {#a216c0fdb0cdd991dcf320bd42ff4c39e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * SparcTargetLowering::expandSelectCC (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, unsigned BROpcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4874816314c3308be0bf1e71de2078d8">llvm::MachineBasicBlock::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a>.</p>


<p>Referenced by <a href="#a8f7e9408933821a2800b763af49074ea">EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### getConstraintType() {#a2c5a958743bc5a86564032ba9a3aaa58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparcTargetLowering::ConstraintType SparcTargetLowering::getConstraintType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a7bc0fe0fa6be5eaabb77e46c8d9ab2c8">llvm::TargetLowering::C_Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a1d7718fd43ac0a5c715686a76f9cfd89">llvm::TargetLowering::C_RegisterClass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a45b2deb637d370d68d3bd3786c21e415">llvm::TargetLowering::getConstraintType</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### getExceptionPointerRegister() {#a630502f67375e993b814de858f6c2090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SparcTargetLowering::getExceptionPointerRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PersonalityFn)</td>
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

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>.</p>

</div>
</div>

### getExceptionSelectorRegister() {#a923f53075d535b24c0fdb2dd41fa3e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SparcTargetLowering::getExceptionSelectorRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PersonalityFn)</td>
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

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>.</p>

</div>
</div>

### getRegForInlineAsmConstraint() {#a299e5debf3d108b71fc6642ecd31e5e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, const TargetRegisterClass * &gt; SparcTargetLowering::getRegForInlineAsmConstraint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5b6faabb08339ea1dd11e9d37a668634">llvm::StringRef::back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aceda0d316aed2b818b731917d21b88bc">llvm::getAsUnsignedInteger</a>, <a href="#a299e5debf3d108b71fc6642ecd31e5e7">getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#af09507c47dcb4cdb2a13064aaa6d5243">llvm::TargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a299e5debf3d108b71fc6642ecd31e5e7">getRegForInlineAsmConstraint</a>.</p>

</div>
</div>

### getRegisterByName() {#af4f13984fe50ba9df4f0345922c76639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SparcTargetLowering::getRegisterByName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RegName, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 1146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getScalarShiftAmountTy() {#a9e2bda06b567e2d0535b19e4de0f63b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::SparcTargetLowering::getScalarShiftAmountTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
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


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>.</p>

</div>
</div>

### getSetCCResultType() {#ab6fdf85d994da1352162850ae53f7020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT SparcTargetLowering::getSetCCResultType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 2036 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a0351571482fea42a3b326147fb2ce9e2">llvm::EVT::changeVectorElementTypeToInteger</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### getSingleConstraintMatchWeight() {#a237a27aeef06752d11d7ab1dc1560239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::ConstraintWeight SparcTargetLowering::getSingleConstraintMatchWeight (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a> &amp; info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * constraint)</td>
</tr>
</table>
</td>
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


<p>The operand object must already have been set up with the operand type.</p>


<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abca632c68154579a54426d0841e490ddb40">llvm::TargetLowering::CW_Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abcad4df0dd48c58dea43776a5a77e74ba76">llvm::TargetLowering::CW_Default</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a7f5cab5437026605269663cda7389abca2a03cc05a305d0cd861ff2d070da40ca">llvm::TargetLowering::CW_Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#afaa66a325b7b8c5c79eb2c8e9822ffd2">llvm::TargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>.</p>

</div>
</div>

### getTargetNodeName() {#aef588454306eb754b24d6d78cb818c9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * SparcTargetLowering::getTargetNodeName (unsigned Opcode)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 1995 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a2b7c862577b27caf7cf95593afa80efb">llvm::SPISD::BPICC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a7dd96ca405c8c5eff4859c546ebcc90d">llvm::SPISD::BPXCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a849a571c08b32ebe76e20e6e06c02918">llvm::SPISD::BR_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35ad17a88625c7d2528aa275430a3aa013e">llvm::SPISD::BRFCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35ac3579dff33e5299d880e89abd2eb200e">llvm::SPISD::BRFCC_V9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a4160ab34383285d68f77158bc9fe5c46">llvm::SPISD::BRICC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35ad850a16944c76310207c76144c671fe6">llvm::SPISD::CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a7bcd9a91adcf12703a32ba84c8862873">llvm::SPISD::CMPFCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a615b9435b359afc4ac41e8512beb59ea">llvm::SPISD::CMPFCC_V9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35aee173683795c69db043c057180a0c24e">llvm::SPISD::CMPICC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a27b3db85b70e06b585791b94f9588498">llvm::SPISD::FIRST_NUMBER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a72f01d37a839894dc51486aca05cf1d1">llvm::SPISD::FLUSHW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35ad33751a842f525acd8ffc4f9bf9d6f4b">llvm::SPISD::FTOI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35ac1d0665fd7c7b7f60eae74c83894fd44">llvm::SPISD::FTOX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35ac6381bf059519add497cb2da3a33db6f">llvm::SPISD::GLOBAL_BASE_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a154b73611a4eb455f9b37af8b9e09e8b">llvm::SPISD::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35ac0bd422e0c9af4aa321ee39ef34837b3">llvm::SPISD::ITOF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a9e72c1acace3b907901e215f668085a6">llvm::SPISD::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a7c9f7d96c222e3cc4e7dc45fd3b3bc51">llvm::SPISD::LOAD_GDOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a53cf9620d59d409ce4ac938c8a69c033">llvm::SPISD::RET_GLUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35abda9c95ee3b4c99e97ebb1ad56d50e2f">llvm::SPISD::SELECT_FCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a52206dee1158f69604c50a230c255c01">llvm::SPISD::SELECT_ICC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a180b9006417261ba1c689ca088810cc3">llvm::SPISD::SELECT_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a210eedf63f9f1b7ca903a027cc1b4458">llvm::SPISD::SELECT_XCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a3c580eac1cc15b32f48917609a1bf56b">llvm::SPISD::TAIL_CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a06394b87de34caf1268847eafe1da5b2">llvm::SPISD::TLS_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a0689b4f4adb0bc28f3ec0cb2f7241f5a">llvm::SPISD::TLS_CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a8d369f22424360c97ef7bb6459701598">llvm::SPISD::TLS_LD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a63621d0b8667a4577f24282d736ed650">llvm::SPISD::XTOF</a>.</p>

</div>
</div>

### insertSSPDeclarations() {#a92024824569c276179f28c519ed0fec2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SparcTargetLowering::insertSSPDeclarations (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3566 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af3e31a71f6d0e55d41956d5b20ed7989">llvm::TargetLoweringBase::insertSSPDeclarations</a>.</p>

</div>
</div>

### IsEligibleForTailCallOptimization() {#a4ae582227faa40eda6e7066409e56596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SparcTargetLowering::IsEligibleForTailCallOptimization (<a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; CCInfo, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp; CLI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsEligibleForTailCallOptimization - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the call is eligible for tail call optimization.</p>

<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#ac57dc1a949dd5e9d1d7aef280f2a26e5">llvm::CCState::getStackSize</a> and <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ad07ce660c9cb208ae98a53ad8b3ce1de">llvm::TargetLowering::CallLoweringInfo::Outs</a>.</p>


<p>Referenced by <a href="#ad97db5ef296bd1bc041ace70b1224812">LowerCall_32</a> and <a href="#a796fb7765de0aab1aa00f7a13f5796f9">LowerCall_64</a>.</p>

</div>
</div>

### isOffsetFoldingLegal() {#a4d18817015c8dbbcc039cf4b6f2007e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SparcTargetLowering::isOffsetFoldingLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * GA)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>

</div>
</div>

### LowerAsmOperandForConstraint() {#af4eec9eb2d2c80156afb3788f2361f14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SparcTargetLowering::LowerAsmOperandForConstraint (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7fc96403de39ca28a30bf2a4a38b113f">llvm::SelectionDAG::getSignedTargetConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ad3f2eb78e627fd0d785fd4119d299558">llvm::TargetLowering::LowerAsmOperandForConstraint</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### LowerBlockAddress() {#a58d1040bc9ca646c704f74ba3a076098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerBlockAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 2197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>Reference <a href="#a8c1423d81607a5548a57bf11a3ab447c">makeAddress</a>.</p>


<p>Referenced by <a href="#ae64cc4af32654deb89d3073cc5ef4290">LowerOperation</a>.</p>

</div>
</div>

### LowerCall() {#a466c698ef1cf9d946c2a69ef5ef3698e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerCall (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">TargetLowering::CallLoweringInfo</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="#ad97db5ef296bd1bc041ace70b1224812">LowerCall_32</a> and <a href="#a796fb7765de0aab1aa00f7a13f5796f9">LowerCall_64</a>.</p>

</div>
</div>

### LowerCall\_32() {#ad97db5ef296bd1bc041ace70b1224812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerCall_32 (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">TargetLowering::CallLoweringInfo</a> &amp; CLI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 822 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45acc07b91f72979f3e9b12c2e0c355db46">llvm::CCValAssign::AExt</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a919797ac95a1d84d08e4f43eedededa4">llvm::CCState::AnalyzeCallOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a34218a663a02de9dc2d26a5639f58ebe">llvm::CCState::AnalyzeCallResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a0f94adbbe71c94edaa533a25973bbffc">llvm::CCValAssign::BCvt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="#a2107ac6ce763ed1ad3e60ba0e473139b">bitcastConstantFPToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35ad850a16944c76310207c76144c671fe6">llvm::SPISD::CALL</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae47a430364102f6e179d49cb3411b955">llvm::TargetLowering::CallLoweringInfo::CallConv</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a31faa4803c937d756c28947a070c6c2e">llvm::TargetLowering::CallLoweringInfo::Callee</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#acd79db0f7d45129e8af1258541861ef8">llvm::TargetLowering::CallLoweringInfo::CB</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#aa4872f31b8be67e8a1998454db0766bd">llvm::TargetLowering::CallLoweringInfo::Chain</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1ae307f415a8989475e3f7ddd6eefc8b">llvm::MachineFrameInfo::CreateStackObject</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae76ac9826f02f95aae34e845ac110244">llvm::TargetLowering::CallLoweringInfo::DAG</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a3b6fcbb7bdd8ae29e8af4cd38bce7a40">llvm::TargetLowering::CallLoweringInfo::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#aa703537070b60dd03f662555fdd576ec">emitReservedArgRegCallError</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a8b73d77b9e54663c2e80a48d0917dce1">llvm::CCValAssign::Full</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#abbf22b8a1f5ed1623341605748ec8df4">llvm::TargetLowering::CallLoweringInfo::getArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b631ac3ef73be923372fb2fb1de405e">llvm::SelectionDAG::getCALLSEQ_END</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9146909da2f666439a0a0a0a65e45100">llvm::SelectionDAG::getCALLSEQ_START</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6551350658729b36c93362fcff19abab">llvm::SelectionDAG::getCopyFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acb59cbd8f4a8c1cf820b2b540aebdac1">llvm::SelectionDAG::getFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab85f5fcb2f3bb0aaf83041a41182a2d4">llvm::SelectionDAG::getIntPtrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2897ab064cc53e41f2b6ae3d69902abc">llvm::CCValAssign::getLocInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#aa531ef30c8af299cbbd1a6660b3cf225">llvm::CCValAssign::getLocMemOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a17dbc2feaea84ef8d353095d6e618f29">llvm::CCValAssign::getLocReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#ab7c2e47e51795ce2f60500846109d5a7">llvm::CCValAssign::getLocVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4590e453df8847d8d5eda7e37ae9dffa">llvm::SelectionDAG::getMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acfe1250a2214797a59c6457dd2180df9">llvm::SelectionDAG::getRegisterMask</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#ac57dc1a949dd5e9d1d7aef280f2a26e5">llvm::CCState::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6f9eed3ec877628ac2b052733cee4d4">llvm::SelectionDAG::getTargetExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a05c0ae3eb411a8c53a6ce48b66c0d3f8">llvm::SelectionDAG::getTargetGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#aa48b3b7e554b44f4e513d5dd8d9f9343">llvm::DataLayout::getTypeAllocSize</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a2dd702dca28f51ec1137faed5d0e5837">llvm::TargetLoweringBase::getVectorIdxTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a5640521ba3a9873a718e79f0bc49eadb">hasReturnsTwiceAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a423dda4ff918d4145ccc1861f059f940">llvm::TargetLowering::CallLoweringInfo::Ins</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a4a6fb3ac38359791e56965c6b5329e69">isAnyArgRegReserved</a>, <a href="#a4ae582227faa40eda6e7066409e56596">IsEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5bb903a1b21cafe8f73ce95ed629882e">llvm::CCValAssign::isMemLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aa8ab0804ddb40450da6549e1943817a2">llvm::TargetLowering::isPositionIndependent</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a07dddcff2886a2b840f993f7ce17dd28">llvm::CCValAssign::isRegLoc</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a283b7df55a414e3185b56aeea1ec7ee7">llvm::TargetLowering::CallLoweringInfo::IsTailCall</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a3eb6e80dc80f35553ccc33a89d691df8">llvm::TargetLowering::CallLoweringInfo::IsVarArg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5378385666bd865565fcf8407fcc36f9">llvm::CCValAssign::needsCustom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ad07ce660c9cb208ae98a53ad8b3ce1de">llvm::TargetLowering::CallLoweringInfo::Outs</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#adba9c4dde08bb0a9de1c99e7e039d8a0">llvm::TargetLowering::CallLoweringInfo::OutVals</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a701abf47478571dfb8c619678b7ce7d7">llvm::MachineFrameInfo::setHasTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a7fd25972cdb14499949c7726499e0cb6">llvm::CCValAssign::SExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a3c580eac1cc15b32f48917609a1bf56b">llvm::SPISD::TAIL_CALL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a255fe9c612d68137bc4af488c99f5a6e">toCallerWindow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c6d8f265e9e16e5debdb9a536b55d3d">llvm::ISD::UNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0aea5914496aa2e808c471c9855e9e2403">llvm::SparcMCExpr::VK_Sparc_WDISP30</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a590c6e92dc4e4a6bce8e55207c07afc0">llvm::SparcMCExpr::VK_Sparc_WPLT30</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a> and <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a807a4e133d7f743724d809a3f3875aa2">llvm::CCValAssign::ZExt</a>.</p>


<p>Referenced by <a href="#a466c698ef1cf9d946c2a69ef5ef3698e">LowerCall</a>.</p>

</div>
</div>

### LowerCall\_64() {#a796fb7765de0aab1aa00f7a13f5796f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerCall_64 (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">TargetLowering::CallLoweringInfo</a> &amp; CLI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 1223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45acc07b91f72979f3e9b12c2e0c355db46">llvm::CCValAssign::AExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a919797ac95a1d84d08e4f43eedededa4">llvm::CCState::AnalyzeCallOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a34218a663a02de9dc2d26a5639f58ebe">llvm::CCState::AnalyzeCallResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aee4f13218bdbb5c5697f7e786618ecb2">llvm::ISD::AssertSext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af23301e60475124fd80a2cb51f6ba863">llvm::ISD::AssertZext</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a0f94adbbe71c94edaa533a25973bbffc">llvm::CCValAssign::BCvt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35ad850a16944c76310207c76144c671fe6">llvm::SPISD::CALL</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae47a430364102f6e179d49cb3411b955">llvm::TargetLowering::CallLoweringInfo::CallConv</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a31faa4803c937d756c28947a070c6c2e">llvm::TargetLowering::CallLoweringInfo::Callee</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#acd79db0f7d45129e8af1258541861ef8">llvm::TargetLowering::CallLoweringInfo::CB</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#aa4872f31b8be67e8a1998454db0766bd">llvm::TargetLowering::CallLoweringInfo::Chain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a84c47705bcf7271413738ae8bf3871e6">llvm::ISD::CopyFromReg</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae76ac9826f02f95aae34e845ac110244">llvm::TargetLowering::CallLoweringInfo::DAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a3b6fcbb7bdd8ae29e8af4cd38bce7a40">llvm::TargetLowering::CallLoweringInfo::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#aa703537070b60dd03f662555fdd576ec">emitReservedArgRegCallError</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a4046c9ff3e500fb323f37cf298adc970">fixupVariableFloatArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a8b73d77b9e54663c2e80a48d0917dce1">llvm::CCValAssign::Full</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b631ac3ef73be923372fb2fb1de405e">llvm::SelectionDAG::getCALLSEQ_END</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9146909da2f666439a0a0a0a65e45100">llvm::SelectionDAG::getCALLSEQ_START</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6551350658729b36c93362fcff19abab">llvm::SelectionDAG::getCopyFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab85f5fcb2f3bb0aaf83041a41182a2d4">llvm::SelectionDAG::getIntPtrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2897ab064cc53e41f2b6ae3d69902abc">llvm::CCValAssign::getLocInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#aa531ef30c8af299cbbd1a6660b3cf225">llvm::CCValAssign::getLocMemOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a17dbc2feaea84ef8d353095d6e618f29">llvm::CCValAssign::getLocReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#ab7c2e47e51795ce2f60500846109d5a7">llvm::CCValAssign::getLocVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acfe1250a2214797a59c6457dd2180df9">llvm::SelectionDAG::getRegisterMask</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#ac57dc1a949dd5e9d1d7aef280f2a26e5">llvm::CCState::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6f9eed3ec877628ac2b052733cee4d4">llvm::SelectionDAG::getTargetExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a05c0ae3eb411a8c53a6ce48b66c0d3f8">llvm::SelectionDAG::getTargetGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5972ab02a98f9b5ce46e7f55fd711982">llvm::CCValAssign::getValVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a5640521ba3a9873a718e79f0bc49eadb">hasReturnsTwiceAttr</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a423dda4ff918d4145ccc1861f059f940">llvm::TargetLowering::CallLoweringInfo::Ins</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a4a6fb3ac38359791e56965c6b5329e69">isAnyArgRegReserved</a>, <a href="#a4ae582227faa40eda6e7066409e56596">IsEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#aa00f5c6b7e90595b7eaa2776a51e1c38">llvm::CCValAssign::isExtInLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5bb903a1b21cafe8f73ce95ed629882e">llvm::CCValAssign::isMemLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aa8ab0804ddb40450da6549e1943817a2">llvm::TargetLowering::isPositionIndependent</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a07dddcff2886a2b840f993f7ce17dd28">llvm::CCValAssign::isRegLoc</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a283b7df55a414e3185b56aeea1ec7ee7">llvm::TargetLowering::CallLoweringInfo::IsTailCall</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a3eb6e80dc80f35553ccc33a89d691df8">llvm::TargetLowering::CallLoweringInfo::IsVarArg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5378385666bd865565fcf8407fcc36f9">llvm::CCValAssign::needsCustom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ad07ce660c9cb208ae98a53ad8b3ce1de">llvm::TargetLowering::CallLoweringInfo::Outs</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#adba9c4dde08bb0a9de1c99e7e039d8a0">llvm::TargetLowering::CallLoweringInfo::OutVals</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a701abf47478571dfb8c619678b7ce7d7">llvm::MachineFrameInfo::setHasTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a7fd25972cdb14499949c7726499e0cb6">llvm::CCValAssign::SExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a3c580eac1cc15b32f48917609a1bf56b">llvm::SPISD::TAIL_CALL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a255fe9c612d68137bc4af488c99f5a6e">toCallerWindow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0aea5914496aa2e808c471c9855e9e2403">llvm::SparcMCExpr::VK_Sparc_WDISP30</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a590c6e92dc4e4a6bce8e55207c07afc0">llvm::SparcMCExpr::VK_Sparc_WPLT30</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a> and <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a807a4e133d7f743724d809a3f3875aa2">llvm::CCValAssign::ZExt</a>.</p>


<p>Referenced by <a href="#a466c698ef1cf9d946c2a69ef5ef3698e">LowerCall</a>.</p>

</div>
</div>

### LowerConstantPool() {#ae827a181342834e756f5baeb36360a67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerConstantPool (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 2192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>Reference <a href="#a8c1423d81607a5548a57bf11a3ab447c">makeAddress</a>.</p>


<p>Referenced by <a href="#ae64cc4af32654deb89d3073cc5ef4290">LowerOperation</a>.</p>

</div>
</div>

### LowerF128\_LibCallArg() {#a525e9355bccd735cf648afbde45acfc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerF128_LibCallArg (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae4ac6bc14db22dbd7b94a3b1bd276796">ArgListTy</a> &amp; Args, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Arg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 2306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1ae307f415a8989475e3f7ddd6eefc8b">llvm::MachineFrameInfo::CreateStackObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acb59cbd8f4a8c1cf820b2b540aebdac1">llvm::SelectionDAG::getFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab0cfceeb37508e56f9c127e59766a668">llvm::EVT::getTypeForEVT</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a6f174fc924aa9cccf2abce5ef4b5ec9a">llvm::Type::isFP128Ty</a>.</p>


<p>Referenced by <a href="#af92646d30b3f15471c866cd83fadfb62">LowerF128Compare</a> and <a href="#a85b82d7c69a744603ea8eccd2c40d52e">LowerF128Op</a>.</p>

</div>
</div>

### LowerF128Compare() {#af92646d30b3f15471c866cd83fadfb62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerF128Compare (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, unsigned &amp; SPCC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 2387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35aee173683795c69db043c057180a0c24e">llvm::SPISD::CMPICC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a80f16f53e18c59ae3681b303cda7a308">llvm::SPCC::FCC_E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9aed8356273fdf3a0487c872cb3d085542">llvm::SPCC::FCC_G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9ac202b4c5d9c55d73489b315c7e393836">llvm::SPCC::FCC_GE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a965bae47c4fccd3973ecbf040869ff7f">llvm::SPCC::FCC_L</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a607f8b24c191bb766a34c2eb1bfb63c4">llvm::SPCC::FCC_LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a53356323fdd97606927cec5c20cd6215">llvm::SPCC::FCC_LG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a488d679dc60c1f44701c9f0af8aa5d2c">llvm::SPCC::FCC_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9ab6d11f42acc70a53b6bf5d36feb0f6e8">llvm::SPCC::FCC_O</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a6820b0c58a07365f1341ca30d64bd218">llvm::SPCC::FCC_U</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9abaea969a35799493146fdd78c36dfa4c">llvm::SPCC::FCC_UE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a2106f4522bd06f6daad2a8e8769a6270">llvm::SPCC::FCC_UG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9ad38b12aa07c4354222b6b9422bbb90d6">llvm::SPCC::FCC_UGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9afbb30e35da42c9cac83731fe3709387b">llvm::SPCC::FCC_UL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a0823c4f36acc84808ba44f1f92fe58f2">llvm::SPCC::FCC_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0f68c9c0e4a38aebd5773f80dd5b716">llvm::SelectionDAG::getEntryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa8f1c26a4e070ead6c67b4e9a5d93124">llvm::SelectionDAG::getExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9ac1dc27bfc24df99cd29246ec54419659">llvm::SPCC::ICC_E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a2e9b359e236c3f89d1cd1646419a0438">llvm::SPCC::ICC_G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9ab9a7855b45288146df6d3ab3e321c43b">llvm::SPCC::ICC_NE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aafb9a152dd1ee4089f5fc96a33c5c90d2">llvm::TargetLoweringBase::LibCall</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aabd42a6eddc3daec9153679b54f79300">llvm::TargetLowering::LowerCallTo</a>, <a href="#a525e9355bccd735cf648afbde45acfc5">LowerF128_LibCallArg</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#af85f2971df75297dfac1455dc7211b11">llvm::TargetLowering::CallLoweringInfo::setCallee</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae8c9a19c4e49854df72efd6a33299ca6">llvm::TargetLowering::CallLoweringInfo::setChain</a> and <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#aa05efb86ccf079a618d7ccc2d0984510">llvm::TargetLowering::CallLoweringInfo::setDebugLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#aa4e01dc958f21a55df83d4fc9b811999">LowerBR_CC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#ad6539bf0f1a9d3264ca7797741a5fbe6">LowerSELECT_CC</a>.</p>

</div>
</div>

### LowerF128Op() {#a85b82d7c69a744603ea8eccd2c40d52e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerF128Op (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * LibFuncName, unsigned numArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 2333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1ae307f415a8989475e3f7ddd6eefc8b">llvm::MachineFrameInfo::CreateStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0f68c9c0e4a38aebd5773f80dd5b716">llvm::SelectionDAG::getEntryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa8f1c26a4e070ead6c67b4e9a5d93124">llvm::SelectionDAG::getExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acb59cbd8f4a8c1cf820b2b540aebdac1">llvm::SelectionDAG::getFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6f174fc924aa9cccf2abce5ef4b5ec9a">llvm::Type::isFP128Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aabd42a6eddc3daec9153679b54f79300">llvm::TargetLowering::LowerCallTo</a>, <a href="#a525e9355bccd735cf648afbde45acfc5">LowerF128_LibCallArg</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#af85f2971df75297dfac1455dc7211b11">llvm::TargetLowering::CallLoweringInfo::setCallee</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae8c9a19c4e49854df72efd6a33299ca6">llvm::TargetLowering::CallLoweringInfo::setChain</a> and <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#aa05efb86ccf079a618d7ccc2d0984510">llvm::TargetLowering::CallLoweringInfo::setDebugLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#ad9f2a3ee0460ca9514c403597bae9c89">LowerF128_FPEXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a8f372bae6d4902915c7d2070917438c6">LowerF128_FPROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a484d63924acd6ae7d8af32aed5161f50">LowerFP_TO_SINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a019e4e53b69fe324f03f9a3ace47c2cd">LowerFP_TO_UINT</a>, <a href="#ae64cc4af32654deb89d3073cc5ef4290">LowerOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afff765831cac78f912587a320a211573">LowerSINT_TO_FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a068cd28641dad2c75711d91843724394">LowerUINT_TO_FP</a> and <a href="#a16e6c862a36871c4f388c826ad65b07c">ReplaceNodeResults</a>.</p>

</div>
</div>

### LowerFormalArguments() {#a2b83fd7e57877c0eb7870a661b533f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerFormalArguments (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a405578f0decf5610edec9f350a54e81f">LowerFormalArguments_32</a> and <a href="#ae87be78c50d3026c58e203aa8f0b9164">LowerFormalArguments_64</a>.</p>

</div>
</div>

### LowerFormalArguments\_32() {#a405578f0decf5610edec9f350a54e81f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerFormalArguments_32 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LowerFormalArguments32 - V8 uses a very simple ABI, where all values are passed in either one or two GPRs, including FP values.</p>


<p>TODO: we should pass FP values in FP registers for fastcc functions.</p>


<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac9cfa172b885cad0eba3d7c9527568ad">llvm::MachineFunction::addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#ac889107f09b05137fd5964343a935a6c">llvm::MachineRegisterInfo::addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#aec8b01e38583a4e371e14c436324d3be">llvm::CCState::AnalyzeFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aee4f13218bdbb5c5697f7e786618ecb2">llvm::ISD::AssertSext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a41bd84b853e2c03fb1af1f4ca9ebdcaf">llvm::ISD::BUILD_PAIR</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a03cf34252938b54f7e86c736f9fd7dc1">llvm::MachineFrameInfo::CreateFixedObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a5c77792a06583e0fe7a0379ad94a2809">llvm::MachineRegisterInfo::createVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6551350658729b36c93362fcff19abab">llvm::SelectionDAG::getCopyFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0f68c9c0e4a38aebd5773f80dd5b716">llvm::SelectionDAG::getEntryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a191a65cff7d80b2651df427db2bbf908">llvm::CCState::getFirstUnallocated</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acb59cbd8f4a8c1cf820b2b540aebdac1">llvm::SelectionDAG::getFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#aa531ef30c8af299cbbd1a6660b3cf225">llvm::CCValAssign::getLocMemOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a17dbc2feaea84ef8d353095d6e618f29">llvm::CCValAssign::getLocReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#ab7c2e47e51795ce2f60500846109d5a7">llvm::CCValAssign::getLocVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0b02716fe6bb52c384caec3a1f8268be">llvm::SelectionDAG::getRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmachinefunctioninfo/#a2a786ba8981b248449df08e2134ac96e">llvm::SparcMachineFunctionInfo::getSRetReturnReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#ac57dc1a949dd5e9d1d7aef280f2a26e5">llvm::CCState::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5972ab02a98f9b5ce46e7f55fd711982">llvm::CCValAssign::getValVT</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aa73c6ba4efcd37a9afc738793d50b2c9">llvm::Function::hasStructRetAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a377365b0288a4d06a07e09252d7d583f">llvm::DataLayout::isLittleEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5bb903a1b21cafe8f73ce95ed629882e">llvm::CCValAssign::isMemLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a07dddcff2886a2b840f993f7ce17dd28">llvm::CCValAssign::isRegLoc</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5378385666bd865565fcf8407fcc36f9">llvm::CCValAssign::needsCustom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmachinefunctioninfo/#ae23a83eb98f8a37d7a4f7fedd16cb29e">llvm::SparcMachineFunctionInfo::setSRetReturnReg</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>.</p>


<p>Referenced by <a href="#a2b83fd7e57877c0eb7870a661b533f23">LowerFormalArguments</a>.</p>

</div>
</div>

### LowerFormalArguments\_64() {#ae87be78c50d3026c58e203aa8f0b9164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerFormalArguments_64 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool isVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; InVals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac9cfa172b885cad0eba3d7c9527568ad">llvm::MachineFunction::addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#aec8b01e38583a4e371e14c436324d3be">llvm::CCState::AnalyzeFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aee4f13218bdbb5c5697f7e786618ecb2">llvm::ISD::AssertSext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af23301e60475124fd80a2cb51f6ba863">llvm::ISD::AssertZext</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a03cf34252938b54f7e86c736f9fd7dc1">llvm::MachineFrameInfo::CreateFixedObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6551350658729b36c93362fcff19abab">llvm::SelectionDAG::getCopyFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acb59cbd8f4a8c1cf820b2b540aebdac1">llvm::SelectionDAG::getFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1a78b9f867cb5be3a052d6ad972484ca">llvm::TargetLoweringBase::getRegClassFor</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#ac57dc1a949dd5e9d1d7aef280f2a26e5">llvm::CCState::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a7fd25972cdb14499949c7726499e0cb6">llvm::CCValAssign::SExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a> and <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a807a4e133d7f743724d809a3f3875aa2">llvm::CCValAssign::ZExt</a>.</p>


<p>Referenced by <a href="#a2b83fd7e57877c0eb7870a661b533f23">LowerFormalArguments</a>.</p>

</div>
</div>

### LowerGlobalAddress() {#a62e3c214132d2e3b30de28f2d99d4122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerGlobalAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 2187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>Reference <a href="#a8c1423d81607a5548a57bf11a3ab447c">makeAddress</a>.</p>


<p>Referenced by <a href="#ae64cc4af32654deb89d3073cc5ef4290">LowerOperation</a>.</p>

</div>
</div>

### LowerGlobalTLSAddress() {#ab44a5ddbc927f9b63731bf050dee8048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerGlobalTLSAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 2202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120aa530fb2056fbb72e132893eba6ff4883">llvm::TLSModel::GeneralDynamic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b631ac3ef73be923372fb2fb1de405e">llvm::SelectionDAG::getCALLSEQ_END</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9146909da2f666439a0a0a0a65e45100">llvm::SelectionDAG::getCALLSEQ_START</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6551350658729b36c93362fcff19abab">llvm::SelectionDAG::getCopyFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0f68c9c0e4a38aebd5773f80dd5b716">llvm::SelectionDAG::getEntryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode/#aac749351927cd1732994a39d40fdd4f2">llvm::GlobalAddressSDNode::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acfe1250a2214797a59c6457dd2180df9">llvm::SelectionDAG::getRegisterMask</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa99670b16fe6d370e306896cd91b6fa6">llvm::SelectionDAG::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6f9eed3ec877628ac2b052733cee4d4">llvm::SelectionDAG::getTargetExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a07028bb765a646ca5ca5375162a93d7c">llvm::TargetMachine::getTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35ac6381bf059519add497cb2da3a33db6f">llvm::SPISD::GLOBAL_BASE_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a154b73611a4eb455f9b37af8b9e09e8b">llvm::SPISD::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120a3cae4242c478d473bfa1af350f126545">llvm::TLSModel::InitialExec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a9e72c1acace3b907901e215f668085a6">llvm::SPISD::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120a110e377ad85dc311cb9bce1e32bea8aa">llvm::TLSModel::LocalDynamic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120ae13ef3bbe423ce80086f0a684fd25753">llvm::TLSModel::LocalExec</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#afdea2f06c6c1098b324fa2e2a1b9b2f4">llvm::TargetLowering::LowerToTLSEmulatedModel</a>, <a href="#a54b7a062e4a4b0e09e407970da1e18ec">makeHiLoPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a5bb88f5f9d77d753e87c256950f16955">llvm::MachineFrameInfo::setHasCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a06394b87de34caf1268847eafe1da5b2">llvm::SPISD::TLS_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a0689b4f4adb0bc28f3ec0cb2f7241f5a">llvm::SPISD::TLS_CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a8d369f22424360c97ef7bb6459701598">llvm::SPISD::TLS_LD</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a650b3b6ac132345d10690adc3e3f418c">llvm::TargetMachine::useEmulatedTLS</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0acd233ef9284f92629e64c89b21f0a86d">llvm::SparcMCExpr::VK_Sparc_TLS_GD_ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0abeeb1275ea190bb3a8760a0eb4a887ac">llvm::SparcMCExpr::VK_Sparc_TLS_GD_CALL</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a9dad0b01511e8face16f8cc70e062232">llvm::SparcMCExpr::VK_Sparc_TLS_GD_HI22</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a3ac71b33573ef43ff8b5013b6f4dc25d">llvm::SparcMCExpr::VK_Sparc_TLS_GD_LO10</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a2fb42d09a2de76428d48ae8410688513">llvm::SparcMCExpr::VK_Sparc_TLS_IE_ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a63a897e43fa1abd5e60bbfc19ca092db">llvm::SparcMCExpr::VK_Sparc_TLS_IE_HI22</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0ac1c8bab39c32c4e9bcae30a5a24a349d">llvm::SparcMCExpr::VK_Sparc_TLS_IE_LD</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0aacaa5b6c84b1210758ec39748a642e21">llvm::SparcMCExpr::VK_Sparc_TLS_IE_LDX</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a8252eb7a6b7e4164527e2348ead44be0">llvm::SparcMCExpr::VK_Sparc_TLS_IE_LO10</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a58061e0f2d8f042fa6e7fdfcc177ed0a">llvm::SparcMCExpr::VK_Sparc_TLS_LDM_ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a7e414d3bc27c693f028487410a850e31">llvm::SparcMCExpr::VK_Sparc_TLS_LDM_CALL</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0affc01e91a9afd407ed37897246d29002">llvm::SparcMCExpr::VK_Sparc_TLS_LDM_HI22</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a0ff450acb7f2102251d49cdc5e264b73">llvm::SparcMCExpr::VK_Sparc_TLS_LDM_LO10</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0ae022bee41da8708e26dee16ab90a4dcc">llvm::SparcMCExpr::VK_Sparc_TLS_LDO_ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0aff138a104ddd424331d02569e1cb379c">llvm::SparcMCExpr::VK_Sparc_TLS_LDO_HIX22</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a47a470d16ff4332499b0169602010ba8">llvm::SparcMCExpr::VK_Sparc_TLS_LDO_LOX10</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a372f87e883df69c3b70e82db21cc6fec">llvm::SparcMCExpr::VK_Sparc_TLS_LE_HIX22</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a5570cce2bee83481fe954962ae3e6c06">llvm::SparcMCExpr::VK_Sparc_TLS_LE_LOX10</a>, <a href="#a1a6633d479bd7811ef8c96ebb8372ee7">withTargetFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>.</p>


<p>Referenced by <a href="#ae64cc4af32654deb89d3073cc5ef4290">LowerOperation</a>.</p>

</div>
</div>

### LowerINTRINSIC\_WO\_CHAIN() {#a9049c6bff42f918ef0156327330b026c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerINTRINSIC_WO_CHAIN (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>.</p>


<p>Referenced by <a href="#ae64cc4af32654deb89d3073cc5ef4290">LowerOperation</a>.</p>

</div>
</div>

### LowerOperation() {#ae64cc4af32654deb89d3073cc5ef4290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerOperation (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c47226f266248f4b8c155b83601b109">llvm::ISD::ATOMIC_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1db943abc1bf78a911daeb7b03d81de8">llvm::ISD::ATOMIC_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb">llvm::ISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa71ac22470bf853868fe6b39a25bac72">llvm::ISD::DYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2b4d07600495a563319d6a3dda8dc44d">llvm::ISD::FABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abc6c09c7af98236460f0b020eb3be94e">llvm::ISD::FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178">llvm::ISD::FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d26c45c040d8f85d577a5f645261d1a">llvm::ISD::FNEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdb38c8daa8c1ab881007062d113cef3">llvm::ISD::FRAMEADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae1118ddac1ce0af8e9f7cc16c9e94fc0">llvm::ISD::FSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad">llvm::ISD::FSUB</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae365cf8f9a6844685be3fd9f12956c33">llvm::TargetLoweringBase::getLibcallName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#aa8913052bffd3cb40dfb554ce578e6b9">LowerATOMIC_LOAD_STORE</a>, <a href="#a58d1040bc9ca646c704f74ba3a076098">LowerBlockAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#aa4e01dc958f21a55df83d4fc9b811999">LowerBR_CC</a>, <a href="#ae827a181342834e756f5baeb36360a67">LowerConstantPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a5a204a396ded16cd692c0dc91ce216f4">LowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#ad9f2a3ee0460ca9514c403597bae9c89">LowerF128_FPEXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a8f372bae6d4902915c7d2070917438c6">LowerF128_FPROUND</a>, <a href="#a85b82d7c69a744603ea8eccd2c40d52e">LowerF128Op</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#adf6a42cc1a9f660d92f18fdb7004fa1e">LowerFNEGorFABS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a484d63924acd6ae7d8af32aed5161f50">LowerFP_TO_SINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a019e4e53b69fe324f03f9a3ace47c2cd">LowerFP_TO_UINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a6db5b08ff3c4b9eb3b6892f59612f526">LowerFRAMEADDR</a>, <a href="#a62e3c214132d2e3b30de28f2d99d4122">LowerGlobalAddress</a>, <a href="#ab44a5ddbc927f9b63731bf050dee8048">LowerGlobalTLSAddress</a>, <a href="#a9049c6bff42f918ef0156327330b026c">LowerINTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a3fedecc58b422c10a3527f8f5db694bf">LowerLOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afa7dd71b99cc3f038bc3f91104cf66ee">LowerRETURNADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#ad6539bf0f1a9d3264ca7797741a5fbe6">LowerSELECT_CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afff765831cac78f912587a320a211573">LowerSINT_TO_FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#adb9776e3c9f8cf35e243fe5585cdafd3">LowerSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a068cd28641dad2c75711d91843724394">LowerUINT_TO_FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#ae1416413e8b25024ca51882c2e1cd4db">LowerVAARG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcisellowering-cpp/#a9ca04dd1028e57cb539334540a46beea">LowerVASTART</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2dfacb29792dd59f2cfbe529206265bc">llvm::ISD::RETURNADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae77d03846b31c41c4860bcd96d780a78">llvm::ISD::VAARG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adfe32beaa596a1512b17e66b46e773ed">llvm::ISD::VASTART</a>.</p>

</div>
</div>

### LowerReturn() {#a7deb9a2cf7eca6e363907cf09b677a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerReturn (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a97357df4054a9551eb9a07b609cea109">LowerReturn_32</a> and <a href="#aa76596666bd4af3c0104b7a8fd514db0">LowerReturn_64</a>.</p>

</div>
</div>

### LowerReturn\_32() {#a97357df4054a9551eb9a07b609cea109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerReturn_32 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool IsVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutVals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a73b07a938dd8182363ba52719d38bf53">llvm::CCState::AnalyzeReturn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6551350658729b36c93362fcff19abab">llvm::SelectionDAG::getCopyFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a17dbc2feaea84ef8d353095d6e618f29">llvm::CCValAssign::getLocReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#ab7c2e47e51795ce2f60500846109d5a7">llvm::CCValAssign::getLocVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmachinefunctioninfo/#a2a786ba8981b248449df08e2134ac96e">llvm::SparcMachineFunctionInfo::getSRetReturnReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a2dd702dca28f51ec1137faed5d0e5837">llvm::TargetLoweringBase::getVectorIdxTy</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aa73c6ba4efcd37a9afc738793d50b2c9">llvm::Function::hasStructRetAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a07dddcff2886a2b840f993f7ce17dd28">llvm::CCValAssign::isRegLoc</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5378385666bd865565fcf8407fcc36f9">llvm::CCValAssign::needsCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a53cf9620d59d409ce4ac938c8a69c033">llvm::SPISD::RET_GLUE</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a7deb9a2cf7eca6e363907cf09b677a03">LowerReturn</a>.</p>

</div>
</div>

### LowerReturn\_64() {#aa76596666bd4af3c0104b7a8fd514db0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::LowerReturn_64 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool IsVarArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutVals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45acc07b91f72979f3e9b12c2e0c355db46">llvm::CCValAssign::AExt</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a73b07a938dd8182363ba52719d38bf53">llvm::CCState::AnalyzeReturn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a8b73d77b9e54663c2e80a48d0917dce1">llvm::CCValAssign::Full</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2897ab064cc53e41f2b6ae3d69902abc">llvm::CCValAssign::getLocInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a17dbc2feaea84ef8d353095d6e618f29">llvm::CCValAssign::getLocReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#ab7c2e47e51795ce2f60500846109d5a7">llvm::CCValAssign::getLocVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5972ab02a98f9b5ce46e7f55fd711982">llvm::CCValAssign::getValVT</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a07dddcff2886a2b840f993f7ce17dd28">llvm::CCValAssign::isRegLoc</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5378385666bd865565fcf8407fcc36f9">llvm::CCValAssign::needsCustom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a53cf9620d59d409ce4ac938c8a69c033">llvm::SPISD::RET_GLUE</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a7fd25972cdb14499949c7726499e0cb6">llvm::CCValAssign::SExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a> and <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a807a4e133d7f743724d809a3f3875aa2">llvm::CCValAssign::ZExt</a>.</p>


<p>Referenced by <a href="#a7deb9a2cf7eca6e363907cf09b677a03">LowerReturn</a>.</p>

</div>
</div>

### makeAddress() {#a8c1423d81607a5548a57bf11a3ab447c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::makeAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 2128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#aa85a26f5f6b24110a2388e4726cdd282">getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0f68c9c0e4a38aebd5773f80dd5b716">llvm::SelectionDAG::getEntryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#aa70144cee705b3f0db7f53ff3bf004e9">llvm::MachinePointerInfo::getGOT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35ac6381bf059519add497cb2da3a33db6f">llvm::SPISD::GLOBAL_BASE_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aa8ab0804ddb40450da6549e1943817a2">llvm::TargetLowering::isPositionIndependent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a9e72c1acace3b907901e215f668085a6">llvm::SPISD::Lo</a>, <a href="#a54b7a062e4a4b0e09e407970da1e18ec">makeHiLoPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a5bb88f5f9d77d753e87c256950f16955">llvm::MachineFrameInfo::setHasCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a>, <a href="/web-llvm/docs/api/namespaces/llvm/piclevel/#a66ddbf1bb21f90ddc44260d1ca677b6ba930654495acf7b77bcf00f2c65c32347">llvm::PICLevel::SmallPIC</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a0a52e554a258a7d372633a1c06e3fcf8">llvm::SparcMCExpr::VK_Sparc_GOT10</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a44a67d006ec25ec5260bd980ba20fc6c">llvm::SparcMCExpr::VK_Sparc_GOT13</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a567ee252480e04bf85b1fc21844ccc08">llvm::SparcMCExpr::VK_Sparc_GOT22</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a149694e627b7a3afd016ae37cc1abf18">llvm::SparcMCExpr::VK_Sparc_H44</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0aacdc766ee0cae5af952c551c6efc0ce6">llvm::SparcMCExpr::VK_Sparc_HH</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a7cc3a40023555c0f1f8ec0fb52e14643">llvm::SparcMCExpr::VK_Sparc_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0aa3ed710d0eceeff3a3657b87612459e7">llvm::SparcMCExpr::VK_Sparc_HM</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a33e42b130d33bc70b96779be96719c95">llvm::SparcMCExpr::VK_Sparc_L44</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0a7d943f8130bcbcbe1d07fc8093a0d828">llvm::SparcMCExpr::VK_Sparc_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0acd9a32326cc297655ce42f1cb302b68b">llvm::SparcMCExpr::VK_Sparc_M44</a> and <a href="#a1a6633d479bd7811ef8c96ebb8372ee7">withTargetFlags</a>.</p>


<p>Referenced by <a href="#a58d1040bc9ca646c704f74ba3a076098">LowerBlockAddress</a>, <a href="#ae827a181342834e756f5baeb36360a67">LowerConstantPool</a> and <a href="#a62e3c214132d2e3b30de28f2d99d4122">LowerGlobalAddress</a>.</p>

</div>
</div>

### makeHiLoPair() {#a54b7a062e4a4b0e09e407970da1e18ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::makeHiLoPair (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, unsigned HiTF, unsigned LoTF, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 2116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a154b73611a4eb455f9b37af8b9e09e8b">llvm::SPISD::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spisd/#a3d1898cf75ca99cdce12d228aad03d35a9e72c1acace3b907901e215f668085a6">llvm::SPISD::Lo</a> and <a href="#a1a6633d479bd7811ef8c96ebb8372ee7">withTargetFlags</a>.</p>


<p>Referenced by <a href="#ab44a5ddbc927f9b63731bf050dee8048">LowerGlobalTLSAddress</a> and <a href="#a8c1423d81607a5548a57bf11a3ab447c">makeAddress</a>.</p>

</div>
</div>

### PerformBITCASTCombine() {#a9f32b61ceb023325bed9e826ade5d6e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::PerformBITCASTCombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="#a2107ac6ce763ed1ad3e60ba0e473139b">bitcastConstantFPToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#acf37bd7e831bdb2a5c9da8d63f843101">llvm::TargetLowering::DAGCombinerInfo::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a975d8653451eccbb54e12c11b39f1990">PerformDAGCombine</a>.</p>

</div>
</div>

### PerformDAGCombine() {#a975d8653451eccbb54e12c11b39f1990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::PerformDAGCombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a9f32b61ceb023325bed9e826ade5d6e4">PerformBITCASTCombine</a>.</p>

</div>
</div>

### ReplaceNodeResults() {#a16e6c862a36871c4f388c826ad65b07c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SparcTargetLowering::ReplaceNodeResults (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3483 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a41bd84b853e2c03fb1af1f4ca9ebdcaf">llvm::ISD::BUILD_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#a80f0411207d75b649465f8505a2609f6">llvm::MemSDNode::getAAInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#a20fd5ba47db6a4cc8ad9d197fc1bbbee">llvm::LoadSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ab858661e16a61c4fc6b27b6b26aac17b">llvm::MemSDNode::getChain</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6551350658729b36c93362fcff19abab">llvm::SelectionDAG::getCopyFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#ad85ec82447c2f1824538de9b449ffed0">llvm::LoadSDNode::getExtensionType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a03140e92d989c9a96312035efb8f67fc">llvm::SelectionDAG::getExtLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#ab991bb1444579648a165d1b134a0854d">llvm::MachineMemOperand::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae365cf8f9a6844685be3fd9f12956c33">llvm::TargetLoweringBase::getLibcallName</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aa078a60d1127b9daad580b6d2ba7ef91">llvm::MemSDNode::getMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aee0e58997cd08983518f051e79b855d9">llvm::MemSDNode::getMemoryVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#a85cc92919f7704331920d260e71a7439">llvm::MemSDNode::getOriginalAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ab58a98ad2eb07046ef0584d2bc8f1d2d">llvm::MemSDNode::getPointerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac0a534d63ac5c5b87f36acdade953fbe">llvm::SDNode::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="#a85b82d7c69a744603ea8eccd2c40d52e">LowerF128Op</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac43f9bea13e29622bbf18c861b52144d">llvm::ISD::READCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>.</p>

</div>
</div>

### shouldExpandAtomicRMWInIR() {#a29137845e271a0520a8f1c3c397faf50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AtomicExpansionKind SparcTargetLowering::shouldExpandAtomicRMWInIR (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * RMW)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 1508 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a369f472273bc816735055f13a6e6fd6c">llvm::TargetLoweringBase::CmpXChg</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a99fd4ef84981d6a2774c14c741b5ed65">llvm::AtomicRMWInst::getOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a6adf97f83acf6453d4a6a4b1070f3754">llvm::TargetLoweringBase::None</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77">llvm::AtomicRMWInst::Xchg</a>.</p>

</div>
</div>

### shouldInsertFencesForAtomic() {#a045327926fd1d9568e3c573b3a57f099}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SparcTargetLowering::shouldInsertFencesForAtomic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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


<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### ShouldShrinkFPConstant() {#aea64b94dec6ae1dd7d09aee6d3879991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SparcTargetLowering::ShouldShrinkFPConstant (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
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

<p>If true, then instruction selection should seek to shrink the FP constant of the specified type to a smaller type in order to save space and / or reduce runtime.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>.</p>

</div>
</div>

### useLoadStackGuardNode() {#adbada954ccf57e9f3a90869f740419b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SparcTargetLowering::useLoadStackGuardNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 3559 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ad2b27b633b21a362571660ad09273d52">llvm::TargetLowering::useLoadStackGuardNode</a>.</p>

</div>
</div>

### useSoftFloat() {#a1f0b79c7c0f89f0a0309f622ff4f8310}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SparcTargetLowering::useSoftFloat ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 1991 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>

</div>
</div>

### withTargetFlags() {#a1a6633d479bd7811ef8c96ebb8372ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue SparcTargetLowering::withTargetFlags (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, unsigned TF, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>, definition at line 2089 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac28c549afb9f9751d45c37dc9a9b9a7d">llvm::SelectionDAG::getTargetBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aeab75f932b62381e1db6624dff1c2636">llvm::SelectionDAG::getTargetConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6f9eed3ec877628ac2b052733cee4d4">llvm::SelectionDAG::getTargetExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a05c0ae3eb411a8c53a6ce48b66c0d3f8">llvm::SelectionDAG::getTargetGlobalAddress</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#ab44a5ddbc927f9b63731bf050dee8048">LowerGlobalTLSAddress</a>, <a href="#a8c1423d81607a5548a57bf11a3ab447c">makeAddress</a> and <a href="#a54b7a062e4a4b0e09e407970da1e18ec">makeHiLoPair</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Subtarget {#abdc824653365e8bf338f35c33e76779a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SparcSubtarget* llvm::SparcTargetLowering::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp">SparcISelLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-h">SparcISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
