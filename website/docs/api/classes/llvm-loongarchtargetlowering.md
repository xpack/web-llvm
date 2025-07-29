---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loongarchtargetlowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LoongArchTargetLowering` Class



## Declaration

<div class="doxyDeclaration">
class llvm::LoongArchTargetLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">Target/LoongArch/LoongArchISelLowering.h</a>"
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">bool <a href="#aba75fbfbfee8a3ad46ccd903e38d93be">LoongArchCCAssignFn</a>(const DataLayout &DL, LoongArchABI::ABI ABI, unsigned ValNo, MVT ValVT, CCValAssign::LocInfo LocInfo, ISD::ArgFlagsTy ArgFlags, CCState &State, bool IsFixed, bool IsRet, Type *OrigTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-specific function used to lower <a href="/web-llvm/docs/api/namespaces/llvm/loongarch">LoongArch</a> calling conventions. <a href="#aba75fbfbfee8a3ad46ccd903e38d93be">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae88df257bb50084c96393d09161583e6">LoongArchTargetLowering</a> (const TargetMachine &amp;TM, const LoongArchSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loongarchsubtarget">LoongArchSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf37c127ac8908b234cac97735e4901">getSubtarget</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba733a912432252bb046a162e451a378">isOffsetFoldingLegal</a> (const GlobalAddressSDNode *GA) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if folding a constant offset with the given GlobalAddress is legal. <a href="#aba733a912432252bb046a162e451a378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ef534d36e46abca83eac5efaa895f19">LowerOperation</a> (SDValue Op, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is invoked for operations that are unsupported by the target, which are registered to use 'custom' lowering, and whose defined values are all legal. <a href="#a5ef534d36e46abca83eac5efaa895f19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac83ceb8e67e1ee6ca693e3ff1ffbac0f">ReplaceNodeResults</a> (SDNode *N, SmallVectorImpl&lt; SDValue &gt; &amp;Results, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is invoked when a node result type is illegal for the target, and the operation was registered to use 'custom' lowering for that result type. <a href="#ac83ceb8e67e1ee6ca693e3ff1ffbac0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a114238b6f08e91873cbd29bae3f069c3">PerformDAGCombine</a> (SDNode *N, DAGCombinerInfo &amp;DCI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be invoked for all target nodes and for any target-independent nodes that the target has registered with invoke it for. <a href="#a114238b6f08e91873cbd29bae3f069c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87bf38d6764b70f2bc18bfee326a7b52">getTargetNodeName</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns the name of a target specific DAG node. <a href="#a87bf38d6764b70f2bc18bfee326a7b52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4e7be374a3346400a32967d91108c3e">LowerFormalArguments</a> (SDValue Chain, CallingConv::ID CallConv, bool IsVarArg, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const SDLoc &amp;DL, SelectionDAG &amp;DAG, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower the incoming (formal) arguments, described by the Ins array, into the specified DAG. <a href="#af4e7be374a3346400a32967d91108c3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4645ff56012ec55aea9987f6200f2a2">CanLowerReturn</a> (CallingConv::ID CallConv, MachineFunction &amp;MF, bool IsVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, LLVMContext &amp;Context, const Type *RetTy) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook should be implemented to check whether the return values described by the Outs array can fit into the return registers. <a href="#af4645ff56012ec55aea9987f6200f2a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aece826681b1fdc9ec7c82f4a9152000f">LowerReturn</a> (SDValue Chain, CallingConv::ID CallConv, bool IsVarArg, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const SmallVectorImpl&lt; SDValue &gt; &amp;OutVals, const SDLoc &amp;DL, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower outgoing return values, described by the Outs array, into the specified DAG. <a href="#aece826681b1fdc9ec7c82f4a9152000f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45d8aec8b73256f724d9c7517306f030">LowerCall</a> (TargetLowering::CallLoweringInfo &amp;CLI, SmallVectorImpl&lt; SDValue &gt; &amp;InVals) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower calls into the specified DAG. <a href="#a45d8aec8b73256f724d9c7517306f030">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9565be01bfa9b95ffa4ca88646b21f72">isCheapToSpeculateCttz</a> (Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is cheap to speculate a call to intrinsic cttz. <a href="#a9565be01bfa9b95ffa4ca88646b21f72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aa724bc41e0e125707ebb4f2d56aa05">isCheapToSpeculateCtlz</a> (Type *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is cheap to speculate a call to intrinsic ctlz. <a href="#a5aa724bc41e0e125707ebb4f2d56aa05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab478fcd80e64e7adf9de2d41c40363ca">hasAndNot</a> (SDValue Y) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target has a bitwise and-not operation: X = ~A &amp; B This can be used to simplify select or other instructions. <a href="#ab478fcd80e64e7adf9de2d41c40363ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLowering::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5916c5a40e28fd6b62ec267bfe57e43d">shouldExpandAtomicRMWInIR</a> (AtomicRMWInst *AI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the IR-level AtomicExpand pass should expand the given AtomicRMW, if at all. <a href="#a5916c5a40e28fd6b62ec267bfe57e43d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3d0b842e1c779edc912cf2863bd5fcd">emitExpandAtomicRMW</a> (AtomicRMWInst *AI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a atomicrmw expansion using a target-specific way. <a href="#ad3d0b842e1c779edc912cf2863bd5fcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6afb7e7298c87508bd965772db54ec19">emitMaskedAtomicRMWIntrinsic</a> (IRBuilderBase &amp;Builder, AtomicRMWInst *AI, Value *AlignedAddr, Value *Incr, Value *Mask, Value *ShiftAmt, AtomicOrdering Ord) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a masked atomicrmw using a target-specific intrinsic. <a href="#a6afb7e7298c87508bd965772db54ec19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3612d2574f9af7ad6fe1fbd439141ef3">getSetCCResultType</a> (const DataLayout &amp;DL, LLVMContext &amp;Context, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a> of the result of SETCC operations. <a href="#a3612d2574f9af7ad6fe1fbd439141ef3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84">TargetLowering::AtomicExpansionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f3b0d090892cc5dd71222862723e231">shouldExpandAtomicCmpXchgInIR</a> (AtomicCmpXchgInst *CI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the given atomic cmpxchg should be expanded by the IR-level AtomicExpand pass. <a href="#a2f3b0d090892cc5dd71222862723e231">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34f5b50de28a2e4f6aa78069f36c9816">emitMaskedAtomicCmpXchgIntrinsic</a> (IRBuilderBase &amp;Builder, AtomicCmpXchgInst *CI, Value *AlignedAddr, Value *CmpVal, Value *NewVal, Value *Mask, AtomicOrdering Ord) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a masked cmpxchg using a target-specific intrinsic. <a href="#a34f5b50de28a2e4f6aa78069f36c9816">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a923a973f854adf14baf2b4bc75cce855">getTgtMemIntrinsic</a> (IntrinsicInfo &amp;Info, const CallInst &amp;I, MachineFunction &amp;MF, unsigned Intrinsic) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an intrinsic, checks if on the target the intrinsic will need to map to a MemIntrinsicNode (touches memory). <a href="#a923a973f854adf14baf2b4bc75cce855">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e2659b4bac369ae2aa509712d6af245">isFMAFasterThanFMulAndFAdd</a> (const MachineFunction &amp;MF, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if an FMA operation is faster than a pair of fmul and fadd instructions. <a href="#a3e2659b4bac369ae2aa509712d6af245">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ef533b3f965b127fb1557d19d50f6b1">getExceptionPointerRegister</a> (const Constant *PersonalityFn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register, this returns the register that receives the exception address on entry to an EH pad. <a href="#a7ef533b3f965b127fb1557d19d50f6b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac475f3e61b79916d73660b75c74c9403">getExceptionSelectorRegister</a> (const Constant *PersonalityFn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a physical register, this returns the register that receives the exception typeid on entry to a landing pad. <a href="#ac475f3e61b79916d73660b75c74c9403">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfe7f16ddfd462c6af041f6d5121143a">isFsqrtCheap</a> (SDValue Operand, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if SQRT(X) shouldn't be replaced with X*RSQRT(X). <a href="#adfe7f16ddfd462c6af041f6d5121143a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21d5aa7b68dde74be2f35a4e633109b0">getSqrtEstimate</a> (SDValue Operand, SelectionDAG &amp;DAG, int Enabled, int &amp;RefinementSteps, bool &amp;UseOneConstNR, bool Reciprocal) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hooks for building estimates in place of slower divisions and square roots. <a href="#a21d5aa7b68dde74be2f35a4e633109b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4045f6be99c3e145e4d8c51ea9646b">getRecipEstimate</a> (SDValue Operand, SelectionDAG &amp;DAG, int Enabled, int &amp;RefinementSteps) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reciprocal estimate value for the input operand. <a href="#aed4045f6be99c3e145e4d8c51ea9646b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8780ea85a4823ea04c360157f4b31a53">getExtendForAtomicOps</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the platform's atomic operations are extended (ZERO_EXTEND, SIGN_EXTEND, or ANY_EXTEND). <a href="#a8780ea85a4823ea04c360157f4b31a53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad80bf09d08cd002a0ecb9f707c436469">getExtendForAtomicCmpSwapArg</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns how the platform's atomic compare and swap expects its comparison value to be extended (ZERO_EXTEND, SIGN_EXTEND, or ANY_EXTEND). <a href="#ad80bf09d08cd002a0ecb9f707c436469">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae7bdcf65f4ce313299a333956258f10">getRegisterByName</a> (const char *RegName, LLT VT, const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the name passed in. <a href="#aae7bdcf65f4ce313299a333956258f10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8e9c88323f8d9fe7be7b37f05397069">mayBeEmittedAsTailCall</a> (const CallInst *CI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target may be able emit the call instruction as a tail call. <a href="#af8e9c88323f8d9fe7be7b37f05397069">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b9031dbdb100545e0f3a0c0b11efe03">decomposeMulByConstant</a> (LLVMContext &amp;Context, EVT VT, SDValue C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is profitable to transform an integer multiplication-by-constant into simpler operations like shifts and adds. <a href="#a4b9031dbdb100545e0f3a0c0b11efe03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cb17d64ed4f7499fba8ffcf1dfca7db">isUsedByReturnOnly</a> (SDNode *N, SDValue &amp;Chain) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if result of the specified node is used by a return node only. <a href="#a0cb17d64ed4f7499fba8ffcf1dfca7db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97827ae16535ba63871ef5a031909264">isLegalAddressingMode</a> (const DataLayout &amp;DL, const AddrMode &amp;AM, Type *Ty, unsigned AS, Instruction *I=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the addressing mode represented by AM is legal for this target, for a load/store of the specified type. <a href="#a97827ae16535ba63871ef5a031909264">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b720caeeb3d526f78b95e517536582">isLegalICmpImmediate</a> (int64_t Imm) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified immediate is legal icmp immediate, that is the target has icmp instructions which can compare a register against the immediate without having to materialize the immediate into a register. <a href="#a28b720caeeb3d526f78b95e517536582">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9454e2103e4288c189bce5fb7f7ba2b8">isLegalAddImmediate</a> (int64_t Imm) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified immediate is legal add immediate, that is the target has add instructions which can add a register with the immediate without having to materialize the immediate into a register. <a href="#a9454e2103e4288c189bce5fb7f7ba2b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d2ec1ce7215cedcdc42943f9bac07af">isZExtFree</a> (SDValue Val, EVT VT2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if zero-extending the specific node Val to type VT2 is free (either because it's implicitly zero-extended such as <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> ldrb / ldrh or because it's folded such as <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> zero-extending loads). <a href="#a7d2ec1ce7215cedcdc42943f9bac07af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5911cf68d89bae0e4709656bc02eff29">isSExtCheaperThanZExt</a> (EVT SrcVT, EVT DstVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if sign-extension from FromTy to ToTy is cheaper than zero-extension. <a href="#a5911cf68d89bae0e4709656bc02eff29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a808bb58d9e36f7e9c27b5606d6a9e7d0">signExtendConstant</a> (const ConstantInt *CI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this constant should be sign extended when promoting to a larger type. <a href="#a808bb58d9e36f7e9c27b5606d6a9e7d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed3ff8fad69ca37f759203cafc789f39">hasAndNotCompare</a> (SDValue Y) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target should transform: (X &amp; Y) == Y ---&gt; (~X &amp; Y) == 0 (X &amp; Y) != Y ---&gt; (~X &amp; Y) != 0. <a href="#aed3ff8fad69ca37f759203cafc789f39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f0d882e507c522c5393dfc6051f5318">convertSelectOfConstantsToMath</a> (EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a select of constants (select Cond, C1, C2) should be transformed into simple math ops with the condition value. <a href="#a0f0d882e507c522c5393dfc6051f5318">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a4f92e4ca4ddb847b8dde652bd6a779">allowsMisalignedMemoryAccesses</a> (EVT VT, unsigned AddrSpace=0, Align Alignment=Align(1), MachineMemOperand::Flags Flags=MachineMemOperand::MONone, unsigned *Fast=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the target supports unaligned memory accesses. <a href="#a5a4f92e4ca4ddb847b8dde652bd6a779">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0775baf95feccdf4651a817f5899af2c">isShuffleMaskLegal</a> (ArrayRef&lt; int &gt; Mask, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets can use this to indicate that they only support <em>some</em> VECTOR_SHUFFLE operations, those with specific masks. <a href="#a0775baf95feccdf4651a817f5899af2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba6c89645db02d840b73f8732ac60bee">shouldConsiderGEPOffsetSplit</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bf8f8ed2aa15edbba86ec715f21823a">shouldSignExtendTypeInLibCall</a> (Type *Ty, bool IsSigned) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if arguments should be sign-extended in lib calls. <a href="#a9bf8f8ed2aa15edbba86ec715f21823a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab04541bff69db3996f2b64ecfb14c8f">shouldExtendTypeInLibCall</a> (EVT Type) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if arguments should be extended in lib calls. <a href="#aab04541bff69db3996f2b64ecfb14c8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f8cd8acbf7bece2f42aa6c412abf2f5">shouldAlignPointerArgs</a> (CallInst *CI, unsigned &amp;MinSize, Align &amp;PrefAlign) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the pointer arguments to CI should be aligned by aligning the object whose address is being passed. <a href="#a5f8cd8acbf7bece2f42aa6c412abf2f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4695f8c8ca9c1bec88785e099c49814">isFPImmVLDILegal</a> (const APFloat &amp;Imm, EVT VT) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2fe9aa84c9cdfd1e3d1e2b860b224a">analyzeInputArgs</a> (MachineFunction &amp;MF, CCState &amp;CCInfo, const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, bool IsRet, LoongArchCCAssignFn Fn) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b414f8384a983b0fe1c3c00e74f79b2">analyzeOutputArgs</a> (MachineFunction &amp;MF, CCState &amp;CCInfo, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, bool IsRet, CallLoweringInfo *CLI, LoongArchCCAssignFn Fn) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4d7ad91400a763a2c78dbbb05d5b172c">getAddr</a> (NodeTy *N, SelectionDAG &amp;DAG, CodeModel::Model M, bool IsLocal=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95cd8c33b49a3aef1307f392c66734b2">getStaticTLSAddr</a> (GlobalAddressSDNode *N, SelectionDAG &amp;DAG, unsigned Opc, bool UseGOT, bool Large=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b34c62886ef4ed63948b943f16e4dc3">getDynamicTLSAddr</a> (GlobalAddressSDNode *N, SelectionDAG &amp;DAG, unsigned Opc, bool Large=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf8d054a548a958438a4f710d9d34c4e">getTLSDescAddr</a> (GlobalAddressSDNode *N, SelectionDAG &amp;DAG, unsigned Opc, bool Large=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48900be575ae843f16b5a7aedb3f242d">lowerGlobalAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50505ff9aca974085fdbefd54d792f73">lowerBlockAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a886da5746dc5abe106d447cb6eb89e0c">lowerJumpTable</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7efd8c5ef6c4470f6986a390be39d738">lowerGlobalTLSAddress</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc3a4d93ac3c0483206740d768781069">lowerShiftLeftParts</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35e93477834cdd084df977d7bf7efe72">lowerShiftRightParts</a> (SDValue Op, SelectionDAG &amp;DAG, bool IsSRA) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a990cf077ce2bdde571005399b362a">EmitInstrWithCustomInserter</a> (MachineInstr &amp;MI, MachineBasicBlock *BB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'usesCustomInserter' flag. <a href="#a17a990cf077ce2bdde571005399b362a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aca120488258f07b7e3c0c1eec7c153">lowerATOMIC_FENCE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2b31000228f3dd36420b8ad5c247d95">lowerConstantPool</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42f8e09a8221db518e46525c33c99f9d">lowerEH_DWARF_CFA</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f467d2ba15c8cd72612869674a8671a">lowerFP_TO_SINT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeedcda3f3b69b154df54cc32a393431">lowerBITCAST</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4c7c1cda2a7d17da62a785253dba6a4">lowerUINT_TO_FP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1bbf20d43bed2520eae76b89f458520">lowerSINT_TO_FP</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4c6deb9d5229738118cc8f3d6692b45">lowerVASTART</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac311ad578e20c51c618b7474f5d295d4">lowerINTRINSIC_WO_CHAIN</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf25989cc9726857525ceeba198d08e0">lowerINTRINSIC_W_CHAIN</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d3338661a30ca962047628b1d1f9093">lowerINTRINSIC_VOID</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a341c7a0df73920b7cedcfd298d1fb6df">lowerFRAMEADDR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8dc72a43d265fedc741e25f33087df7">lowerRETURNADDR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac13079dc4ac88c9631aba9e57b0f6a9f">lowerWRITE_REGISTER</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d10811a47135dc8b270478ed7c9f1d4">lowerEXTRACT_VECTOR_ELT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f7e410368c1e031973262654d532d3">lowerINSERT_VECTOR_ELT</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2faa77a056f9439888b4b16369bf6f5">lowerBUILD_VECTOR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c25798034f9391164a3f63c16e79fd8">lowerVECTOR_SHUFFLE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb33705eaea1a9a3660c7904ee022803">lowerBITREVERSE</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa95e270670363d89a936fabc63e34d31">lowerSCALAR_TO_VECTOR</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab18bcc0c5944ef1ed0c251f8b9a6aecc">lowerPREFETCH</a> (SDValue Op, SelectionDAG &amp;DAG) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a650cced7777c1d02f4bdd4010f2293">isFPImmLegal</a> (const APFloat &amp;Imm, EVT VT, bool ForCodeSize) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target can instruction select the specified FP immediate natively. <a href="#a9a650cced7777c1d02f4bdd4010f2293">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae87408d59695398ba2997aa645e476c2">shouldInsertFencesForAtomic</a> (const Instruction *I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether <a href="/web-llvm/docs/api/classes/llvm/atomicexpandpass">AtomicExpandPass</a> should automatically insert fences and reduce ordering for this atomic. <a href="#ae87408d59695398ba2997aa645e476c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116">ConstraintType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a492e47c6d86f32c814dfb5624feea4fe">getConstraintType</a> (StringRef Constraint) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a constraint, return the type of constraint it is for this target. <a href="#a492e47c6d86f32c814dfb5624feea4fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a411187f959588c75b111946638544d64">getInlineAsmMemConstraint</a> (StringRef ConstraintCode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5743b130308cfad517210da4f828a595">getRegForInlineAsmConstraint</a> (const TargetRegisterInfo *TRI, StringRef Constraint, MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a physical register constraint (e.g. <a href="#a5743b130308cfad517210da4f828a595">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af37026f64d4c27be7b6aff27e608b72f">LowerAsmOperandForConstraint</a> (SDValue Op, StringRef Constraint, std::vector&lt; SDValue &gt; &amp;Ops, SelectionDAG &amp;DAG) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower the specified operand into the Ops vector. <a href="#af37026f64d4c27be7b6aff27e608b72f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11dd4d91f75bad3490380d1c31ada3c2">isEligibleForTailCallOptimization</a> (CCState &amp;CCInfo, CallLoweringInfo &amp;CLI, MachineFunction &amp;MF, const SmallVectorImpl&lt; CCValAssign &gt; &amp;ArgLocs) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a095935285d20d68f893fd1783b0879fb">softPromoteHalfType</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loongarchsubtarget">LoongArchSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bd1be36d40cc60dfe89a46b83fe41a1">Subtarget</a></td>
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


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LoongArchCCAssignFn {#aba75fbfbfee8a3ad46ccd903e38d93be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef bool llvm::LoongArchTargetLowering::LoongArchCCAssignFn(const DataLayout &amp;DL, LoongArchABI::ABI ABI, unsigned ValNo, MVT ValVT, CCValAssign::LocInfo LocInfo, ISD::ArgFlagsTy ArgFlags, CCState &amp;State, bool IsFixed, bool IsRet, Type *OrigTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Target-specific function used to lower <a href="/web-llvm/docs/api/namespaces/llvm/loongarch">LoongArch</a> calling conventions.</p>

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LoongArchTargetLowering() {#ae88df257bb50084c96393d09161583e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoongArchTargetLowering::LoongArchTargetLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loongarchsubtarget">LoongArchSubtarget</a> &amp; STI)</td>
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



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7c45a718f16057459d95d09d42ec6902">llvm::TargetLoweringBase::addRegisterClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9c91befeca2a25c8050d4c3dff8b6d67">llvm::ISD::ATOMIC_CMP_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a385d7f9c63f921a2b28e8426e4101de8">llvm::ISD::ATOMIC_FENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeea401cc0b7fa5aa6f4d3a0612140e1d">llvm::ISD::BITREVERSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb">llvm::ISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716d19ebad1927a2e8dd5fe3f951f882">llvm::ISD::BR_JT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a477ef80c70c7359199eace0e5d3133b1">llvm::ISD::BUILTIN_OP_END</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6df03220bbe2ea3cfb905f36fb26822c">llvm::TargetLoweringBase::computeRegisterProperties</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5">llvm::ISD::CONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c">llvm::ISD::CTLZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a991d07d163bd4d9984cf1ef36e92c214">llvm::ISD::CTPOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6da41a113af0909470baea7486b3386b">llvm::ISD::CTTZ</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa3441acf8576e4bbf48e9bd73ca3c0d8c">llvm::TargetLoweringBase::Custom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a967fcb624e84458e135a763d1c11346a">llvm::ISD::DEBUGTRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa71ac22470bf853868fe6b39a25bac72">llvm::ISD::DYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abad932e63381a4671b5db19a3404c82e">llvm::ISD::EH_DWARF_CFA</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa4b85349547c5b6126817e10152007931">llvm::TargetLoweringBase::Expand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">llvm::ISD::EXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad56e9199ae3993a09af36ff41d327a11">llvm::ISD::FCEIL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9133d7cfb6a66404ff7757b699bc3941">llvm::ISD::FCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abc6c09c7af98236460f0b020eb3be94e">llvm::ISD::FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4336c27826676e1ef61383cafa999219">llvm::ISD::FFLOOR</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a850652b63276e9d79e6c1e05146c84c0">llvm::MVT::fixedlen_vector_valuetypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a25e670389809910f59726e8a11fa82e0">llvm::ISD::FMAXNUM_IEEE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a907932b29f929b1827b1b93171dcaa3c">llvm::ISD::FMINNUM_IEEE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178">llvm::ISD::FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d26c45c040d8f85d577a5f645261d1a">llvm::ISD::FNEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3e12fcc9960ef3bf0ae5876382d4c66f">llvm::ISD::FP16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a38f379e4fddf750c36f1323a04d12171">llvm::ISD::FP_TO_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1a6952b1572a4ce241cc3cf45a9ab071">llvm::ISD::FPOW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdd7bbb76dac7962dda6e116e33699da">llvm::ISD::FREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a68014623710f7a44c808cd412236d6a1">llvm::ISD::FRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab3cb85375f983765b93341d57a2f3838">llvm::ISD::FROUNDEVEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad46ae9fdfe20cd04f7fda7ccbb937543">llvm::ISD::FSIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6ba8fc92ee5081d3e533cb5322f74f29">llvm::ISD::FSINCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae1118ddac1ce0af8e9f7cc16c9e94fc0">llvm::ISD::FSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad">llvm::ISD::FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1e92ea554489509b0ad970901bcc715b">llvm::ISD::FTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a76b6d3008e806ea613323ff316ef72c3">llvm::ISD::IS_FPCLASS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0c70100db6ddc0b37b56feb242145cf4">llvm::ISD::JumpTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adb1de74d602ef905e06785e0052b55bf">llvm::ISD::LROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa2a7c3eccf06b41e4275bbeadb46d22e">llvm::ISD::MULHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8a80d3b085af08f0dce1724207ef99b5">llvm::ISD::MULHU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a691a4c9004e9bd04d1c0bebc5df57443">llvm::ISD::PREFETCH</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aaba91ac521e4f01f57413216273fd7b7f">llvm::TargetLoweringBase::Promote</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92fceabd268d62ef2c95799a102b8abf">llvm::ISD::READ_REGISTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715">llvm::ISD::ROTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6b928e5a6718acab4fa0030ce9198e8a">llvm::TargetLoweringBase::setBooleanContents</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0662d63e058816bf77a5b8f35331bd9d">llvm::TargetLoweringBase::setBooleanVectorContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#abbec47c0a3f39ed8fa200ccc9933318f">llvm::TargetLoweringBase::setCondCodeAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a7f47862de23f7210f88ccf98ae1efbe4">llvm::ISD::SETGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a5ad12b466e3a5900d0c307b301465d25">llvm::ISD::SETGT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad1d4d71bf37fea6a3170f27438d41e6d">llvm::TargetLoweringBase::setLoadExtAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4df001a3c611cc8b423ca0e54560210f">llvm::TargetLoweringBase::setMaxAtomicSizeInBitsSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3ddb810ec23c0f90abd0d5085e86ed50">llvm::TargetLoweringBase::setMaxBytesForAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab6a8a4a9115087b5dd7aa1dbff26a193">llvm::TargetLoweringBase::setMinCmpXchgSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6566d8c65c03ad2f7b18ed08f0e7f208">llvm::TargetLoweringBase::setMinFunctionAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ac7bb30d4918c1ee9dd208083154e109f">llvm::ISD::SETOGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a31d1e24e08b255d6aa290d67d16ce2c9">llvm::ISD::SETOGT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a07c0c67913bb543fc45ce9ef65ef260a">llvm::TargetLoweringBase::setOperationAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8bb50938977c871d4dfa617d1b759a9a">llvm::TargetLoweringBase::setPrefFunctionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4aebe88e5c44bdb37513651bc72c2889">llvm::TargetLoweringBase::setPrefLoopAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab8a44fb1f49bcfbed806fef69301a67a">llvm::TargetLoweringBase::setStackPointerRegisterToSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac87dc82fa9f824a797198e7b0e16141d">llvm::TargetLoweringBase::setTargetDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa243085e56636cc454143f916686c190">llvm::TargetLoweringBase::setTruncStoreAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a9dff1dcbac65852b71473818c11869b1">llvm::ISD::SETUGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a292be4a9782030bfad637581d25a5897">llvm::ISD::SETUGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af3b59179b6fcbc89463181015ace8e9b">llvm::ISD::SMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaac895215ecbb3c411c957c8beb39b70">llvm::ISD::SMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1354c6f8508d6cd697dc89a5d9a52dfd">llvm::ISD::SMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a023a9de787026fe61b024476bf9c32cb">llvm::ISD::STACKRESTORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a031ce694e40832d40a163d7254a8df14">llvm::ISD::STACKSAVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0466b21bfb4f3596e41380d8e2d1956f">llvm::ISD::STRICT_FSETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c8d07d668872f2176fb34724cd799c4">llvm::ISD::STRICT_FSETCCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aaa96f111a59a7a2e7f9c689b344543df">llvm::TargetLowering::TargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac5fb8808f3dcb9f0a83f1fc2e7747485">llvm::ISD::TRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af675e759c0ffff8d48ea14a60fe3517b">llvm::ISD::UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a17126302da6199930e55e841ca1b082d">llvm::ISD::UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a79c959df09509d7ff66d9b04bc40d18d">llvm::ISD::UMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c6d8f265e9e16e5debdb9a536b55d3d">llvm::ISD::UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28">llvm::ISD::UREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae77d03846b31c41c4860bcd96d780a78">llvm::ISD::VAARG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a804c1960ac64628cdd1f74d7de885284">llvm::ISD::VACOPY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1aadbb14ab26b74d841ac003363e3a5d">llvm::ISD::VAEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adfe32beaa596a1512b17e66b46e773ed">llvm::ISD::VASTART</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0b7d2c769fd0fbaab3c4a2fc8e7ea0c">llvm::ISD::VSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a61a1595d03afe86764ad7625d358608e">llvm::ISD::WRITE_REGISTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a695a19c9c3ae14638be151add82755cb">llvm::TargetLoweringBase::ZeroOrNegativeOneBooleanContent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a0e2d72cfdcc49d2d189f440b3cc31dff">llvm::TargetLoweringBase::ZeroOrOneBooleanContent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allowsMisalignedMemoryAccesses() {#a5a4f92e4ca4ddb847b8dde652bd6a779}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::allowsMisalignedMemoryAccesses (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>, unsigned AddrSpace=0, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(1), <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dd">MachineMemOperand::Flags</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">MachineMemOperand::MONone</a>, unsigned *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the target supports unaligned memory accesses.</p>


<p>This function returns true if the target allows unaligned memory accesses of the specified type in the given address space. If true, it also returns a relative speed of the unaligned memory access in the last argument by reference. The higher the speed number the faster the operation comparing to a number returned by another such call. This is used, for example, in situations where an array copy/move/set is converted to a sequence of store operations. Its use helps to ensure that such replacements don't generate code that causes an alignment error (trap) on the target machine.</p>


<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 4786 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>.</p>

</div>
</div>

### CanLowerReturn() {#af4645ff56012ec55aea9987f6200f2a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::CanLowerReturn (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5757 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a54bef4de515c1876b876bac86b81975c">CC_LoongArch</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a8b73d77b9e54663c2e80a48d0917dce1">llvm::CCValAssign::Full</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### convertSelectOfConstantsToMath() {#a0f0d882e507c522c5393dfc6051f5318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoongArchTargetLowering::convertSelectOfConstantsToMath (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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


<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>.</p>

</div>
</div>

### decomposeMulByConstant() {#a4b9031dbdb100545e0f3a0c0b11efe03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::decomposeMulByConstant (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> C)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#ad958859a7af278dd5ea2b593c2b25050">llvm::EVT::isScalarInteger</a>.</p>

</div>
</div>

### emitExpandAtomicRMW() {#ad3d0b842e1c779edc912cf2863bd5fcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchTargetLowering::emitExpandAtomicRMW (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * AI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a atomicrmw expansion using a target-specific way.</p>


<p>This is expected to be called when masked atomicrmw and bit test atomicrmw don't work, and the target supports another way to lower atomicrmw.</p>


<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5912 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a660a31179bfecd737a256372e5fd6122">llvm::AtomicRMWInst::And</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab2a2c89b21cf14b2c729a898006cb438">llvm::IRBuilderBase::CreateAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a89f675aadae7232445c74ee4167ff591">llvm::IRBuilderBase::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8aeced5e71d2589fa3e9791043af5cb">llvm::PointerType::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a99fd4ef84981d6a2774c14c741b5ed65">llvm::AtomicRMWInst::getOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#aefa60bfe67b4721c395ce966ac73b439">llvm::AtomicRMWInst::getOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a506260aecca4d92e8633628f8d4b83ae">llvm::AtomicRMWInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#ac97b19e5c8e2843543087d67e47be222">llvm::AtomicRMWInst::getSyncScopeID</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#ae55438e0a802a1a20d6dcabf71b552ad">llvm::AtomicRMWInst::getValOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5954f59053121b87ebe0c5fe79942c6e">llvm::AtomicRMWInst::Or</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a71aab8ee954b6d71a4eed315e8f6556e">llvm::AtomicRMWInst::Xor</a>.</p>

</div>
</div>

### emitMaskedAtomicCmpXchgIntrinsic() {#a34f5b50de28a2e4f6aa78069f36c9816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * LoongArchTargetLowering::emitMaskedAtomicCmpXchgIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst">AtomicCmpXchgInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * AlignedAddr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CmpVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Mask, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ord)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6058 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a514c327438f006bc3fe66da51943b5cb">llvm::AtomicCmpXchgInst::getFailureOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a95df4f20c933779306b9a936b88b99a5">llvm::IRBuilderBase::getIntN</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>

</div>
</div>

### emitMaskedAtomicRMWIntrinsic() {#a6afb7e7298c87508bd965772db54ec19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * LoongArchTargetLowering::emitMaskedAtomicRMWIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * AI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * AlignedAddr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Incr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Mask, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ShiftAmt, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ord)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6077 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a660a31179bfecd737a256372e5fd6122">llvm::AtomicRMWInst::And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab2a2c89b21cf14b2c729a898006cb438">llvm::IRBuilderBase::CreateAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a89f675aadae7232445c74ee4167ff591">llvm::IRBuilderBase::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a92c83e803f2cf22906da0aaec44ff6d7">llvm::IRBuilderBase::CreateSub</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a0b5bee42a0652f7f46ec24c924e610d7">llvm::AtomicRMWInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a95df4f20c933779306b9a936b88b99a5">llvm::IRBuilderBase::getIntN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#af52b5cf263a7dfc130b83dc9b82385ae">getIntrinsicForMaskedAtomicRMWBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a99fd4ef84981d6a2774c14c741b5ed65">llvm::AtomicRMWInst::getOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#aefa60bfe67b4721c395ce966ac73b439">llvm::AtomicRMWInst::getOrdering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#ae55438e0a802a1a20d6dcabf71b552ad">llvm::AtomicRMWInst::getValOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a13cc1f5d3225f4ec063520a747acec4c">llvm::ConstantInt::isMinusOne</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a882d55a6aa2028e1a5ad708b275334e0">llvm::ConstantInt::isZero</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2">llvm::AtomicRMWInst::Max</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d">llvm::AtomicRMWInst::Min</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5954f59053121b87ebe0c5fe79942c6e">llvm::AtomicRMWInst::Or</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77">llvm::AtomicRMWInst::Xchg</a>.</p>

</div>
</div>

### getExceptionPointerRegister() {#a7ef533b3f965b127fb1557d19d50f6b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register LoongArchTargetLowering::getExceptionPointerRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PersonalityFn)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### getExceptionSelectorRegister() {#ac475f3e61b79916d73660b75c74c9403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register LoongArchTargetLowering::getExceptionSelectorRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * PersonalityFn)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### getExtendForAtomicCmpSwapArg() {#ad80bf09d08cd002a0ecb9f707c436469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::NodeType LoongArchTargetLowering::getExtendForAtomicCmpSwapArg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns how the platform's atomic compare and swap expects its comparison value to be extended (ZERO_EXTEND, SIGN_EXTEND, or ANY_EXTEND).</p>


<p>This is separate from getExtendForAtomicOps, which is concerned with the sign-extension of the instruction's output, whereas here we are concerned with the sign-extension of the input. For targets with compare-and-swap instructions (or sub-word comparisons in their LL/SC loop expansions), the input can be ANY_EXTEND, but the output will still have a specific extension.</p>


<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6546 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>.</p>

</div>
</div>

### getExtendForAtomicOps() {#a8780ea85a4823ea04c360157f4b31a53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::NodeType llvm::LoongArchTargetLowering::getExtendForAtomicOps ()</td>
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

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>.</p>

</div>
</div>

### getRecipEstimate() {#aed4045f6be99c3e145e4d8c51ea9646b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::getRecipEstimate (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Operand, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, int Enabled, int &amp; RefinementSteps)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cbb26a6b04c9a328e0e0966881da33fa8e243db2e3806dcf4997c408a355ddfc">llvm::TargetLoweringBase::Enabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173da468ab4eca324aeab0cd676e2439e9adc">llvm::LoongArchISD::FRECIPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a358de7df4d2c34f66bcce7dbe0253cd7">getEstimateRefinementSteps</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cbb26a6b04c9a328e0e0966881da33faef4d83ea802e3b855bf36ea9689414b9">llvm::TargetLoweringBase::Unspecified</a>.</p>

</div>
</div>

### getRegisterByName() {#aae7bdcf65f4ce313299a333956258f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register LoongArchTargetLowering::getRegisterByName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RegName, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/asmparser/avrasmparser-cpp/#a12e31c0c30a774b7e1a19becc5fa1890">MatchRegisterAltName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a4ff6b3fd769bb0563feaa4fd3e58e23f">MatchRegisterName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a>.</p>

</div>
</div>

### getSetCCResultType() {#a3612d2574f9af7ad6fe1fbd439141ef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT LoongArchTargetLowering::getSetCCResultType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5872 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a0351571482fea42a3b326147fb2ce9e2">llvm::EVT::changeVectorElementTypeToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### getSqrtEstimate() {#a21d5aa7b68dde74be2f35a4e633109b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::getSqrtEstimate (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Operand, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, int Enabled, int &amp; RefinementSteps, bool &amp; UseOneConstNR, bool Reciprocal)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cbb26a6b04c9a328e0e0966881da33fa8e243db2e3806dcf4997c408a355ddfc">llvm::TargetLoweringBase::Enabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178">llvm::ISD::FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173daa21f8bd517cb679984facaac23390c28">llvm::LoongArchISD::FRSQRTE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a358de7df4d2c34f66bcce7dbe0253cd7">getEstimateRefinementSteps</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cbb26a6b04c9a328e0e0966881da33faef4d83ea802e3b855bf36ea9689414b9">llvm::TargetLoweringBase::Unspecified</a>.</p>

</div>
</div>

### getSubtarget() {#a1cf37c127ac8908b234cac97735e4901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoongArchSubtarget &amp; llvm::LoongArchTargetLowering::getSubtarget ()</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>.</p>

</div>
</div>

### getTargetNodeName() {#a87bf38d6764b70f2bc18bfee326a7b52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LoongArchTargetLowering::getTargetNodeName (unsigned Opcode)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 4798 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173daa9409a153dcb4da4dd167053ce07b78e">llvm::LoongArchISD::FIRST_NUMBER</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#a5a3237f2dd913ef611a858ffc74366bc">NODE_NAME_CASE</a>.</p>

</div>
</div>

### getTgtMemIntrinsic() {#a923a973f854adf14baf2b4bc75cce855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::getTgtMemIntrinsic (<a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/intrinsicinfo">IntrinsicInfo</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;, unsigned)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5885 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda796891d6ca349b671fce24b6d01d77a8">llvm::MachineMemOperand::MOVolatile</a>.</p>

</div>
</div>

### hasAndNot() {#ab478fcd80e64e7adf9de2d41c40363ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::hasAndNot (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> X)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5880 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### hasAndNotCompare() {#aed3ff8fad69ca37f759203cafc789f39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::hasAndNotCompare (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Y)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### isCheapToSpeculateCtlz() {#a5aa724bc41e0e125707ebb4f2d56aa05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::isCheapToSpeculateCtlz (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5849 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### isCheapToSpeculateCttz() {#a9565be01bfa9b95ffa4ca88646b21f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::isCheapToSpeculateCttz (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5845 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### isFMAFasterThanFMulAndFAdd() {#a3e2659b4bac369ae2aa509712d6af245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::isFMAFasterThanFMulAndFAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
</tr>
</table>
</td>
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


<p>NOTE: This may be called before legalization on types for which FMAs are not legal, but should return true if those types will eventually legalize to types that support FMAs. After legalization, it will only be called on types that support FMAs (via Legal or Custom actions)</p>


<p>Targets that care about soft float support should return false when soft float code is being generated (i.e. use-soft-float).</p>


<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>

</div>
</div>

### isFPImmVLDILegal() {#aa4695f8c8ca9c1bec88785e099c49814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::isFPImmVLDILegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Imm, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5817 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### isFsqrtCheap() {#adfe7f16ddfd462c6af041f6d5121143a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoongArchTargetLowering::isFsqrtCheap (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> X, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Return true if SQRT(X) shouldn't be replaced with X*RSQRT(X).</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>.</p>

</div>
</div>

### isLegalAddImmediate() {#a9454e2103e4288c189bce5fb7f7ba2b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::isLegalAddImmediate (int64_t)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6510 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>.</p>

</div>
</div>

### isLegalAddressingMode() {#a97827ae16535ba63871ef5a031909264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::isLegalAddressingMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode">AddrMode</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned AddrSpace, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6462 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a2d775e3fd8ebcd0941d1e12cbfccda3d">llvm::TargetLoweringBase::AddrMode::BaseGV</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a115ffe6d615735fbe8b1bf31877565ba">llvm::TargetLoweringBase::AddrMode::BaseOffs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8868c35de6c36dc0d57e84f256c4ffde">llvm::TargetLoweringBase::AddrMode::HasBaseReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a> and <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/addrmode/#a8ea7d02f0e4b0c1d37d6986ec9f7f5c0">llvm::TargetLoweringBase::AddrMode::Scale</a>.</p>

</div>
</div>

### isLegalICmpImmediate() {#a28b720caeeb3d526f78b95e517536582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::isLegalICmpImmediate (int64_t)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6506 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>.</p>

</div>
</div>

### isOffsetFoldingLegal() {#aba733a912432252bb046a162e451a378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::isOffsetFoldingLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * GA)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### isSExtCheaperThanZExt() {#a5911cf68d89bae0e4709656bc02eff29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::isSExtCheaperThanZExt (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> FromTy, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ToTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if sign-extension from FromTy to ToTy is cheaper than zero-extension.</p>

<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### isShuffleMaskLegal() {#a0775baf95feccdf4651a817f5899af2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoongArchTargetLowering::isShuffleMaskLegal (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt;, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
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

<p>Targets can use this to indicate that they only support <em>some</em> VECTOR_SHUFFLE operations, those with specific masks.</p>


<p>By default, if a target supports the VECTOR_SHUFFLE node, all mask values are assumed to be legal.</p>


<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>.</p>

</div>
</div>

### isUsedByReturnOnly() {#a0cb17d64ed4f7499fba8ffcf1dfca7db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::isUsedByReturnOnly (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5424 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93bc27ca4d9e211c54b0d9efb660f080">llvm::ISD::CopyToReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173daef4e84dbabd85304b0ab5cb2b22d41f1">llvm::LoongArchISD::RET</a>.</p>

</div>
</div>

### isZExtFree() {#a7d2ec1ce7215cedcdc42943f9bac07af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::isZExtFree (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT2)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6514 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a342be90695496b88a8854a775dfd030f">llvm::TargetLoweringBase::isZExtFree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6aacde2c67988b43a261a7f7ceac4be3">llvm::ISD::NON_EXTLOAD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>

</div>
</div>

### LowerCall() {#a45d8aec8b73256f724d9c7517306f030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::LowerCall (<a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">TargetLowering::CallLoweringInfo</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a471f60ab3308e8e2a12a42b0aae03111">llvm::SelectionDAG::addNoMergeSiteInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a919797ac95a1d84d08e4f43eedededa4">llvm::CCState::AnalyzeCallOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173daea7e732b7ad28bd5de4822cbcbe21424">llvm::LoongArchISD::CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173da995de542569efd8aeffa340e606fe7e3">llvm::LoongArchISD::CALL_LARGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173da9e54be457abe8f04aa81e8214b17eca2">llvm::LoongArchISD::CALL_MEDIUM</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae47a430364102f6e179d49cb3411b955">llvm::TargetLowering::CallLoweringInfo::CallConv</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a31faa4803c937d756c28947a070c6c2e">llvm::TargetLowering::CallLoweringInfo::Callee</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#acd79db0f7d45129e8af1258541861ef8">llvm::TargetLowering::CallLoweringInfo::CB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a54bef4de515c1876b876bac86b81975c">CC_LoongArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a7c58eb7c6cf6b55da864fe749fea62ad">CC_LoongArch_GHC</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#aa4872f31b8be67e8a1998454db0766bd">llvm::TargetLowering::CallLoweringInfo::Chain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a79833f5d23f7d199579738f2dc85ab60">convertLocVTToValVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a654343d6b7c4aa6aa1329f9ed421b225">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1ae307f415a8989475e3f7ddd6eefc8b">llvm::MachineFrameInfo::CreateStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae83b3d8e9a944b5d818e80524a5003e2">llvm::SelectionDAG::CreateStackTemporary</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae76ac9826f02f95aae34e845ac110244">llvm::TargetLowering::CallLoweringInfo::DAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a3b6fcbb7bdd8ae29e8af4cd38bce7a40">llvm::TargetLowering::CallLoweringInfo::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b631ac3ef73be923372fb2fb1de405e">llvm::SelectionDAG::getCALLSEQ_END</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9146909da2f666439a0a0a0a65e45100">llvm::SelectionDAG::getCALLSEQ_START</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ae106f6c6362377b3016f0d174227e193">llvm::TargetMachine::getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6551350658729b36c93362fcff19abab">llvm::SelectionDAG::getCopyFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acb59cbd8f4a8c1cf820b2b540aebdac1">llvm::SelectionDAG::getFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab85f5fcb2f3bb0aaf83041a41182a2d4">llvm::SelectionDAG::getIntPtrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2897ab064cc53e41f2b6ae3d69902abc">llvm::CCValAssign::getLocInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#aa531ef30c8af299cbbd1a6660b3cf225">llvm::CCValAssign::getLocMemOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a17dbc2feaea84ef8d353095d6e618f29">llvm::CCValAssign::getLocReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4590e453df8847d8d5eda7e37ae9dffa">llvm::SelectionDAG::getMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a531405bfbd93bc7c3464eea0d9144774">getPrefTypeAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acfe1250a2214797a59c6457dd2180df9">llvm::SelectionDAG::getRegisterMask</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#ac57dc1a949dd5e9d1d7aef280f2a26e5">llvm::CCState::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a1572b31fadbd0d758314b8d35a050410">llvm::EVT::getStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa99670b16fe6d370e306896cd91b6fa6">llvm::SelectionDAG::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6f9eed3ec877628ac2b052733cee4d4">llvm::SelectionDAG::getTargetExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a05c0ae3eb411a8c53a6ce48b66c0d3f8">llvm::SelectionDAG::getTargetGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a30aa4a06549273240892d58449b8d268">llvm::TargetLoweringBase::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45aacf7e7d80f766b55b2bbdaf3d354c39e">llvm::CCValAssign::Indirect</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a423dda4ff918d4145ccc1861f059f940">llvm::TargetLowering::CallLoweringInfo::Ins</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5bb903a1b21cafe8f73ce95ed629882e">llvm::CCValAssign::isMemLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a50426b12f4acb3d9f74d0778948e9597">llvm::CallBase::isMustTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a07dddcff2886a2b840f993f7ce17dd28">llvm::CCValAssign::isRegLoc</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a283b7df55a414e3185b56aeea1ec7ee7">llvm::TargetLowering::CallLoweringInfo::IsTailCall</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a3eb6e80dc80f35553ccc33a89d691df8">llvm::TargetLowering::CallLoweringInfo::IsVarArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078a47cd4b1e13d896a3c839c26ce7c9bace">llvm::LoongArchII::MO_CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a03a83eb6d12005ac7d43d370f4eb5078adc1fe3e72c9d5fd9003f77dfbf61505a">llvm::LoongArchII::MO_CALL_PLT</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#aa91cc3233b03071cdfbb5a88d90703c9">llvm::TargetLowering::CallLoweringInfo::NoMerge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ad07ce660c9cb208ae98a53ad8b3ce1de">llvm::TargetLowering::CallLoweringInfo::Outs</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#adba9c4dde08bb0a9de1c99e7e039d8a0">llvm::TargetLowering::CallLoweringInfo::OutVals</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a701abf47478571dfb8c619678b7ce7d7">llvm::MachineFrameInfo::setHasTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#aa3f0dc829be1fe9aa1c7d5151db1bf21">llvm::TargetMachine::shouldAssumeDSOLocal</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173da53b1450373a01565b0598c3679e45b74">llvm::LoongArchISD::TAIL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173da5ca4184707b9b7c314b7213ba4206039">llvm::LoongArchISD::TAIL_LARGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173dadb4b2bff938bc0a222fb3f68d9a8742c">llvm::LoongArchISD::TAIL_MEDIUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### LowerFormalArguments() {#af4e7be374a3346400a32967d91108c3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::LowerFormalArguments (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#aec8b01e38583a4e371e14c436324d3be">llvm::CCState::AnalyzeFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#aa88409177d80547eb31363501517a066">ArgGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a54bef4de515c1876b876bac86b81975c">CC_LoongArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a7c58eb7c6cf6b55da864fe749fea62ad">CC_LoongArch_GHC</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a03cf34252938b54f7e86c736f9fd7dc1">llvm::MachineFrameInfo::CreateFixedObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6551350658729b36c93362fcff19abab">llvm::SelectionDAG::getCopyFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a191a65cff7d80b2651df427db2bbf908">llvm::CCState::getFirstUnallocated</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acb59cbd8f4a8c1cf820b2b540aebdac1">llvm::SelectionDAG::getFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab85f5fcb2f3bb0aaf83041a41182a2d4">llvm::SelectionDAG::getIntPtrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2897ab064cc53e41f2b6ae3d69902abc">llvm::CCValAssign::getLocInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#ac57dc1a949dd5e9d1d7aef280f2a26e5">llvm::CCState::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5972ab02a98f9b5ce46e7f55fd711982">llvm::CCValAssign::getValVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45aacf7e7d80f766b55b2bbdaf3d354c39e">llvm::CCValAssign::Indirect</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a07dddcff2886a2b840f993f7ce17dd28">llvm::CCValAssign::isRegLoc</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#af586c31be6208a365b50ac3a892be6d7">unpackFromRegLoc</a>.</p>

</div>
</div>

### LowerOperation() {#a5ef534d36e46abca83eac5efaa895f19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::LowerOperation (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a385d7f9c63f921a2b28e8426e4101de8">llvm::ISD::ATOMIC_FENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeea401cc0b7fa5aa6f4d3a0612140e1d">llvm::ISD::BITREVERSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abad932e63381a4671b5db19a3404c82e">llvm::ISD::EH_DWARF_CFA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdb38c8daa8c1ab881007062d113cef3">llvm::ISD::FRAMEADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0c70100db6ddc0b37b56feb242145cf4">llvm::ISD::JumpTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a691a4c9004e9bd04d1c0bebc5df57443">llvm::ISD::PREFETCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2dfacb29792dd59f2cfbe529206265bc">llvm::ISD::RETURNADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adfe32beaa596a1512b17e66b46e773ed">llvm::ISD::VASTART</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a61a1595d03afe86764ad7625d358608e">llvm::ISD::WRITE_REGISTER</a>.</p>

</div>
</div>

### LowerReturn() {#aece826681b1fdc9ec7c82f4a9152000f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::LowerReturn (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5775 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a54bef4de515c1876b876bac86b81975c">CC_LoongArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a654343d6b7c4aa6aa1329f9ed421b225">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a17dbc2feaea84ef8d353095d6e618f29">llvm::CCValAssign::getLocReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#ab7c2e47e51795ce2f60500846109d5a7">llvm::CCValAssign::getLocVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a07dddcff2886a2b840f993f7ce17dd28">llvm::CCValAssign::isRegLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173daef4e84dbabd85304b0ab5cb2b22d41f1">llvm::LoongArchISD::RET</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### mayBeEmittedAsTailCall() {#af8e9c88323f8d9fe7be7b37f05397069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::mayBeEmittedAsTailCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/callinst/#a52104f0d6ca7bd74add63deb0cb7e2a7">llvm::CallInst::isTailCall</a>.</p>

</div>
</div>

### PerformDAGCombine() {#a114238b6f08e91873cbd29bae3f069c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::PerformDAGCombine (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo">DAGCombinerInfo</a> &amp; DCI)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 4410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173dafd69c1352cb6f9c53c74cca401982531">llvm::LoongArchISD::BITREV_W</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#acf37bd7e831bdb2a5c9da8d63f843101">llvm::TargetLowering::DAGCombinerInfo::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64b9ecc144bf0b95267b353d6ddf5b9b">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ada069dd931c50ac8a36e7da178768eeb">performBITREV_WCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a001a6e7473d9f11917ec04f38e3cb498">performINTRINSIC_WO_CHAINCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a33f99c1c02a48f20e7ec9d30d11d093c">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa26d28bee621b8087f1521482dc3b825">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a5885643f7123cbe2d37a298d2551c9e1">performSRLCombine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>.</p>

</div>
</div>

### ReplaceNodeResults() {#ac83ceb8e67e1ee6ca693e3ff1ffbac0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchTargetLowering::ReplaceNodeResults (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 2965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9c91befeca2a25c8050d4c3dff8b6d67">llvm::ISD::ATOMIC_CMP_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173da6099f35e3a2fe882620fd5ee87687d70">llvm::LoongArchISD::BITREV_4B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173dafd69c1352cb6f9c53c74cca401982531">llvm::LoongArchISD::BITREV_W</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeea401cc0b7fa5aa6f4d3a0612140e1d">llvm::ISD::BITREVERSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aac2f0a84dd2aa5ee4c3f1385e9565f5e">llvm::ISD::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173da8c573ef6048d08099be7543585ad916f">llvm::LoongArchISD::CPUCFG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a6a6197a004a425f0e1cabef2dea0141b">CRC_CASE_EXT_BINARYOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a96a7ed35a64edf142d68155d4edb932d">CRC_CASE_EXT_UNARYOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#aeab31037daf476a2f52c5d52ccb26b0d">CSR_CASE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173daf3a2de25eaa2b291b53217107644c140">llvm::LoongArchISD::CSRRD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173da276d956ade33407a64a64f9742c3084c">llvm::LoongArchISD::CSRWR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173da80ed9f3139f2e6424c8767738d99f6eb">llvm::LoongArchISD::CSRXCHG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c">llvm::ISD::CTLZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6da41a113af0909470baea7486b3386b">llvm::ISD::CTTZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ab42ac60e33f89fbdaac10587d7b8f045">customLegalizeToWOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a765b869533ec8cb0d992e1199f71eb40">customLegalizeToWOpWithSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a4447dfc5ac5a8784a0a933a5be56bbf5">llvm::LLVMContext::emitError</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a36eb02ea70b6f7df1795c2df0b297f16">emitErrorAndReplaceIntrinsicResults</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173da7c466bbc4d5a7ba227150e094771f3e0">llvm::LoongArchISD::FTINT</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6e64fef2ad2ba4052cd8365e97e8d2">llvm::SDNode::getAsZExtVal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a9a76e0197f5c34a3e15ba92fbdc9c8b4">llvm::EVT::getFloatingPointVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#aa70a6cd6c880ca47e604870efe33eba4">llvm::RTLIB::getFPTOSINT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4c20c587f89ae2926f9e8a99093e8419">llvm::SelectionDAG::getTargetLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad859786d7e54bdc5c568ac20c69816e0">llvm::TargetLoweringBase::getTypeAction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b0e59823444a55c295af279611a9d24">llvm::SelectionDAG::getUNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#adc93385f9c267e9ae073bbe2096db40b">IOCSRRD_CASE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adb1de74d602ef905e06785e0052b55bf">llvm::ISD::LROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ad4a2abb087afa577d8f4239b01acbea0">llvm::TargetLowering::makeLibCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173da2d832b2ed68ba866279ed35d6eba4e82">llvm::LoongArchISD::MOVFCSR2GR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173dab3d99ae88997dab6593c4e44acfefb7b">llvm::LoongArchISD::MOVFR2GR_S_LA64</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92fceabd268d62ef2c95799a102b8abf">llvm::ISD::READ_REGISTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ad7a2ce0778f9b0a95ac96bd8e3f9de78">replaceCMP_XCHG_128Results</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ae9668c83a73c0b3d546522e1d9860cba">replaceINTRINSIC_WO_CHAINResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173da2378eaa2a4dfe9ad0d87733456df7b9f">llvm::LoongArchISD::REVB_2H</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchisd/#a16e44310c7754d9aa2f8ef078680173da5e1fbdb336d9a092ae95c49c23eaa95b">llvm::LoongArchISD::REVB_2W</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715">llvm::ISD::ROTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/makelibcalloptions/#a82aba70f7fd14f1d0c6d83caa1e5061e">llvm::TargetLowering::MakeLibCallOptions::setTypeListBeforeSoften</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681a2f11b8376488870063cf0c3036fb9577">llvm::TargetLoweringBase::TypeSoftenFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28">llvm::ISD::UREM</a>.</p>

</div>
</div>

### shouldAlignPointerArgs() {#a5f8cd8acbf7bece2f42aa6c412abf2f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::shouldAlignPointerArgs (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *, unsigned &amp;, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp;)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### shouldConsiderGEPOffsetSplit() {#aba6c89645db02d840b73f8732ac60bee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoongArchTargetLowering::shouldConsiderGEPOffsetSplit ()</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>.</p>

</div>
</div>

### shouldExpandAtomicCmpXchgInIR() {#a2f3b0d090892cc5dd71222862723e231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AtomicExpansionKind LoongArchTargetLowering::shouldExpandAtomicCmpXchgInIR (<a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst">AtomicCmpXchgInst</a> * AI)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6046 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a39126826c171851bae4062b25b48e74e">llvm::AtomicCmpXchgInst::getCompareOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84ae8e80c2bf991369add363ad75aa12137">llvm::TargetLoweringBase::MaskedIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a6adf97f83acf6453d4a6a4b1070f3754">llvm::TargetLoweringBase::None</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### shouldExpandAtomicRMWInIR() {#a5916c5a40e28fd6b62ec267bfe57e43d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLowering::AtomicExpansionKind LoongArchTargetLowering::shouldExpandAtomicRMWInIR (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * RMW)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a0794c42b44989f9d9f1454d79ca0dd88">llvm::AtomicRMWInst::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a660a31179bfecd737a256372e5fd6122">llvm::AtomicRMWInst::And</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a369f472273bc816735055f13a6e6fd6c">llvm::TargetLoweringBase::CmpXChg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a8098b34f582537833b36b58273c3545b">llvm::TargetLoweringBase::Expand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a99fd4ef84981d6a2774c14c741b5ed65">llvm::AtomicRMWInst::getOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a667d327df48643f4d2111a0065b192f2">llvm::AtomicRMWInst::isFloatingPointOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84ae8e80c2bf991369add363ad75aa12137">llvm::TargetLoweringBase::MaskedIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afdcdc631cf4fa6829fd7499cd06a306b">llvm::AtomicRMWInst::Nand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aba40628328a660c78a9d73cc209f5e84a6adf97f83acf6453d4a6a4b1070f3754">llvm::TargetLoweringBase::None</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5954f59053121b87ebe0c5fe79942c6e">llvm::AtomicRMWInst::Or</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5db6ca0c3e18acd87290f22ccb2ce564">llvm::AtomicRMWInst::Sub</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615ad3ed1a8c334bc3a50d59aaa57ee9e9f3">llvm::AtomicRMWInst::UDecWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a9334c9815ddc2b25804c6c03b68cc39b">llvm::AtomicRMWInst::UIncWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a0f94e2ef083268e45d22a220f92567a4">llvm::AtomicRMWInst::USubCond</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a7bf1abb23eccced685c706917aff605c">llvm::AtomicRMWInst::USubSat</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77">llvm::AtomicRMWInst::Xchg</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a71aab8ee954b6d71a4eed315e8f6556e">llvm::AtomicRMWInst::Xor</a>.</p>

</div>
</div>

### shouldExtendTypeInLibCall() {#aab04541bff69db3996f2b64ecfb14c8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::shouldExtendTypeInLibCall (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if arguments should be extended in lib calls.</p>

<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6559 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### shouldSignExtendTypeInLibCall() {#a9bf8f8ed2aa15edbba86ec715f21823a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::shouldSignExtendTypeInLibCall (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool IsSigned)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6551 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### signExtendConstant() {#a808bb58d9e36f7e9c27b5606d6a9e7d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::signExtendConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this constant should be sign extended when promoting to a larger type.</p>

<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6534 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### analyzeInputArgs() {#a4c2fe9aa84c9cdfd1e3d1e2b860b224a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchTargetLowering::analyzeInputArgs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; CCInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, bool IsRet, LoongArchCCAssignFn Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### analyzeOutputArgs() {#a1b414f8384a983b0fe1c3c00e74f79b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchTargetLowering::analyzeOutputArgs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; CCInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, bool IsRet, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> * CLI, LoongArchCCAssignFn Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### EmitInstrWithCustomInserter() {#a17a990cf077ce2bdde571005399b362a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * LoongArchTargetLowering::EmitInstrWithCustomInserter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 4709 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### getAddr() {#a4d7ad91400a763a2c78dbbb05d5b172c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::getAddr (NodeTy * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> M, bool IsLocal=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1800 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### getConstraintType() {#a492e47c6d86f32c814dfb5624feea4fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoongArchTargetLowering::ConstraintType LoongArchTargetLowering::getConstraintType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint)</td>
</tr>
</table>
</td>
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

<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### getDynamicTLSAddr() {#a0b34c62886ef4ed63948b943f16e4dc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::getDynamicTLSAddr (<a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Opc, bool Large=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1935 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### getInlineAsmMemConstraint() {#a411187f959588c75b111946638544d64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAsm::ConstraintCode LoongArchTargetLowering::getInlineAsmMemConstraint (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ConstraintCode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### getRegForInlineAsmConstraint() {#a5743b130308cfad517210da4f828a595}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, const TargetRegisterClass * &gt; LoongArchTargetLowering::getRegForInlineAsmConstraint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### getStaticTLSAddr() {#a95cd8c33b49a3aef1307f392c66734b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::getStaticTLSAddr (<a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Opc, bool UseGOT, bool Large=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1896 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### getTLSDescAddr() {#adf8d054a548a958438a4f710d9d34c4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::getTLSDescAddr (<a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Opc, bool Large=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1970 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### isEligibleForTailCallOptimization() {#a11dd4d91f75bad3490380d1c31ada3c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::isEligibleForTailCallOptimization (<a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; CCInfo, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp; CLI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &gt; &amp; ArgLocs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5456 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### isFPImmLegal() {#a9a650cced7777c1d02f4bdd4010f2293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::isFPImmLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>, bool ForCodeSize)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5835 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### LowerAsmOperandForConstraint() {#af37026f64d4c27be7b6aff27e608b72f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchTargetLowering::LowerAsmOperandForConstraint (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
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


<p>If it is invalid, don't add anything to Ops.</p>


<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 6347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerATOMIC\_FENCE() {#a9aca120488258f07b7e3c0c1eec7c153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerATOMIC_FENCE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1576 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerBITCAST() {#adeedcda3f3b69b154df54cc32a393431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerBITCAST (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1743 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerBITREVERSE() {#afb33705eaea1a9a3660c7904ee022803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerBITREVERSE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerBlockAddress() {#a50505ff9aca974085fdbefd54d792f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerBlockAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1863 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerBUILD\_VECTOR() {#ad2faa77a056f9439888b4b16369bf6f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerBUILD_VECTOR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1476 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerConstantPool() {#ab2b31000228f3dd36420b8ad5c247d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerConstantPool (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1875 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerEH\_DWARF\_CFA() {#a42f8e09a8221db518e46525c33c99f9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerEH_DWARF_CFA (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1660 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerEXTRACT\_VECTOR\_ELT() {#a5d10811a47135dc8b270478ed7c9f1d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerEXTRACT_VECTOR_ELT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerFP\_TO\_SINT() {#a1f467d2ba15c8cd72612869674a8671a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerFP_TO_SINT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1757 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerFRAMEADDR() {#a341c7a0df73920b7cedcfd298d1fb6df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerFRAMEADDR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1610 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerGlobalAddress() {#a48900be575ae843f16b5a7aedb3f242d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerGlobalAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerGlobalTLSAddress() {#a7efd8c5ef6c4470f6986a390be39d738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerGlobalTLSAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1989 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerINSERT\_VECTOR\_ELT() {#a22f7e410368c1e031973262654d532d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerINSERT_VECTOR_ELT (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1569 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerINTRINSIC\_VOID() {#a1d3338661a30ca962047628b1d1f9093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerINTRINSIC_VOID (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 2473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerINTRINSIC\_W\_CHAIN() {#acf25989cc9726857525ceeba198d08e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerINTRINSIC_W_CHAIN (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 2352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerINTRINSIC\_WO\_CHAIN() {#ac311ad578e20c51c618b7474f5d295d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerINTRINSIC_WO_CHAIN (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 2063 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerJumpTable() {#a886da5746dc5abe106d447cb6eb89e0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerJumpTable (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1869 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerPREFETCH() {#ab18bcc0c5944ef1ed0c251f8b9a6aecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerPREFETCH (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerRETURNADDR() {#ae8dc72a43d265fedc741e25f33087df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerRETURNADDR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1637 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerSCALAR\_TO\_VECTOR() {#aa95e270670363d89a936fabc63e34d31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerSCALAR_TO_VECTOR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerShiftLeftParts() {#abc3a4d93ac3c0483206740d768781069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerShiftLeftParts (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 2639 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerShiftRightParts() {#a35e93477834cdd084df977d7bf7efe72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerShiftRightParts (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool IsSRA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 2679 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerSINT\_TO\_FP() {#ac1bbf20d43bed2520eae76b89f458520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerSINT_TO_FP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1718 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerUINT\_TO\_FP() {#ad4c7c1cda2a7d17da62a785253dba6a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerUINT_TO_FP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1684 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerVASTART() {#ac4c6deb9d5229738118cc8f3d6692b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerVASTART (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1668 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerVECTOR\_SHUFFLE() {#a8c25798034f9391164a3f63c16e79fd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerVECTOR_SHUFFLE (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### lowerWRITE\_REGISTER() {#ac13079dc4ac88c9631aba9e57b0f6a9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LoongArchTargetLowering::lowerWRITE_REGISTER (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 1592 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### shouldInsertFencesForAtomic() {#ae87408d59695398ba2997aa645e476c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoongArchTargetLowering::shouldInsertFencesForAtomic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
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


<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>, definition at line 5853 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a>.</p>

</div>
</div>

### softPromoteHalfType() {#a095935285d20d68f893fd1783b0879fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoongArchTargetLowering::softPromoteHalfType ()</td>
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



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Subtarget {#a3bd1be36d40cc60dfe89a46b83fe41a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoongArchSubtarget&amp; llvm::LoongArchTargetLowering::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp">LoongArchISelLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
